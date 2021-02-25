# Dmitry Budinsky

## Contacts
 * email: budinsky.dmitry@gmail.com
 * phone/viber: +375(29) 720-93-27
 * Telegram: @budya_d

## About me
 * Objective:
    * Start a developer career 
    * Learning and become a professional
    * Bring benefits and see the results of my work
 * Experience:
    * Since 2012 I have been working at the 1st Minsk Poultry Plant OJSC as deputy chief economist. In everyday work, there is coordination of the department’s work, execution of instructions from senior management, maintenance and submission of periodic analytical information to organizations of state control, analytics of the work of structural units, development and implementation of standards for remuneration, and statistical reporting.   

## Skills:

**Few Words**
>At the beginning of my study as a programmer, I focused on developing desktop applications, but as more I learned, I began understand that under certain conditions, the assigned task can be solved by using web technologies, and this will be a simpler and more optimal solution.
   * Programming Languages
     * JS / TS 
     * С#
   * Frameworks:
     * Angular
     * Express
     * ASP.NET MVC 5
     * EntityFramework
    * Other:
      * Git
      * Visual Studio
      * Visual Studio Code
      * JB WebStorm 
   *  Code example:
    
    
    ~~~
    @Component({
      selector: 'app-root',
      template: `
        Search: <input type="text" (keyup)="onChange($event.target.value)"/>
        <div *ngFor="let log of _logs">
          Search: &nbsp;{{log}} 
        </div>    
      `,
      styles: []
    })
    export class AppComponent {
      title = 'rxjs-ex300debounce';
      _searchText: string;
      _searchSubject: Subject<string>;
      _logs: Array<string> = [];
      constructor() {
        this._searchSubject = new Subject<string>();
        this._searchSubject
        .pipe(debounceTime(300))
        .pipe(distinctUntilChanged())
        .subscribe(
            searchText => this._logs.push(searchText)
        );
        }
        public onChange(searchText: string){
          this._searchSubject.next(searchText);
        }
    }
    ~~~
## Dev experience
  * Courses "Computer Academy 'Step' " (itstep.by 2015-2018)
  * Internship Angular (may 2019 - september 2019)
  * [Learnjavascript.online](https://learnjavascript.online/)
  * [freeCodeCamp](https://www.freecodecamp.org/)
  * [html academy](https://www.freecodecamp.org/)

## English level: A2

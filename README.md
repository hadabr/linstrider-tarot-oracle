# Easy busy frontend setup
Checklist. Best practices
### Сontents:
##### Project management
[Task management](#task-management)   
[Connection and synchronization](#Connection-and-synchronization)  
[Time management](#time-management) 
##### Development and testing
[App architecture](#app-architecture)  
[QA](#qa)    
[JS](#js)  
[Appearance](#Appearance)  
[APIs](#apis)  
[Database](#Database)  
##### Design and prototyping
[Branding](#branding)  
[UI/UX](#UI/UX)  
[Assets and media files](#Appearance)  
##### Deployment
[Version control management](#version-control-management)  
[Computing resources and storage](#computing-resources-and-storage)   
...
##### Intelectual resources
[License](#license)  
[Credits](#credits)  
[Disclaymer](#disclaymer)    
...
##### Marketing
...  
__  
[before start](#before-start) 

## Project management
### Task management
[⇑ back to Contents](#Сontents)  
```Tool:``` [*Trello, quire, Asana or Jira etc.*]  
```Pattern:``` **Kanban-based pattern**  
```Guidelines:```   
It's **a conveyor with a drum** omitting conveyor's boredom and preventing frustrations through clearness about forecast, control, analyse what, how and when is doing, simplicity to observe and participate with **visualization**, **interaction**, **partition** and **synchronization**  
- main workflow is split into ```ideas```, ```tasks```, ```issues``` and ```blocked``` boards by default; also, ```common``` list  
 
![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/Screenshot_102.png?raw=true)
  
- boards follow columns template: 
TO-DOs &nbsp;⇒&nbsp; In process &nbsp;⇒&nbsp; Completed &nbsp;*or*&nbsp; Postponed   
![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/sams.png?raw=true)  
> As here is a simpler approach than Scrum - we have a *non-iterative* one-dimensional straightforward flow. Anyway, tasks still can be _postponed_ or *blocked* for a time and reopen later.  

- tasks are moved between boards and inside a board, changing their status  

<img src="https://github.com/hadabr/assets/blob/master/working-enviroment-setup/sams2.png?raw=true" width="420"/><img src="https://github.com/hadabr/assets/blob/master/working-enviroment-setup/sams1.png?raw=true" width="420"/>

- after appeared in **To-DOs** can be freely taken by who wants to do them - at **flat organizational structure** or will be assigned by a supervisor - at **hierarchical** one

__  
*be sure, that **blocked** will not appear on your Calendar; it can be set as non-tracking board or i.e. board with only *completed* column, which will not appear in the calendar

- sublists  
 in case of a complexed macrotask with a lot of subtasks and details, notes or repetitive processes - **when to unfold a task is more important than its terms**, better to use **sublists**

![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/Screenshot_105.png?raw=true)  

```Concept:``` **Context-based tags and filters**
> original **Kanban** used system of colorful priority cards to control the flow; 
> for the same approach we are using **colorful tags**  
> 1) to give more information about a task from first sight  
> 2) allows to apply filters and make a search through tasks simpler  
> it is suggested to use so few tags how possible    
- (optional) **categories** tags:  
if you don't have on task manager categories, you can set it through tags ```PM```, ```development```, ```design```, ```deployment``` etc.; by default it can be sections from this setup
- **priority** tags:  
in the next order:  

non-tagged tasks - you can consider it like "general"  
```main``` - highest, tasks on which depend a lot of other  
```other``` - vice versa to *main*; you can consider them as "in project, but something additional"  
```extra``` - lowest, *postponed* or non-cored tasks, some features can be added later  
- **special** tags: 

```urgent``` - of course, you can set directly priority; plus, there is easy to observe overdue tasks, but sometimes it just needs more attention   
```discussion``` - something on a task needs live text/talk conversation  
- not tags, but **deadlines**:  

| routine       | weekly/monthly | overall  |
| ------------- |---------------| -----  |
| repetitive, "never-ending" tasks     | deadline by a date and hours | no fixed deadline    |

- good task has only 2-3 tags  
- at the end set the same **filters**, based on your tags, for every board/list you have  

#### Connection and synchronization 
[⇑ back to Contents](#Сontents)     
- simplified communication in a team  
talk+inbox+chat all-in-one tools exceed other  
for **code sharing** we have Git  
- reduced communications frequency - DRY is to use here  
dynamic, version controlled **documentation**
**screen sharing** instead of chatting and half-free **streams for coding** (i.e. by debugging)  
etc. - there is no concrete setup, it's rather an approach  
...
- app integrations and cross-links 
![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/Screenshot_111.png?raw=true)  
**link** version control software with task management - every commit should have a link (i.e. comment) to corresponded task and vice versa  
**calendar** is set to fetch tasks for a contributor  
and calendars are set for a supervisor to control **time workload** and **rewards**  
- use system of notifications about ```commits```, ```tasks```, ```tests```, ```news```  
![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/Screenshot_112.png?raw=true) 

#### Time management
[⇑ back to Contents](#Сontents)   
```Tool:``` time tracker, i.e. **Toggl**  
```Pattern:``` **Pomodoro** 

## Development and testing
### App architecture
[⇑ back to Contents](#Сontents)  
```Pattern:``` **Modular all-to-one architecture**  

### QA  
[⇑ back to Contents](#Сontents)  
### JS  
[⇑ back to Contents](#Сontents)  
```Concept:``` **Event performance**  
- Control event bubbling and event target precision  
- Debouncing over Throttling over nothing  

### Appearance   
[⇑ back to Contents](#Сontents)  
```Concept:``` **SCSS over CSS**  
```Pattern:``` **SCSS all-to-one modules**  
```Concept:``` **Grid of grids**  
```Concept:``` **BEM**  
```Concept:``` **Responsive grid**  
```Concept:``` **Context-based grid**  
```Concept:``` **Flex-to-flex**  

### APIs  
[⇑ back to Contents](#Сontents)  
### Database  
[⇑ back to Contents](#Сontents)   
## Design and prototyping  
### Branding  
[⇑ back to Contents](#Сontents)    
### UI/UX  
[⇑ back to Contents](#Сontents)  
### Assets and media files  
[⇑ back to Contents](#Сontents)  

## Deployment
### Version control management  
[⇑ back to Contents](#Сontents)  
### Computing resources and storage   
[⇑ back to Contents](#Сontents)  

## Intelectual resources  
### License  
[⇑ back to Contents](#Сontents)  
### Credits  
[⇑ back to Contents](#Сontents)  
### Disclaymer   
[⇑ back to Contents](#Сontents)  
   

## Marketing
[⇑ back to Contents](#Сontents)  


###### before start:
```
before start 
- check if in .gitignore contains next lines:
dist/
src/styles/
node_modules/
- install node modules:
~$ npm install
- run liveserver:
~$ npm start
you should see opened index.html and sass watching for changes
```

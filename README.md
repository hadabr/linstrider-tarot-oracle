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
##### Security  
[Team-protocols](#team-protocols)  
[Client-side](#client-side)  
[Server-side](#server-side)   
... 
##### Intelectual resources
[License](#license)  
[Credits](#credits)  
[Disclaymer](#disclaymer)    
...
##### Deployment
[Version control management](#version-control-management)  
[Computing resources and storage](#computing-resources-and-storage)   
...
##### Marketing
...  
__  
[before start](#before-start) 

## Project management
### Task management
[⇑ back to Contents](#Сontents)  
```Tool```: *Trello, quire, Asana or Jira etc.*
```Pattern```: **Kanban-based pattern**  
```Guidelines```:   
[**Main principles**](#Connection-and-synchronization)      
In general, it's **a conveyor with a drum** omitting conveyor's boredom and preventing frustrations thanks clearness - splitting tasks in the smallest possible chunks, but providing at least simplified whole picture what is happening - there is a lot details, but main aspects are **visualization**, **interaction**, **partition** and **synchronization**  
   
- main workflow is split into ```ideas```, ```tasks```, ```issues``` and ```blocked``` boards by default; also, ```common``` list  
 
![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/Screenshot_102.png?raw=true)
  
- every task moves straightforward from ```ideas``` to ```tasks``` or ```blocked``` and: 
TO-DOs &nbsp;⇒&nbsp; In process &nbsp;⇒&nbsp; Completed &nbsp;*or*&nbsp; Postponed inside a board, changing its status  
![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/sams.png?raw=true)  
> As it is a simpler approach than Scrum - we have a *less iterative* flow. Anyway, tasks still can be _postponed_ or *blocked* for a time and reopen later.  

<img src="https://github.com/hadabr/assets/blob/master/working-enviroment-setup/sams2.png?raw=true" width="420"/><img src="https://github.com/hadabr/assets/blob/master/working-enviroment-setup/sams1.png?raw=true" width="420"/>

- tasks in **To-DOs** should be freely taken by who wants - at **flat organizational structure** or will be assigned by a supervisor - at **hierarchical** one

__  
*be sure, that **blocked** will not appear on your Calendar; it can be set as non-tracking board or i.e. board with only *completed* column, which will not appear in the calendar

- sublists  
 in case of a complexed macrotask with a lot of subtasks and details, or for repetitive processes - **when to unfold a task is more important than its terms**, better to use **sublists**

![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/Screenshot_105.png?raw=true)  

```Concept```: **Context-based tags and filters**
> original **Kanban** used system of colorful priority cards to control the flow; 
> for the same approach we are using **colorful tags**  
> 1) to give more information about a task from first sight  
> 2) allows to apply filters and make a search through tasks simpler  
> it is suggested to use so few tags how possible    
- (optional) **categories** tags:  
i.e. ```PM```, ```development```, ```design```, ```deployment``` etc.; i.e. it's really helpful to separate design and coding  
- **priority** tags:  
in the next order:  

non-tagged tasks - you can consider it like "general"  
```core``` - highest, task on which depends main processes, can be used, when no dependency for tasks is set  
```main``` - high, tasks on which depend a lot of other  
```other``` - vice versa to *main*; you can consider them as "in project, but something additional"  
```extra``` - lowest, *postponed* or non-cored tasks, some features can be added later  
- **special** tags: 

```urgent``` - of course, you can set directly priority; plus, there is easy to observe overdue tasks, but sometimes it just needs more attention   
```discussion``` - something on a task needs live text/talk conversation  

- good task has only 2-3 tags  

![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/Screenshot_119.png?raw=true)  
- at the end set the same **filters**, based on the tags, for every board/list you have  
easy to observe a workload  

#### Connection and synchronization 
[⇑ back to Contents](#Сontents)     
- **simplified** communication in a team  
all-in-one (talk+inbox+chat) tools exceed other 
it's up to a team to use a strict or cozy PM style, but **don't mix up** enviroments for code, conversations, task management (i.e., better no chats on github, no commits in messenger etc.)  
for **code sharing** there is github    
- **reduced** communications' **length** and **frequency** - DRY is to use here  
dynamic, version controlled **documentation** over everything  
**screen sharing** over chatting  
applied half-free **coding streams for** (i.e. by debugging)  
etc. - fot other there is no concrete setup, it's rather an approach  
...
- app integrations and cross-links 
**link** version control software with task management - every commit should have a link (i.e. comment) to corresponded task and vice versa  
**calendar** is set to fetch tasks for a contributor  

![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/ipugkhjklk.png?raw=true)    
and calendars are set for a supervisor to control **time workload** and **rewards**  
- use system of notifications about ```commits```, ```tasks```, ```tests```, ```news```  

![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/Screenshot_112.png?raw=true) 

#### Time management
[⇑ back to Contents](#Сontents)  
```Concept```: **Two deadlines** 
there should be only 

| routine       | one deadline | two deadlines | overall  |
| ------------- |---------------| -----  | -----  |
| repetitive, "never-ending" tasks     | daily or incapsulation tasks |tasks with start and end date | no fixed deadline    |  

**two deadlines** should exceed any other approach  
together with TO-DOs &nbsp;⇒&nbsp; In process &nbsp;⇒&nbsp; Completed is the most powerful thing to control, when a task comes in an action (**1st deadline**) and when it should be finished (**2nd deadline**))  
&nbsp;
```Pattern```: **Pomodoro**  
```Tool```: time tracker, i.e. **Toggl**  

## Development and testing
### App architecture
[⇑ back to Contents](#Сontents)  
```Pattern```: **Modular all-to-one architecture**  

![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/Screenshot_113.png?raw=true)  
```Concept```: **Split-to-branches** 

### QA  
[⇑ back to Contents](#Сontents)  
### JS  
[⇑ back to Contents](#Сontents)  
```Concept```: **Events and animations performance**  
- Control event bubbling and layout reflow  
[About](https://gist.github.com/paulirish/5d52fb081b3570c81e3a)    
- Debouncing over ```requestAnimationFrame()``` over Throttling over nothing  

### Appearance   
[⇑ back to Contents](#Сontents)  
```Concept```: **SCSS over CSS**  
```Pattern```: **SCSS all-to-one modules**  
```Concept```: **Grid of grids**  
```Concept```: **BEM**  
```Concept```: **Responsive grid**  
```Concept```: **Context-based grid**  
```Concept```: **Flex-to-flex**  

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

## Security  
### Team-protocols  
[⇑ back to Contents](#Сontents)  
### Client-side  
[⇑ back to Contents](#Сontents)  
### Server-side  
[⇑ back to Contents](#Сontents)  

## Intelectual resources  
### License  
[⇑ back to Contents](#Сontents)  
### Credits  
[⇑ back to Contents](#Сontents)  
### Disclaymer   
[⇑ back to Contents](#Сontents)  
   
## Deployment
### Version control management  
[⇑ back to Contents](#Сontents)  
### Computing resources and storage   
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

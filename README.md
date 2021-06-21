# Angular Essential Training
This is the repository for the LinkedIn Learning course `Angular Essential Training`.
The full course is available from [LinkedIn Learning]().

_See the readme file in the main branch for updated instructions and information._

## Course Description
Angular was designed by Google to address challenges programmers face building complex, 
single-page applications. This JavaScript platform provides a solid core of web 
functionality, letting you take care of the design and implementation details. In 
this course, Justin Schwartzenberger introduces you to the essentials of this 
"superheroic" platform, including powerful features such as two-way data binding, 
comprehensive routing, and dependency injection. Justin steps through the platform 
one feature at a time, focusing on the component-based architecture of Angular. 
Learn what Angular is and what it can do, as Justin builds a full-featured web 
app from start to finish. After mastering the essentials, you can tackle the 
other project-based courses in our library and create your own Angular app.

Topics include:
- What is Angular?
- Working with components
- Binding events and properties
- Getting data to components
- Using directives and pipes
- Creating Angular forms
- Validating form data
- How Angular does dependency injection
- Making HTTP calls
- Routing
- Styling components
- Performance tips
- Animations
- Internationalization (i18n)

## Instructions
This repository has branches for each of the videos in the course. You can use the
branch pop up menu in GitHub to switch to a specific branch and take a look at the
course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the
branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course.
The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03`
corresponds to the second chapter and the third video in that chapter.
Some branches will have a beginning and an end state. These are marked
with the letters `b` for "beginning" and `e` for "end". The `b` branch
contains the code as it is at the beginning of the movie. The `e` branch
contains the code as it is at the end of the movie. The `main` branch
holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:

    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

## Installing
1. To use these exercise files, you must have the following installed:
  - [node.js](http://nodejs.org/)
  - [git](http://git-scm.com/)
2. Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like SourceTree.
   CD to the folder

   `cd angular-esst-2889546`
   and then fetch all the remote branches for the repository

   `git fetch --all`

3. Run the following to install the project dependencies:

   `npm ci`

4. Run the ng serve command to build the code, watch for file changes, and serve up the site locally:

   `ng serve`

5. Navigate to http://localhost:4200. The app will automatically reload if you change any of the source files.

   `http://localhost:4200/`

_NOTE: You can switch from one exercise branch to the next and not have to 
re-run `npm ci` each time since you will remain in the same root folder._

## Angular CLI
This project was generated with [Angular CLI](https://github.com/angular/angular-cli).

To get more help on the Angular CLI use `ng help` or go check out the
[Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

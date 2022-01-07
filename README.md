## Description

Tech Stack:
* Sequelize + SQLite (database)
* Express (web server)
* Node.js (run-time environment)

## Project Setup
1. Install Node.js: https://nodejs.org/
2. Download project files
3. ``` $ cd quiz-api ``` # navigate to project's root directory
4. ``` $ npm i ``` # install the packages listed in package.json
5. ``` $ npm start ``` # start server

## Routes and Resources
```
   GET     /quizzes                ->  indexController()
   GET     /quizzes/:id/play       ->  playController()
   GET     /quizzes/:id/check      ->  checkController()
   GET     /quizzes/new            ->  newController()
   POST    /quizzes                ->  createController()
   GET     /quizzes/:id/edit       ->  editController()
   PUT     /quizzes/:id/update     -> updateController()
   DELETE  /quizzes/:id            -> destroyController()
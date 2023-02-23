# IGME-430-02: Rich Media Web App Dev II

<!-- * [Syllabus](link) -->
* [Course Coding Standards](/coding-standards.md)
* [IGME-235 Master Git](https://github.com/tonethar/IGME-230-Master)
* [IGME-230 Shared Git](https://github.com/tonethar/IGME-235-Shared)
* [IGME-330 Master Git](https://github.com/tonethar/IGME-330-Master)
<!-- * [IGME-430-1](https://github.com/tonethar/IGME-430-Fall-2020) -->
<!-- * [IGME-430-2](https://github.com/tonethar/IGME-430-Spring-2021) -->
<!-- * [NAME](url) -->
<!-- * [NAME](url) -->
<!-- * [NAME](url) -->
<!-- * [330: Intro to Web Components](https://github.com/tonethar/IGME-330-Master/blob/master/notes/HW-wc-1.md) -->
<!-- * [Canvas Stuff From 330](https://github.com/HauntedPineapple/IGME-330-Fall-2021/blob/main/weekly/week-10A-notes.md) -->

<hr>

### Assignment Instructions
* [Git and Heroku Setup](./430/assignments/instructions/Git%20and%20Heroku%20Setup.pdf)
* [Simple HTTP Homework](./430/assignments/instructions/Simple%20HTTP%20Homework.pdf)
* [Streaming Media Assignment](./430/assignments/instructions/streaming_media_assignment.pdf)
* [HTTP API Study Guide](./430/assignments/instructions/HTTP_API_SG.pdf)
* [HTTP API Assignment I](./430/assignments/instructions/HTTP_API_Assignment(Revised).pdf)
* [HTTP API Assignment II](./430/assignments/instructions/http-api-assignment-2.pdf)
* [HTTP Server Design SG](./430/assignments/instructions/HTTP%20Server%20Design%20SG.pdf)
* [Database SG](/430/assignments/instructions/Database%20SG.pdf)
* [Simple Models HW](./430/assignments/instructions/SimpleModelsHW_1.2.pdf)
* [DomoMaker A](./430/assignments/instructions/Domomaker-A-2022-1.pdf)
* [DomoMaker B](./430/assignments/instructions/Domomaker-B-2022.pdf)
* [DomoMaker C](./430/assignments/instructions/Domomaker-C-2022-2.pdf)
* [DomoMaker D](./430/assignments/instructions/Domomaker-D-2022-2.pdf)
* [DomoMaker E](./430/assignments/instructions/Domomaker-E-2022.pdf)
* [Project 1](./430/assignments/project-1/Project%201.pdf)
* [Project 2](./430/assignments/project-2/Project%202.pdf)
<!-- * [Assignment](url) -->

<hr>

### Guides
* [Assignment Links Guide (Getting Heroku, GitHub, and CircleCI Links)](./430/assignments/guides/Assignment%20Links%20Guide.pdf)
* [Setting Up a Node Project](./430/assignments/guides/Setting%20Up%20a%20Node%20Project.pdf)
* [Pushing To Heroku](./430/assignments/guides/Pushing%20To%20Heroku.pdf)
* [Debugging Node](./430/assignments/guides/Debugging%20Node.pdf)
* [MongoDB Cloud Setup](./430/assignments/guides/MongoDBCloudSetup.pdf)
* [How to use MongoDB Compass](https://www.mongodb.com/docs/compass/current/)
* [Setting up MongoDB Locally](./430/assignments/guides/Setting%20Up%20MongoDB%20Locally.pdf)
* [Setting up Redis for Local Use](./430/assignments/guides/Setting%20up%20Redis%20for%20Local%20Use-2022-1.pdf)
<!-- * [NAME](url) -->

<hr>

### Helpful Resources
* [HTML Validator](https://appdevtools.com/html-validator)
* [CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_upload)
* [JSON Validator](https://jsonlint.com/)
* [Node.js Documentation](https://nodejs.org/api/)
* [ES6 Cheatsheet](https://github.com/DrkSephy/es6-cheatsheet)
* [HTML Cheatsheet ](https://github.com/iLoveCodingOrg/html-cheatsheet)
* [CSS Cheatsheet](https://github.com/iLoveCodingOrg/html-cheatsheet)
* [JavaScript Cheatsheet](https://github.com/iLoveCodingOrg/javascript-cheatsheet)
<!-- * [CSS Gradients](https://webgradients.com/) -->
<!-- * [NAME](url) -->

<hr>

### Textbooks and References
**Title:** *Safari HTML5 Canvas Guide*
**Publisher:** Apple Inc.
- HTML Version: https://developer.apple.com/library/safari/documentation/AudioVideo/Conceptual/HTML-canvas-guide/Introduction/Introduction.html

**Title:** *Mozilla Developer Network*
**Publisher:** Mozilla Inc.
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference
- The definitive JavaScript Reference

<hr>

### Node Setup
Check node and npm versions with `node ‐v` and `npm ‐v`

In package.json:
```
"engines":{
    "node": "16.14.0",
    "npm": "8.3.1"
  },
"main": "./src/server.js",
"scripts": {
   "start": "node ./src/server.js",
   "pretest": "eslint ./src --fix",
   "test": "echo \"Error: no test specified\" && exit 1"
  },
 "devDependencies": {
    "eslint": "^8.33.0",
    "eslint-config-airbnb": "^19.0.4",
    "eslint-plugin-import": "^2.27.5"
  }
```

Install ESLint node modules with:
`npm install --save-dev eslint eslint-plugin-import eslint-config-airbnb`
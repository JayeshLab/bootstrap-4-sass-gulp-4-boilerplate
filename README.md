# Bootstrap 4 boilerplate with sass and gulp 4
A Bootstrap 4.3.1 boilerplate with font-awesome, sass, gulp 4 tasks, browserSync (with hot-reloading). You can override bootstrap sass variables by placing those variables in `bootstrap-4-sass-gulp-4-boilerplate/assets/scss/_bootstrap_variable_overrides.scss`

## Pre-requisite
- [Node.js](https://nodejs.org/en/download/ "Node Js")
-  NPM (Comes with Node.js)
- [Gulp 4](https://gulpjs.com/ "Gulp")

Install Gulp cli

     $ npm install --global gulp-cli
     

## Getting started

1. Clone repository:
`git clone https://github.com/JayeshLab/bootstrap-4-sass-gulp-4-boilerplate.git`

2. Change directory:
`cd bootstrap-4-sass-gulp-4-boilerplate`
    
3. Install all dependencies and libraries:
   `npm install`

4. Run Gulp Task:
  - `gulp`      - To compile scss to css, minify css and js and build ready for production files in **dist** folder.

  - `gulp dev`  - Starts a local server with browserSync and hot reloading on changes to files (HTML, SCSS, JS).
   

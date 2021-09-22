<!-- Contributing -->
# Contributing
[(Back to home)](https://github.com/vanzasetia/faq-accordion-card#readme)

![Banner](/images/contributing.gif)

## Table of contents
- [Overview](#overview)
- [Practice](#practice)
- [Prerequisite](#prerequisite)
- [Setup](#setup)

## Overview
You can contribute to this project by improving the existing code.

## Practice
If this the first time, you are starting to contribute to an open source, it might be confusing to follow along. I recommend to check this article about [make your first open-source contribution by Marco Denic](https://community.codenewbie.org/denicmarko/make-your-first-open-source-contribution-19k2). After that, you can come back and follow along.

## Prerequisite
- If you find bug, typo, issue, grammar error, or anything that can be improved, then continue.
- You need to have [Node.js](https://nodejs.org/en/) installed on your machine. To check that you have Node.js, try to run this command on your terminal:
```shell
node --version
```
- You need all these packages **installed globally** to run all the scripts on `package.json`.
  - [Browsersync](https://browsersync.io/) for the development server.
  - [Sass](https://www.npmjs.com/package/sass) to compile Sass code into CSS.
  - [npm-run-all](https://www.npmjs.com/package/npm-run-all) to run the `devserver` and the `watch:sass` script simultaneously. Also, for the `build` script.
  - [Postcss](https://www.npmjs.com/package/postcss) to run autoprefixer.
  - [Autoprefixer](https://www.npmjs.com/package/autoprefixer) to add vendor prefixes if needed.
  - [Prettier](https://www.npmjs.com/package/prettier) to format the HTML code.
  - [csscomb](https://www.npmjs.com/package/csscomb) to format and sort the properties order the Sass and CSS files.
  - [markserv](https://www.npmjs.com/package/markserv) live server for the markdown file. (Optional).
  - [semistandard](https://www.npmjs.com/package/semistandard) to format the JavaScript files.

## Setup
- First, fork this repo.
- Clone this repo to your local machine with HTTPS or SSH.
- Navigate to this project folder using your favorite terminal.
- Add the project repository as the "upstream" remote.
  - In your project repository, click the download button and then copy the HTTPS URL.
  - Then type this and paste the URL.
```shell
git remote add upstream <url>
```
  - Use git `remote -v` to check that you now have two remotes.
- To make sure that you have the lastest version of the project repository, run this command.
```shell
git pull 
```
- Create a new branch, by execute this command. You can change the branch name based on what are you going to do, for this example I call it, `fixingbugs`.
```shell
git checkout -b fixingbugs
```
- Now, you can start editing the files. Run `npm start` for the development environment. `localhost:8080` for web development and `localhost:8642` for `README.md`.
- After you have finished editing, simply run `npm run ready`.
- Add all files to staging area.
```shell
git add .
```
- Then, you can commit your changes.
```shell
git commit -m "Fixed bugs"
```
- Push your changes.
```shell
git push -u origin fixingbugs
```
- After that you can see the `Compare and Pull Request` button and follow the instructions.
- Now, you can relax and wait for your pull request to be accepted.
<!-- ENDOF Contributing -->

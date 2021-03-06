# TO.DO

<h1 align="center">
    <img src="./docs/running.gif" alt="App">
</h1>

[![LEIAME.md](https://img.shields.io/badge/-Leia%20em%20Portugu%C3%AAs-brightgreen?style=for-the-badge)](./LEIAME.md)

## Summary

* [๐งพ About](#-about)
* [๐ Main technologies](#-main-technologies)
* [๐ฝ How to download the project](#-how-to-download-the-project)
* [๐ป How to run the project](#-how-to-run-the-project)
* [๐ How to use the app](#-how-to-use-the-app)
<br>

## ๐งพ About

A _[todo](https://todoist.com/)_ app made with Javascript, Typescript e ReactJS ๐
<br>

## ๐ Main technologies

* [React](https://reactjs.org/)
* [Typescript](https://www.typescriptlang.org/)
* [Webpack](https://webpack.js.org/)
* [Babel](https://babeljs.io/)
* [Sass](https://sass-lang.com/)

_(You can see all the dependencies in the [package.json](./package.json) file)_
<br>

## ๐ฝ How to download the project

```bash
$ git clone https://github.com/victorbadaro/ignite-react-todo-list
```
<br>

## ๐ป How to run the project

The commands below use the [yarn](https://yarnpkg.com/) package manager.

```bash
# 1. Install all the project dependencies
$ yarn

# 2. Run the app
$ yarn dev

# You can also generate the files to put the app into production with:
$ yarn build

# the files will be available in the dist/ folder
```

If everything runs correctly, a message will be displayed on your terminal informing that the app code has been successfully compiled:

```bash
Compiled successfully
```

After that open your browser and access: http://localhost:8080/

โ Nice! If you followed all the steps above correctly the project will be running locally on your machine already.
<br>

## ๐ How to use the app

* Enter a new _task_ and click on the green button at the top right of the page. The new _task_ informed will be presented as a list:
    <img src="./docs/add_new_task.png" alt="Add a task">

* You can complete or renew a task (by clicking on the checkbox field next to the task description) or delete it:
    <img src="./docs/handle_task.png" alt="Handle a task">

<br>

---
<p align="center">This project was created using this <a href="https://github.com/rocketseat-education/ignite-template-reactjs-conceitos-do-react">template</a> and developed with โค by <a href="https://github.com/victorbadaro">Victor Badarรณ</a></p>
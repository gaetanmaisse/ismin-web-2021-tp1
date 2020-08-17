Part of Web Development - ISMIN 2021

Course followed by students of Mines St Etienne, ISMIN - M2 Computer Science.

[![jest](https://jestjs.io/img/jest-badge.svg)](https://github.com/facebook/jest)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![TypeScript](https://badges.frapsoft.com/typescript/love/typescript.png?v=101)](https://github.com/ellerbrock/typescript-badges/)
[![Mines St Etienne](./logo.png)](https://www.mines-stetienne.fr/)

# TP1: Introduction to TypeScript

## 📝 Goal

The goal is to discover TypeScript and its ecosystem by implementing:

- 📙 A `Book` interface containing 3 string attributes:
  - `title`
  - `author`
  - `date`
- 📚 A `Bookshelf` class that internally store books and have the following public functions:
  - `addBook(book: Book)`
  - `getBook(name: string)` returning a `Book`
  - `getBooksOf(author: string)` returning an array of `Book`s
  - `getAllBooks()` returning an array of `Book`s
  - `getTotalNumberOfBooks()` returning a number

To guide you and help you find out if everything is ✅ a test suite is available in `./Bookshelf.test.ts`.
These tests can be ran using Jest in command line or inside your IDE.

## 🚀 Getting Started

Open a terminal, go to the directory of this TP and run the following commands:

```sh
# This will install all needed dependencies
npm install

# This will run the tests once
npm run test

OR

# This will run the tests everytime a change is made in the source code
npm run test:watch

# This will build the source and put the transpiled code in `/dist` directory
npm run build
```

That's it! You can code!

## 🛰 Extra:

- Handle the `date` attribut as a Date and not a string
- Add a test, and a function `getBooksPublishedBefore(aDate: string | Date)` returning an array of `Book`s

## 🔑 Solution

An implementation of the TP is available on `solution` branch. To switch to the solution just do: 

```
# Commit or revert your local changes
# git add . && git commit -m "YOUR_MSG" 


# Update your repository
git pull

# Switch to `solution` branch
git checkout solution
```

#N Queens

Solving the famous N Queens problem in JavaScript: Given an n x n chessboard, how many different ways can you place n queens, such that none of them can attack each other? I completed this project as a student at [Hack Reactor Remote Beta](http://www.hackreactor.com/remote-beta).

## Structure:

The repository consists of

- a Backbone app
- Spec test files.

### BoardViewer - Backbone

The boardviewer is Backbone app allowing to visualize an n x n chessboard and interact with it. The chessboard will detect invalid boards by highlighting the rows, columns and/or diagonals (major or minors) with conlficts.

To run it, simply open `BoardViewer.html` in your browser.

### SpecRunner - Mocha

The specrunner contains both the tests for the BoardViewer, and in particular for the

- Empty board
- Board with row conflicts
- Board with column conflicts
- Board with major diagonal conflicts
- Board with minor diagonal conflicts

as well as test for the solvers:

- Finds a valid n-queens solution for n of 0-7
- Finds the number of valid n-queens solutions for n of 0-8


Tests are made with the [Mocha](https://github.com/mochajs/mocha) testing framework.
Test are located in the ./spec directory. To run the Just open the spec runner file with chrome.

```
SpecRunner.html
```

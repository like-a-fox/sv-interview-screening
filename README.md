# Simpleview Interview Screening Questions

- [Simpleview Inc](https://simpleviewinc.com) - Simpleview Home Page


Evaluation of general product stack:

- React.js
- Redux
- Material UI
- GraphQL
- SQL
- Node.js
- Express.js
- JSS/CSS
- JavaScript

## Instructions Puzzle 1 (Easy Option)

Write a function that logs an array containing every RGB combination as

```
function generateColors() {
	...
}
# Log should have an array of [<0-255>, <0-255>, <0 /*(since this one is the easy tier just RB)*/>]
# [...RGBArrays]
```

## Instructions Puzzle 1 (Medium Option)

In addition to the easy  requirements also include all variants of G
* Hint - this should account for every combination not just each index rising concurrently.

```
function generateColors() {
	...
}
# Log should have an array of [<0-255>, <0-255>,  <0-255>]
# [...RGBArrays]
```

## Instructions Puzzle 1 (Hard Option)

In addition to the easy and medium requirements index the colors into red, yellow, green, cyan, blue, violet, and shades [any time all three are equal]. the function should now return an object with each color as its keys with an array containing all values defined as that color.

```
function generateColors() {
	...
}

/*
possible logged object
const colors = {
	red: [...RGBArrays],
	yellow: [...RGBArrays],
	green: [...RGBArrays],
	cyan: [...RGBArrays],
	blue: [...RGBArrays],
	violet: [...RGBArrays],
	shades: [...RGBArrays]
}
*/
```

## Instructions Puzzle 1 (Extreme Option)

In addition to all previous requirements the RGBArrays will be changed from an array of [<0-255>, <0-255>,  <0-255>] to an array of objects {rgb: [<0-255>, <0-255>,  <0-255>], hex: #XXXXXX}

```
function generateColors() {
	...
}

/*
possible logged object
const colors = {
	red: [...{rgb: [<0-255>, <0-255>,  <0-255>], hex: #XXXXXX}[]],
	yellow: [...{rgb: [<0-255>, <0-255>,  <0-255>], hex: #XXXXXX}[]],
	green: [...{rgb: [<0-255>, <0-255>,  <0-255>], hex: #XXXXXX}[]],
	cyan: [...{rgb: [<0-255>, <0-255>,  <0-255>], hex: #XXXXXX}[]],
	blue: [...{rgb: [<0-255>, <0-255>,  <0-255>], hex: #XXXXXX}[]],
	violet: [...{rgb: [<0-255>, <0-255>,  <0-255>], hex: #XXXXXX}[]],
	shades: [...{rgb: [<0-255>, <0-255>,  <0-255>], hex: #XXXXXX}[]]
}
*/
```



## Stack Docs

- [JavaScript/CSS/HTML](https://developer.mozilla.org/en-US/docs/Web) - Mozilla docs on basic web technologies
- [React.js](https://reactjs.org/docs/) - Front End JavaScript Library
- [Material-UI](https://material-ui.com/) - React.js Theming Framework
- [Redux](https://react-redux.js.org/) - State Management for React.js
- [Node.js](https://nodejs.org/en/) - Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.
- [Express.js](http://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js
- [GraphQL](https://graphql.org/) - GraphQL
- [Apollo Server](https://www.apollographql.com/docs/) - Apollo Server For GraphQL
- [MSSQL](https://docs.microsoft.com/en-us/sql/sql-server/index?view=sql-server-ver15) -Microsoft SQL Server

## Authors

- **Derek Musser** - [Like A Fox](https://github.com/like-a-fox)
- **David Lovet** - [Like A Fox](https://github.com/logiccosmic)

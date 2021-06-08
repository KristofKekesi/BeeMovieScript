# Your favourite movie's script in one place.
# [![Node.js Package](https://github.com/KristofKekesi/BeeMovieScript/actions/workflows/npm-publish.yml/badge.svg)](https://github.com/KristofKekesi/BeeMovieScript/actions/workflows/npm-publish.yml)

#### Have you ever wanted to spam your terminal with Bee Movie script or make something with it?

__Who wouldn't__

## Variables
- Crystal: `BeeMovieScriptText`, `BeeMovieScriptList`
- Dart: `BeeMovieScriptText`, `BeeMovieScriptList`
- JavaScript: `BeeMovieScriptText`, `BeeMovieScriptList`
- Python: `BeeMovieScriptText`, `BeeMovieScriptList`
- Reason: `beeMovieScriptText`, `beeMovieScriptList`
- Ruby: `BeeMovieScriptText`, `BeeMovieScriptList`

## JavaScript
### Install
`npm i beemoviescript`

### Variables:
`BeeMovieScriptText`, `BeeMovieScriptList`

### Example
``` js
var Bee = require("beemoviescript");

// prints out the whole Bee Movie script
console.log(Bee.BeeMovieScriptText);

// prints out the whole Bee Movie script
for (index = 0; index < Bee.BeeMovieScriptList.length; index++) {
    console.log(Bee.BeeMovieScriptList[index]);
}
```

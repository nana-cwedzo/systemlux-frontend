# Systemlux-Frontend
## Setup
### Installation on Linux, Mac OS and Windows

* [Follow the guide here](https://help.github.com/articles/fork-a-repo) on how to clone or fork a repo
* [Follow the guide here](http://simononsoftware.com/virtualenv-tutorial/) on how to create virtualenv
* [Follow the guide here](https://nodejs.org/en/download/) to get node.js pre-built installer

### Install dependencies
  ```
  $ npm install
  ```

## Linters
> Lint, or a linter, is a static code analysis tool used to flag programming errors, bugs, stylistic errors and suspicious constructs

### Hint for html files
#### Check hint errors
```
npx hint .
```

### Stylelint for css/scss files
#### Check stylelint errors
```
npx stylelint "**/*.{css,scss}"
```

#### Fix stylelint errors
```
npx stylelint "**/*.{css,scss}" --fix
```

### Eslint for javascript files
#### Check eslint errors
```
npx eslint .
```

#### Fix eslint errors
```
npx eslint . --fix
```
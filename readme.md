# Commits Element

## Contents

- [Introduction](#introduction)
- [Installation](#installation)
  - [Bower](#bower)
  - [npm](#npm)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

List commits on a repository using Polymer and GitHub API.

## Installation

### Bower

```
$ bower install commits-element
```

### npm

```
$ npm install commits-element
```

## Usage

### index.html

```html
<!doctype html>
<html>
  <head>
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    <link rel="import" href="bower_components/commits-element/commits-element.html">
  </head>
  <body>
    <commits-element owner="polymer" repo="docs"></commits-element>
  </body>
</html>
```

## Contributing

[Contributing](contributing.md)

## License

© 2015 Charbel Rami

[MIT](license.txt)

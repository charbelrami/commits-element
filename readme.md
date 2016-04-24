# Commits Element

## Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Development](#development)
  - [Run local server](#run-local-server)
  - [Bump version](#bump-version)
- [Contributing](#contributing)
- [License](#license)

## Introduction

List commits on a repository using Polymer and GitHub API.

## Installation

```sh
$ bower install commits-element
```

## Usage

### index.html

```html
<!doctype html>
<html>
  <head>
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js" async></script>
    <link rel="import" href="bower_components/commits-element/commits-element.html">
  </head>
  <body>
    <commits-element owner="polymer" repo="docs"></commits-element>
  </body>
</html>
```

## Development

- Clone the repository
- `cd` into directory and install local dependencies

```sh
$ cd commits-element && npm i && bower i
```

### Run local server

```sh
$ polyserve
```

- Navigate to http://localhost:8080/components/commits-element/

### Bump version

```sh
$ npm version [<newversion> | major | minor | patch | premajor | preminor | prepatch | prerelease | from-git]
```

- Ensures the working tree is clean
- Bumps the version in package.json
- Updates the git index to match the working tree
- Creates a git tag
- Pushes all the refs, including annotated tags
- Publishes the package to the npm registry

## Contributing

[Contributing](contributing.md)

## License

© 2015-2016 Charbel Rami

[MIT](license.txt)

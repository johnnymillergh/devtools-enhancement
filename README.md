[![GitHub release](https://img.shields.io/github/release/johnnymillergh/devtools-enhancement.svg)](https://github.com/johnnymillergh/devtools-enhancement/releases)
[![Build Status](https://travis-ci.com/johnnymillergh/devtools-enhancement.svg?branch=master)](https://travis-ci.com/johnnymillergh/devtools-enhancement)
[![GitHub issues](https://img.shields.io/github/issues/johnnymillergh/devtools-enhancement)](https://github.com/johnnymillergh/devtools-enhancement/issues)
[![GitHub forks](https://img.shields.io/github/forks/johnnymillergh/devtools-enhancement)](https://github.com/johnnymillergh/devtools-enhancement/network)
[![GitHub stars](https://img.shields.io/github/stars/johnnymillergh/devtools-enhancement)](https://github.com/johnnymillergh/devtools-enhancement/stargazers)
[![GitHub license](https://img.shields.io/github/license/johnnymillergh/devtools-enhancement)](https://github.com/johnnymillergh/devtools-enhancement/blob/master/LICENSE)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/johnnymillergh/devtools-enhancement?style=social)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fjohnnymillergh%2Fdevtools-enhancement)

# Devtools Enhancement

**Devtools Enhancement** is a Vue based project that prevents any user's unexpected inspection operations in DevTools.

[Official Docker Image](https://hub.docker.com/r/ijohnnymiller/devtools-enhancement-prod)

## Features

Here are the highlights of **Devtools Enhancement**:

1. Prevents any user's unexpected inspection operations in DevTools
2. Based on the most modern and latest [**Type**Script]
3. Docker support

## Roadmap

- [ ] Left blank temporarily

## Usage

### Project Setup

Recommended IDE is the latest version JetBrains WebStorm.

1. Clone or download this project.

   ```shell
   $ git clone https://github.com/johnnymillergh/devtools-enhancement.git
   ```

2. Project setup.

   ```shell
   npm install
   ```

### Compiles and Hot-reloads for Development

   ```shell
npm run serve
   ```

### Compiles and Minifies for Production

```shell
npm run build
```

### Run Your Unit Tests

```sh
npm run test:unit
```

### Lints and fixes files

```shell
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

## Docker Integration

Docker deployment can defer by environment. Here is the list of environments:

| #    | Environment Name | Environment Alias Name | Description |
| ---- | ---------------- | ---------------------- | ----------- |
| 1    | production       | prod                   |             |

### The Procedures of Docker Deployment

1. Compile and minify source (can be deferred by environment, if it’s `development_docker`, then the command could be `npm run build:dev_dkr`)

   ```shell
   npm run build
   ```

2. Build Docker image and run by Docker Compose. Available Docker Compose:

   - production

## Maintainers

[@johnnymillergh](https://github.com/johnnymillergh).

## Contributing

Feel free to dive in! [Open an issue](https://github.com/johnnymillergh/devtools-enhancement/issues/new).

### Contributors

This project exists thanks to all the people who contribute. 

- Johnny Miller [[@johnnymillergh](https://github.com/johnnymillergh)]
- …


### Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://github.com/johnnymillergh)]

## License

[Apache License](https://github.com/johnnymillergh/devtools-enhancement/blob/master/LICENSE) © Johnny Miller

2020 - Present



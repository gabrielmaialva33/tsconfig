<h1 align="center">
  <br>
  <img src=".github/assets/typescript.png" alt="TypeScript" width="200">
  <br>
  tsconfig – Shared TypeScript Config for My Projects
  <br>
</h1>

<p align="center">
  <strong>Shared TypeScript configuration to standardize and streamline project setups</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/gabrielmaialva33/tsconfig?color=00b8d3&style=flat&logo=appveyor" alt="License" />
  <img src="https://img.shields.io/github/languages/top/gabrielmaialva33/tsconfig?style=flat&logo=appveyor" alt="GitHub top language" >
  <img src="https://img.shields.io/github/languages/count/gabrielmaialva33/tsconfig?style=flat&logo=appveyor" alt="GitHub language count" >
  <img src="https://img.shields.io/github/repo-size/gabrielmaialva33/tsconfig?style=flat&logo=appveyor" alt="Repository size" >
  <a href="https://github.com/gabrielmaialva33/tsconfig/commits/master">
    <img src="https://img.shields.io/github/last-commit/gabrielmaialva33/tsconfig?style=flat&logo=appveyor" alt="GitHub last commit" >
  </a>
</p>

<br>

<p align="center">
  <a href="#bookmark-about">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#package-installation">Installation</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-usage">Usage</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

<br>

## :bookmark: About

**tsconfig** is a shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) designed
to standardize and simplify the configuration of TypeScript projects. With a set of best practices pre-configured, it
helps you start your projects quickly and consistently.

<br>

## :computer: Technologies

- **[TypeScript](https://www.typescriptlang.org/)**
- **[Node.js](https://nodejs.org/)**

<br>

## :package: Installation

### :heavy_check_mark: Install

Install the package as a development dependency:

```sh
npm install --save-dev @gabrielmaialva33/tsconfig
```

*This config requires TypeScript 5 or later.*

<br>

## :rocket: Usage

Configure your project by extending this configuration in your `tsconfig.json` file.

### Basic Setup

```json
{
  "extends": "@gabrielmaialva33/tsconfig",
  "compilerOptions": {
    "outDir": "dist"
  }
}
```

<br>

### Targeting a Higher Node.js Version

When targeting a higher version of Node.js, adjust the ECMAScript target accordingly:

```json
{
  "extends": "@gabrielmaialva33/tsconfig",
  "compilerOptions": {
    "outDir": "dist",
    "target": "ES2023"
  }
}
```

<br>

## :memo: License

This project is licensed under the **MIT** license. See [LICENSE](./LICENSE) for more details.

<br>

## :rocket: **Contributors**

| [![Maia](https://avatars.githubusercontent.com/u/26732067?size=100)](https://github.com/gabrielmaialva33) |
|-----------------------------------------------------------------------------------------------------------|
| [Maia](https://github.com/gabrielmaialva33)                                                               |

<br>

<p align="center"><img src="https://raw.githubusercontent.com/gabrielmaialva33/gabrielmaialva33/master/assets/gray0_ctp_on_line.svg?sanitize=true" /></p>
<p align="center">&copy; 2017-present <a href="https://github.com/gabrielmaialva33/" target="_blank">Maia</a></p>

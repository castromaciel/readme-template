<!-- PROJECT SHIELDS -->
[![The MIT License][license-shield]][license-url]
[![stars][stars-shield]][stars-url]

<!-- PROJECT TITLE -->
<h1 align="center">Template: README</h1>

<!-- PROJECT DESCRIPTION -->
<div align="center">
  <p align="center">
    A simple and straightforward README template.
    <br />
    <a href="https://github.com/castromaciel/readme-template">View Demo</a>
    •
    <a href="https://github.com/castromaciel/readme-template/issues">Report Bug</a>
    •
    <a href="https://github.com/castromaciel/readme-template/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#technologies-used">Technologies used</a></li>
      </ul>
    </li>
    <li>
      <a href="#development">Development</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#make-it-your-own">Make it your own</a></li>
        <li><a href="#install-dependencies">Install dependencies</a></li>
        <li><a href="#available-scripts">Available Scripts</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#base-dependencies">Base Dependencies</a></li>
    <li><a href="#folder-structure">Folder Structure</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#credits">Credits</a></li>
  </ol>
</details>

## About the project

Here we place the objective of the application as such. We can add additional information about the scope.

[![page][page-image]][page-image-url]

### Technologies used
[![react][react]][react-url]
[![redux][redux]][redux-url]
[![sass][sass]][sass-url]
[![typescript][ts]][ts-url]
[![jest][jest]][jest-url]
[![react-testing-library][react-testing-library]][react-testing-library-url]


## Development

### Prerequisites
Here we'll list things you need to use the software and how to install them.

* [Node js][nodejs-url]

### Make it your own
To get a local copy, clone it using:
```sh
git clone https://github.com/castromaciel/readme-template.git
```

Or get it downloading

```sh
rm -rf .git && git init
git add .
git commit -m "Initial commit"
```

### Install dependencies:

```sh
pnpm install
#or
yarn install
#or
npm install 
```

### Available Scripts

In this project, you can run the following scripts:

| Scripts       | Description                                         |
| ------------- | --------------------------------------------------- |
| npm build     | Builds the app for production to the `dist` folder.  |
| npm dev       | Runs the app in the development mode.                |
| npm test      | Runs tests.                                          |

## Usage

### Use Template button
Click the `Use this template` button above the file list, then use the Owner drop-down menu, and select the account you want to own the repository. Creating a repository from a template has the following advantages:

A repository created from a template starts with a single commit.
Commits to a repository created from a template do appear in your contribution graph.
Creating a repository from a template starts a new project quickly.

## Base Dependencies

- [react][react-url] create user interfaces from components.
- [redux][redux-url] for stylesheets.
- [jest][jest-url] and [react-testing-library][react-testing-library] for testing.

## Folder Structure

```
project-name
├── node_modules
├── public
└── src
    ├── __tests__
        ├── App.test.tsx
    ├── assets
        ├── react.svg
    ├── App.scss
    ├── App.tsx
    ├── index.scss
    ├── main.tsx
    └── vite-env.d.ts
├── .env.development
├── .eslintignore
├── .eslintrc.json
├── .gitignore
├── index.html
├── LICENSE
├── package.json
├── README.md
├── tsconfig.json
├── tsconfig.node.json
├── vite.config.js
```

## License

This project is licensed under the terms of the [MIT license][license-url].

## Credits

README template is built and maintained by [Castro Maciel](https://github.com/castromaciel).

Badges used from [Ileriayo • markdown-badges](https://github.com/Ileriayo/markdown-badges).


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-shield]: https://img.shields.io/github/license/castromaciel/readme-template?style=flat-square
[license-url]: https://github.com/castromaciel/readme-template/blob/main/LICENSE
[stars-shield]: https://img.shields.io/github/stars/castromaciel/readme-template?style=flat-square
[stars-url]: https://github.com/castromaciel/readme-template
[nodejs-url]: https://nodejs.org/en
[react]: https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB
[react-url]: https://react.dev/
[redux]: https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white
[redux-url]: https://redux.js.org/
[sass]: https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white
[sass-url]: https://sass-lang.com/
[ts]: https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white
[ts-url]: https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white
[jest]: https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white
[jest-url]: https://jestjs.io/
[react-testing-library]: https://img.shields.io/badge/-TestingLibrary-%23E33332?style=for-the-badge&logo=testing-library&logoColor=white
[react-testing-library-url]: https://testing-library.com/docs/react-testing-library/intro/
[page-image]: ./images/page-preview.png
[page-image-url]: ./images/page-preview.png

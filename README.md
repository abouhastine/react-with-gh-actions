# Setting up a CI/CD workflow on GitHub Actions for a React App (with GitHub Pages and Codecov)

![CI/CD](https://github.com/abouhastine/react-with-gh-actions/workflows/CI/CD/badge.svg)
[![Codecov](https://img.shields.io/codecov/c/github/abouhastine/react-with-gh-actions)](https://codecov.io/gh/abouhastine/react-with-gh-actions)
![License](https://img.shields.io/github/license/abouhastine/react-with-gh-actions)

In this tutorial, I'm going to show you how to create a simple workflow that I use on my personal projects with React.

This workflow created on [GitHub Actions](https://github.com/features/actions) will be responsible for automatically test the source code, generate a test coverage report and upload it on [Codecov](https://codecov.io), build and deploy the project on [GitHub Pages](https://pages.github.com). All these jobs are activated by a push or pull request event on master branch.

# Italiancoders Netlify Auth

> Service Auth provider for Italiancoders Netlify CMS

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

## Prerequisites

This project requires NodeJS (at least version 6) and NPM.
[Node](http://nodejs.org/) and [NPM](https://npmjs.org/) are really easy to install.
To make sure you have them available on your machine,
try running the following command.

```sh
$ node --version
v10.6.0

$ npm --version
6.1.0
```

## Table of contents

- [Italiancoders Netlify Auth](#italiancoders-netlify-auth)
  - [Prerequisites](#prerequisites)
  - [Table of contents](#table-of-contents)
  - [Getting Started](#getting-started)
    - [Installation](#installation)
  - [Configuration](#configuration)
    - [Environment Variables](#environment-variables)
  - [Deployment](#deployment)
  - [License](#license)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installation

**BEFORE YOU INSTALL:** please read the [prerequisites](#prerequisites)

Start with cloning this repo on your local machine:

```sh
$ git clone https://github.com/ItalianCoders/italiancoders-netlify-auth.git
$ cd italiancoders-netlify-auth
```

Then install all the Node dependencies usin npm or Yarn

```sh
$ npm install
```

Or using Yarn

```sh
$ yarn
```

## Configuration

### Environment Variables

This project uses [DotEnv](https://github.com/motdotla/dotenv) to load environment
variables from a `.env` file into `process.env`.

First of all rename the `template.env` file into `.env`.
Then, replate the listed variables according to your deployment configuration.

## Deployment

```sh
$ npm run deploy
```

This task will deploy the service using [Now](https://zeit.co/) following the
configuration listed inside the `now.json` file.

## License

ISC License © ItalianCoders

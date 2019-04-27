---
title: Installation
layout: docs
---

## Prerequisites

Saber requires [Node.js 8](https://nodejs.org/en/) or above.

When you have Node.js installed on your machine, the `node` and `npm` commands will be available in your terminal.

Run following command to check your Node.js version:

```bash
node -v
```

## Install

Using `npm` which is the default package manager for Node.js:

```bash
cd my-website
npm install saber
```

Or using [Yarn](https://yarnpkg.com) which is an alternative package manager developed by Facebook:

```bash
cd my-website
# You need to install yarn first
yarn add saber
```

## Run

Just put `saber .` as script to simplify your starting:

```json
{
    "name": "my-website",
    "scripts": {
        "start": "saber ."
    }
}
```

Then start your writing by:

```bash
npm start
```

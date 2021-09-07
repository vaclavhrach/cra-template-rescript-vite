# cra-template-rescript-vite

[![npm](https://img.shields.io/npm/v/cra-template-rescript-vite)](https://npm.im/cra-template-rescript-vite)
[![npm downloads per month](https://img.shields.io/npm/dm/cra-template-rescript-vite)](https://npm.im/cra-template-rescript-vite)

ReScript + React + Vite template for Create React App

## Usage

use with npx

```shell
npx create-react-app --template=rescript-vite my-rescript-vite-app
```

or with yarn

```shell
yarn create react-app --template=rescript-vite my-rescript-vite-app
```

## Scripts

```shell
# Run app with builds and hot reload
npm start

# Start rescript app with watch
npm run start:re

# Run app without builds
npm run start:vi

# Build vite and rescript app
npm run build

# Build rescript app with dependencies
npm run build:re

# Build vite
npm run build:vi

# Clear rescript lib folder 
npm run clean
```

## Tests
This template does not include a test runner by default.

## Settings included

- ReScript syntax (`*.res`)
- Vite configuration 
- Prettier

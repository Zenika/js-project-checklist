# :white_check_mark: JS Project Checklist

Checklist to browse before starting a JS project

- [Framework](#framework)
- [Tooling](#tooling)
  - [Module management](#module-management)
  - [Language](#language)
  - [SSR](#ssr)
  - [Scripts](#scripts)
  - [Unit test](#unit-test)
  - [Linter](#linter)
  - [Formater](#formater)
  - [Code editor](#code-editor)
  - [E2E](#e2e)
- [Code](#code)
  - [Server communication](#server-communication)
  - [Backend collaboration](#backend-collaboration)
  - [Backend language](#backend-language)
  - [Backend mocking strategy](#backend-mocking-strategy)
  - [Authentication](#authentication)
  - [Internationnalization](#internationnalization)
  - [State Management](#state-management)
  - [Async code style](#async-code-style)
  - [Code validation process](#code-validation-process)
  - [Component isolation](#component-isolation)
- [Style](#style)
  - [CSS Framework](#css-framework)
  - [Design process](#design-process)
  - [Integration process](#integration-process)
  - [CSS management](#css-management)
  - [CSS preprocessor](#css-preprocessor)
  - [CSS postprocessor](#css-postprocessor)
  - [Flexbox positionning](#flexbox-positionning)

## Framework

- React
- Vue
- Angular
- Other

Other can be very large: Vanilla with or without Web Components, smaller but popular frameworks (Ember, Elm, Svelte, Cycle, Stencil...)

## Tooling

### Module management

- NPM
- Yarn

### Language

- TypeScript
- Babel
- Vanilla (with modules handled by the bundler)
- Full vanilla (modules in the browser)

### SSR

- Packaged framework: Next, Nuxt
- Express with specific script
- No SSR

### Scripts

- Through SSR framework (includes Webpack)
- Official CLI tools of the framework (includes Webpack)
- Starter kit with open configuration
- Manual configuration with Webpack
- Manual configuration with Parcel

### Unit test

- Jest
- Karma
- Other framework (Mocha, AVA...) with manual JSDom
- Other framework withou DOM (only for React)

### Linter

- ESLint with recomanded
- ESLint with AirBnB
- ESLint with custom rules
- TSLint (to be discontinued in profit of ESLint)

### Formater

- Prettier
- Not Prettier

### Code editor

- No recomandation
- WebStorm
- VSCode
- Atom
- Vim

Never forbid to use other editor than the recomandation. Yet, most projects has their first choice.

### E2E

- Cypress
- Nightwatch
- Protractor (for Angular)

## Code

### Server communication

- Rest with request library: fetch, axios, superagent...
- GraphQL with Apollo
- GraphQL manually

### Backend collaboration

- Same people
- Same team, different people
- Different team, same location
- Different team, different location

### Backend language

- Java
- Node
- PHP
- Other

### Backend mocking strategy

- Backend already present
- Backend to develop during the project
- Synchronous JSON mock in source files
- Synchronous JSON mock with async simulation

### Authentication

- None
- Login page
- Header token
- Cookie token
- JWT
- SSO

### State Management

- Redux like implementation of the framework: Redux, VueX, NgRX
- The real Redux
- MobX
- Singleton services (especially for Angular)
- Specific solution with RxJS

### Internationnalization

- None
- Simple
- Advanced
- i18next
- Async loading
- Translation file format

### Async code style

- Async functions
- Promises
- RxJS
- Other Reactive programming library (Bacon...)
- Callbacks

### Code validation process

- Push to master
- PR Review
- Pairing

## Component isolation tool

- Storybook
- Styleguidist
- None

## Style

### CSS Framework

- Material Design integration with the framework
- Bootstrap integration with the framework
- Other CSS framework (Bulma, Tailwind, Semantic, Foundation) integration
- CSS framework (anyone) with no integration, only CSS
- Pure CSS

### Design process

- No design
- Design produces only UX
- Design produces UX & UI

### Integration process

- JS developers produces CSS
- JS developers & CSS developers produce CSS
- Only CSS developers touch CSS code

### CSS management

- Full global CSS files
- Part global CSS and in components
- CSS next to the components
- CSS in JS

### CSS preprocessor

- No preprocessor
- Modern CSS
- Sass
- Stylus
- CSS in JS

### CSS postprocessor

- None
- Autoprefixer

### Flexbox positionning

Whether or not using flexbox for positionning.
Almost no argument not to use it except IE support (IE 10-11 partial, bellow none)

- No
- Yes

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
  - [State Management](#state-management)
  - [Async code style](#async-code-style)
  - [Code validation process](#code-validation-process)
- [Style](#style)
  - [CSS Framework](#css-framework)
  - [Design process](#design-process)
  - [Integration process](#integration-process)
  - [CSS management](#css-management)
  - [CSS preprocessor](#css-preprocessor)

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

### State Management

- Redux like implementation of the framework: Redux, VueX, NgRX
- The real Redux
- MobX
- Singleton services (especially for Angular)
- Specific solution with RxJS

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


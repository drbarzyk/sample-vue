# Installation

## Dev Environment

### Brew Installation

1. `$ brew --version`
   - if missing, visit <https://github.com/Homebrew/brew/releases/latest>
2. `$ brew update`
3. `$ brew upgrade`
4. `$ brew cleanup`

## NPM Installation

1. `$ brew install node`
   - _check with_ `$ node -v`
   - _check with_ `$ npm -v`
2. `$ npm install -g n`
   - _check with_ `$ n --version`

### Vue Native installation (ignore if using [quasar](#vue-quasar-installation))

1. `$ npm create vue@latest`
   - ✔ Project name: … **_\<your-project-name>_**
     ✔ Add TypeScript? … No / **Yes**  
     ✔ Add JSX Support? … **No** / Yes  
     ✔ Add Vue Router for Single Page Application development? … No / **Yes**  
     ✔ Add Pinia for state management? … No / **Yes**  
     ✔ Add Vitest for Unit testing? … **No** / Yes  
     ✔ Add an End-to-End Testing Solution? … **No** / Cypress / Playwright  
     ✔ Add ESLint for code quality? … No / **Yes**  
     ✔ Add Prettier for code formatting? … No / **Yes**
2. `$ cd <your-project-name>`
3. `$ npm install`
4. `$ npm run dev`

### Vue Quasar Installation

1. `$ npm init quasar`
   - ✔ What would you like to build? › **App with Quasar CLI, let's go!**
     ✔ Project folder: … **_\<project-folder>_**  
     ✔ Pick Quasar version: › **Quasar v2 (Vue 3 | latest and greatest)**  
     ✔ Pick script type: › **Typescript**  
     ✔ Pick Quasar App CLI variant: › **Quasar App CLI with Vite**  
     ✔ Package name: … **_\<package-name>_**  
     ✔ Project product name: (must start with letter if building mobile apps) … **_\<app-name>_**  
     ✔ Project description: … **_\<description>_**  
     ✔ Author: … **_\<author-name>_**
     ✔ Pick a Vue component style: › **Composition API with \<script setup>**
     ✔ Pick your CSS preprocessor: › **Sass with SCSS syntax**  
     ✔ Check the features needed for your project: › **ESLint, State Management (Pinia), Axios**  
     ✔ Pick an ESLint preset: › **Prettier**
2. `cd <project-folder>`
3. `$ npm install`
4. Run app with `$ npm run dev`

# Installation

## Brew Installation

1. `$ brew --version`
    - if missing, visit <https://github.com/Homebrew/brew/releases/latest>
2. `$ brew update`
3. `$ brew upgrade`
4. `$ brew cleanup`

## NPM Installation

1. `$ brew install node`
    - *check with* `$ node -v`
    - *check with* `$ npm -v`
2. `$ npm install -g n`
    - *check with* `$ n --version`

## Vue installation

1. `$ npm create vue@latest`
    - ✔ Project name: … ***\<your-project-name>***
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

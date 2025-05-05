<h1 align="center">Nuxt Web Boilerplate</h1>

### Overview

Most relevant technologies used in the Boilerplate:

- **Vue:** The progressive JavaScript framework.
- **Nuxt:** Universal Vue.js Applications.
- **TypeScript:** All the code uses TypeScript.
- **Express:** Backend ready project.
- **SASS:** Scss structure with good practises.
- **Linting:** Linting for JavaScript and SASS.
- **BEM (Non strict) + BEMIT:** Some conventions for CSS classes.

### 📚 Setup and scripts

> Before start [download](https://github.com/alpredovandy/nuxt-web-boilerplate/archive/master.zip) or clone the boilerplate.
> **Install** all the dependencies.

```shell
$ npm install
```

**Run** the project for local development.

```shell
$ npm start
```

**Build** the project for a production environment.

```shell
$ npm run build
```

If you want to **test**, there are some options.

```shell
$ npm test # (Will run unit and e2e tests)
$ npm run test:unit # (Only unit tests)
$ npm run test:e2e # (Only e2e tests)
```

The **linting** is configured with [**husky**](https://github.com/typicode/husky) and will run before push, but you can run it.

```shell
$ npm run lint # (Will run scripts and styles linting)
$ npm run lint:scripts # (Only scripts lint)
$ npm run lint:styles # (Only styles lint)
```

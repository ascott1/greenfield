# Greenfield

> A starter project for creating public domain products

This is a thought experiment in how we might structure a boilerplate repo
for new open source product development. **Status**: Alpha. Not to be used for production.

Features:

- Framework agnostic
- Configuration-free build process, local dev server, auto-refresh, and more with [Parcel](https://parceljs.org)
- Unit and integration test setup with [Jest](https://jestjs.io) and [Cypress](https://www.cypress.io)
- Linting with [ESLint](https://eslint.org)
- Automatic code formatting with [Prettier](https://prettier.io/)
- Easy documentation site generation with [Docsify](https://docsify.js.org)

## Installation

```
yarn
```

## Generating Documentation

To create the documentation site, add content to the `/docs/README.md` file. Additional pages
can be added by creating additional `.md` files in the `docs` directory.

To deploy the documentation as a GitHub pages site, select master branch `/docs` folder as the Github Pages source in the repositories' settings page.

Example: https://github.com/ascott1/greenfield

## Tests

For unit tests with Jest:

```
yarn run test:jest
```

For functional/integration tests with Cypress, make sure you have a local development server running at http://localhost:1234 and run:

```
yarn run test:cypress
```

To run all tests:

```
yarn run test
```

## Open source licensing info

1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)
3. [CFPB Source Code Policy](https://github.com/cfpb/source-code-policy/)

# node-library-template

>A repository template for a Node.js library.

## Structure

This repository is written in TypeScript and uses [gts](https://github.com/google/gts) for linting and formatting. It is set up to be published to npm automatically using GitHub Actions.

Commits are standardized through Conventional Commits and Semantic Versioning. This is enforced by [commitlint](https://www.npmjs.com/package/@commitlint/cli).
Pushes to the `master` branch create a new release and publish to npm.

The [lib](./lib) directory contains the library source code.
The [test](./test) directory contains the tests. Tests are written with [mocha](https://www.npmjs.com/package/mocha) and [chai](https://www.npmjs.com/package/chai).

## Usage

1. Initial setup
	1. Clone this repository.
	2. Run `npm install`.
	3. Run `npm run setup` to set up the project.

2. License
	1. Choose a license and add it to the `LICENSE` file.
	2. Change the license badge to the `README.md` file.
	3. Change the license in the `package.json` file.
	4. Change the license code in the `.vscode/settings.json` file.

3. Final changes
	1. Make sure to remove this section from the `README.md` file.
	2. Change the `README.md` file to describe your project.
	3. Add a description in the `package.json` file.
	4. Add the repository secret `NPM_TOKEN` in order for automated npm publishing to work.
	5. Run `npm install` to clean up the `package-lock.json` file.

4. Begin development!

**BELOW IS THE README FOR THE TEMPLATE REPOSITORY.**
**REMOVE THIS SECTION FROM YOUR README.**

---
---
---

# node-library-template

>A repository template for a Node.js library.

<br>

[![Downloads](https://badgen.net/npm/dt/@pextra/node-library-template)](https://www.npmjs.com/package/@pextra/node-library-template)
[![npm dependents](https://badgen.net/npm/dependents/@pextra/node-library-template)](https://www.npmjs.com/package/@pextra/node-library-template?activeTab=dependents)
[![Version](https://badgen.net/npm/v/@pextra/node-library-template)](https://www.npmjs.com/package/@pextra/node-library-template)
[![License](https://badgen.net/npm/license/@pextra/node-library-template)](https://opensource.org/license/mit/)

## NOTICE

**This package is still in development and *is not* yet ready for production use. There *will* be breaking changes before the package is stable.**

Most commands are implemented, but a few are not yet. Not many of the command options are implemented yet, but the most common ones are.

**Please open an issue if you would like a specific option implemented.**

## Install

```sh
npm install @pextra/node-library-template
```

## Usage

Your usage instructions here.

## Support/Contact

For enterprise licensing, support, and consulting, please visit [our website](https://pextra.cloud/enterprise). Alternatively, you can contact us at [enterprise@pextra.cloud](mailto:support@pextra.cloud).

If you have any questions, please feel free open an issue or a discussion. You can also contact us at [support@pextra.cloud](mailto:support@pextra.cloud).

## Contributions

We welcome contributions! If you find any bugs, have feature requests, or would like to contribute enhancements, please feel free to open issues or submit pull requests.

We use [gts](https://github.com/google/gts) for linting and formatting.

## License

node-library-template is licensed under the [MIT License](./LICENSE).

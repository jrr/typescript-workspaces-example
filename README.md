# TypeScript Yarn 2 Workspace Example

This combines [Yarn Workspaces](https://yarnpkg.com/features/workspaces) with TypeScript [Project References](https://www.typescriptlang.org/docs/handbook/project-references.html) to organize a project into separate modules, like you find in other language ecosystems.

Directories:

```
hello-lib	shared library
hello-lib-test	test suite for it
hello-cli	command-line executable using the library
```

## To Use:

Start with a single `yarn install` at the top level.

To run the tests (from the `hello-lib-test/` directory):

- `yarn build`
- `yarn test`

To run the CLI tool (from the `hello-cli/` directory):

- `yarn build`
- `yarn go`

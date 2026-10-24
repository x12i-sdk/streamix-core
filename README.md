# @x12i/streamix-core usage example

Activity, scope, and configuration model for Streamix.

This consuming application demonstrates **validate incoming json and report contract errors** using the published npm package, pinned to `0.2.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- A consumer needs the following capability: Activity, scope, and configuration model for Streamix.
- A Streamix integration needs to reuse the capabilities of @x12i/streamix-core inside a larger application.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/streamix-core)
- [Implementation monorepo](https://github.com/x12i/streamix)
- [Reviewed package source](https://github.com/x12i/streamix/tree/b4ab8abd8ac781d2b934a7a864276c5c5509fa6d/packages/core)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.

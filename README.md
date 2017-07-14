# simple-webpack-boilerplate

The simplest possible webpack boilerplate so you can use ES6 (er 2015?) and all those amazing JS packages, installed with `npm` or `yarn`.

### Howto

```
yarn
yarn run serve
```
or
```
npm install
npm run serve
```

Oh and it also supports JSX. Okay, okay, so it's not actually the simplest possible webpack boilerplate. It imports React, ReactDOM, and says "Hello, World!" with JSX-ey React. But you can easily remove React (and JSX) if you want.

### One command publish to GitHub Pages

`yarn run publish-gh-pages` or `npm run publish-gh-pages` will publish a build to GitHub pages via a `gh-pages` branch. Okay so this boilerplate is getting less simple, but hey you don't have to use the `publish-gh-pages` command and it creates no additional dependencies.

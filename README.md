# roast-my-deps

> Your dependencies are bad and you should feel bad

## Install

```sh
yarn add roast-my-deps
```

## Example

From [Spectrum](https://github.com/withspectrum/spectrum):

```
roast-my-deps --ignore draft-js* --ignore apollo-link-ws
```

**Output**

```
┌─────────────────────────────────────────────┬─────────┬─────────┐
│ Name                                        │ min     │ min+gz  │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ All                                         │ 1.97 MB │ 499 kB  │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ moment                                      │ 260 kB  │ 65.5 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-dom                                   │ 91 kB   │ 28.9 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ draft-js                                    │ 98.8 kB │ 25.3 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ raven-js                                    │ 37.6 kB │ 13 kB   │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ prismjs                                     │ 31.4 kB │ 11.7 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ validator                                   │ 40.6 kB │ 10.2 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ styled-components                           │ 27.1 kB │ 9.68 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ apollo-client                               │ 36.1 kB │ 9.2 kB  │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-flip-move                             │ 21.4 kB │ 6.23 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ lodash                                      │ 20.2 kB │ 5.8 kB  │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-apollo                                │ 23.5 kB │ 5.7 kB  │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ draft-js-markdown-plugin                    │ 20.3 kB │ 5.51 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-helmet-async                          │ 19 kB   │ 5.31 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ apollo-cache-inmemory                       │ 16.9 kB │ 5.07 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-modal                                 │ 17.3 kB │ 4.83 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ history                                     │ 20 kB   │ 4.74 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ apollo-utilities                            │ 16.5 kB │ 4.59 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-stripe-elements                       │ 17.4 kB │ 3.91 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-router                                │ 16.8 kB │ 3.61 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-redux                                 │ 11.9 kB │ 3.46 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ draft-js-plugins-editor                     │ 11.4 kB │ 3.03 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-stripe-checkout                       │ 8.75 kB │ 2.95 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ redraft                                     │ 10.3 kB │ 2.75 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-textarea-autosize                     │ 6.69 kB │ 2.27 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react                                       │ 5.44 kB │ 2.22 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ draft-js-focus-plugin                       │ 7.23 kB │ 2.13 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-trend                                 │ 5.27 kB │ 2.08 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-router-dom                            │ 7.65 kB │ 1.99 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-transition-group                      │ 5.91 kB │ 1.89 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ redux                                       │ 4.63 kB │ 1.72 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ draft-js-drag-n-drop-plugin                 │ 4.76 kB │ 1.71 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ emoji-regex                                 │ 7.15 kB │ 1.67 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-error-boundary                        │ 3.95 kB │ 1.54 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-loadable                              │ 4.27 kB │ 1.44 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-infinite-scroller-with-scroll-element │ 4.33 kB │ 1.43 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-popper                                │ 4.52 kB │ 1.39 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ recompose                                   │ 6.1 kB  │ 1.34 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ slugg                                       │ 3.25 kB │ 1.34 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ apollo-link                                 │ 3.74 kB │ 1.29 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ draft-js-image-plugin                       │ 3.42 kB │ 1.25 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ draft-js-embed-plugin                       │ 3.12 kB │ 1.2 kB  │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ draft-js-linkify-plugin                     │ 3.25 kB │ 1.18 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ react-clipboard.js                          │ 3.54 kB │ 1.13 kB │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ query-string                                │ 2.21 kB │ 845 B   │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ graphql-tag                                 │ 1.68 kB │ 777 B   │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ apollo-upload-client                        │ 1.71 kB │ 760 B   │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ string-replace-to-array                     │ 1.15 kB │ 469 B   │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ css.escape                                  │ 771 B   │ 373 B   │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ draft-js-prism-plugin                       │ 878 B   │ 372 B   │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ apollo-link-ws                              │ 803 B   │ 325 B   │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ hoist-non-react-statics                     │ 691 B   │ 309 B   │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ draft-js-code-editor-plugin                 │ 931 B   │ 286 B   │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ debounce                                    │ 434 B   │ 170 B   │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ offline-plugin                              │ 316 B   │ 164 B   │
├─────────────────────────────────────────────┼─────────┼─────────┤
│ redux-thunk                                 │ 244 B   │ 103 B   │
└─────────────────────────────────────────────┴─────────┴─────────┘
```

## Methodology

First we find all of your `package.json` dependencies and install them in a
fresh directory.

Then we search through all your source code to find `import`'s and `require`'s.
This way we have the exact imports you have in your app.

You can configure which files we search by passing globs:

```sh
roast-my-deps 'src/**/*.js' '!**/__tests__/**'
```

Then we create entry points for each dependency that look like this:

```js
// module-name.js
f(require("module-name"));
```

> The `f()` is a missing global to prevent any code from being optimized away.

Everything outside of that dependency is marked "external" and won't be
included in that module's bundle. This means that:

- The sizes are a representation of just the code in that module
- Sub-dependencies don't get displayed directly

We also create an "all" entry. This is _not_ a sum of the other bundles. It
creates a separate bundle from an entry point that looks like this:

```js
// _all.js
f(require("module-name-1"));
f(require("module-name-2"));
f(require("module-name-3"));
f(require("module-name-4"));
f(require("module-name-5"));
// ...
```

All bundles are run through Webpack in the "production" mode.

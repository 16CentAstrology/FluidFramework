# @fluid-example/clicker

**Clicker** is a Fluid object that displays a number with a button. Pressing the button
increments the counter. This is a basic example using the interface model and stock
classes.

**Clicker** also demonstrates how use the built in taskManager to setup a simple agent.

There is another experimental implementation of Clicker using a WiP Fluid React Component in components/experimental/clicker-react. While it uses a state update model instead of an event-listening model that some React developers may find more familiar, the code is still being developed and may contain bugs.

<!-- AUTO-GENERATED-CONTENT:START (README_EXAMPLE_GETTING_STARTED_SECTION:usesTinylicious=FALSE) -->

<!-- prettier-ignore-start -->
<!-- NOTE: This section is automatically generated using @fluid-tools/markdown-magic. Do not update these generated contents directly. -->

## Getting Started

You can run this example using the following steps:

1. Install [pnpm](https://pnpm.io/) by running `npm i -g pnpm`.
1. Run `pnpm install` and `npm run build:fast -- --nolint` from the `FluidFramework` root directory.
    - For an even faster build, you can add the package name to the build command, like this:
      `npm run build:fast -- --nolint @fluid-example/clicker`
1. Run `npm start` from this directory and open <http://localhost:8080> in a web browser to see the app running.

<!-- prettier-ignore-end -->

<!-- AUTO-GENERATED-CONTENT:END -->

## Testing

```bash
    npm run test:jest
```

For in browser testing update `./jest-puppeteer.config.js` to:

```javascript
  launch: {
    dumpio: true, // output browser console to cmd line
    slowMo: 500,
    headless: false,
  },
```

## Data model

Badge uses the following distributed data structures:

-   SharedDirectory - root

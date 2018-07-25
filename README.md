# \<material-design-typo-explore\>

Quick explore for material design typography.
Hosted on [firebase](https://md-typo-explore.firebaseapp.com/)

If you're interested in this application, clone it and use polymer cli `polymer serve`.

If you're going to deploy it on firebase, first, you need a firebase project.
And `polymer build` to generate bundle files.
Run `firebase deploy`.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

# `preact-scripts-ts` [![npm version](https://badge.fury.io/js/@jerrygreen%2Fpreact-scripts-ts.svg)](https://badge.fury.io/js/@jerrygreen%2Fpreact-scripts-ts)

> Notice: this is a light update of a abondoned [jmfirth/create-preact-app-typescript](https://github.com/jmfirth/create-preact-app-typescript)

Create Preact apps (with Typescript) with no build configuration.

Compressed output:

```
File sizes after gzip:

  8.42 KB  build/static/js/main.c57e6d2d.js
  289 B    build/static/css/main.9a0fe4f1.css
```

## tl;dr

```sh
yarn install -g create-react-app

create-react-app my-app --scripts-version=@jerrygreen/preact-scripts-ts
cd my-app/
yarn start
```

# If you already have a repo

```
yarn install @jerrygreen/preact-scripts-ts
```

## Additional Features

**Code highlighting on error**

When you run `yarn build` the terminal will output the error, including the highlighted sourecode (like babel)!

![CodeHighlight](https://cloud.githubusercontent.com/assets/175278/22310149/1ee66ccc-e346-11e6-83ff-e3a053701fb4.gif)

## Credits

Forked from [jmfirth/create-preact-app-typescript](https://github.com/jmfirth/create-preact-app-typescript).

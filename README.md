# Node package manager benchmark

This benchmark compares the performance of [npm](https://github.com/npm/npm), [pnpm](https://github.com/pnpm/pnpm) and [yarn](https://github.com/yarnpkg/yarn).

## React app

The app's `package.json` [here](./fixtures/react-app/package.json)

| command | time in ms | size in bytes |
| --- | --- | --- |
| npm install | 42.2s | 96.6 MB |
| yarn | 39s | 158 MB |
| pnpm install | 12.8s | 96.9 MB |

## Ember app

The app's `package.json` [here](./fixtures/ember-quickstart/package.json)

| command | time in ms | size in bytes |
| --- | --- | --- |
| npm install | 1m 5.6s | 114 MB |
| yarn | 26.6s | 110 MB |
| pnpm install | 18.5s | 114 MB |

## Angular app

The app's `package.json` [here](./fixtures/angular-quickstart/package.json)

| command | time in ms | size in bytes |
| --- | --- | --- |
| npm install | 36.2s | 93.7 MB |
| yarn | 17s | 86.6 MB |
| pnpm install | 9.7s | 96.5 MB |
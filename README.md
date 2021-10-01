Boltr SDK : Introduction
=====================================
[![Version](https://img.shields.io/npm/v/boltr-sdk)](https://www.npmjs.com/package/boltr-sdk)

![BoltrSDK](https://github.com/boltrswap/Boltr-Swap-SDK/blob/main/boltrGITSDK.jpg) 

**Well created by Boltr Dev. (2021)**


BoltrSDK is a core system behind the Boltrswap DEX on KCC


### Boltr Mission

Our mission is to build the world best decentralize exchange with a high performance trading engine and safety which can be trusted and enjoyed by users. Additionally we want to move the cryptocurrency exchange technology forward by providing support and add new features in the decentralize ecosystem



## Running tests

To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/boltrswap/Boltr-SDK/
```

Move into the Boltr-SDK working directory

```sh
cd  Boltr-SDK
```

Install dependencies

```sh
yarn install
```

Run tests

```sh
yarn test
```

You should see output like the following:

```sh
yarn run v1.22.4
$ tsdx test
 PASS  test/constants.test.ts
 PASS  test/pair.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/entities.test.ts
 PASS  test/trade.test.ts

Test Suites: 1 skipped, 6 passed, 6 of 7 total
Tests:       3 skipped, 82 passed, 85 total
Snapshots:   0 total
Time:        5.091s
Ran all test suites.
✨  Done in 6.61s.
```

# MDEX BSC SDK

Forked from the [Uniswap SDK](https://github.com/Uniswap/uniswap-v2-sdk).

You can refer to the Uniswap SDK documentation [uniswap.org](https://uniswap.org/docs/v2/SDK/getting-started/).

```
FACTORY_ADDRESS = '0x3CD1C46068dAEa5Ebb0d3f55F6915B10648062B8'
ROUTER_ADDRESS = '0x0384E9ad329396C3A6A401243Ca71633B2bC4333'
```

## Running tests

To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/mdexSwap/bsc-sdk.git
```

Move into the bsc-sdk working directory

```sh
cd bsc-sdk/
```

Install dependencies

```sh
yarn
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

Test Suites: 1 skipped, 9 passed, 9 of 10 total
Tests:       3 skipped, 125 passed, 128 total
Snapshots:   0 total
Time:        2.466s, estimated 9s
Ran all test suites.
✨  Done in 5.71s.
```

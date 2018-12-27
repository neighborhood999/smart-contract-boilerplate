# Smart Contract Boilerplate

![smart contract by Solidity](https://flat.badgen.net/badge/ethereum/solidity/grey)

> 🔨 Create smart contract for personal use.

## Installation

```console
$ yarn install
```

## Usage

Delete the local repository and initial:

```shell
$ rm -rf .git
$ git init
```

Change directory to the `contracts` folder and create your contract. Default has the `Ownable` and `Migrations` contract.

## Test

Remove comment and update contract name in `migrations/2_deploy_contract.js` and create the contract test file in the `test` folder and running testrpc:

```shell
$ yarn run ganache
```

then:

```shell
$ yarn test
```

## LICENSE

MIT © [Peng Jie](https://github.com/neighborhood999/)

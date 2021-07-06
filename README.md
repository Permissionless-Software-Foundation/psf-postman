# psf-postman

This is a collection of Postman Collections and an Environment file for working with the bch-api REST API offered by [FullStack.cash](https://fullstack.cash).

- You can [get Postman here](https://www.postman.com/).
- You can install Postman on Linux with `sudo snap install postman`

There is one Collection file, which tells Postman how to interface with bch-api REST API. Load this file first:

- [PSF.postman_collection.json](./PSF.postman_collection.json)

There are three environment files, based on the blockchain you want to work with. BCH is the most popular, and most likely the one you want to work with:

- [BCHN.postman_environment.json](./BCHN.postman_environment.json)
- [ABC.postman_environment.json](./ABC.postman_environment.json)
- [TESTNET.postman_environment.json](./TESTNET.postman_environment.json)

TESTNET is for the testnet3 blockchain, commonly referred to as 'testnet' within BCH. ABC is for the [eCash](https://e.cash) blockchain.

## Installation

1. Download [Postman](https://www.postman.com/)
2. Import Postman Collection: Collections --> Import --> Upload Files --> [PSF.postman_collection.json](./PSF.postman_collection.json)
3. Import the example PSF Environment for FullStack.cash: Environments --> Import --> Upload Files --> [BCHN.postman_environment.json](./BCHN.postman_environment.json)
4. Call any FullStack.cash REST API endpoint.

## Contributing

We're hoping to continuously keep this collection up-to-date with the [bch-api](https://github.com/Permissionless-Software-Foundation/bch-api) REST API, offered through [FullStack.cash](https://fullstack.cash). If you're able to help improve this Postman Collection in any way, first create a feature branch by branching off of `master`, next make the improvements on your feature branch and lastly create a [pull request](https://github.com/Permissionless-Software-Foundation/psf-postman/pulls) to merge your work back in to `master`.

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

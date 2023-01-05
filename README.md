# Updated for a simple minting dapp


## Installation 🛠️

Make sure you have node.js installed so you can use npm, then run:

```sh
npm install
```

## Usage ℹ️

In order to make use of this dapp, all you need to do is change the configurations to point to your smart contract as well as update the images and theme file.

For the most part all the changes will be in the `public` folder.

To link up your existing smart contract, go to the `public/config/config.json` file and update the following fields to fit your smart contract, network and marketplace details. The cost field should be in wei.

Note: this dapp is designed to work with the intended NFT smart contract, that only takes one parameter in the mint function "mintAmount". But you can change that in the App.js file if you need to use a smart contract that takes 2 params.

Make sure you copy the contract ABI from remix and paste it in the `public/config/abi.json` file.

change the theme colors to your liking in the `public/config/theme.css` file.

Remember to update the title and description the `public/index.html` file

Also remember to update the short_name and name fields in the `public/manifest.json` file

After all the changes you can run.

```sh
npm run start
```

Or create the build if you are ready to deploy.

```sh
npm run build
```


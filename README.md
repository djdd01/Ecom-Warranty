#Ecom Warranty <br />
Flipkart Grid 4.0 Problem Statement 2: Blockchain Based Ecommerce Warranty System.

To access Contracts: packages/hardhat/contracts <br />
To access React Frontend: packages/react-app

To run the application: <br />
If you have node.js installed, run the following commands in order. 

npm uninstall -g yarn pnpm <br />
npm install -g corepack <br />
yarn install <br />
yarn chain (keep this terminal open and open a new terminal) <br />
yarn deploy <br />
yarn start <br />

Make sure to add ether to wallet using faucet before creating NFT. <br />
In case the application is stuck on "uploading to nft.storage" <br />
go to https://nft.storage/login/ and create an API key <br />
replace NFT_STORAGE_KEY in packages/react-app/src/constants.js with the API key <br />
Redo steps 4-6

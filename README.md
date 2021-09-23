## JU-PG-Connect

- This is an ethuream based blockchain app which uses the concept of NFT marketspace, that allow you to put up PG rooms and hostels for rent and at the same time allows the students to book the same.

![](./imagae-PG)

### Tools used

- Javascipt
- Solidity
- NextJS
- ReactJS
- Tailwind
- Infura
- Polygon

###Prerequisites

- Chrome
- Metamask Extension for Chrome


### Local setup

To run this project locally, follow these steps.

1. Clone the project locally, change into the directory, and install the dependencies:

```sh
git clone https://github.com/dabit3/polygon-ethereum-nextjs-marketplace.git

cd polygon-ethereum-nextjs-marketplace

# install using NPM or Yarn
npm install

# or

yarn
```

2. Start the local Hardhat node

```sh
npx hardhat node
```

3. With the network running, deploy the contracts to the local network in a separate terminal window

```sh
npx hardhat run scripts/deploy.js --network localhost
```

4. Start the app

```
npm run dev
```

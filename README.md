# NFT_Marketplace

## Installation
### Technology Stack & Tools

- Solidity (Writing Smart Contract)
- Javascript (React & Testing)
- [Ethers](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Pinata](https://app.pinata.cloud/) (NFT storage)

### Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/)
- Install [Hardhat](https://hardhat.org/)
   
### Installation process
### 1. Clone/Download the Repository
- Click the green button on the top right side of the repository and copy HTTPS link.
<img src="/screenshots/2.png" alt="Alt text" title="Optional title">
- Run command line. Choose the directory, where you want to clone the repository. Then run this command: </br>
`
$ git clone <link to the repository> <name of new directory> [optional]
`

</br><img src="/screenshots/3.png" alt="Alt text" title="Optional title">

### 2. Install Dependencies:
```
$ cd marketplace
$ npm install
```
### 3. Connect to Goerli Test Network in Metamask
- Install Metamask if you haven’t already.
- If you have not added Goerli TestNet to the list of networks on your metamask, open up a browser, click the fox icon, then click the top center dropdown button that lists all the available networks then click add networks.
- Next, navigate to  <a href="https://faucets.chain.link/">faucets.chain.link</a>. Connect with your Metamask wallet. Solve the captcha, and click on the "Send 0.1 test ETH" button.
<img src="/screenshots/1.png" alt="Alt text" title="Optional title">

### 4. Migrate Smart Contracts
`$ npx hardhat run /scripts/deploy.js --network goerli`

### 5. Run Tests
`$ npx hardhat test`

### 6. Launch the dAPP
`$ npm run start`

## Usage





## Examples



## License
Contract is released under the [MIT License](LICENSE).

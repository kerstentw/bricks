# Bricks

Bricks is a sandbox and instruction manual collection for building smart contract exploits for Ethereum blockchains, designed to help developers think like hackers in a safe, fun environment.
Use Bricks to:
  - Build malicious blockchain-based ERC-20 assets
  - Test Re-entry Attacks on Example Exchanges
  - Perform Oracle Manipulation and Race Condition Exploits using example Flash Loan providers and margin platforms.

## Requirements
 - Node.js & npm (If you don't have them, don't know, and/or npm command doesn't work in your terminal, install [here](https://nodejs.org/en/))
 - Truffle (npm install -g truffle)
 - Ganache (If you don't have it, install [here](https://www.trufflesuite.com/ganache))
 - Basic understanding of how all of these work.

### Installation

```git clone https://github.com/mikedeshazer/bricks```

Bricks requires [Node.js](https://nodejs.org/) v13+ to run properly

Open Your Ganache application and open a workspace, keeping the default settings and using your bricks directory's truffle-config.js file to start the project from within Ganache. This will create a personal blockchain which responds to this particular project.

Run `truffle migrate` to deploy the smart contracts in the repo and start playing around.

Navigate to the  /manuals folder, and select a .md file tied to a particular exploit you would like to build. The /contracts/kits folder contains all the different kits connected to manuals (same name).



### Development

Want to contribute? Great! Please send any pull requests to the `develop` branch.



### Todos

 - Add more manuals and kits for users to build stuff

License
----

MIT

# Application

## Challenge: KaseiCoin Token Crowdsale

You will create a fungible token that is ERC-20 compliant and that will be minted by using a `Crowdsale` contract from the OpenZeppelin Solidity library.

The crowdsale contract that you create will manage the entire crowdsale process, allowing users to send ether to the contract and in return receive KAI, or KaseiCoin tokens. Your contract will mint the tokens automatically and distribute them to buyers in one transaction.
# Compilation
![CoinCompile.png](/CoinCompile.png "CoinCompile")
![CrowdSaleCompile.png](/CrowdSaleCompile.png "CrowdSaleCompile")


# Deployment
 * Deploy KaseiCoinCrowdsaleDeployer filling in  name,symbol, wallet address (This wallet will recieve sale proceeds)
 * Copy the token address from KaseiCoinCrowdsaleDeployer deployment and Deploy KaseiCoin "at address"
 * Copy the kaseiCrowdsale address from KaseiCoinCrowdsaleDeployer deployment and Deply KaseiCoinCrowdsale using "at address"

![CrowdsaleDeployment.png](/CrowdsaleDeployment.png "CrowdsaleDeployment")

# Link MetaMask and Ganache
   * create a new Ganace Instance
   * Add a local network in Metamask at http://localhost:7545 on chainid 1337
   * Import 2 accounts from the Localnetwork into Metamask to purchase KaseiCoin.
   * Import 1 additional account (wallet used in deplyment) to verify the purchase proceedings.
# Purchase using crowdsale
* Fill in the required number of wei(1:1 KC), add 1st account for purchasing 100000 KC
* Fill in the required number of wei(1:1 KC), add 2nd account for purchasing 200000 KC
* Verify the transcations are pulled into network

![TokenBalances.png](/TokenBalances.png "TokenBalances")

# Verification
## Check the WeiRaised and Total Tokens minted.
![WeiRaisedAndTotalSupply.png](/WeiRaisedAndTotalSupply.png "WeiRaisedAndTotalSupply")
## Make a bigger transaction of 1ETH.
### Verification
![BigTrans.png](/BigTrans.png "BigTrans")
![SalePrompt.png](/SalePrompt.png "SalePrompt")

### Verify on Ganache
![BigGanache.png](/BigGanache.png "BigGanache")
### Verify on Metamask
![BigTransMeta.png](/BigTransMeta.png "BigTransMeta")






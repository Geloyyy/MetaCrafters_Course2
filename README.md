# SheeshGCoin Token (SGC)

This Solidity contract represents the implementation of the **SheeshGCoin (SGC)**, a simple token contract that allows minting and burning of tokens. This project demonstrates basic Solidity functionality, including public variables, mappings, and conditional logic in the `mint` and `burn` functions.

## Description

This contract stores the details of the SheeshGCoin token, including the token name, abbreviation, and total supply. The contract also allows users to mint(AddSupply) new tokens to an address and burn(BurnSupply) tokens from an address. The current total supply is updated dynamically based on these operations.

## Getting Started

### Installing
You will need to do the following to run this contract:
* You can run this Solidity contract on Remix, an online IDE for Solidity smart contracts.
* You can access Remix here: (https://remix.ethereum.org/)

### Executing program

Steps in Remix:
1. Paste the contract code into a new Solidity file.
2. On the left-hand side in Remix, click on the Solidity Compiler tab.
  * Make sure the compiler is set to version 0.8.18.
  * Click on Compile MyToken.sol.
3. After the contract is compiled, go to the Deploy & Run Transactions tab.
  * Deploy the contract by clicking on the Deploy button.
4. Once deployed, you can interact with the contract functions:
  * Minting: Call the addSupply function by providing an address and the number of tokens you want to add.
```
addSupply (address _myAddress, uint _myValue)
```
Upon calling the addsupply function you need to input this, for Example:
```
[Your Test Account ADDRESS] , 5000 
```
This means that you want to Mint/add 5000 supply to your account balance


  * Burning: Call the burnSupply function by providing an address and the number of tokens you want to burn.
```
burnSupply (address _myAddress, uint _myValue)
```
Upon calling the burnsupply function you need to input this, for Example:
```
[Your Test Account ADDRESS] , 4000 
```
This means that you want to Burn/deduct 4000 supply to your account balance
  
  * You can click the supplyStatus to check if you successfully mint or burn supplies from you address
  * You can doucle check it by clicking the balances or totalSuply for you to check the current value/balance that you address has

## Help
1. To find you Account Address:
* Under the Deploy & Run Transactions tab. you can see and copy your ACCOUNT address under the ENVIRONMENT options and above GAS LIMIT options
2. Even though you can check if you successfully burn supply from your balances using supplyStatus, make sure that your address does have enough balance to be burned or else nothing will happen in your current balance.

## Authors

Carl Angelo L. Cruzpero
202110959@fit.edu.ph

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

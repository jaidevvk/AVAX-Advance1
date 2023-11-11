# AVAX-Advance1

In this module, I learnt how to setup my local subnet and deploy the game contract to that subnet.

## Description

In this advance project module , I created a DEFI gaming smart contract which is able to follow the basic ERC20 standard contract functionalities like mint, burn, transfer and also number of items collected function which when called increments the items collected by the player. This smart contract is deployed to the subnet created locally and in the demo video I have showed how I interact with it.

 ## Getting Started
 
 ### Executing the code
 To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., Electricity.sol). Copy and paste the  code into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.19" (or another compatible version), and then click on the "Compile Electricity.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button along with the string input to start the game.

But before you deploy the contract make sure to change the environemt to injected provider metamask and connect your account with test tokens in it.

Once the contract is deployed, you can interact with it .

## Creating a Local Subnet 

Open WSL terminal or zsh terminal and follow this readme file to install Avalanche CLI first : https://github.com/ava-labs/avalanche-cli/blob/main/README.md

After installing CLI , in order to create a subnet :
```
avalanche subnet create <subnetName>
```

```
avalanche subnet deploy <subnetName>
```
 
 ## Authors
 
 Jaidev K[jaidevvk12@gmail.com]
 
 ## License
 
 This project is licensed under the MIT License - see the LICENSE.md file for details
 
 

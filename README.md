# ETH-PROOF---Asssessment

# Creating a Token

Using Solidity 

This Solidity contract represents the "ACES" toke with the token abbrevation "SPACE".
It allows for minting and burning tokens, as well as querying token balances.

# Getting Started 

Excuting the program

To run this program, you can use Remix, an online Solidity IDE. To get started, 
go to the Remix website at https://remix.ethereum.org/.

First of all, you are on the Remix website, create a new file by clicking the file icon on the left sidebar. 
Save the file with the .sol extension (eg. MyToken.sol)

# License 
This contract is realeased under the MIT.

# Prequisities
Solidity version must be 0.8.18 or higher

# Public Variables 
The contract defines the following by the public variables

tokenName: A string variable representing the name of token
("ACES").
tokenAbbrv: A string variable representing the namme of token abbreviation
("SPACE").
totalSupply: An unsigned interger variables that represent the totalSupply

# Mapping
To store token balances for each address, the contract makes use of the 
balances mapping variables.

# Functon 
New tokens can be created and sent to a specific address using 
the mint function.

function mint(address _address, uint_value) public 
the mint function performs the following steps:
Increase tbe totalSupply by the specified_value.
Adds the value to the balances mapping for the _address.

# Burn Function
The burn function it's allow to elimination of the token from as specified address 
only performs the burn operations if the _address has enough for the token balances

# Run / Deploy
Using a wallet or contract interfaces you can deploy this contract to a blockchain
network that compatible and interact with through fucntiion calls. It's a basic 
implementation focusing on the minting,burning and querying balances.

# Authors 
Jencen Wee
8212778@ntc.edu.ph

# License 
This project is licensed under the MIT License - see the LICENSE.md file for details

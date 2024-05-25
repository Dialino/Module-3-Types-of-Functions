# Module-3-Types-of-Functions

# Description
JackyToken is a Solidity smart contract that implements an ERC20 token. It extends the functionality of the ERC20 standard token by providing additional functions such as minting, burning, and transfer and transferFrom.

# Getting Started
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., JackyToken.sol). Copy and paste the following code into the file:

# Code Explaination
The mint() function is used to create new tokens and add them to the total supply. This function typically increases the balance of a specified address and the total supply of the token.

The burn() function is used to destroy tokens, reducing the total supply. This function decreases the balance of the caller and the total supply of the token.

The transfer() function is used to send tokens from the caller’s address to another address. It is the basic function for transferring tokens between accounts.

The transferFrom() function is used to transfer tokens on behalf of another address, typically used in conjunction with allowances set by the approve() function. It allows a spender to transfer tokens from the owner’s account.

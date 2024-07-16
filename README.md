# MyWSTtoken Smart Contract
## Description
This program defines a Solidity smart contract named MyWSTtoken, which implements the ERC20 token standard and inherits functionalities from OpenZeppelin's ERC20 and Ownable contracts. The contract initializes a token named "WEST" with symbol "WST" and mints 10,000 tokens to the deployer's address upon deployment. It includes additional functionalities for token transfers, burning tokens, and minting new tokens, with access control enforced through the Ownable contract.

# Getting Started
## Executing the program
To deploy and interact with this contract, you can use Remix, an online Solidity IDE. Visit https://remix.ethereum.org/ and follow these steps:

1. Create a new file named MyWSTtoken.sol.
2. Copy and paste the provided Solidity code into the file.
3. Ensure the compiler version is set to 0.8.18.
4. Compile the contract by clicking on the "Solidity Compiler" tab and then "Compile MyWSTtoken.sol".
5. Deploy the contract using the "Deploy & Run Transactions" tab, ensuring to select MyWSTtoken from the contract dropdown.
6. After deployment, interact with the contract through its functions.

## Interacting with the Contract
- **transfer(address recipient, uint256 amount)**: Transfers tokens from the caller's address to the recipient.
- **burn(uint256 amount)**: Destroys tokens from the caller's address, reducing the total supply.
- **mint(address account, uint256 amount)**: Creates new tokens and adds them to the specified account. Only accessible by the contract owner.

# Authors
West Pagbilao
GitHub: @WestPagbilao4

# License
This project is licensed under the MIT License. See the LICENSE file for details.

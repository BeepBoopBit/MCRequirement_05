# MyERC20Token

This repository contains a simple ERC-20 token contract written in Solidity.

## Contract Details

- **Token Name:** MyTokenName
- **Token Symbol:** MTK
- **Decimals:** 22
- **Initial Supply:** Specified during contract deployment


## Usage

To run the program, you can use Remix, an online Solidity IDE to get started. Here's the step-by-step instruction on how to make this work:

1. Open Remix (https://remix.etherum.org)
2. Copy the `main.sol` in the text editor inside remix
3. Compile the code with compiler set to 0.8.9+
4. Deploy and Run The Code

## Testing


After deploying the code, you should be able to `Deploy & Run Transactions` using the contract. Click the `Deploy` button and you'll see under `Deployed/Unpin Contract` your deployed contract. You can then proceed to test the code there using the UI they provide for testing how it works.

You can test most of the function specified at [Public Function](###Public Function)

## Functions

### Public Functions

- **totalSupply:** Returns the total supply of the tokens.
- **balanceOf:** Returns the token balance of a given account.
- **transfer:** Transfers a specified amount of tokens to a recipient.
- **allowance:** Returns the remaining number of tokens that the spender is allowed to spend on behalf of the owner.
- **approve:** Approves a spender to spend a specified amount of tokens on behalf of the message sender.
- **transferFrom:** Transfers a specified amount of tokens from one account to another, given the sender has been approved to spend the amount.

### Owner-Only Functions

- **updateOwner:** Updates the owner of the contract.
- **mint:** Mints new tokens to the owner's account.
- **burn:** Burns a specified amount of tokens from the owner's account.

### Internal Functions

- **_transfer:** Handles the transfer of tokens between accounts.
- **_approve:** Handles the approval of a spender to spend a specified amount of tokens on behalf of the owner.
- **_mint:** Handles the minting of new tokens.
- **_burn:** Handles the burning of tokens.

## Events

- **Transfer:** Emitted when tokens are transferred from one account to another.
- **Approval:** Emitted when an account approves a spender to spend tokens on its behalf.

## Deployment

To deploy the contract, provide an initial supply value. The contract deployer will be assigned as the owner of the contract.

## Author

Renz Angelo Aguirre

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


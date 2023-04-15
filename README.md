# Token
This contract can be deployed on the Ethereum blockchain and used to create a new token named "Meta" with the ability to mint and burn tokens. The token can then be used for various purposes.

# Overview
This contract use Solidity version 0.8.18
1. This contract have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
2. This contract have a mapping of addresses to balances (address => uint)
3. We have a mint function that takes two parameters: an address and a value. 
   The function then increases the total supply by that number and increases the balance of the “sender” address by that amount
4. This contract have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
   It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
   and from the balance of the “sender”.
5. Lastly, the burn function's conditional statements are there to make sure the balance of "sender" is greater than or equal 
   to the amount that is supposed to be burned.
   
# Description
This project is a simple token contract written in Solidity, a programming language used for creating smart contracts on the Ethereum blockchain. The purpose of the contract is to provide a basic implementation for a token named "Meta" with the ability to mint (create) and burn (destroy) tokens.

The mint function allows the contract owner to create new tokens and assign them to a specific address. This function is useful in scenarios where new tokens need to be created, such as in an initial coin offering (ICO) or to reward users for certain actions.

On the other hand, the burn function allows the contract owner to destroy existing tokens from a specific address. This function is useful in scenarios where tokens need to be removed from circulation, such as when a user wants to sell their tokens back to the contract owner or if tokens are lost or stolen.

# Conclusion
Overall, this contract can be used as a starting point for creating a more complex token contract that includes additional features such as token transfers, token locking, and voting.

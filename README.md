# Solidity-Token
This is a sample token created using Solidity Programming Language

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

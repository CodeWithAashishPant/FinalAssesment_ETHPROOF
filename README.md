# FinalAssesment_ETHPROOF

This Solidity contract implements a basic token with the following features:

# Public Variables:
1) TokenName: Stores the token's human-readable name ("TheMyToken" by default).
2) TokenAbbrv: Represents the token's abbreviation ("TMT" by default).
3) TotalSupply: Tracks the total number of tokens in circulation, initially set to 0.
   
# Balance Mapping:
balance: A public mapping that stores the token balance for each address.

# Minting Functionality:
mint(address _address, uint _value): Allows authorized parties to create new tokens and add them to the recipient's address (_address) and the total supply.

# Burning Functionality:
burn(address _address, uint _value): Enables the burning of tokens, effectively removing them from the total supply and the balance of the specified address (_address). 
It includes a safety check (require statement) to ensure sufficient balance before burning.

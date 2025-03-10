---
id: IERC20hTokenBranch
title: IERC20hTokenBranch
---

**Author:**
MaiaDAO.

ERC20 hToken contract deployed in the Branch Chains of the Ulysses Omnichain Liquidity System.
1:1 ERC20 representation of a token deposited in a  Branch Chain's Port. Is only minted upon
user request otherwise underlying tokens are cleared and the matching Root hToken has been burned.


## Functions
### mint

Function to mint tokens in the Branch Chain.


```solidity
function mint(address account, uint256 amount) external returns (bool);
```
**Parameters**

|Name|Type|Description|
|----|----|-----------|
|`account`|`address`|Address of the account to receive the tokens.|
|`amount`|`uint256`|Amount of tokens to be minted.|

**Returns**

|Name|Type|Description|
|----|----|-----------|
|`<none>`|`bool`|Boolean indicating if the operation was successful.|


### burn

Function to burn tokens in the Branch Chain.


```solidity
function burn(uint256 value) external;
```
**Parameters**

|Name|Type|Description|
|----|----|-----------|
|`value`|`uint256`|Amount of tokens to be burned.|



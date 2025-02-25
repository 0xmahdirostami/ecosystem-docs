---
id: VirtualAccount
title: VirtualAccount
---

**Inherits:**
[IVirtualAccount](./interfaces/IVirtualAccount)

## State Variables

### userAddress

Returns the address of the user that owns the VirtualAccount.

```solidity
address public immutable userAddress;
```

### localPortAddress

Returns the address of the local port.

```solidity
address public localPortAddress;
```

## Functions

### constructor

```solidity
constructor(address _userAddress, address _localPortAddress);
```

### withdrawERC20

Withdraws ERC20 tokens from the VirtualAccount.

```solidity
function withdrawERC20(address _token, uint256 _amount) external requiresApprovedCaller;
```

**Parameters**

| Name      | Type      | Description                                 |
| --------- | --------- | ------------------------------------------- |
| `_token`  | `address` | The address of the ERC20 token to withdraw. |
| `_amount` | `uint256` | The amount of tokens to withdraw.           |

### withdrawERC721

Withdraws ERC721 tokens from the VirtualAccount.

```solidity
function withdrawERC721(address _token, uint256 _tokenId) external requiresApprovedCaller;
```

**Parameters**

| Name       | Type      | Description                                  |
| ---------- | --------- | -------------------------------------------- |
| `_token`   | `address` | The address of the ERC721 token to withdraw. |
| `_tokenId` | `uint256` | The id of the token to withdraw.             |

### call

```solidity
function call(Call[] calldata calls)
    external
    requiresApprovedCaller
    returns (uint256 blockNumber, bytes[] memory returnData);
```

**Parameters**

| Name    | Type     | Description |
| ------- | -------- | ----------- |
| `calls` | `Call[]` |             |

### onERC721Received

```solidity
function onERC721Received(address, address, uint256, bytes calldata) external pure override returns (bytes4);
```

### requiresApprovedCaller

Modifier that verifies msg sender is the approved to use the virtual account. Either the owner or an approved router.

```solidity
modifier requiresApprovedCaller();
```

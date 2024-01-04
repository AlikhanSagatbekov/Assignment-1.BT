# AITU_Alikhan Token

This is a simple ERC-20 token named "Coin" with symbol "cn" created by AITU_Alikhan. The contract includes additional functionality to retrieve transaction information.

## Usage

1. Deploy the contract on a Ethereum-compatible blockchain.
2. Interact with the contract using your preferred Ethereum wallet or through a smart contract interaction tool.
3. Use the following functions to retrieve transaction information:
   - `getLatestTransactionTimestamp`: Returns the current block timestamp in hours, minutes, and seconds.
   - `getAddressTransactionSender`: Returns the address of the transaction sender.
   - `getTransactionReceiver`: Returns the address of the contract itself (receiver).

## Demo Screenshots

Include screenshots or gifs here to showcase the usage of the contract, such as deploying the contract, calling the functions, and receiving the emitted events.

![2024-01-04_23-37-45](https://github.com/AlikhanSagatbekov/Assignment-1.BT/assets/129541689/844d1275-3af8-442a-ae45-7a4677835315)

![2024-01-04_23-40-44](https://github.com/AlikhanSagatbekov/Assignment-1.BT/assets/129541689/6ef18e13-7a09-4db1-a92f-d24754ddef4f)


## Examples

### Getting the Latest Transaction Timestamp

```javascript
// Use a contract interaction tool or a script to call the function
let timestamp = await contract.getLatestTransactionTimestamp();
console.log("Current Block Timestamp:", timestamp);
```

### Getting the Transaction Sender's Address

```javascript
// Use a contract interaction tool or a script to call the function
let senderAddress = await contract.getAddressTransactionSender();
console.log("Transaction Sender Address:", senderAddress);
```

### Getting the Transaction Receiver's Address

```javascript
// Use a contract interaction tool or a script to call the function
let receiverAddress = await contract.getTransactionReceiver();
console.log("Transaction Receiver Address:", receiverAddress);
```

Make sure to replace `contract` with the actual instance of your deployed contract in these examples.

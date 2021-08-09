# Hackathon: Nervos - Broaden the Spectrum

## Gitcoin: 3) Issue A Smart Contract Call To The Deployed Smart Contract

1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
   ![image](https://github.com/MrJacobSullivan/nervos/blob/main/submissions/task_3/call-contract.png?raw=true)

2. The transaction hash from the console output (in text format).
   `0xf684d718f01bea9e20152492c1b3672ec1e6e12aaaaeb038fbab6db69c4e4140`

3. The contract address that you called (in text format).
   `0xEE11af32d86032f15592f321E108d80b60d53682`

4. The ABI for contract you made a call on (in text format).

```
[
  {
    "inputs": [],
    "stateMutability": "payable",
    "type": "constructor"
  },
  {
    "inputs": [
      {
        "internalType": "uint256",
        "name": "x",
        "type": "uint256"
      }
    ],
    "name": "set",
    "outputs": [],
    "stateMutability": "payable",
    "type": "function"
  },
  {
    "inputs": [],
    "name": "get",
    "outputs": [
      {
        "internalType": "uint256",
        "name": "",
        "type": "uint256"
      }
    ],
    "stateMutability": "view",
    "type": "function"
  }
]
```

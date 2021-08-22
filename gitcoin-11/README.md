### Use A Tron Wallet To Execute A Smart Contract Call (gitcoin-11)


### 1-) A screenshot of the accounts you created

<img src="https://github.com/wizardlog/gitcoin-nervos-hackacton/blob/master/gitcoin-11/ss1.png" />


### 2-) A link to the Layer 1 address you funded on the Testnet Explorer

<a href="https://explorer.nervos.org/aggron/address/ckt1qyqys7mc4wfyqw6z8znc5j4wep5zddcf7e2ssfr6nw" > Explorer link </a>

### 3-) A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2

<img src="https://github.com/wizardlog/gitcoin-nervos-hackacton/blob/master/gitcoin-11/ss2.png" />

### 4-) A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

<img src="https://github.com/wizardlog/gitcoin-nervos-hackacton/blob/master/gitcoin-11/ss3.png" />

### 5) The transaction hash of the "Contract call" from the console output

```bash
0x7d5bc90744f5890d8c13ad347166dfd4e5cc3e31674d6b0d1d7546baeb9b847f
```
### 6) The contract address that you called

```bash
0x5Edb8E79E57abE3C00438b5aE2Bd638DD4595D3b
```

### 7) The ABI for contract you made a call on

```javascript
[
    {
      "inputs": [],
      "stateMutability": "nonpayable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "ideas",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "internalType": "uint256",
          "name": "topicId",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "comment",
          "type": "string"
        },
        {
          "internalType": "address",
          "name": "creator",
          "type": "address"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "topics",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "internalType": "address",
          "name": "creator",
          "type": "address"
        },
        {
          "internalType": "string",
          "name": "title",
          "type": "string"
        },
        {
          "internalType": "uint256",
          "name": "totalTopicIdea",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "totalIdeas",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "totalTopics",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_title",
          "type": "string"
        }
      ],
      "name": "createTopic",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "_topicId",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "_comment",
          "type": "string"
        }
      ],
      "name": "addIdeaToTopic",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "_topicId",
          "type": "uint256"
        }
      ],
      "name": "fetchTopicIdeas",
      "outputs": [
        {
          "components": [
            {
              "internalType": "uint256",
              "name": "id",
              "type": "uint256"
            },
            {
              "internalType": "uint256",
              "name": "topicId",
              "type": "uint256"
            },
            {
              "internalType": "string",
              "name": "comment",
              "type": "string"
            },
            {
              "internalType": "address",
              "name": "creator",
              "type": "address"
            }
          ],
          "internalType": "struct Discussion.Idea[]",
          "name": "",
          "type": "tuple[]"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]

```

### 8) Your Tron address

```bash
TNT6ALNXckQnkS9gFE68E4mCz5kkxUtM88
```

### Port An Existing Ethereum DApp To Polyjuice (gitcoin-7)

# Unstoppable Discussion by Nervos

### 1-) Screenshot and Video

- <a href="https://youtu.be/NZ_vwTvIKZA" > YOUTUBE VIDEO </a>

<img src="https://github.com/wizardlog/gitcoin-nervos-hackacton/blob/master/gitcoin-7/a1.png" />
<hr/>
<img src="https://github.com/wizardlog/gitcoin-nervos-hackacton/blob/master/gitcoin-7/a2.png" />
<hr/>
<img src="https://github.com/wizardlog/gitcoin-nervos-hackacton/blob/master/gitcoin-7/a3.png" />
<hr/>

### 2-) Project Github Repo

- <a href="https://github.com/wizardlog/unstoppable-discussion-gitcoin7" > SOURCE CODE </a>

### 3-) Transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract

Transaction hash:

```bash
0x6bd007adcaefeb21e321683321fce8f13f8b63066355d5ca1c6ccf3c565681fc
```

Deployed Contract Address:

```bash
0x5Edb8E79E57abE3C00438b5aE2Bd638DD4595D3b
```

ABI:

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

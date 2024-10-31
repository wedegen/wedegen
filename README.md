# TokenFactory - Token Creation API

### TokenFactory Contract Addresses
- **Base network**: `0xf9a2ca80aee0002e04a6e94283411c24a4fb55db`
- **World network**: `0x60c4cEED9014a233cd8839F18f81Dbe32AA0F384`
- **Ethereum network**: To be determined
---

### Benchmark Token Contract
- **Base network (DEGEN)**: `0x4ed4E862860beD51a9570b96d89aF5E1B0Efefed`
- **World network (WLD)**: `0x2cFc85d8E48F8EAB294be644d9E25C3030863003`
- **Ethereum network (SHIB)**: `0x95ad61b0a150d79219dcf64e1e6cc01f0b64c4ce`
---

### Swap Router Addresses
- **World network**: `0x541aB7c31A119441eF3575F6973277DE0eF460bd`
- **Base network**: `0x4752ba5DBc23f44D87826276BF6Fd6b1C372aD24`
- **Ethereum network**: `0x4752ba5DBc23f44D87826276BF6Fd6b1C372aD24`
---

### Method: `createToken`
**Description**: Used to create an AI social meme token contract.

#### Parameters

| Parameter   | Description                | Type     | Constraints          |
|-------------|----------------------------|----------|----------------------|
| `name`      | Token name                 | `string` | Length: 2-20 chars   |
| `symbol`    | Token symbol               | `string` | Length: 2-20 chars   |
| `image`     | Token icon                 | `string` | -                    |
| `desc`      | Token description          | `string` | -                    |
| `website`   | Social - Official website link | `string` | URL format expected  |
| `warpcaster`| Social - Warpcaster link   | `string` | URL format expected  |
| `telegram`  | Social - Telegram link     | `string` | URL format expected  |
| `twitter`   | Social - Twitter link      | `string` | URL format expected  |

#### Method ABI: `createToken`  (JSON format)
```json
{
  "inputs": [
    {
      "internalType": "string",
      "name": "name",
      "type": "string"
    },
    {
      "internalType": "string",
      "name": "symbol",
      "type": "string"
    },
    {
      "internalType": "string",
      "name": "image",
      "type": "string"
    },
    {
      "internalType": "string",
      "name": "desc",
      "type": "string"
    },
    {
      "internalType": "string",
      "name": "website",
      "type": "string"
    },
    {
      "internalType": "string",
      "name": "warpcaster",
      "type": "string"
    },
    {
      "internalType": "string",
      "name": "telegram",
      "type": "string"
    },
    {
      "internalType": "string",
      "name": "twitter",
      "type": "string"
    }
  ],
  "name": "createToken",
  "outputs": [],
  "stateMutability": "payable",
  "type": "function"
}
```

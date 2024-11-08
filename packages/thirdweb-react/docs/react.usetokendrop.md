<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@thirdweb-dev/react](./react.md) &gt; [useTokenDrop](./react.usetokendrop.md)

## useTokenDrop() function

Hook for getting an instance of a `Token Drop` contract.

<b>Signature:</b>

```typescript
export declare function useTokenDrop(contractAddress?: string): TokenDrop | undefined;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  contractAddress | string | <i>(Optional)</i> the address of the Token Drop contract, found in your thirdweb dashboard |

<b>Returns:</b>

TokenDrop \| undefined

## Example


```javascript
import { useTokenDrop } from '@thirdweb-dev/react'

export default function Component() {
  const tokenDrop = useTokenDrop("<YOUR-CONTRACT-ADDRESS>")

  // Now you can use the token drop contract in the rest of the component

  // For example, this function will get the connected wallets token balance
  async function balance() {
    const balance = await tokenDrop.balance()
    return balance
  }

  ...
}
```


<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@thirdweb-dev/react](./react.md) &gt; [useSignatureDrop](./react.usesignaturedrop.md)

## useSignatureDrop() function

Hook for getting an instance of an `SignatureDrop` contract. This contract is meant to interface with ERC721 compliant NFTs that can be lazily minted.

<b>Signature:</b>

```typescript
export declare function useSignatureDrop(contractAddress?: string): SignatureDrop | undefined;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  contractAddress | string | <i>(Optional)</i> the address of the NFT Drop contract, found in your thirdweb dashboard |

<b>Returns:</b>

SignatureDrop \| undefined

## Example


```javascript
import { useSignatureDrop } from '@thirdweb-dev/react'

export default function Component() {
  const signatureDrop = useSignatureDrop("<YOUR-CONTRACT-ADDRESS>")

  // Now you can use the Signature drop contract in the rest of the component

  // For example, this function will let the connected wallet claim a new NFT
  async function claim(quantity) {
    await signatureDrop.claim(quantity)
  }

  ...
}
```


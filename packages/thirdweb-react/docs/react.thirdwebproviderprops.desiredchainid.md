<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@thirdweb-dev/react](./react.md) &gt; [ThirdwebProviderProps](./react.thirdwebproviderprops.md) &gt; [desiredChainId](./react.thirdwebproviderprops.desiredchainid.md)

## ThirdwebProviderProps.desiredChainId property

The chainId that your dApp is running on. While this \*can\* be `undefined` it is required to be passed. Passing `undefined` will cause no SDK to be instantiated. When passing a chainId, it \*\*must\*\* be part of the `supportedChains` array.

<b>Signature:</b>

```typescript
desiredChainId: TSupportedChain extends Chain ? TSupportedChain["id"] : TSupportedChain | undefined;
```

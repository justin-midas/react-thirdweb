<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@thirdweb-dev/react](./react.md) &gt; [useTokenBalance](./react.usetokenbalance.md)

## useTokenBalance() function

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 

Use this to get the balance of your  contract for a given address.

<b>Signature:</b>

```typescript
export declare function useTokenBalance(contract: RequiredParam<Erc20>, walletAddress: RequiredParam<WalletAddress>): import("@tanstack/react-query").UseQueryResult<{
    symbol: string;
    value: import("ethers").BigNumber;
    name: string;
    decimals: number;
    displayValue: string;
}, unknown>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  contract | [RequiredParam](./react.requiredparam.md)<!-- -->&lt;Erc20&gt; | an instance of a Token contract. |
|  walletAddress | [RequiredParam](./react.requiredparam.md)<!-- -->&lt;[WalletAddress](./react.walletaddress.md)<!-- -->&gt; |  |

<b>Returns:</b>

import("@tanstack/react-query").UseQueryResult&lt;{ symbol: string; value: import("ethers").BigNumber; name: string; decimals: number; displayValue: string; }, unknown&gt;

a response object that includes the balance of the address

## Example


```javascript
const { data: balance, isLoading, error } = useTokenBalance(<YourTokenContractInstance>);
```

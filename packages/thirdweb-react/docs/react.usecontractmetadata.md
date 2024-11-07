<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@thirdweb-dev/react](./react.md) &gt; [useContractMetadata](./react.usecontractmetadata.md)

## useContractMetadata() function

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 

Use this to get the contract metadata for a (built-in or custom) contract.

<b>Signature:</b>

```typescript
export declare function useContractMetadata(contractAddress: RequiredParam<ContractAddress>): import("@tanstack/react-query").UseQueryResult<{
    [x: string]: import("@thirdweb-dev/sdk").Json;
    description?: string | undefined;
    image?: any;
    external_link?: string | undefined;
    name: string;
}, unknown>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  contractAddress | [RequiredParam](./react.requiredparam.md)<!-- -->&lt;[ContractAddress](./react.contractaddress.md)<!-- -->&gt; | the address of the deployed contract |

<b>Returns:</b>

import("@tanstack/react-query").UseQueryResult&lt;{ \[x: string\]: import("@thirdweb-dev/sdk").Json; description?: string \| undefined; image?: any; external\_link?: string \| undefined; name: string; }, unknown&gt;

a response object that includes the contract metadata of the deployed contract

## Example


```javascript
const { data: contractMetadata, isLoading, error } = useContractMetadata("{{contract_address}}");
```

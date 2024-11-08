<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@thirdweb-dev/react](./react.md) &gt; [useCreateDirectListing](./react.usecreatedirectlisting.md)

## useCreateDirectListing() function

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 

Use this to create a new Direct Listing on your marketplace contract.

<b>Signature:</b>

```typescript
export declare function useCreateDirectListing(contract: RequiredParam<Marketplace>): import("@tanstack/react-query").UseMutationResult<import("@thirdweb-dev/sdk").TransactionResultWithId<never>, unknown, NewDirectListing, unknown>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  contract | [RequiredParam](./react.requiredparam.md)<!-- -->&lt;Marketplace&gt; | an instance of a Marketplace contract |

<b>Returns:</b>

import("@tanstack/react-query").UseMutationResult&lt;import("@thirdweb-dev/sdk").TransactionResultWithId&lt;never&gt;, unknown, NewDirectListing, unknown&gt;

a mutation object that can be used to create a new direct listing

## Example


```jsx
const Component = () => {
  const {
    mutate: createDirectListing,
    isLoading,
    error,
  } = useCreateDirectListing(">>YourMarketplaceContractInstance<<");

  if (error) {
    console.error("failed to create direct listing", error);
  }

  return (
    <button
      disabled={isLoading}
      onClick={() => createDirectListing(directListingData)}
    >
      Create Direct Listing!
    </button>
  );
};
```


<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@thirdweb-dev/react](./react.md) &gt; [useContract](./react.usecontract.md)

## useContract() function

Use this resolve a contract address to a smart contract instance.

<b>Signature:</b>

```typescript
export declare function useContract(contractAddress: RequiredParam<ContractAddress>): {
    contract: null;
    data: undefined;
    error: unknown;
    isError: true;
    isLoading: false;
    isLoadingError: true;
    isRefetchError: false;
    isSuccess: false;
    status: "error";
    dataUpdatedAt: number;
    errorUpdatedAt: number;
    failureCount: number;
    errorUpdateCount: number;
    isFetched: boolean;
    isFetchedAfterMount: boolean;
    isFetching: boolean;
    isPaused: boolean;
    isPlaceholderData: boolean;
    isPreviousData: boolean;
    isRefetching: boolean;
    isStale: boolean;
    refetch: <TPageData>(options?: (import("@tanstack/react-query").RefetchOptions & import("@tanstack/react-query").RefetchQueryFilters<TPageData>) | undefined) => Promise<import("@tanstack/react-query").QueryObserverResult<{
        contractType: "split" | "nft-drop" | "signature-drop" | "nft-collection" | "edition-drop" | "edition" | "token-drop" | "token" | "vote" | "marketplace" | "pack" | "multiwrap" | undefined;
        compilerMetadata: null;
    } | {
        contractType: "custom";
        compilerMetadata: {
            name: string;
            metadata: Record<string, any>;
            abi: {
                [x: string]: any;
                type: string;
                name: string;
                outputs: {
                    [x: string]: any;
                    components?: {
                        [x: string]: any;
                        type: string;
                        name: string;
                    }[] | undefined;
                    stateMutability?: string | undefined;
                    type: string;
                    name: string;
                }[];
                inputs: {
                    [x: string]: any;
                    components?: {
                        [x: string]: any;
                        type: string;
                        name: string;
                    }[] | undefined;
                    stateMutability?: string | undefined;
                    type: string;
                    name: string;
                }[];
            }[];
            info: {
                title?: string | undefined;
                author?: string | undefined;
                details?: string | undefined;
                notice?: string | undefined;
            };
            licenses: string[];
        } | undefined;
    } | undefined, unknown>>;
    remove: () => void;
    fetchStatus: import("@tanstack/react-query").FetchStatus;
} | {
    contract: null;
    data: undefined;
    error: null;
    isError: false;
    isLoading: true;
    isLoadingError: false;
    isRefetchError: false;
    isSuccess: false;
    status: "loading";
    dataUpdatedAt: number;
    errorUpdatedAt: number;
    failureCount: number;
    errorUpdateCount: number;
    isFetched: boolean;
    isFetchedAfterMount: boolean;
    isFetching: boolean;
    isPaused: boolean;
    isPlaceholderData: boolean;
    isPreviousData: boolean;
    isRefetching: boolean;
    isStale: boolean;
    refetch: <TPageData>(options?: (import("@tanstack/react-query").RefetchOptions & import("@tanstack/react-query").RefetchQueryFilters<TPageData>) | undefined) => Promise<import("@tanstack/react-query").QueryObserverResult<{
        contractType: "split" | "nft-drop" | "signature-drop" | "nft-collection" | "edition-drop" | "edition" | "token-drop" | "token" | "vote" | "marketplace" | "pack" | "multiwrap" | undefined;
        compilerMetadata: null;
    } | {
        contractType: "custom";
        compilerMetadata: {
            name: string;
            metadata: Record<string, any>;
            abi: {
                [x: string]: any;
                type: string;
                name: string;
                outputs: {
                    [x: string]: any;
                    components?: {
                        [x: string]: any;
                        type: string;
                        name: string;
                    }[] | undefined;
                    stateMutability?: string | undefined;
                    type: string;
                    name: string;
                }[];
                inputs: {
                    [x: string]: any;
                    components?: {
                        [x: string]: any;
                        type: string;
                        name: string;
                    }[] | undefined;
                    stateMutability?: string | undefined;
                    type: string;
                    name: string;
                }[];
            }[];
            info: {
                title?: string | undefined;
                author?: string | undefined;
                details?: string | undefined;
                notice?: string | undefined;
            };
            licenses: string[];
        } | undefined;
    } | undefined, unknown>>;
    remove: () => void;
    fetchStatus: import("@tanstack/react-query").FetchStatus;
} | {
    contract: import("@thirdweb-dev/sdk").SmartContract<import("ethers").BaseContract> | null;
    data: {
        contractType: "split" | "nft-drop" | "signature-drop" | "nft-collection" | "edition-drop" | "edition" | "token-drop" | "token" | "vote" | "marketplace" | "pack" | "multiwrap" | undefined;
        compilerMetadata: null;
    } | {
        contractType: "custom";
        compilerMetadata: {
            name: string;
            metadata: Record<string, any>;
            abi: {
                [x: string]: any;
                type: string;
                name: string;
                outputs: {
                    [x: string]: any;
                    components?: {
                        [x: string]: any;
                        type: string;
                        name: string;
                    }[] | undefined;
                    stateMutability?: string | undefined;
                    type: string;
                    name: string;
                }[];
                inputs: {
                    [x: string]: any;
                    components?: {
                        [x: string]: any;
                        type: string;
                        name: string;
                    }[] | undefined;
                    stateMutability?: string | undefined;
                    type: string;
                    name: string;
                }[];
            }[];
            info: {
                title?: string | undefined;
                author?: string | undefined;
                details?: string | undefined;
                notice?: string | undefined;
            };
            licenses: string[];
        } | undefined;
    } | undefined;
    error: unknown;
    isError: true;
    isLoading: false;
    isLoadingError: false;
    isRefetchError: true;
    isSuccess: false;
    status: "error";
    dataUpdatedAt: number;
    errorUpdatedAt: number;
    failureCount: number;
    errorUpdateCount: number;
    isFetched: boolean;
    isFetchedAfterMount: boolean;
    isFetching: boolean;
    isPaused: boolean;
    isPlaceholderData: boolean;
    isPreviousData: boolean;
    isRefetching: boolean;
    isStale: boolean;
    refetch: <TPageData>(options?: (import("@tanstack/react-query").RefetchOptions & import("@tanstack/react-query").RefetchQueryFilters<TPageData>) | undefined) => Promise<import("@tanstack/react-query").QueryObserverResult<{
        contractType: "split" | "nft-drop" | "signature-drop" | "nft-collection" | "edition-drop" | "edition" | "token-drop" | "token" | "vote" | "marketplace" | "pack" | "multiwrap" | undefined;
        compilerMetadata: null;
    } | {
        contractType: "custom";
        compilerMetadata: {
            name: string;
            metadata: Record<string, any>;
            abi: {
                [x: string]: any;
                type: string;
                name: string;
                outputs: {
                    [x: string]: any;
                    components?: {
                        [x: string]: any;
                        type: string;
                        name: string;
                    }[] | undefined;
                    stateMutability?: string | undefined;
                    type: string;
                    name: string;
                }[];
                inputs: {
                    [x: string]: any;
                    components?: {
                        [x: string]: any;
                        type: string;
                        name: string;
                    }[] | undefined;
                    stateMutability?: string | undefined;
                    type: string;
                    name: string;
                }[];
            }[];
            info: {
                title?: string | undefined;
                author?: string | undefined;
                details?: string | undefined;
                notice?: string | undefined;
            };
            licenses: string[];
        } | undefined;
    } | undefined, unknown>>;
    remove: () => void;
    fetchStatus: import("@tanstack/react-query").FetchStatus;
} | {
    contract: import("@thirdweb-dev/sdk").SmartContract<import("ethers").BaseContract> | null;
    data: {
        contractType: "split" | "nft-drop" | "signature-drop" | "nft-collection" | "edition-drop" | "edition" | "token-drop" | "token" | "vote" | "marketplace" | "pack" | "multiwrap" | undefined;
        compilerMetadata: null;
    } | {
        contractType: "custom";
        compilerMetadata: {
            name: string;
            metadata: Record<string, any>;
            abi: {
                [x: string]: any;
                type: string;
                name: string;
                outputs: {
                    [x: string]: any;
                    components?: {
                        [x: string]: any;
                        type: string;
                        name: string;
                    }[] | undefined;
                    stateMutability?: string | undefined;
                    type: string;
                    name: string;
                }[];
                inputs: {
                    [x: string]: any;
                    components?: {
                        [x: string]: any;
                        type: string;
                        name: string;
                    }[] | undefined;
                    stateMutability?: string | undefined;
                    type: string;
                    name: string;
                }[];
            }[];
            info: {
                title?: string | undefined;
                author?: string | undefined;
                details?: string | undefined;
                notice?: string | undefined;
            };
            licenses: string[];
        } | undefined;
    } | undefined;
    error: null;
    isError: false;
    isLoading: false;
    isLoadingError: false;
    isRefetchError: false;
    isSuccess: true;
    status: "success";
    dataUpdatedAt: number;
    errorUpdatedAt: number;
    failureCount: number;
    errorUpdateCount: number;
    isFetched: boolean;
    isFetchedAfterMount: boolean;
    isFetching: boolean;
    isPaused: boolean;
    isPlaceholderData: boolean;
    isPreviousData: boolean;
    isRefetching: boolean;
    isStale: boolean;
    refetch: <TPageData>(options?: (import("@tanstack/react-query").RefetchOptions & import("@tanstack/react-query").RefetchQueryFilters<TPageData>) | undefined) => Promise<import("@tanstack/react-query").QueryObserverResult<{
        contractType: "split" | "nft-drop" | "signature-drop" | "nft-collection" | "edition-drop" | "edition" | "token-drop" | "token" | "vote" | "marketplace" | "pack" | "multiwrap" | undefined;
        compilerMetadata: null;
    } | {
        contractType: "custom";
        compilerMetadata: {
            name: string;
            metadata: Record<string, any>;
            abi: {
                [x: string]: any;
                type: string;
                name: string;
                outputs: {
                    [x: string]: any;
                    components?: {
                        [x: string]: any;
                        type: string;
                        name: string;
                    }[] | undefined;
                    stateMutability?: string | undefined;
                    type: string;
                    name: string;
                }[];
                inputs: {
                    [x: string]: any;
                    components?: {
                        [x: string]: any;
                        type: string;
                        name: string;
                    }[] | undefined;
                    stateMutability?: string | undefined;
                    type: string;
                    name: string;
                }[];
            }[];
            info: {
                title?: string | undefined;
                author?: string | undefined;
                details?: string | undefined;
                notice?: string | undefined;
            };
            licenses: string[];
        } | undefined;
    } | undefined, unknown>>;
    remove: () => void;
    fetchStatus: import("@tanstack/react-query").FetchStatus;
};
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  contractAddress | [RequiredParam](./react.requiredparam.md)<!-- -->&lt;[ContractAddress](./react.contractaddress.md)<!-- -->&gt; | the address of the deployed contract |

<b>Returns:</b>

{ contract: null; data: undefined; error: unknown; isError: true; isLoading: false; isLoadingError: true; isRefetchError: false; isSuccess: false; status: "error"; dataUpdatedAt: number; errorUpdatedAt: number; failureCount: number; errorUpdateCount: number; isFetched: boolean; isFetchedAfterMount: boolean; isFetching: boolean; isPaused: boolean; isPlaceholderData: boolean; isPreviousData: boolean; isRefetching: boolean; isStale: boolean; refetch: &lt;TPageData&gt;(options?: (import("@tanstack/react-query").RefetchOptions &amp; import("@tanstack/react-query").RefetchQueryFilters&lt;TPageData&gt;) \| undefined) =&gt; Promise&lt;import("@tanstack/react-query").QueryObserverResult&lt;{ contractType: "split" \| "nft-drop" \| "signature-drop" \| "nft-collection" \| "edition-drop" \| "edition" \| "token-drop" \| "token" \| "vote" \| "marketplace" \| "pack" \| "multiwrap" \| undefined; compilerMetadata: null; } \| { contractType: "custom"; compilerMetadata: { name: string; metadata: Record&lt;string, any&gt;; abi: { \[x: string\]: any; type: string; name: string; outputs: { \[x: string\]: any; components?: { \[x: string\]: any; type: string; name: string; }\[\] \| undefined; stateMutability?: string \| undefined; type: string; name: string; }\[\]; inputs: { \[x: string\]: any; components?: { \[x: string\]: any; type: string; name: string; }\[\] \| undefined; stateMutability?: string \| undefined; type: string; name: string; }\[\]; }\[\]; info: { title?: string \| undefined; author?: string \| undefined; details?: string \| undefined; notice?: string \| undefined; }; licenses: string\[\]; } \| undefined; } \| undefined, unknown&gt;&gt;; remove: () =&gt; void; fetchStatus: import("@tanstack/react-query").FetchStatus; } \| { contract: null; data: undefined; error: null; isError: false; isLoading: true; isLoadingError: false; isRefetchError: false; isSuccess: false; status: "loading"; dataUpdatedAt: number; errorUpdatedAt: number; failureCount: number; errorUpdateCount: number; isFetched: boolean; isFetchedAfterMount: boolean; isFetching: boolean; isPaused: boolean; isPlaceholderData: boolean; isPreviousData: boolean; isRefetching: boolean; isStale: boolean; refetch: &lt;TPageData&gt;(options?: (import("@tanstack/react-query").RefetchOptions &amp; import("@tanstack/react-query").RefetchQueryFilters&lt;TPageData&gt;) \| undefined) =&gt; Promise&lt;import("@tanstack/react-query").QueryObserverResult&lt;{ contractType: "split" \| "nft-drop" \| "signature-drop" \| "nft-collection" \| "edition-drop" \| "edition" \| "token-drop" \| "token" \| "vote" \| "marketplace" \| "pack" \| "multiwrap" \| undefined; compilerMetadata: null; } \| { contractType: "custom"; compilerMetadata: { name: string; metadata: Record&lt;string, any&gt;; abi: { \[x: string\]: any; type: string; name: string; outputs: { \[x: string\]: any; components?: { \[x: string\]: any; type: string; name: string; }\[\] \| undefined; stateMutability?: string \| undefined; type: string; name: string; }\[\]; inputs: { \[x: string\]: any; components?: { \[x: string\]: any; type: string; name: string; }\[\] \| undefined; stateMutability?: string \| undefined; type: string; name: string; }\[\]; }\[\]; info: { title?: string \| undefined; author?: string \| undefined; details?: string \| undefined; notice?: string \| undefined; }; licenses: string\[\]; } \| undefined; } \| undefined, unknown&gt;&gt;; remove: () =&gt; void; fetchStatus: import("@tanstack/react-query").FetchStatus; } \| { contract: import("@thirdweb-dev/sdk").SmartContract&lt;import("ethers").BaseContract&gt; \| null; data: { contractType: "split" \| "nft-drop" \| "signature-drop" \| "nft-collection" \| "edition-drop" \| "edition" \| "token-drop" \| "token" \| "vote" \| "marketplace" \| "pack" \| "multiwrap" \| undefined; compilerMetadata: null; } \| { contractType: "custom"; compilerMetadata: { name: string; metadata: Record&lt;string, any&gt;; abi: { \[x: string\]: any; type: string; name: string; outputs: { \[x: string\]: any; components?: { \[x: string\]: any; type: string; name: string; }\[\] \| undefined; stateMutability?: string \| undefined; type: string; name: string; }\[\]; inputs: { \[x: string\]: any; components?: { \[x: string\]: any; type: string; name: string; }\[\] \| undefined; stateMutability?: string \| undefined; type: string; name: string; }\[\]; }\[\]; info: { title?: string \| undefined; author?: string \| undefined; details?: string \| undefined; notice?: string \| undefined; }; licenses: string\[\]; } \| undefined; } \| undefined; error: unknown; isError: true; isLoading: false; isLoadingError: false; isRefetchError: true; isSuccess: false; status: "error"; dataUpdatedAt: number; errorUpdatedAt: number; failureCount: number; errorUpdateCount: number; isFetched: boolean; isFetchedAfterMount: boolean; isFetching: boolean; isPaused: boolean; isPlaceholderData: boolean; isPreviousData: boolean; isRefetching: boolean; isStale: boolean; refetch: &lt;TPageData&gt;(options?: (import("@tanstack/react-query").RefetchOptions &amp; import("@tanstack/react-query").RefetchQueryFilters&lt;TPageData&gt;) \| undefined) =&gt; Promise&lt;import("@tanstack/react-query").QueryObserverResult&lt;{ contractType: "split" \| "nft-drop" \| "signature-drop" \| "nft-collection" \| "edition-drop" \| "edition" \| "token-drop" \| "token" \| "vote" \| "marketplace" \| "pack" \| "multiwrap" \| undefined; compilerMetadata: null; } \| { contractType: "custom"; compilerMetadata: { name: string; metadata: Record&lt;string, any&gt;; abi: { \[x: string\]: any; type: string; name: string; outputs: { \[x: string\]: any; components?: { \[x: string\]: any; type: string; name: string; }\[\] \| undefined; stateMutability?: string \| undefined; type: string; name: string; }\[\]; inputs: { \[x: string\]: any; components?: { \[x: string\]: any; type: string; name: string; }\[\] \| undefined; stateMutability?: string \| undefined; type: string; name: string; }\[\]; }\[\]; info: { title?: string \| undefined; author?: string \| undefined; details?: string \| undefined; notice?: string \| undefined; }; licenses: string\[\]; } \| undefined; } \| undefined, unknown&gt;&gt;; remove: () =&gt; void; fetchStatus: import("@tanstack/react-query").FetchStatus; } \| { contract: import("@thirdweb-dev/sdk").SmartContract&lt;import("ethers").BaseContract&gt; \| null; data: { contractType: "split" \| "nft-drop" \| "signature-drop" \| "nft-collection" \| "edition-drop" \| "edition" \| "token-drop" \| "token" \| "vote" \| "marketplace" \| "pack" \| "multiwrap" \| undefined; compilerMetadata: null; } \| { contractType: "custom"; compilerMetadata: { name: string; metadata: Record&lt;string, any&gt;; abi: { \[x: string\]: any; type: string; name: string; outputs: { \[x: string\]: any; components?: { \[x: string\]: any; type: string; name: string; }\[\] \| undefined; stateMutability?: string \| undefined; type: string; name: string; }\[\]; inputs: { \[x: string\]: any; components?: { \[x: string\]: any; type: string; name: string; }\[\] \| undefined; stateMutability?: string \| undefined; type: string; name: string; }\[\]; }\[\]; info: { title?: string \| undefined; author?: string \| undefined; details?: string \| undefined; notice?: string \| undefined; }; licenses: string\[\]; } \| undefined; } \| undefined; error: null; isError: false; isLoading: false; isLoadingError: false; isRefetchError: false; isSuccess: true; status: "success"; dataUpdatedAt: number; errorUpdatedAt: number; failureCount: number; errorUpdateCount: number; isFetched: boolean; isFetchedAfterMount: boolean; isFetching: boolean; isPaused: boolean; isPlaceholderData: boolean; isPreviousData: boolean; isRefetching: boolean; isStale: boolean; refetch: &lt;TPageData&gt;(options?: (import("@tanstack/react-query").RefetchOptions &amp; import("@tanstack/react-query").RefetchQueryFilters&lt;TPageData&gt;) \| undefined) =&gt; Promise&lt;import("@tanstack/react-query").QueryObserverResult&lt;{ contractType: "split" \| "nft-drop" \| "signature-drop" \| "nft-collection" \| "edition-drop" \| "edition" \| "token-drop" \| "token" \| "vote" \| "marketplace" \| "pack" \| "multiwrap" \| undefined; compilerMetadata: null; } \| { contractType: "custom"; compilerMetadata: { name: string; metadata: Record&lt;string, any&gt;; abi: { \[x: string\]: any; type: string; name: string; outputs: { \[x: string\]: any; components?: { \[x: string\]: any; type: string; name: string; }\[\] \| undefined; stateMutability?: string \| undefined; type: string; name: string; }\[\]; inputs: { \[x: string\]: any; components?: { \[x: string\]: any; type: string; name: string; }\[\] \| undefined; stateMutability?: string \| undefined; type: string; name: string; }\[\]; }\[\]; info: { title?: string \| undefined; author?: string \| undefined; details?: string \| undefined; notice?: string \| undefined; }; licenses: string\[\]; } \| undefined; } \| undefined, unknown&gt;&gt;; remove: () =&gt; void; fetchStatus: import("@tanstack/react-query").FetchStatus; }

a response object that includes the contract once it is resolved

## Example


```javascript
const { contract, isLoading, error } = useContract("{{contract_address}}");
```

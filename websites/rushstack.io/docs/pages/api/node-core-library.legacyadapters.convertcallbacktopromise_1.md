---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [LegacyAdapters](./node-core-library.legacyadapters.md) &gt; [convertCallbackToPromise](./node-core-library.legacyadapters.convertcallbacktopromise_1.md)

## LegacyAdapters.convertCallbackToPromise() method

<b>Signature:</b>

```typescript
static convertCallbackToPromise<TResult, TError, TArg1>(fn: (arg1: TArg1, cb: LegacyCallback<TResult, TError>) => void, arg1: TArg1): Promise<TResult>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  fn | (arg1: TArg1, cb: [LegacyCallback](./node-core-library.legacycallback.md) &lt;TResult, TError&gt;) =&gt; void |  |
|  arg1 | TArg1 |  |

<b>Returns:</b>

Promise&lt;TResult&gt;

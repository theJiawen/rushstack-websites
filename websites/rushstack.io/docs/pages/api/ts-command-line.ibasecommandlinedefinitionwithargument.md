---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/ts-command-line](./ts-command-line.md) &gt; [IBaseCommandLineDefinitionWithArgument](./ts-command-line.ibasecommandlinedefinitionwithargument.md)

## IBaseCommandLineDefinitionWithArgument interface

The common base interface for parameter types that accept an argument.

<b>Signature:</b>

```typescript
export interface IBaseCommandLineDefinitionWithArgument extends IBaseCommandLineDefinition 
```
<b>Extends:</b> [IBaseCommandLineDefinition](./ts-command-line.ibasecommandlinedefinition.md)

## Remarks

An argument is an accompanying command-line token, such as "123" in the example "--max-count 123".

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [argumentName](./ts-command-line.ibasecommandlinedefinitionwithargument.argumentname.md) | string | The name of the argument, which will be shown in the command-line help. |
|  [completions?](./ts-command-line.ibasecommandlinedefinitionwithargument.completions.md) | () =&gt; Promise&lt;string\[\]&gt; | <i>(Optional)</i> An optional callback that provides a list of custom choices for tab completion. |

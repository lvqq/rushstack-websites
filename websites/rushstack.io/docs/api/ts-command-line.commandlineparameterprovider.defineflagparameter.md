---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/ts-command-line](./ts-command-line.md) &gt; [CommandLineParameterProvider](./ts-command-line.commandlineparameterprovider.md) &gt; [defineFlagParameter](./ts-command-line.commandlineparameterprovider.defineflagparameter.md)

## CommandLineParameterProvider.defineFlagParameter() method

Defines a command-line switch whose boolean value is true if the switch is provided, and false otherwise.

<b>Signature:</b>

```typescript
defineFlagParameter(definition: ICommandLineFlagDefinition): CommandLineFlagParameter;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  definition | [ICommandLineFlagDefinition](./ts-command-line.icommandlineflagdefinition.md) |  |

<b>Returns:</b>

[CommandLineFlagParameter](./ts-command-line.commandlineflagparameter.md)

## Remarks

Example usage of a flag parameter:

```
example-tool --debug
```

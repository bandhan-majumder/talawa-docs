[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [utilities/graphQLConnection](../README.md) / isNotNullish

# Function: isNotNullish()

\> **isNotNullish**\<`T0`\>(`value`): `value is T0`

This function is used to check nullish state of a value passed to it. Nullish means the
value being either `null` or `undefined`. If the value is found to be nullish, the function
returns the boolean `false`, else it returns the boolean `true`.

## Type Parameters

• **T0**

## Parameters

• **value**: `undefined` \| `null` \| `T0`

## Returns

`value is T0`

## Example

```ts
Here's an example:-
function print(str: string | null) \{
  if(isNotNullish(str)) \{
    console.log(`the string is $\{str\}`)
  \} else \{
    console.log(`the string is null`)
  \}
\}
```

## Defined in

[src/utilities/graphQLConnection/index.ts:15](https://github.com/PalisadoesFoundation/talawa-api/blob/bba5d82264abb62b9e358a3d3fe1af18a8a8f6e4/src/utilities/graphQLConnection/index.ts#L15)

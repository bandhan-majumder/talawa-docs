[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / CreateAgendaItemInput

# Type Alias: CreateAgendaItemInput

\> **CreateAgendaItemInput**: `object`

## Type declaration

### attachments?

\> `optional` **attachments**: [`InputMaybe`](InputMaybe.md)\<[`InputMaybe`](InputMaybe.md)\<[`Scalars`](Scalars.md)\[`"String"`\]\[`"input"`\]\>[]\>

### categories?

\> `optional` **categories**: [`InputMaybe`](InputMaybe.md)\<[`InputMaybe`](InputMaybe.md)\<[`Scalars`](Scalars.md)\[`"ID"`\]\[`"input"`\]\>[]\>

### description?

\> `optional` **description**: [`InputMaybe`](InputMaybe.md)\<[`Scalars`](Scalars.md)\[`"String"`\]\[`"input"`\]\>

### duration

\> **duration**: [`Scalars`](Scalars.md)\[`"String"`\]\[`"input"`\]

### organizationId

\> **organizationId**: [`Scalars`](Scalars.md)\[`"ID"`\]\[`"input"`\]

### relatedEventId?

\> `optional` **relatedEventId**: [`InputMaybe`](InputMaybe.md)\<[`Scalars`](Scalars.md)\[`"ID"`\]\[`"input"`\]\>

### sequence

\> **sequence**: [`Scalars`](Scalars.md)\[`"Int"`\]\[`"input"`\]

### title?

\> `optional` **title**: [`InputMaybe`](InputMaybe.md)\<[`Scalars`](Scalars.md)\[`"String"`\]\[`"input"`\]\>

### urls?

\> `optional` **urls**: [`InputMaybe`](InputMaybe.md)\<[`InputMaybe`](InputMaybe.md)\<[`Scalars`](Scalars.md)\[`"String"`\]\[`"input"`\]\>[]\>

### users?

\> `optional` **users**: [`InputMaybe`](InputMaybe.md)\<[`InputMaybe`](InputMaybe.md)\<[`Scalars`](Scalars.md)\[`"ID"`\]\[`"input"`\]\>[]\>

## Defined in

[src/types/generatedGraphQLTypes.ts:427](https://github.com/PalisadoesFoundation/talawa-api/blob/bba5d82264abb62b9e358a3d3fe1af18a8a8f6e4/src/types/generatedGraphQLTypes.ts#L427)

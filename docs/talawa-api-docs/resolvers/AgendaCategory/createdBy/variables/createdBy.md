[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/AgendaCategory/createdBy](../README.md) / createdBy

# Variable: createdBy

\> `const` **createdBy**: [`AgendaCategoryResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/AgendaCategoryResolvers.md)\[`"createdBy"`\]

Resolver function for the `createdBy` field of an `AgendaCategory`.

This function retrieves the user who created a specific agenda category.

## Param

The parent object representing the agenda category. It contains information about the agenda category, including the ID of the user who created it.

## Returns

A promise that resolves to the user document found in the database. This document represents the user who created the agenda category.

## See

 - User - The User model used to interact with the users collection in the database.
 - AgendaCategoryResolvers - The type definition for the resolvers of the AgendaCategory fields.

## Defined in

[src/resolvers/AgendaCategory/createdBy.ts:17](https://github.com/PalisadoesFoundation/talawa-api/blob/bba5d82264abb62b9e358a3d3fe1af18a8a8f6e4/src/resolvers/AgendaCategory/createdBy.ts#L17)

[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Advertisement/organization](../README.md) / organization

# Variable: organization

\> `const` **organization**: [`AdvertisementResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/AdvertisementResolvers.md)\[`"organization"`\]

Resolver function for the `organization` field of an `Advertisement`.

This function fetches the organization associated with a given advertisement.
It uses the `organizationId` field from the parent `Advertisement` object to find the corresponding organization in the database.
The organization details are then returned in a plain JavaScript object format.

## Param

The parent `Advertisement` object. This contains the `organizationId` field, which is used to find the organization.

## Returns

A promise that resolves to the organization object found in the database, or `null` if no organization is found.

## Defined in

[src/resolvers/Advertisement/organization.ts:15](https://github.com/PalisadoesFoundation/talawa-api/blob/bba5d82264abb62b9e358a3d3fe1af18a8a8f6e4/src/resolvers/Advertisement/organization.ts#L15)

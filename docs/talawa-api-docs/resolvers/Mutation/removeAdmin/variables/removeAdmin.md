[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/removeAdmin](../README.md) / removeAdmin

# Variable: removeAdmin

\> `const` **removeAdmin**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"removeAdmin"`\]

This function enables to remove an admin.

## Param

parent of current request

## Param

payload provided with the request

## Param

context of entire application

## Remarks

The following checks are done:
1. If the user exists
2. If the organization exists.
3. If the user to be removed is an admin.
4. If the user removing the admin is the creator of the organization
5 .If the current user and user has appUserProfile or not

## Returns

Updated appUserProfile.

## Defined in

[src/resolvers/Mutation/removeAdmin.ts:37](https://github.com/PalisadoesFoundation/talawa-api/blob/bba5d82264abb62b9e358a3d3fe1af18a8a8f6e4/src/resolvers/Mutation/removeAdmin.ts#L37)

[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/leaveOrganization](../README.md) / leaveOrganization

# Variable: leaveOrganization

\> `const` **leaveOrganization**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"leaveOrganization"`\]

This function enables to leave an organization.

## Param

parent of current request

## Param

payload provided with the request

## Param

context of entire application

## Remarks

The following checks are done:
1. If the organization exists
2. If the user exists
3. If the user is the creator of the organization
4. If the user is a member of the organization

## Returns

Updated user

## Defined in

[src/resolvers/Mutation/leaveOrganization.ts:36](https://github.com/PalisadoesFoundation/talawa-api/blob/bba5d82264abb62b9e358a3d3fe1af18a8a8f6e4/src/resolvers/Mutation/leaveOrganization.ts#L36)

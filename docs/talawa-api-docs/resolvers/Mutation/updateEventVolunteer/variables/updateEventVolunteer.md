[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/updateEventVolunteer](../README.md) / updateEventVolunteer

# Variable: updateEventVolunteer

\> `const` **updateEventVolunteer**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"updateEventVolunteer"`\]

This function enables to update an Event Volunteer

## Param

parent of current request

## Param

payload provided with the request

## Param

context of entire application

## Remarks

The following checks are done:
1. Whether the user exists
2. Whether the EventVolunteer exists
3. Whether the current user is the user of EventVolunteer
4. Update the EventVolunteer

## Defined in

[src/resolvers/Mutation/updateEventVolunteer.ts:21](https://github.com/PalisadoesFoundation/talawa-api/blob/bba5d82264abb62b9e358a3d3fe1af18a8a8f6e4/src/resolvers/Mutation/updateEventVolunteer.ts#L21)

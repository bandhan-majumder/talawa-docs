[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/EventVolunteerGroup/event](../README.md) / event

# Variable: event

\> `const` **event**: [`EventVolunteerGroupResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/EventVolunteerGroupResolvers.md)\[`"event"`\]

Resolver function for the `event` field of an `EventVolunteerGroup`.

This function retrieves the event associated with a specific event volunteer group.

## Param

The parent object representing the event volunteer group. It contains information about the event volunteer group, including the ID of the event associated with it.

## Returns

A promise that resolves to the event document found in the database. This document represents the event associated with the event volunteer group.

## See

 - Event - The Event model used to interact with the events collection in the database.
 - EventVolunteerGroupResolvers - The type definition for the resolvers of the EventVolunteerGroup fields.

## Defined in

[src/resolvers/EventVolunteerGroup/event.ts:16](https://github.com/PalisadoesFoundation/talawa-api/blob/4a88fe62b20ebda9653c55ae8d39d6c6fac8831f/src/resolvers/EventVolunteerGroup/event.ts#L16)

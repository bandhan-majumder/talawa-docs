[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Organization/membershipRequests](../README.md) / membershipRequests

# Variable: membershipRequests

\> `const` **membershipRequests**: [`OrganizationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/OrganizationResolvers.md)\[`"membershipRequests"`\]

Resolver function for the `membershipRequests` field of an `Organization`.

This function retrieves the membership requests related to a specific organization.

## Param

The parent object representing the organization. It contains information about the organization, including the IDs of the membership requests.

## Returns

A promise that resolves to an array of membership request documents found in the database. These documents represent the membership requests related to the organization.

## See

 - MembershipRequest - The MembershipRequest model used to interact with the membership requests collection in the database.
 - OrganizationResolvers - The type definition for the resolvers of the Organization fields.

## Defined in

[src/resolvers/Organization/membershipRequests.ts:16](https://github.com/PalisadoesFoundation/talawa-api/blob/bba5d82264abb62b9e358a3d3fe1af18a8a8f6e4/src/resolvers/Organization/membershipRequests.ts#L16)

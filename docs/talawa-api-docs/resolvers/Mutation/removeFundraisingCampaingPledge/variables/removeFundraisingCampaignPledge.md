[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/removeFundraisingCampaingPledge](../README.md) / removeFundraisingCampaignPledge

# Variable: removeFundraisingCampaignPledge

\> `const` **removeFundraisingCampaignPledge**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"removeFundraisingCampaignPledge"`\]

This function enables to remove fundraising campaign pledge .

## Param

parent of current request

## Param

payload provided with the request

## Param

context of entire application

## Remarks

The following checks are done:
1. If the user exists
2. If the fundraising campaign pledge exists.
3. If the user has made the pledge.

## Returns

Deleted fundraising campaign pledge.

## Defined in

[src/resolvers/Mutation/removeFundraisingCampaingPledge.ts:28](https://github.com/PalisadoesFoundation/talawa-api/blob/bba5d82264abb62b9e358a3d3fe1af18a8a8f6e4/src/resolvers/Mutation/removeFundraisingCampaingPledge.ts#L28)

[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [utilities/createSampleOrganizationUtil](../README.md) / generatePostData

# Function: generatePostData()

\> **generatePostData**(`users`, `organizationId`): `Promise`\<[`InterfacePost`](../../../models/Post/interfaces/InterfacePost.md) & `Document`\<`any`, `any`, [`InterfacePost`](../../../models/Post/interfaces/InterfacePost.md)\>\>

Generates post data for a given list of users and organization.

## Parameters

• **users**: [`InterfaceUser`](../../../models/User/interfaces/InterfaceUser.md)[]

The list of users associated with the post

• **organizationId**: `string`

The ID of the organization the post belongs to

## Returns

`Promise`\<[`InterfacePost`](../../../models/Post/interfaces/InterfacePost.md) & `Document`\<`any`, `any`, [`InterfacePost`](../../../models/Post/interfaces/InterfacePost.md)\>\>

A promise that resolves to the created post

## Defined in

[src/utilities/createSampleOrganizationUtil.ts:151](https://github.com/PalisadoesFoundation/talawa-api/blob/bba5d82264abb62b9e358a3d3fe1af18a8a8f6e4/src/utilities/createSampleOrganizationUtil.ts#L151)

[**talawa-admin**](../../../../README.md) • **Docs**

***

[talawa-admin](../../../../modules.md) / [components/ProfileDropdown/ProfileDropdown](../README.md) / default

# Function: default()

\> **default**(): `Element`

Renders a profile dropdown menu for the user.

This component displays the user's profile picture or an avatar, their name (truncated if necessary),
and their role (SuperAdmin, Admin, or User). It provides options to view the profile or log out.

- If a user image is available, it displays that; otherwise, it shows an avatar.
- The displayed name is truncated if it exceeds a specified length.
- The logout function revokes the refresh token and clears local storage before redirecting to the home page.

## Returns

`Element`

JSX.Element - The profile dropdown menu.

## Defined in

[src/components/ProfileDropdown/ProfileDropdown.tsx:24](https://github.com/PalisadoesFoundation/talawa-admin/blob/9dd5d7fd647f8a7c9e1c1e14bf645b71b32c51c2/src/components/ProfileDropdown/ProfileDropdown.tsx#L24)

# Ban
Ban a user from the server.

## Usage
`ban <user> [delete days] [reason]`

## Aliases
`b`

## Examples
- `ban bad-pete` This will ban the user "bad-pete" from the server indefinitely, if more than one user is found, an option list will be displayed.
- `ban naughty-sarah Spamming users` This will ban the user "naughty-sarah" from the server indefinitely. It will also DM the user why they have been banned with the reason "Spamming users", if more than one user is found, an option list will be displayed.
- `ban badboy 2` This will ban the user "badboy" from the server for 2 days. After this, the user will be able to re-join using an invite link. If more than one user is found, an option list will be displayed.
- `ban deadpool 2 Shooting people` This will ban the user "deadpool" from the server for 2 days, sending them a DM explaining why they have been banned, in this case "Shooting people". After this, the user will be able to re-join using an invite link. If more than one user is found, an option list will be displayed.

## Permissions
For this command to work, you are required to have the **Ban Members** (`banMembers`)  permission within the server you wish to use this command.
# Mute
Prevents a user from sending messages within the server.

## Usage
`mute <user> [duration] [reason]`

## Aliases
`m`

## Examples
- `mute talk-a-lot` This will prevent the user "talk-a-lot" from sending messages indefinitely, if more than one user is found, an option list will be displayed. 
- `mute mrMouth Shouting` This will prevent the user "mrMouth" from sending messages indefinitely and also DM him with the reason "Shouting". If more than one user is found, an option list will be displayed.
- `mute trin 1d` This will prevent the user "trin" from talking on the server for *1 day*. ([More on durations can be found here](/durations)). If more than one user is found, an option list will be displayed.
- `mute bailey 3d Annoying everyone` This will prevent the user "bailey" from sending messages for *3 days*. ([More on durations can be found here](/durations)). It will also DM the user with the reason "Annoying everyone" if more than one user is found, an option list will be displayed.

## Permissions
For this command to work, you are required to have the **Manage Roles** (`manageRoles`)  permission within the server you wish to use this command.
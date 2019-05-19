# Capitals
Configures whether or not automod should punish a user for having higher than a set percentage of capitals in their message.

## Usage
`automod-capitals [enable | disable] [warn | mute | kick | soft-ban | temp-ban | ban] [percentage]`

## Aliases
`automodcapitals` and `capitals`

## Examples
- `automod-capitals enable soft-ban 50%` This will [soft-ban](/commands/moderation/soft-ban) a user if their message consists of a ratio of half or more capitals to lowercase letters. For example: *WHAT IS this?!*
- `automod-capitals enable ban 90%` This will [ban](/commands/moderation/ban) a user if their message consists of a ratio of 90% or more capitals to lowercase letters. For example: *AGHHHHHHHh*
- `automod-capitals disable` This will disable this command and will allow a user to post a message with any ratio of capital to lowercase letters without being punished. 

## Permission
For this command to work, KoalaBoat requires the **Manage Guild** (`manageGuild`)  permission within your server. 
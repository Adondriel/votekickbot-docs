# Cooldown Commands

### Description

The bot has three different cooldowns. A Command cooldown a Voice cooldown, and a Role cooldown.

The Command Cooldown is used to prevent the same user from spamming the votekick command.

The Voice Cooldown starts when a user joins a voice channel.

The Role Cooldown is used to set a cooldown time with a specific role. 
For example, you can set a @Member role for 25 seconds, and a @Premium role for 5 seconds. 
If a user has neither role, it will default to the Command Cooldown.

The /vk-toggle-role-cooldown-conflict command allows the server owner to toggle the cooldown behavior for users who possess multiple roles that have individual cooldown times set. This feature ensures a fair and customizable cooldown experience based on the roles assigned to users.

When executing the command, the server owner can toggle between two options: highest or lowest.

highest: If this option is selected, the bot will enforce the longest cooldown time among the user's roles. For instance, if a user has both "Role A" with a cooldown of 30 seconds and "Role B" with a cooldown of 60 seconds, the user will have to wait 60 seconds before using the vote kick command.

lowest: Selecting this option will enforce the shortest cooldown time among the user's roles. In the above example, the user would only need to wait 30 seconds as that is the shortest cooldown time among their roles.

### Usage

`/vk-set-cooldown <seconds>`

`/vk-set-voice-cooldown <seconds>`

`/vk-set-role-cooldown <seconds> <role>`

`vk-remove-role-cooldown`

`/vk-toggle-role-cooldown-conflict`



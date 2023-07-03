# Cooldown Commands

### Description

The bot has three different cooldowns. A Command cooldown a Voice cooldown, and a Role cooldown.

The Command Cooldown is used to prevent the same user from spamming the votekick command.

The Voice Cooldown starts when a user joins a voice channel.

The Role Cooldown is used to set a cooldown time with a specific role. 
For example, you can set a @Member role for 25 seconds, and a @Premium role for 5 seconds. 
If a user has neither role, it will default to the Command Cooldown.

### Usage

`/vk-set-cooldown <seconds>`

`/vk-set-voice-cooldown <seconds>`

`/vk-set-role-cooldown <seconds> <role>`



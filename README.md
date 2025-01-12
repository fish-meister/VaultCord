# [VAULTCORD](https://discord.com/oauth2/authorize?client_id=1326296257035112548) SECURITY 🔒
VaultCord is dedicated to providing extra security to Discord Server's of all kinds.<br />
Protect your Server with User Verification and more!

## Index
- [Features](https://github.com/fish-meister/VaultCord/blob/main/README.md#features)
- [Commands & Functions](https://github.com/fish-meister/VaultCord/blob/main/README.md#commands--functions)
- [Verification Methods](https://github.com/fish-meister/VaultCord/blob/main/Methods.md)

## FEATURES
### Automatic User Authentication
_Requires the `connections` permission cloud-side._

_Requires the `send_messages`, `manage_messages`, `kick_members` and `manage_roles` permission's._
- Discreetly checks for malicious patterns in other Guild's.
- Automatically asks User's to verify upon entering the Guild.
- Failure to acknoledge the verification results in removal.
- Ignores genuine Discord Bot Application's.
- Grants a Role to User's upon successful authentication.

### Customisation
- Allows you to customise variables within the Authentication Process.
  - The Channel that messages are sent to.
  - The Verification Role.
  - The Staff Team Role.
  - The Moderation Logging Channel.
  - The Verification Method.

### Moderation
_Requires the `kick_members`, `ban_members` and `moderate_members` permission's._
- Provides a Moderation Panel
- Kick & Ban User's when you need to.

## COMMANDS & FUNCTIONS
Below is a list of Command's and their necessary User & Bot Permission's.
| Command | Description | User Permission | Bot Permission |
| :---: | :---: | :---: | :---: |
| premiumsettings | Opens the Premium Guild Setting's Panel | `manage_guild` | `-` |
| settings | Opens the Guild Setting's Panel | `manage_guild` | `-` |
| modlogs | Set a Channel to receive Mod Logging Messages | `manage_guild` | `send_messages`  |
| moderate | Moderate Member's Efficiently | `moderate_members` | `kick_members` `ban_members` |
| usercheck | Get information about a specific Member | `-` | `-` |
| guildcheck | Get information about the Guild | `-` | `-` |
| backup-guild | Create a backup of your Guild | `manage_guild` | `manage_guild` |
| statistics | Get Statistical Information about VaultCord | `-` | `-` |

Below is a list of Function's and their necessary User & Bot Permission's.
| Function | Description | User Permission | Bot Permission |
| :---: | :---: | :---: | :---: |
| authentication | The Authentication functionality | `-` | `connections` `manage_roles` `send_messages` `read_message_history` |
| customisation | The Customisation functionality | `manage_guild` | `-` |
| moderation | The Authentication functionality | `moderate_members` | `kick_members` `ban_members` |


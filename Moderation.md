# Moderation Features

Both the Poll and Giveaway features have support for automatic moderator functions, In order to take full advantage you will need to use the Admin Configuration panel.

## Notes on the config settings Moderation_Mode and Blacklist_Mode

### Firstly the Moderation_Mode, You will notice that the options are None, Mild, Moderate, Severe. Each option has a unique purpose

**None: No Moderator action is to be taken should a user attempt multiple entries, This option also does not add the user to the blacklist.**

**Mild: No Moderator action is to be taken, however after 5 attempts past the first entry or vote the users vote or entry gets removed.**

**Moderare: Moderator action is to be taken after 5 attempts past the first by timing the user out and remove the vote or entry.**

**Severe: Moderator action is to be taken after 3 attempts after the first by timing the user out and removing the entry or vote.**

### Secondly the Blacklist_Mode, You will notice that the options are Session, Permenant

**Session: The blacklist is only maintained for the duration of the application being open (You should close the app after each stream).**

**Permenant: The blacklist gets saved to a file in the applications folder, any user added to the blacklist will not be counted for either a giveaway entry or a vote on a poll.**

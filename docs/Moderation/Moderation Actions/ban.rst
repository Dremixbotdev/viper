Ban


Usage: ``{p}ban @user (optional reason)``

If no reason is provided, the reason is set to ``Not provided`` by default.

Checks:

Both you and the bot must have ban_members permission to be eligible to use this command.
  
If the member is in the server, then 
 1. Your highest role must be above the member's highest role.
 2. The bot's highest role must be above the user's highest role.

else,
 1. The ``ban_members`` permissions is enough. 
     
**Ban Settings**
    
1. ``ban_purge_days``: This indicates the number of days to clear the user's messages on the server. Must be between 1 and 7 inclusive. Defaults to 0.
2. ``ban_dm_alert``: This indicates whether to alert the user via dms that the user is banned. Defaults to true.
3. ``ban_dm_alert_anon``: This indicates whether to anonymously state that the user was banned, not revealing the user who banned them. Defaults to false.
4. ``ban_log``: This indicates whether to log the ban. Defaults to false.
5. ``ban_log_channel``: This indicates the channel where to log the ban. Defaults to none.

****

Command usage syntax: []: Required argument | (): Optional argument

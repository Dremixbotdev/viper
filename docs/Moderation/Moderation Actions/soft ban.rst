Softban

Softban means, to ban the user and immediatly unban them. This is useful for deleting the messages the user sent.

Usage: ``{p}softban @user (optional reason)``

If no reason is provided, the reason is set to ``Not provided`` by default.

Checks:
	1. Your highest role's position must be above the user's highest role.
	2. The bot's highest role's position must be above the user's hoghest role.

Both you and the bot must have ban_members permission to be eligible to use this command.
     
**Softban Settings**

1. ``soft_ban_purge_days``: The number of days to clear the user's messages before banning them. Must be between 0 and 7 inclusive. Defaults to 0.    
2. ``soft_ban_dm_alert``: This indicates whether to alert the user via dms that the user is soft banned. Defaults to true.
3. ``soft_ban_dm_alert_anon``: This indicates whether to anonymously state that the user was softbanned, not revealing the user who soft banned them. Defaults to false.
4. ``soft_ban_log``: This indicates whether to log the soft ban. Defaults to false.
5. ``soft_ban_log_channel``: This indicates the channel where to log the softban. Defaults to none.

Note: This is the same as banning the user and unbanning them.

****

Command usage syntax: []: Required argument | (): Optional argument


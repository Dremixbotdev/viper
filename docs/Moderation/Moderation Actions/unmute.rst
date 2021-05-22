Unmute


Usage: ``{p}unmute @user (optional reason)``

If no reason is provided, the reason is set to ``Not provided`` by default.

Checks:

The bot must have ``manage_roles`` permission and you must have ``manage_messages`` permission to be eligible to use this command.
     
**Unmute Settings**
    
1. ``unmute_dm_alert``: This indicates whether to alert the user via dms that the user is unmuted. Defaults to true.
2. ``unmute_dm_alert_anon``: This indicates whether to anonymously state that the user was unmuted, not revealing the user who unmuted them. Defaults to false.
3. ``unmute_log``: This indicates whether to log the unmute. Defaults to false.
4. ``unmute_log_channel``: This indicates the channel where to log the unmute. Defaults to none.
5. ``mute_role_id``: The ``Muted`` role id. Defaults to none. If this is not set, muting or unmuting the member is not possible. 

See also ``docs/Moderation/Moderation Actions/mute.rst``.

****

Command usage syntax: []: Required argument | (): Optional argument

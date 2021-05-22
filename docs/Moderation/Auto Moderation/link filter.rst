Link Filter

The bot uses a professionaly created link filter, which checks for links as well as hidden links. Instead of checking whether the message content contains only ``http`` or 
``https``, the bot also sees whether the matching content is actually a link. 

**Link Filter Settings**

1.``link_whitelisted_users``: White listed users from the link filter. Defualt value: none.
2.``link_whitelisted_roles``: White listed roles from the link filter. Defualt value: none.
3.``link_whitelisted_channels``: White listed channels from the link filter. Defualt value: none.

**Note: Any user with `manage_messages` permission will automatically be whitelisted from the filter.**

****

This part of code is still in the beta version. Any errors are not taken responsible by the development team.

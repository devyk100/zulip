# Archive a channel

{!admin-only.md!}

Archiving a channel will hide the channel from most views in the UI.
Archiving a channel does not delete a channel's messages, and its
messages will remain accessible via search and the like, unless you
first change the channel's access permissions.

Archiving a channel does not remove subscribers or change its access
permissions.

Consider [renaming channels](/help/rename-a-channel) rather than
archiving them where appropriate.

## Archive a channel

{start_tabs}

{tab|desktop-web}

{relative|channel|all}

1. Select a channel.

1. Click the **trash** <i class="fa fa-trash-o"></i> icon near the top right
   corner of the channel settings panel.

1. Approve by clicking **Confirm**.

!!! tip ""

    You can also hover over a channel in the left sidebar, click on the
    **ellipsis** (<i class="zulip-icon zulip-icon-more-vertical"></i>), and
    select **Channel settings** to access the **trash**
    <i class="fa fa-trash-o"></i> icon.

{end_tabs}

!!! warn ""

    Archiving a channel is currently irreversible via the UI.

## Unarchiving archived channels

If you are self-hosting, you can unarchive an archived channel using the
`unarchive_channel` [management command][management-command]. This will restore
it as a private channel with shared history, and subscribe all organization
owners to it. If you are using Zulip Cloud, you can [contact us](/help/contact-support)
for help.

[management-command]:
https://zulip.readthedocs.io/en/latest/production/management-commands.html#other-useful-manage-py-commands

## Related articles

* [Edit a message](/help/edit-a-message)
* [Delete a message](/help/delete-a-message)
* [Delete a topic](/help/delete-a-topic)
* [Message retention policy](/help/message-retention-policy)
* [Channel permissions](/help/channel-permissions)
* [Zulip Cloud or self-hosting?](/help/zulip-cloud-or-self-hosting)

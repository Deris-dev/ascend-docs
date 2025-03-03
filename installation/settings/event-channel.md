# Event Channel

The **"Event Channel"** option allows you to define the channel where **event start notifications** will be sent. Some events also require a configured channel via this option to function properly, as the bot needs to send messages during the event.

### How to Configure the Event Channel?

1. Use the `/settings` command and select **Event Channel**.
2. In the dropdown menu, choose the channel where:
   * **Event start notifications** will be sent.
   * Events requiring bot interactions can function properly.

### How the Event Channel Works

1. **Event Start Notifications**:\
   When the bot starts an event, it sends a notification in the configured channel to inform members.
2. **Events Requiring a Channel**:\
   Some events need a dedicated channel where the bot can:
   * Send messages to guide members.
   * Post updates or specific actions related to the event.

{% hint style="danger" %}
If no event channel is configured, these events will not work.
{% endhint %}

### What Happens If I Don’t Configure an Event Channel?

If no channel is set, event start notifications will not be sent, and some events requiring specific bot interactions will not function.

### Can I Change the Event Channel Later?

Yes, you can modify the event channel at any time using the `/settings` command.

### Do All Events Require an Event Channel?

No, only certain specific events need a configured channel to function. Other events can proceed without this setting.

### Can I Use the Same Channel for Rank Notifications and Events?

Yes, you can use the same channel for both if it fits your server’s structure.

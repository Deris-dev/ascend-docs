# Event role

The **"Event Role"** option allows you to configure a specific role that will be mentioned to notify members when events start. This ensures that only interested members are notified without disturbing the entire server.

### How to Configure the Event Role?

1. Use the `/settings` command and select **Event Role**.
2. In the dropdown menu, choose the role you want to use for event notifications.
3. Click **Save** to confirm your choice.

{% hint style="warning" %}
The bot **does not create the role automatically**. You must create the role beforehand in your Discord server settings.
{% endhint %}

### How the Event Role Works

* **Targeted Notifications**: When an event starts, the bot will mention only the configured role, ensuring that only interested members are notified.
* **Full Customization**: You can select any existing role on your server for this function, allowing you to manage events according to your specific needs.

### Does the Bot Automatically Create the Event Role?

No, the bot does not create a role. You must manually create the role in your Discord server settings before configuring it via `/settings`.

### Can I Change the Event Role Later?

Yes, you can modify the role at any time using `/settings`.

### What Happens If No Event Role Is Configured?

If no role is configured, the bot will not mention any role when sending event notifications.

### Can I Disable Mentions for Events?

Yes, if you do not configure an event role, no mentions will be sent. You can also remove the event role via `/settings`.

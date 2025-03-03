# Blacklist

The **"Blacklist"** option allows you to block RP gain in specific channels on your server. This can be useful to prevent activity in irrelevant channels, such as spam or game channels, from affecting members' ranks.

### How to Add or Remove a Channel from the Blacklist?

1. Use the `/settings` command and select **Blacklist**.
2. In the dropdown menu, choose:
   * **Add**: to prevent RP gain in a specific channel.
   * **Remove**: to allow RP gain again in a previously blacklisted channel.
3. Select the relevant channel from the list.
4. Click **Save** to apply the changes.

### How the Blacklist Works

* Channels added to the blacklist **no longer generate any RP** for members interacting there.
* The bot will continue to function normally in these channels (commands, logs, etc.), but member activity will not count toward ranks.

### Example Use Cases

* You have a `#games` channel where members spend a lot of time interacting.\
  👉 Add this channel to the blacklist so that this activity does not affect their ranks.
* You mistakenly blacklisted the `#general` channel.\
  👉 Use the **Remove** option to allow this channel to generate RP again.

#### **Can I Blacklist Multiple Channels at Once?**

Yes, you can add multiple channels to the blacklist. Simply repeat the process for each channel.

#### **What Happens If I Delete a Blacklisted Channel?**

If the channel is deleted, it will automatically be removed from the blacklist.

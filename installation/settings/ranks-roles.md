# Ranks (Roles)

The **"Ranks (Roles)"** option allows you to automatically create and manage roles associated with the bot's ranking system. These roles help structure your server and assign specific permissions based on members' ranks.

### Automatic Role Creation

1. Use the `/settings > Ranks > Setup Ranks`command to automatically generate all roles linked to the bot’s ranking system.
2. The bot creates two types of roles for each tier:
   * **Tier Role**: Example: `Bronze`
   * **Tier Level Roles**: Example: `Bronze 1`, `Bronze 2`, `Bronze 3`

Please note that executing this command may take around 20 seconds.

### Why a Tier Role Without a Number (Like `Bronze`)?

The tier role (without a number) is created for two main reasons:

1. **Organization**: Helps separate members in the channel list for better visibility.
2. **Permissions**: Allows assigning permissions to an entire rank tier easily.

You can delete these roles if you wish, but members will no longer receive them when reaching the corresponding rank.

### Role Customization

You can customize the bot-created roles to fit your needs:

* **Rename** the roles
* Change **colors**
* Add **icons**

These modifications will not affect the role names in bot commands (like `/ranks`) or the canvas display.

### Managing Rank-Linked Roles

To link or remove a role associated with a rank:

1. Use the `/settings` command and select **Rank**.
2. Choose the rank you want to modify.
3. Add or remove the associated role(s).

### How Rank Roles Work

The bot automatically manages the roles assigned to members:

* A member will keep **only the latest roles linked to their current rank**.
* Lower-rank roles will be automatically removed.

**Example:**\
A member with the `Gold 2` rank will have the following roles:\
`Gold` and `Gold 2`.\\\
All lower-tier roles (`Bronze`, `Silver`, etc.) will be removed.

#### **Can I Customize Role Names?**

Yes, you can rename roles. The change will not affect their functionality within the bot.

#### **What Happens If I Delete a Role?**

If you delete a role, members will no longer receive that role when reaching the corresponding rank.

#### **How Can I Assign Specific Permissions to Roles?**

Set permissions directly on Discord for each role. You can use the tier role (e.g., `Bronze`) to grant global permissions to an entire group.

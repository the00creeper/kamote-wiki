---
description: Discord account are unlinked for special cases.
---

# 🔗 Unlinking Discord Accounts

Use `/discord unlink <player>` only in the following cases:

When a player switches to a new Minecraft account:

1. Instruct them to store all their items in an accessible chest.
2. Execute `/discord unlink <player>` (this will kick them automatically).
3. Ban the old account using `/ban <player> switching accounts`.
4. Once the new account is linked and joined:
   * Assist them in retrieving their items.
   * Teleport them to the chest if necessary.
5. Restore their rank using `/rankset <player> <rank>`.

## 🍵 **Bedrock Player Linked to Java**

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure></div>

* When Bedrock players join, they may initially appear as Java accounts.
* This often occurs on their first login, causing their Discord account to be linked to a Java profile.
* Upon rejoining, they correctly connect as Bedrock but are prompted to relink their Discord because it is already associated with a Java account.

### 📇 **Identification**

You can verify whether the issue has occurred using the following indicators:

* **Username Format**
  * Bedrock players have a period `.` before their username (e.g., `.Shinjiru1975`).
  * Java players do not have this prefix.
* **Discord Role**
  * Bedrock players typically have the **Bedrock** role selected during onboarding.
* **Vulcan Alerts**
  * The player may be repeatedly and falsely flagged in the `#vulcan-alerts` channel.
  *   Their ping may display as **0 ms**, which is common for Bedrock clients.<br>

      <div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure></div>

### 📝 **Resolution Procedure**

1. **Confirm** that the player is a Bedrock user.
2. Unlink the incorrectly linked Java account: `/discord unlink <player>`
3. Inform the player to relink their Discord account.
4. Verify that the correct Bedrock account is linked.
5. If the issue persists, repeat the process.

{% hint style="info" %}
Always verify before unlinking to avoid disrupting legitimate Java players.
{% endhint %}

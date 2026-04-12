# Mass Joining in Telegram with Deskgram 2

![Join Groups Main](assets/screenshots/join-groups__main__en.png)

Join Groups is a Deskgram 2 module for distributing Telegram accounts across channels, chats, and folders. It is useful when you need to prepare accounts for the next workflows, expand presence in selected communities, and build the infrastructure layer for a larger Telegram operation.

[Deskgram 2 Hub](https://github.com/Deskgram-2/deskgram-2-telegram-automation-en) · [Website](https://deskgram2.com/) · [Telegram Bot](https://t.me/DG2welcomebot) · [Web Preview](https://deskgram2.com/web-preview)

## About the module

| Parameter | What is inside |
|---|---|
| Main task | Mass joining Telegram channels, chats, and folders |
| Important blocks | Link list, statistics, logs, joining modes, limitations |
| Useful for | Account preparation, infrastructure setup, workflow scaling |
| Related modules | Accounts Panel, Proxy, Invite |

## What it can do

- join public channels and chats;
- work with invite links and Telegram folders;
- distribute links across accounts without unnecessary overlap;
- show success, error, and progress statistics;
- apply delays, threads, and limitations for safer execution.

## Quick start

1. Prepare a list of links to channels, chats, or folders.
2. Configure the joining mode and account limits.
3. Select the accounts and proxies if needed.
4. Start the task and monitor statistics.
5. Use the prepared accounts in the next modules.

## Interface highlights

### Statistics

![Join Groups Stats](assets/screenshots/join-groups__stats__en.png)

### Main settings

![Join Groups Settings](assets/screenshots/join-groups__main-settings__en.png)

### Subscription options

![Join Groups Options](assets/screenshots/join-groups__subscription-options__en.png)

## How the scenario is structured

### Source list

The module starts from a base of public links, invite links, or Telegram folder links. The quality of that list affects the whole task.

### Distribution mode

Deskgram 2 can work with account-specific lists or a shared distribution logic where links are assigned across accounts without duplicates.

### Limit control

Delays, limits, and visible task statistics help reduce overload and keep the joining process easier to control.

## When it is especially useful

- before invite, warmup, or broader infrastructure workflows;
- when many accounts must be connected to selected communities;
- when joining should be managed centrally rather than manually;
- when the next modules depend on a prepared subscription layer.

## Why it is more convenient than manual joining

| Manual approach | Join Groups in Deskgram 2 |
|---|---|
| Scaling is slow | The module works across an account grid |
| Limits are hard to manage | Delays, threads, and statistics are visible |
| Source lists become chaotic fast | Link processing is centralized |
| Harder to prepare accounts for the next modules | It becomes an infrastructure layer for future workflows |

## Related repositories

- [Deskgram 2 Hub](https://github.com/Deskgram-2/deskgram-2-telegram-automation-en)
- [Audience Parser](https://github.com/Deskgram-2/telegram-audience-parser-deskgram-en)
- [Direct Messaging](https://github.com/Deskgram-2/telegram-direct-messaging-deskgram-en)

## FAQ

### Is this only for public links?

No. The module also works with invite links and Telegram folder links.

### Can I use it as a preparation step?

Yes. It is one of the most practical infrastructure modules before invite, warmup, and other next-step workflows.

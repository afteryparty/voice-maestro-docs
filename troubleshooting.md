---
layout: default
title: Troubleshooting
description: Common VoiceMaestro issues and fixes.
permalink: /troubleshooting/
---

## Troubleshooting

### Join-to-create does not create rooms

- Confirm `/setup create` was run successfully.
- Check bot has **Manage Channels** in the server and target category.
- Verify the hub voice channel still exists and is configured.

### Members cannot use owner controls

- Confirm the user is current room owner (or trusted if using trust features).
- Check bot permissions and role placement.
- Re-test with `/claim` if original owner left.

### Interface buttons are not responding

- Confirm the interface message still exists.
- Recreate interface with `/delete interface` then `/interface`.
- Check the channel still allows bot messages and interactions.

### Room visibility/access commands fail

- Check category-level overrides that may block hide/reveal or lock/unlock behavior.
- Confirm the bot can edit permissions in that channel/category.

### Premium features are missing

- Verify premium status with `/premium`.
- Confirm server/account scope for premium features.

## What to send support

- server name
- command used
- expected result
- actual result
- screenshot of role order or channel permissions if relevant

Support: <https://discord.gg/BusuZp2G8w>

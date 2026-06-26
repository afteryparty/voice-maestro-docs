---
layout: default
title: Troubleshooting
description: Common VoiceMaestro issues and fixes.
permalink: /troubleshooting/
---

## Troubleshooting

### Join-to-create does not create rooms

- Confirm `/setup create` was run successfully.
- Check the bot has **Manage Channels**, **Move Members**, and **Connect** where needed.
- Verify the hub voice channel still exists and is configured.

### Members are not moved into their new room

- Confirm the bot has **Move Members** permission.
- Check for channel overrides that block the move.
- Re-test after confirming the hub and category are still valid.

### Owner controls are not working

- Confirm the user is the current room owner.
- Check bot permissions and role placement.
- Re-test with a freshly created room to rule out old permission overrides.

### Interface buttons are not responding

- Confirm the interface message still exists.
- Recreate it with `/interface delete` and `/interface create`.
- Check the channel still allows bot messages and interactions.

### Room visibility or access commands fail

- Check category-level overrides that may block permission edits.
- Confirm the bot can edit permissions in that channel and category.

### VoiceMaestro+ looks confusing

- `/premium` only explains the optional supporter membership.
- VoiceMaestro+ does not unlock normal bot features.

## What to send support

- server name
- command used
- expected result
- actual result
- screenshot of role order or channel permissions if relevant

Support: [Support Server](https://discord.gg/BusuZp2G8w)

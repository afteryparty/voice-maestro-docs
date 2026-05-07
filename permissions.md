---
layout: default
title: Permissions
description: Required VoiceMaestro permissions and what each one does.
permalink: /permissions/
---

## Permissions Guide

VoiceMaestro needs channel and voice permissions to create/manage temporary rooms correctly.

## Core Permissions

### View Channels

Lets the bot see configured voice and interface channels.

### Manage Channels

Required to create, rename, hide, lock, and delete temporary voice rooms.

### Move Members

Required for certain owner moderation flows and controlled voice-room handling.

### Connect

Allows the bot to connect where voice features require active presence.

### Send Messages

Needed for setup confirmations, control responses, and status messages.

### Embed Links

Required for rich response panels and cleaner command feedback.

### Read Message History

Used when commands depend on context from previous setup/control messages.

### Use Slash Commands

Required for all `/` commands.

## Permission Troubleshooting Tip

If a command runs but nothing changes, check both:

1. Bot role permissions in **Server Settings → Roles**
2. Channel-level permission overrides in **Edit Channel → Permissions**

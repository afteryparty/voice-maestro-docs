---
layout: default
title: Permissions
description: Required VoiceMaestro permissions and what each one does.
permalink: /permissions/
---

## Permissions Guide

VoiceMaestro needs channel and voice permissions to create and manage temporary rooms correctly.

## Core Permissions

### View Channels

Lets the bot see configured voice channels and any text channels used for status or interface messages.

### Manage Channels

Required to create, rename, hide, lock, and delete temporary voice rooms.

### Move Members

Required for join-to-create handoff and owner moderation flows.

### Connect

Allows the bot to connect where voice features require active presence.

### Send Messages

Needed for setup confirmations, owner greetings, status messages, and support responses.

### Embed Links

Required for rich status, help, support, and setup responses.

### Read Message History

Used when status or interface flows need to inspect existing messages safely.

### Use Slash Commands

Required for all `/` commands.

## Permission Troubleshooting Tip

If a command runs but nothing changes, check both:

1. Bot role permissions in **Server Settings -> Roles**
2. Channel-level permission overrides in **Edit Channel -> Permissions**

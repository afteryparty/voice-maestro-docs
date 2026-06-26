---
layout: default
title: Setup
description: First-time setup guide for VoiceMaestro server owners.
permalink: /setup/
---

## First-Time Setup

### 1. Invite VoiceMaestro

Use the official invite link:

[Invite VoiceMaestro](https://discord.com/oauth2/authorize?client_id=1165878496879452170&permissions=8&scope=bot%20applications.commands)

### 2. Check Role Position

Open **Server Settings -> Roles** and move the VoiceMaestro role high enough to manage temporary voice channels.

### 3. Create Join-to-Create

Run:

- `/setup create`

This creates the voice entry system where users join one hub channel and receive their own temporary room.

### 4. Optional: Create the Interface Message

Run:

- `/interface create`

This posts an optional interface message for easier room management with buttons.

### 5. Configure Optional Greetings

Run:

- `/tempvc-random-greetings`

Use this to enable or disable random owner greeting messages for new temporary channels.

### 6. Run a Live Test

1. Join the configured hub voice channel.
2. Confirm a temporary room is created.
3. Confirm the joining member is moved into it.
4. Test `/voice info`, `/voice password`, and `/voice reset`.
5. Confirm cleanup works when the room becomes empty.

## Setup Checklist

- Bot can view and manage relevant channels
- Slash commands are visible
- Join-to-create works correctly
- Room owner controls function as expected
- Optional interface message works if enabled

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

Open **Server Settings → Roles** and move the VoiceMaestro role high enough to manage temporary voice channels.

### 3. Create Join-to-Create

Run:

- `/setup create`

This creates the voice entry system where users join one channel and receive their own temporary room.

### 4. Optional: Create Interface Panel

Run:

- `/interface`

This posts a control panel message for easier room management.

### 5. Run a Live Test

1. Join the configured hub voice channel.
2. Confirm a temporary room is created.
3. Test `/lock`, `/rename`, and `/limit`.
4. Confirm owner transfer works with `/transfer`.

## Setup Checklist

- Bot can view/manage relevant channels
- Slash commands are visible
- Join-to-create channel works
- Room owner controls function as expected

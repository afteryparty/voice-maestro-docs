---
layout: default
title: VoiceMaestro
description: Dynamic join-to-create voice management for Discord with owner controls and premium upgrades.
---

## Overview

**VoiceMaestro** creates temporary voice channels on demand and then gives channel owners the controls they need to manage those rooms. It is built for communities that want self-service voice channels without constant moderator involvement.

## Features

- Join-to-create voice room generation
- Channel owner controls for naming, limits, privacy, and access
- Lock, unlock, hide, reveal, and transfer workflows
- Optional panel or interface setup for easier room management
- Premium tools for more advanced voice-channel control

## Quick Start

1. Invite VoiceMaestro to your server.
2. Run `/setup create` to create the join-to-create entry point.
3. Optionally run `/interface` to add the control panel.
4. Join the configured voice hub and test creating a room.

## Commands

### Setup and Configuration

`/setup create`, `/setup delete`, `/interface`, `/delete interface`

### Channel Management

`/lock`, `/unlock`, `/hide`, `/reveal`, `/rename`, `/limit`, `/bitrate`, `/video_quality`

### User Access

`/permit`, `/reject`, `/claim`, `/transfer`, `/trust`, `/untrust`, `/block`, `/unblock`

### Premium and Utility

`/premium`, `/panel`, `/dashboard`, `/automation`, `/voicestats`, `/presets`, `/stats`, `/ping`, `/help`, `/support`

## Required Permissions

- View Channels
- Manage Channels
- Move Members
- Connect
- Send Messages
- Embed Links
- Read Message History
- Use Slash Commands

## Troubleshooting

- If join-to-create is not spawning channels, verify the setup command completed successfully and the bot can manage channels.
- If members cannot manage their rooms, check owner or trust state along with the bot role permissions.
- If the interface panel is not responding, confirm the message still exists and that button interactions are enabled.
- If premium-only features do not appear, verify the current server or user access level first.

## FAQ

### Does every member get their own room?

Members get their own temporary room when the join-to-create flow is configured and they enter the correct hub channel.

### Can users rename and lock their channels?

Yes. VoiceMaestro is built around owner-side controls for room naming, privacy, limits, and access.

### Do I need the optional interface?

No. It helps usability, but the base join-to-create system works without it.

## Support

Use the Support button above for setup help, premium questions, or troubleshooting with the temporary voice workflow.

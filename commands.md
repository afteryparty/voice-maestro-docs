---
layout: default
title: Commands
description: VoiceMaestro command reference.
permalink: /commands/
---

## Commands

VoiceMaestro is **free-first**, so normal server functionality is not locked behind a premium tier.

### Setup and Configuration

| Command | Description | Typical Use |
| --- | --- | --- |
| `/setup create` | Creates the join-to-create voice hub system. | First-time server setup |
| `/setup delete` | Removes the existing voice hub setup. | Reset or rebuild setup |
| `/interface create` | Posts the optional interface message for quick room controls. | Easier member control access |
| `/interface delete` | Removes the interface message. | Cleanup |
| `/tempvc-random-greetings` | Enables or disables random owner greetings for new temp VCs. | Greeting preference |

### Voice and Owner Controls

| Command | Description | Typical Use |
| --- | --- | --- |
| `/channel` | Creates a temporary voice channel manually. | Manual room creation |
| `/bitrate` | Adjusts room audio quality settings. | Quality tuning |
| `/move` | Moves a selected member to your voice channel. | Owner moderation |
| `/release` | Moves members out of a waiting room flow. | Queue handling |
| `/activity` | Starts a compatible Discord activity. | Community sessions |
| `/voice info` | Shows information about your current temporary voice channel. | Room details |
| `/voice password` | Sets, updates, or removes a room password. | Private access |
| `/voice reset` | Resets your temporary voice channel to default settings. | Cleanup |
| `/find` | Finds a user's current voice channel. | Voice lookup |
| `/video quality` | Sets room video quality mode. | Video performance |
| `/age restrict` | Toggles age restriction for the current room. | Room safety |

### Automation and Room Management

| Command | Description | Typical Use |
| --- | --- | --- |
| `/automation` | Configures auto-delete, auto-role, and idle options. | Automation setup |
| `/permissions` | Applies or manages room permission templates. | Access setup |
| `/presets` | Saves or loads room presets. | Reusable setup |
| `/mode` | Applies a saved room mode or preset. | Fast room setup |
| `/leaderboard` | Shows voice activity stats and leaderboards. | Engagement insight |

### Info and Support

| Command | Description | Typical Use |
| --- | --- | --- |
| `/help` | Opens the help menu. | Command discovery |
| `/about` | Shows project and bot information. | Bot overview |
| `/support` | Returns support links and project resources. | Get help |
| `/premium` | Explains VoiceMaestro+ as an optional supporter membership. | Supporter info |
| `/ping` | Shows response latency. | Connectivity check |
| `/status` | Displays bot status and statistics. | Runtime check |
| `/faq` | Opens common questions and answers. | Self-help |

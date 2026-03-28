---
name: h-ear
description: Audio classification and noise monitoring. Classify audio files, list 521+ sound classes, check usage, browse jobs, and set up sound alerts.
version: 0.1.0
author: H-ear World
homepage: https://h-ear.world
openclaw:
  requires:
    env: [HEAR_API_KEY]
    bins: []
  primaryEnv: HEAR_API_KEY
---

# H-ear — Sound Intelligence for AI Agents

Classify audio, detect noise events, and set up real-time sound alerts through any messaging channel.

## Commands

| Command | Description |
|---------|-------------|
| `classify <url>` | Classify audio from a URL |
| `classify batch <url1> <url2>...` | Batch classify multiple audio URLs |
| `sounds [search]` | List supported sound classes (521+) |
| `usage` | Show API usage statistics |
| `jobs [last N]` | List recent classification jobs |
| `job <id>` | Show detailed job results |
| `alerts on <sound>` | Enable alerts for a sound class |
| `alerts off <sound>` | Disable alerts for a sound class |
| `health` | Check API status |

## Setup

Set `HEAR_API_KEY` to your H-ear Enterprise API key. Get one at [h-ear.world](https://h-ear.world).

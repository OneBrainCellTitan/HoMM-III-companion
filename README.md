# HoMM III Companion

HoMM III Companion is a streamer-side companion app for Heroes of Might and Magic III: Horn of the Abyss. It reads live game state from the running game process and sends it to a Twitch Extension, so viewers can inspect the streamer's current hero, army, artifacts, skills, spellbook, movement, spell points, and other useful details without cluttering the broadcast scene.

The project is designed for Heroes III PvP streams, where viewers want quick access to hero information while the streamer keeps the game screen clean.

## What It Does

- Connects to a running Heroes III / HotA game on the streamer's PC.
- Publishes the streamer's current game state to the companion relay server.
- Powers an interactive Twitch overlay for viewers.
- Shows hero portraits, primary stats, morale, luck, experience, secondary skills, artifacts, army stacks, spellbook, and detailed popups.
- Keeps viewer interaction separate from OBS scene layout.

## Streamer App

Release builds of the Windows streamer app will be published in this repository.

The streamer app is intended to be simple:

1. Launch Heroes III / HotA.
2. Launch HoMM III Companion.
3. Connect your Twitch account.
4. Start streaming with the companion Twitch Extension enabled.

## Support

If you want to support the project, you can use the Monobank jar:

https://send.monobank.ua/jar/AGKRYBbgPD

QR widget:

https://send.monobank.ua/widget.html?jar=56wdtBYgRUQSoc2mNkAP4rYTE5nmVEmb&sendId=AGKRYBbgPD&type=qr

## Status

This repository is used for public releases and basic project information. The companion is currently in active development and testing.

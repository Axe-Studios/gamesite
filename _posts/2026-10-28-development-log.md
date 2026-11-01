---
title: "Development Log - October 28, 2026"
date: 2026-10-28
categories:
  - development
tags:
  - unity
  - ai
  - combat
  - development-tools
---

AI pursuit began connecting to attack behavior, with a supporting improvement to NPC debugging.

## Highlights

- Continued pursuit and attack work, including early NPC attack triggering.
- Updated attack actions to support both melee and ranged weapons.
- Kept AI in the pursuing state while checking for available actions at intervals.
- Expanded the debug monitor to support subgroups, making it easier to inspect one NPC among several.

## Commit Summary

Two Unity project commits were recorded, covering AI combat behavior and debug-monitor organization.

## Development Notes

The combat prototype is beginning to connect navigation with action selection: pursuing characters can check for an available attack instead of relying on a separate engaged state.

---
title: "Development Log - July 28, 2026"
date: 2026-07-28
categories:
  - development
tags:
  - unity
  - prototype
  - animation
  - weapons
  - lfs
  - tooling
---

Today's work was a dense animation and weapon-action pass, with some repository storage testing for animation assets.

## Highlights

RPG character animation source files were replaced with extracted animation clips, and the controller was updated to use the new clip layout. Additional animations were added, event triggers were fixed, and more weapon type overrides were introduced.

Combat stance support continued in animation components, including upper body stance work and equip/unequip behavior. A custom animator controller inspector button was added to extract clip names, making animation setup easier to inspect.

Git LFS handling was also tested for animation clips, since animation assets can become large and noisy in normal source control.

## Commit Summary

Nine commits were recorded in the private Unity prototype:

- Replaced source animation files with extracted animation clips.
- Updated animation controller and addressable animation grouping.
- Added and fixed several weapon/action animations.
- Continued combat stance and weapon override implementation.
- Added animator controller tooling for clip-name extraction.
- Tested Git LFS handling for animation clips.

## Development Notes

This was a major animation iteration day. A lot of the work was still experimental, but it pushed weapon-specific animation behavior much closer to the needs of an action prototype.

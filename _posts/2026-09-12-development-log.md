---
title: "Development Log - September 12, 2026"
date: 2026-09-12
categories:
  - development
tags:
  - unity
  - prototype
  - characters
  - assets
  - animation
  - tooling
---

Today's work focused on character assets and early tooling for modular/skinned mesh skeleton remapping.

## Highlights

A batch of modular character assets from an asset pack was added as work-in-progress content. A modular test character prefab was also added, along with missing level-of-detail and mesh data for a test character in the sample scene.

The first pass of a utility for remapping skeletons on skinned meshes was added, followed by in-scene testing and an undo pass. This should help with modular character work where meshes need to line up with a target skeleton.

## Commit Summary

Four commits were recorded in the private Unity project:

- Added a batch of work-in-progress character assets.
- Added a first pass of a skinned mesh skeleton remapping utility.
- Tested skeleton remapping behavior in-scene.
- Added undo support and missing test character data.

## Development Notes

This was a character pipeline day. The work supports more flexible NPC and modular character setup, which should matter as the prototype town starts needing more believable people in it.

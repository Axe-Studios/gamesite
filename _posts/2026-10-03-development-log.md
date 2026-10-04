---
title: "Development Log - October 3, 2026"
date: 2026-10-03
categories:
  - development
tags:
  - unity
  - characters
  - animation
  - assets
---

The week ended with a broad character-asset cleanup and integration pass.

## Highlights

- Added a new male player prefab using the updated NPC Casual Collection meshes.
- Updated experimental skin shader with a smoothness multiplier and adjusted the related materials.
- Replaced temporary imported meshes with newly exported NPC Casual Collection meshes.
- Updated the test prefab to represent a complete character.
- Re-enabled colliders on vegetation prefabs removed during performance profiling.
- Continued and finalized the current pass on the skeleton remapper.
- Removed temporary Mixamo character assets and obsolete editor components.
- Replaced prefabs for the player companion characters and grocery clerk.
- Added collections and small housekeeping changes to the NPC Casual Blender source file.

## Commit Summary

Six Unity project commits and one EncounterAssets commit were recorded, covering character meshes, materials, prefabs, remapping, vegetation collisions, and Blender source organization.

## Development Notes

The work consolidated several temporary character experiments into more complete prefabs and exported meshes. The skeleton-remapping pass is now in a much more finished state, while the companion and NPC replacements move the prototype toward a more consistent character set.

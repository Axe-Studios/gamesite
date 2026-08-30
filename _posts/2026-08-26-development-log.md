---
title: "Development Log - August 26, 2026"
date: 2026-08-26
categories:
  - development
tags:
  - unity
  - prototype
  - ui
  - windows
  - editor
  - asset-management
---

Today's work continued UI window definition and inspector improvements, while also splitting out part of the asset loading responsibility.

## Highlights

Part of the entity manager was split into a new asset manager, helping separate asset/object creation concerns from broader entity management.

The first pass of window definition loading was completed, and window sorting became more explicit with display order IDs and order bias values. Window prefabs were updated to include those values, and sorting logic was revised to use the new ordering data.

The UI window inspector also received more work and cleanup, making editor-time window setup easier to manage.

## Commit Summary

Three commits were recorded in the private Unity project:

- Split asset loading responsibilities out of the entity manager into an asset manager.
- Finished the first pass of window definition loading.
- Added window display order and order bias support.
- Continued UI window inspector updates and cleanup.

## Development Notes

This continued the shift toward more maintainable UI infrastructure, with windows becoming data-driven and editor setup becoming less fragile.

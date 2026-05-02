# Overview: Merging Lightroom Classic Catalogs

## Purpose

This document explains the concept and process of merging multiple Adobe Lightroom Classic catalogs into a single, unified catalog.

The goal is to consolidate photo libraries, edits, and organizational structures while minimizing data loss, duplicates, and broken file links.

---

## What is a Lightroom Catalog?

In Adobe Lightroom Classic, a catalog is a database that stores:
- Photo metadata (ratings, flags, keywords)
- Develop edits (non-destructive adjustments)
- Collection organization
- File references (NOT the actual image files)

A catalog does **not** contain the original photos themselves—it only references them on disk.

---

## Why Merge Catalogs?

Over time, multiple catalogs may be created due to:
- Different projects or years
- Use of multiple computers
- External drive separation
- Backup or migration workflows

Merging catalogs helps:
- Centralize your entire photo library
- Maintain consistent editing history
- Simplify backup and storage
- Improve long-term organization and searchability

---

## Key Concepts Before You Start

### 1. Master Catalog
You must choose one catalog as your **primary (master) catalog**.  
All other catalogs will be imported into this one.

### 2. File Location vs Catalog Data
- Catalog = edits + organization
- Files = actual images stored on drives

Merging catalogs does NOT move your photos automatically.

### 3. Drive Dependencies
If catalogs reference multiple external drives, Lightroom may show missing files until those drives are connected and relinked.

---

## Common Scenarios for Merging

You may need to merge catalogs if:
- You edited photos on multiple machines
- You have separate catalogs per year or project
- You migrated between external drives
- You created backup catalogs over time

---

## Risks and Considerations

Before merging catalogs, be aware of:

- **Duplicate photos** may appear if the same images exist in multiple catalogs
- **Conflicting edits** can occur if the same photo was edited differently
- **Missing files** will appear if external drives are disconnected
- **Storage fragmentation** if folder structures differ between catalogs

---

## Recommended Approach

The safest workflow is:

1. Select the most complete and up-to-date catalog as the master
2. Import older catalogs into it using Lightroom’s “Import from Another Catalog” feature
3. Carefully manage existing vs new photo handling during import
4. Reconnect missing folders by identifying their original drives
5. Optimize and back up the final catalog

---

## Related Guides

- `step-by-step-workflow.md` → Full merging process
- `drive-management.md` → Handling external drives and missing files
- `troubleshooting.md` → Fixing common issues after merging
- `best-practices.md` → Long-term catalog organization strategy

---

## Summary

Merging Lightroom Classic catalogs is a powerful way to consolidate fragmented photo libraries, but it requires careful handling of file paths, edits, and duplicates.

A structured workflow ensures a single, stable catalog that is easier to manage, back up, and scale over time.

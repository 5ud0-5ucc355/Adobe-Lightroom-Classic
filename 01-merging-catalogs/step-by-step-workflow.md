# Lightroom Classic Catalog Merge Workflow

## Overview

This workflow outlines a safe, repeatable process for merging multiple Lightroom Classic catalogs into a single master catalog while preserving edits, minimizing duplicates, and handling multi-drive storage.

---

## Prerequisites

* Identify your **master catalog** (most recent / most complete)
* Ensure sufficient disk space for previews and metadata
* Backup all catalogs before starting

---

## Step 1 — Open Master Catalog

* Launch Lightroom Classic
* Open your chosen **master `.lrcat` file**
* This will be the destination for all imports

---

## Step 2 — Import an Older Catalog

* Navigate to:
  `File → Import from Another Catalog`
* Select an older `.lrcat` file

---

## Step 3 — Configure Import Settings

### For Existing Photos

* Select: **Metadata and develop settings only**
* Optional: Enable **Preserve old settings as virtual copies**

**Purpose:**

* Prevent overwriting newer edits
* Retain older edits safely (if needed)

---

### For New Photos

* Select: **Add new photos to catalog without moving**

**Purpose:**

* Avoid unnecessary file duplication
* Maintain current folder structure

---

## Step 4 — Complete Import

* Execute the import
* Allow previews and metadata to load

---

## Step 5 — Identify Missing Files

* Navigate to **Library Module**
* Review **Folders panel**
* Look for:

  * Missing folders (`?` icon)
  * Offline files (`!` icon)

---

## Step 6 — Relink Drives and Folders

### Determine Source Drive

* Check folder path (e.g., `E:\Photos\...` or `/Volumes/DriveName/...`)
* Identify corresponding physical drive

---

### Reconnect Files

* Connect the appropriate external drive
* Right-click top-level missing folder → **Find Missing Folder**
* Point to correct location

**Tip:**
Relinking a top-level folder reconnects all subfolders automatically

---

## Step 7 — Repeat for All Catalogs

* Repeat Steps 2–6 for each additional catalog
* Always import **into the same master catalog**

---

## Step 8 — Validate Merge

### Check for:

* Missing files (resolve all `!`)
* Folder consistency
* Collection integrity
* Recent edits preserved

---

## Step 9 — Optimize Catalog

* Navigate to:
  `File → Optimize Catalog`

---

## Step 10 — Backup

* Create a fresh backup of the merged catalog
* Store backup on a separate drive if possible

---

## Optional — Duplicate Cleanup

* Sort by:

  * Capture Time
  * File Name
* Identify and remove duplicates manually or via plugin

---

## Recommended Best Practices

* Use **one catalog going forward**
* Store all photos on a **single external drive** when possible
* Maintain consistent folder structure
* Rename drives clearly (avoid "Untitled")

---

## Common Pitfalls

| Issue            | Cause                   | Solution                                 |
| ---------------- | ----------------------- | ---------------------------------------- |
| Missing files    | Disconnected drive      | Reconnect via "Find Missing Folder"      |
| Duplicate images | Overlapping catalogs    | Use careful import settings + cleanup    |
| Lost edits       | Overwrite during import | Use "Metadata and develop settings only" |
| Broken structure | Mixed storage paths     | Consolidate post-merge                   |

---

## Summary

* Always merge **into your latest catalog**
* Do **not overwrite newer edits**
* Relink files after import as needed
* Consolidate storage to simplify future workflows

---

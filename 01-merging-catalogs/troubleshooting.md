# Troubleshooting Lightroom Classic Catalog Merges

## Overview

This guide covers common issues encountered when merging catalogs in Adobe Lightroom Classic and how to resolve them safely.

Most issues arise from file path mismatches, missing external drives, or conflicting catalog data.

---

## 1. Missing Files (! or ? Icons)

### Symptoms
- Photos show a “!” icon
- Folders show a “?” icon
- Thumbnails may still appear but are unusable for editing

### Cause
- External drive is disconnected
- Folder path has changed
- Drive name has changed

### Fix
1. Connect the correct external drive
2. In the Folders panel, right-click the missing folder
3. Select **Find Missing Folder**
4. Point Lightroom to the correct location

---

## 2. Entire Folder Shows as Missing

### Cause
- Root folder moved or renamed outside Lightroom
- Drive letter changed (Windows) or mount point changed (macOS)

### Fix
- Reconnect the top-level folder only
- Lightroom will relink all subfolders automatically

---

## 3. Duplicate Photos After Merge

### Cause
- Same photos exist in multiple catalogs
- Catalogs were merged without consistent structure

### Fix Options
- Sort by filename or capture time in Library view
- Use visual comparison to identify duplicates
- Remove or flag duplicates manually

---

## 4. Edits Missing After Import

### Cause
- Import settings were incorrect during catalog merge
- “Metadata only” option not selected properly

### Fix
- Re-import the affected catalog using:
  - **Metadata and develop settings only**
  - Optionally enable **Virtual Copies**

---

## 5. Catalog Feels Slow After Merge

### Cause
- Large combined catalog
- Too many previews or unresolved file links

### Fix
- Go to **File → Optimize Catalog**
- Build or rebuild smart previews if needed
- Remove unused collections or rejected images

---

## 6. External Drive Not Recognized

### Cause
- Drive disconnected or renamed
- OS assigned a different mount point

### Fix
- Reconnect drive
- If needed, rename drive back to original label
- Use “Find Missing Folder” if Lightroom does not auto-reconnect

---

## 7. Wrong Folder Structure After Import

### Cause
- Catalogs had different organizational systems

### Fix
- Do not move files in Finder/File Explorer
- Reorganize inside Lightroom using the Folders panel

---

## Summary

Most Lightroom Classic issues during catalog merging are caused by mismatched file paths or disconnected drives.

Using consistent drive naming and always reconnecting storage before merging prevents most problems.

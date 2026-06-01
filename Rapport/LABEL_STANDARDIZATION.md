# Label Standardization Report

**Generated:** 2026-05-25

---

## Summary

This report documents all figure and table labels found in the report and proposes a standardized naming scheme for consistency.

- **Total Figures:** 28
- **Total Tables:** 17
- **Total Labels:** 45

---

## CHAPTER 1 (Chapter1.tex)

### Current Figures: 5

| Line | Current Label | Proposed Label | Type |
|------|---------------|----------------|------|
| 75 | `fig:1` | `fig:chapter1-1` | Figure |
| 166 | `fig:2` | `fig:chapter1-2` | Figure |
| 183 | `fig:block_diagram` | `fig:chapter1-3` | Figure |
| 190 | `fig:architecture_diagram` | `fig:chapter1-4` | Figure |
| 231 | `fig:requirements_diagram` | `fig:chapter1-5` | Figure |

### Current Tables: 2

| Line | Current Label | Proposed Label | Type |
|------|---------------|----------------|------|
| 260 | `tab:functional_requirements` | `tab:chapter1-1` | Table |
| 287 | `tab:non_functional_requirements` | `tab:chapter1-2` | Table |

**Files to Update:** `chapters/Chapter1.tex`

---

## CHAPTER 2 (Chapter2.tex)

### Current Figures: 6

| Line | Current Label | Proposed Label | Type |
|------|---------------|----------------|------|
| 15 | `fig:usecase_diagram` | `fig:chapter2-1` | Figure |
| 53 | `fig:sequence_overview_consultation` | `fig:chapter2-2` | Figure |
| 62 | `fig:sequence_stops_export` | `fig:chapter2-3` | Figure |
| 287 | `fig:unwinding-unit-view` | `fig:chapter2-4` | Figure |
| 298 | `fig:inspection-unit-view` | `fig:chapter2-5` | Figure |
| 309 | `fig:rewinding-unit-view` | `fig:chapter2-6` | Figure |

### Current Tables: 8

| Line | Current Label | Proposed Label | Type |
|------|---------------|----------------|------|
| 44 | `tab:use_case_description` | `tab:chapter2-1` | Table |
| 77 | `tab:scope-revision` | `tab:chapter2-2` | Table |
| 117 | `tab:mate-strategy` | `tab:chapter2-3` | Table |
| 145 | `tab:assembly-validation` | `tab:chapter2-4` | Table |
| 173 | `tab:title-block` | `tab:chapter2-5` | Table |
| 203 | `tab:drawing-package` | `tab:chapter2-6` | Table |
| 231 | `tab:view-selection` | `tab:chapter2-7` | Table |
| 259 | `tab:mechanical-reading` | `tab:chapter2-8` | Table |

**Files to Update:** `chapters/Chapter2.tex`

---

## CHAPTER 3 (Chapter3.tex)

### Current Figures: 4

| Line | Current Label | Proposed Label | Type |
|------|---------------|----------------|------|
| 19 | `fig:overview_dashboard` | `fig:chapter3-1` | Figure |
| 32 | `fig:overview_dashboard_period` | `fig:chapter3-2` | Figure |
| 47 | `fig:stops_analytics_page` | `fig:chapter3-3` | Figure |
| 311 | `fig:query-performance-compact` | `fig:chapter3-4` | Figure |

### Current Tables: 7

| Line | Current Label | Proposed Label | Type |
|------|---------------|----------------|------|
| 58 | `tab:core-context-compact` | `tab:chapter3-1` | Table |
| 95 | `tab:query-a-compact` | `tab:chapter3-2` | Table |
| 138 | `tab:index-only-summary` | `tab:chapter3-3` | Table |
| 165 | `tab:query-c-impact` | `tab:chapter3-4` | Table |
| 200 | `tab:generated-columns-compact` | `tab:chapter3-5` | Table |
| 225 | `tab:index-design-compact` | `tab:chapter3-6` | Table |
| 286 | `tab:final-benchmark-summary` | `tab:chapter3-7` | Table |

**Files to Update:** `chapters/Chapter3.tex`

---

## CHAPTER 4 (Chapter4.tex)

### Current Figures: 13

| Line | Current Label | Proposed Label | Type |
|------|---------------|----------------|------|
| 30 | `fig:visiteuse2-deployment` | `fig:chapter4-1` | Figure |
| 87 | `fig:visiteuse2-stop-scenario` | `fig:chapter4-2` | Figure |
| 114 | `fig:visiteuse2-ladder-structure` | `fig:chapter4-3` | Figure |
| 287 | `fig:sql-stop-records` | `fig:chapter4-4` | Figure |
| 294 | `fig:visiteuse2-short-stop-sequence` | `fig:chapter4-5` | Figure |
| 301 | `fig:visiteuse2-long-stop-sequence` | `fig:chapter4-6` | Figure |
| 308 | `fig:visiteuse2-modbus-mapping` | `fig:chapter4-7` | Figure |
| 327 | `fig:hmi-vi20-main` | `fig:chapter4-8` | Figure |
| 334 | `fig:hmi-vi20-causes` | `fig:chapter4-9` | Figure |
| 346 | `fig:web-runtime-status` | `fig:chapter4-10` | Figure |
| 353 | `fig:hmi-web-dashboard` | `fig:chapter4-11` | Figure |
| 360 | `fig:hmi-web-causes` | `fig:chapter4-12` | Figure |
| 408 | `fig:visiteuse2-hmi-complementarity` | `fig:chapter4-13` | Figure |

### Current Tables: 0

No tables found in Chapter 4.

**Files to Update:** `chapters/Chapter4.tex`

---

## Standardization Scheme

### Naming Convention

**For Figures:**
```
\label{fig:chapterN-M}
```
Where:
- `N` = Chapter number (1, 2, 3, or 4)
- `M` = Sequential figure number within that chapter (1, 2, 3, ...)

Example: `fig:chapter1-1`, `fig:chapter2-5`, `fig:chapter4-13`

**For Tables:**
```
\label{tab:chapterN-M}
```
Where:
- `N` = Chapter number (1, 2, 3, or 4)
- `M` = Sequential table number within that chapter (1, 2, 3, ...)

Example: `tab:chapter1-1`, `tab:chapter2-8`, `tab:chapter3-7`

---

## Files Requiring Changes

1. **chapters/Chapter1.tex** — 7 labels to update (5 figures + 2 tables)
2. **chapters/Chapter2.tex** — 14 labels to update (6 figures + 8 tables)
3. **chapters/Chapter3.tex** — 11 labels to update (4 figures + 7 tables)
4. **chapters/Chapter4.tex** — 13 labels to update (13 figures + 0 tables)

**Total Labels to Update:** 45

---

## Benefits of Standardization

✓ **Consistency** — All labels follow the same pattern  
✓ **Clarity** — Easy to identify which chapter a label belongs to  
✓ **Maintainability** — Simple to add/remove/reorder figures and tables  
✓ **Scalability** — Works regardless of content changes  
✓ **Searchability** — Descriptive labels are replaced with systematic ones

---

## Next Steps

1. Update all `\label{...}` commands in each chapter file
2. Update all `\ref{...}` and `\autoref{...}` references to use new labels
3. Verify all cross-references compile correctly
4. Test that hyperlinks and figure/table numbering are correct

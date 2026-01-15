# Asset Inventory

**Project:** [Your Game Title]
**Last Updated:** [Date]

---

## Overview

This document tracks all game assets: graphics, audio, UI elements, and other media files.

### Asset Status Key
| Status | Meaning |
|--------|---------|
| Placeholder | Temporary asset, needs replacement |
| WIP | Work in progress |
| Review | Needs review/approval |
| Final | Complete and approved |

### Asset Folder Structure
```
assets/
├── graphics/
│   ├── sprites/
│   ├── backgrounds/
│   ├── ui/
│   ├── effects/
│   └── tilesets/
├── audio/
│   ├── music/
│   ├── sfx/
│   └── ambient/
├── fonts/
└── data/
```
*(Modify to match your actual structure)*

---

## 1. Graphics - Sprites

### Player Character

| Asset Name | File | Dimensions | Frames | Status | Notes |
|------------|------|------------|--------|--------|-------|
| player_idle | | | | | |
| player_walk | | | | | |
| player_run | | | | | |
| player_jump | | | | | |
| player_attack | | | | | |
| player_death | | | | | |

### Enemies

| Asset Name | File | Dimensions | Frames | Status | Notes |
|------------|------|------------|--------|--------|-------|
| | | | | | |
| | | | | | |

### NPCs

| Asset Name | File | Dimensions | Frames | Status | Notes |
|------------|------|------------|--------|--------|-------|
| | | | | | |

### Items / Pickups

| Asset Name | File | Dimensions | Frames | Status | Notes |
|------------|------|------------|--------|--------|-------|
| | | | | | |

### Projectiles

| Asset Name | File | Dimensions | Frames | Status | Notes |
|------------|------|------------|--------|--------|-------|
| | | | | | |

---

## 2. Graphics - Environments

### Backgrounds

| Asset Name | File | Dimensions | Status | Notes |
|------------|------|------------|--------|-------|
| | | | | |

### Tilesets

| Tileset Name | File | Tile Size | Tile Count | Status | Notes |
|--------------|------|-----------|------------|--------|-------|
| | | | | | |

### Environmental Objects

| Asset Name | File | Dimensions | Animated | Status | Notes |
|------------|------|------------|----------|--------|-------|
| | | | | | |

---

## 3. Graphics - Visual Effects

| Effect Name | File | Dimensions | Frames | Trigger | Status | Notes |
|-------------|------|------------|--------|---------|--------|-------|
| explosion | | | | On enemy death | | |
| hit_spark | | | | On damage | | |
| dust_cloud | | | | On land | | |
| | | | | | | |

---

## 4. Graphics - UI Elements

### Menus

| Asset Name | File | Dimensions | Status | Notes |
|------------|------|------------|--------|-------|
| main_menu_bg | | | | |
| button_normal | | | | |
| button_hover | | | | |
| button_pressed | | | | |
| | | | | |

### HUD

| Asset Name | File | Dimensions | Status | Notes |
|------------|------|------------|--------|-------|
| health_bar_frame | | | | |
| health_bar_fill | | | | |
| score_display | | | | |
| minimap_frame | | | | |
| | | | | |

### Icons

| Asset Name | File | Dimensions | Purpose | Status | Notes |
|------------|------|------------|---------|--------|-------|
| | | | | | |

### Cursors (if custom)

| Asset Name | File | Dimensions | Context | Status | Notes |
|------------|------|------------|---------|--------|-------|
| cursor_default | | | General | | |
| cursor_interact | | | Over interactable | | |
| | | | | | |

---

## 5. Audio - Music

| Track Name | File | Duration | Format | Loop | Context | Status | Notes |
|------------|------|----------|--------|------|---------|--------|-------|
| main_theme | | | | Yes/No | Main menu | | |
| gameplay_01 | | | | | Normal gameplay | | |
| boss_battle | | | | | Boss encounters | | |
| victory | | | | | Level complete | | |
| game_over | | | | | Game over screen | | |
| | | | | | | | |

---

## 6. Audio - Sound Effects

### Player SFX

| Sound Name | File | Duration | Format | Trigger | Status | Notes |
|------------|------|----------|--------|---------|--------|-------|
| player_jump | | | | On jump | | |
| player_land | | | | On land | | |
| player_attack | | | | On attack | | |
| player_hurt | | | | On damage taken | | |
| player_death | | | | On death | | |
| footstep_01 | | | | Walking | | |
| | | | | | | |

### Enemy SFX

| Sound Name | File | Duration | Format | Trigger | Status | Notes |
|------------|------|----------|--------|---------|--------|-------|
| enemy_alert | | | | On spotting player | | |
| enemy_attack | | | | On attack | | |
| enemy_hurt | | | | On damage | | |
| enemy_death | | | | On death | | |
| | | | | | | |

### UI SFX

| Sound Name | File | Duration | Format | Trigger | Status | Notes |
|------------|------|----------|--------|---------|--------|-------|
| ui_click | | | | Button click | | |
| ui_hover | | | | Button hover | | |
| ui_confirm | | | | Selection confirm | | |
| ui_cancel | | | | Cancel/back | | |
| ui_error | | | | Invalid action | | |
| | | | | | | |

### Environment SFX

| Sound Name | File | Duration | Format | Trigger | Status | Notes |
|------------|------|----------|--------|---------|--------|-------|
| door_open | | | | | | |
| item_pickup | | | | | | |
| | | | | | | |

---

## 7. Audio - Ambient

| Track Name | File | Duration | Format | Context | Status | Notes |
|------------|------|----------|--------|---------|--------|-------|
| ambient_forest | | | | Forest areas | | |
| ambient_dungeon | | | | Indoor/dungeon | | |
| | | | | | | |

---

## 8. Fonts

| Font Name | File | Sizes Used | Purpose | License | Status |
|-----------|------|------------|---------|---------|--------|
| | | | Main UI | | |
| | | | Titles | | |
| | | | Dialogue | | |

---

## 9. Data Files

| File Name | Format | Purpose | Status | Notes |
|-----------|--------|---------|--------|-------|
| levels.json | JSON | Level definitions | | |
| items.json | JSON | Item database | | |
| dialogue.json | JSON | NPC dialogue | | |
| config.json | JSON | Game settings | | |
| | | | | |

---

## Asset Production Checklist

### Before Release
- [ ] All placeholders replaced with final assets
- [ ] All assets properly named and organized
- [ ] Audio levels normalized and consistent
- [ ] Sprite dimensions power-of-2 (if required)
- [ ] All licenses documented
- [ ] Unused assets removed from build

### Asset Specifications Reference

**Sprites:**
- Format:
- Color depth:
- Background: Transparent

**Audio:**
- Music format:
- SFX format:
- Sample rate:
- Bit depth:

**Data:**
- Format: JSON
- Encoding: UTF-8

---

## Asset Sources & Licenses

Track where assets come from and their usage rights:

| Asset/Set | Source | License | Attribution Required | Commercial OK |
|-----------|--------|---------|---------------------|---------------|
| | Original | N/A | No | Yes |
| | | | | |

---

## Notes

*Use this section for asset-related notes and decisions:*

-

---

*End of Asset Inventory*

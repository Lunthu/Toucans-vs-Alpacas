# 🪶 Beak & Wool: Tactical Tussle

A light‑hearted, **Advance Wars‑inspired** tactical strategy game where the flamboyant **Toucans** and the stoic **Alpacas** battle for supremacy in the Great Fruit War. Command units, capture villages, and out‑think your opponent across vibrant 8×8 maps.

---

## 🎮 Gameplay Overview

- **Turn‑based combat** on a grid‑based battlefield.
- **Two factions** with unique unit types, abilities, and terrain strengths:
  - **Toucans** thrive in forests and jungles, using mobility and range.
  - **Alpacas** dominate hills and mountains, leveraging defense and staying power.
- Win by eliminating enemy forces or meeting special mission objectives.

---

## 🗺 Features

- **8×8 tactical grid** with diverse terrain: Grass 🌱, Forest 🌲, Mountain ⛰️, Water 🌊, and Village 🏠.
- **Faction‑flavored units** with asymmetric stats and special abilities.
- **Action system**: Move, Attack, Special Ability, or Wait.
- Visual **HP bars** and clear movement/attack highlights.
- **Turn indicator** showing current player and round count.
- **Combat log** to track every action in the match.
- Victory modal when a faction wins.

---

## 🪖 Units & Abilities

| Unit | Faction | HP | Move | Range | ATK | DEF | Special |
|------|---------|----|------|-------|-----|-----|---------|
| **Scout** 🦜 | Toucan | 8 | 6 | 1 | 4 | 2 | *Sky Glide* — ignores terrain penalties |
| **Archer** 🏹 | Toucan | 8 | 4 | 3 | 5 | 3 | *Perch Shot* — +1 range in forest |
| **Dive Bomber** 💥 | Toucan | 10 | 5 | 1 | 6 | 2 | *Swoop Strike* — splash damage |
| **Infantry** 🦙 | Alpaca | 10 | 4 | 1 | 4 | 4 | *Wool Shield* — +2 defense until next turn |
| **Siege Carrier** 🚛 | Alpaca | 12 | 3 | 1 | 7 | 5 | *Payload Drop* — deploy extra infantry |
| **Shield Bearer** 🛡️ | Alpaca | 14 | 2 | 1 | 3 | 7 | *Fortify* — +3 defense until moved |

---

## 🌳 Terrain Effects

| Terrain   | DEF Bonus | Move Cost | Notes |
|-----------|-----------|-----------|-------|
| Grass     | 0         | 1         | — |
| Forest    | +1        | 2         | Great for ambushes |
| Mountain  | +2        | 3         | Only certain units excel here |
| Water     | 0         | —         | Impassable for most |
| Village   | +1        | 1         | May be capturable in future updates |

---

## 🖥 UI Layout

- **Top Bar** – Faction info, turn count, active player.
- **Main Battlefield View** – Grid with units, terrain icons, and animations.
- **Side Panel** – Selected unit portrait, stats, and available actions.
- **Action Buttons** – Move | Attack | Special | Wait | End Turn.
- **Log Panel** – Running play‑by‑play commentary.

---

## 🚀 How to Play

1. **Select a unit** from your faction.
2. **Move** it across valid terrain within its movement range.
3. **Attack** enemies in range or use your **Special Ability**.
4. **Wait** to end the unit’s actions.
5. Use **End Turn** when all your moves are complete.

---

## 🏆 Victory Conditions

- Defeat all enemy units.
- Or achieve scenario‑specific objectives (future expansion).

---

## 📂 Project Structure

- **HTML/CSS** – UI layout, game board visuals, and styling.
- **JavaScript** – Game state, unit logic, movement/attack rules, and win checks.
- **Sprites/Icons** – Emoji placeholders for quick prototyping; replace with pixel art assets for production.

---

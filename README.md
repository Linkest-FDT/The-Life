# The Stone House | 石房子
A narrative 2D story game developed with Godot Engine.
Part of The Life Game Team, hosted under Linkest Foundation.

> This project is licensed under **GNU General Public License v3.0 (GPL-3.0)**.
> The story, original settings, character lore and OST are copyrighted by the original creator.
> Game source code is open under GPLv3. Derivative works based on original plot and assets follow CC BY-NC-SA 4.0.
> This project belongs to the Linkest-FDT team system; copyright is retained by the author and will not be transferred to the foundation.

## 📖 Project Introduction
*The Stone House* is a quiet, memory-focused 2D narrative exploration game.
The story revolves around an old stone house and a sealed teenage past. The tone is restrained, wistful, heavy yet gentle with a sense of fate.
There is no combat. The core experience lies in atmosphere, dialogue, scene exploration and fragmented storytelling.
The main menu OST draws inspiration from *Cage* by Beizhou and the main theme of *Adolescence in Stone*. It is spacious, reserved, sorrowful but not desperate.

## 🎮 Core Game Specs
- Genre: 2D Narrative Exploration / Story RPG
- Engine: Godot 4 (GDScript, no C# dependencies)
- View: Top-down pixel scenes
- Core gameplay: Slow exploration, memory fragment triggers, immersive atmosphere
- Art & Mood: Low-saturation pixel art, cold grey palette, heavy stone texture, soft dim lighting, minimal bright colours

## 📁 Repository Structure

res://
├─ assets/
│  ├─ tiles/        Tilemap assets
│  ├─ chars/        Character sprites & portraits
│  ├─ audio/
│  │   ├─ ost/      Original soundtrack (including main menu theme)
│  │   └─ sfx/      Ambient & interaction sound effects
│  └─ ui/           Menu, dialogue UI assets
├─ scenes/
│  ├─ main_menu.tscn  Main menu (first priority for development)
│  ├─ map/           Stone house and surrounding areas
│  └─ dialog/        Dialogue nodes & story scripts
├─ scripts/         Game logic scripts
└─ docs/
├─ GDD.md        Full Game Design Document
└─ LICENSE       GPLv3 license text


## 🧾 License & Fanwork Rules
1. Godot Engine: MIT License, fully compatible with GPLv3 of this project.
2. **Game source code**: GPL-3.0. Any modified redistribution must remain open-sourced.
3. **Original plot, characters, OST and art assets**: CC BY-NC-SA 4.0
   ✅ Allowed: Non-commercial fan creation, screenshots, story analysis, sharing
   ❌ Forbidden: Commercial use, paid derivatives, reselling, asset theft for commercial projects
4. This project is part of the Linkest Foundation ecosystem and follows the Foundation Community Code, security policy and contribution rules.
5. All contributors are required to sign the project CLA before submitting pull requests.

## 📌 Development Progress
- [ ] Main menu scene + looping main menu BGM
- [ ] Basic dialogue system
- [ ] Initial stone house map
- [ ] Item interaction & memory trigger logic
- [ ] Main story branch writing
- [ ] Build & release workflow

## 🤝 How to Contribute
1. Read the Linkest Foundation Community Code
2. Fork this repo, create feature branches and submit PRs
3. Keep commit messages clear and descriptive
4. Submit feedback, bugs and creative suggestions via GitHub Issues

## 📬 Contact
Linkest Foundation
hi@linkest.org

---
# GDD - The Stone House 石房子
Owner: The Life Game Team / Linkest Foundation

## 1. Core Theme
An enclosed stone house holding a heavy yet tender teenage memory.
Keywords: sealed, quiet, wistful, restrained, blank space, fatalism, sad without despair.
No jump scares or horror elements. The focus is emotional, subtle storytelling.

## 2. Game Type
2D Narrative Exploration
No combat, stats or grinding.
Game loop: wander → interact with objects → unlock memory fragments → piece together the timeline.

## 3. Audio & Visual Style
- Visual: Low-saturation pixel art, dim soft light, thick stone texture, restrained colour palette.
- Music:
  Main theme: Slow instrumental, violin lead, soft piano, subtle ambient noise, large reverb, no heavy drums.
  Reference: *Cage (Beizhou)*, *Adolescence in Stone*.
  Scene audio: Wind, faint stone creaks, quiet floor sounds; ambient sound takes priority over background music.
- UI: Minimalist dark translucent dialogue boxes, plain fonts, no flashy decorations.

## 4. Core Scene
The Stone House.
The core container of all memories. Multi-layered small stone building with thick walls, narrow windows and dusty old belongings.
Almost the whole game takes place inside the house and a tiny outdoor area at the gate.
Every interactable object links to one memory fragment.

## 5. Narrative Design
Fragmented, non-linear storytelling.
Memories are unlocked out of chronological order. Players assemble the full story themselves.
No mandatory guides or highlighted markers. Encourage slow exploration.
Key fragments unlock branching endings.

## 6. Characters
Small cast, restrained appearances. Every character is tied to the stone house and the past events.
Dialogue is implicit, reserved, avoids direct emotional outbursts.

## 7. Endings
Multiple subtle, open endings. No purely happy perfect ending.

## 8. Technical & Open-Source Constraints
- Engine: Godot 4, GDScript
- Code license: GPL-3.0
- Original creative assets: CC BY-NC 4.0
- Governed by Linkest Foundation rules, security disclosure policy and CLA
- Commercial use of original plot, art and soundtrack is prohibited

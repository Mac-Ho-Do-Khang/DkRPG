# DkRPG

![Action Phase 1](ActionPhase1.png){width=600 height=375} ![Action Phase 2](ActionPhase2.png){width=600 height=375}

[**Action RPG**](https://www.fab.com/listings/ef04a196-03c1-4204-998a-c7d5264fade7) is Epic's official Unreal 4 single-player, third-person action role-playing game template. **DkRPG** is my personal re-implementation of the project in Unreal 5, made during a hands-on learning exercise for [**Unreal Engine**](UE.md) and its [**Gameplay Ability System**](GAS.md). Game features include:

- **Enemy system**: normal vs boss enemies, each with unique behavior and attack patterns.
- **Combat mechanics**: target lock, dodge, roll, parry, and block.
- **Skill system**: ranged and melee, incorporating rage consumption and cooldown mechanics.
- **HUD elements**: stat bars, weapon slots, and skill slots.
- **UI screens**: main menu, pause menu, result menu, and loading screen.
- **Audio**: sound effects and background music.
- **Game loop**: survival mode with wave-based enemy spawning.

![Main Menu](MainMenu.png){width=300 height=188} ![Key Bindings](KeysBindingMenu.png){width=300 height=188} ![Pause Menu](PauseMenu.png){width=300 height=188} ![Game Over](GameOverMenu.png){width=300 height=188}

Main Tech Stack

- Unreal Engine 5.3+
- C++ and Blueprints Visual Scripting
- Gameplay Ability System (GAS)

### Demo

Here is a short 🎞️ [**walkthrough video**](https://drive.google.com/file/d/1mwrxOT0ZIanrlv1DxguIFR_l0cuuGSQs/view?usp=sharing) of the latest version.

### Documentation

Code only accounts for part of the total work in this project. The remaining effort was poured within the Unreal Engine editor, doing things such as:

- Asset Creation
- Blueprint Wiring
- Animation Blueprints
- Behavior Trees
- Data Assets
- Level Design
- and so on.

These non-code work is inherently embedded in the project's binary assets. The C++ source files are shared [**here**](../DkRPG/annotated.html) as a transparent record of my coding practice, trying my best to follow the conventions of the Unreal Engine codebase itself, including naming conventions, comment style, system design, etc.

By convention, Unreal Engine game projects typically use a project-specific prefix for their classes and structs to distinguish custom types from those provided by the engine itself. In this project, I use Dk, the initials of my name, as the prefix for all custom classes and structs.

### Releases

Available build, which links to a downloadable `.zip` file, can be accessed via my [**itch.io page**](https://mac-ho-do-khang.itch.io/dkrpg). Extracting the folder and you will find for yourself the following directory structure:

```
├── DkRPG
│   ├── Binaries
│   └── Content
├── DkRPG.exe
├── Engine
│   ├── Binaries
│   ├── Content
│   └── Extras
├── Manifest_DebugFiles_Win64.txt
├── Manifest_NonUFSFiles_Win64.txt
└── Manifest_UFSFiles_Win64.txt
```

Play the game simply by running `DkRPG.exe`.

### Assets

Below is a list of the assets used in this project, along with their sources and usage.

| Source | Description | Usage | Paid/Free |
|--------|-------------|-------|-----------|
| [Action RPG](https://www.fab.com/listings/ef04a196-03c1-4204-998a-c7d5264fade7) | Epic's RPG sample project | Player & enemy characters models with animations and sound; Background music and sound effects; UI textures for menus and HUD. | Free |
| [QMS - Fantasy Sword Pack FREE](https://www.fab.com/listings/30e5e745-d601-4d7b-b2da-56f977769638) | Fantasy sword models with textures. | Player's main weapon. | Free |
| [Easy Shockwaves VFX](https://www.fab.com/listings/7aa80a1a-eab6-4036-a1cc-ebbcb89fbac9) | Shockwave visual effects. | Visual effects for abilities and attacks. | Free |
| [Free Magic Niagara](https://www.fab.com/listings/d0fe50c4-6ebe-40d5-b78a-56960832f49e) | Magic VFX created with Niagara. | Visual effects for gameplay abilities. | Free |
| [SFX Essentials (Free Sample)](https://www.fab.com/listings/c1913024-9011-41c6-95e9-3273724c3bd0) | Sound effects for various actions and events. | Sound effects for some actions and UI interactions. | Free |
| [Essentials Icon Pack - PC](https://www.fab.com/listings/fd535442-bb64-4408-9294-d353e0889934) | A collection of icons for PC keyboards. | Keys menu display. | Free |
| [Elite Landscapes: Demonscape](https://www.fab.com/listings/d45e3868-d7e9-4a2a-a56f-e09d78fbca4f) | Demonic landscape environments. | Main game environments. | Paid |
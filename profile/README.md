# Gravewright

**Your world. Your players. Your next great session.**

[English](https://github.com/Gravewright/.github/blob/main/profile/README.md) · [Português (Brasil)](https://github.com/Gravewright/.github/blob/main/profile/README.pt-BR.md)

Gravewright is a universal virtual tabletop for RPG campaigns: free, open source
and hosted by you. Prepare maps, gather your group in the browser and keep tokens,
character sheets, dice and campaign notes together in a world you control.

**[Explore Gravewright](https://gravewright.com)** · [Download](https://github.com/Gravewright/gravewright/releases/latest) · [Getting started](https://github.com/Gravewright/gravewright/blob/main/docs/en/getting-started.md)

### A place for your campaign

- **Set the atmosphere.** Build scenes with lighting, fog, walls, audio and visual effects. Reveal the world at your pace.
- **Bring your characters.** Use PDF sheets or an independent game system, with characters connected to tokens on the board.
- **Keep the session moving.** Roll dice, share notes, draw cards and follow combat without leaving the table.
- **Carry the story forward.** Keep journals, quests, handouts and discoveries together between sessions.
- **Make the table yours.** Host your own installation and extend it with systems and modules from the Marketplace.

### Start your first table

Download the complete [0.3.0 project ZIP and checksum](https://github.com/Gravewright/gravewright/releases/tag/v0.3.0),
extract it into a writable folder and run the installer for your platform:

| Platform | Installer | Start the table |
| --- | --- | --- |
| [Windows 10 (1803+) / 11, x64](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/en/windows-runner.md) | `Install Windows.bat` | `Gravewright Runner.bat` |
| [Linux, x64 / ARM64](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/en/linux-runner.md) | `bash "./Install Linux.sh"` | `bash "./Gravewright Runner.sh"` |
| [macOS 13.5+, Intel / Apple Silicon](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/en/macos-runner.md) | `Install macOS.command` | `Gravewright Runner.command` |

The installer prepares tools, dependencies and settings and creates your Runner.
Open it, create your administrator account in the browser and start your campaign.
Missing tools and packages need an internet connection; see each platform's guide
for requirements. Configuration, campaign data and managed tools stay inside the
extracted installation by default.

The Runner starts locally on your computer. To invite players over your network
or the internet, follow the [hosting guide](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/en/deployment.md).
Your campaign data stays under your control.

### Available now: Gravewright 0.3.0 Alpha

Version **0.3.0 Alpha** brings map authoring, visual automation and map interchange
to the tabletop:

- **Map Builder.** Build with tiles or terrain painting, organize named layers, import your artwork and keep editable projects with automatic saving and recovery.
- **Smart Objects.** Connect doors, levers, torches and regions to visual behaviors using events, conditions and actions.
- **Map imports and exports.** Import a finished image as a Builder background, or import `.uvtt`, `.dd2vtt` and `.df2vtt` files as native scenes with supported walls, doors and lights. Export a compatible copy of the current native scene.
- **Prepare before sharing.** Generate a private scene and apply later project changes with **Update scene**. Activating it for players remains a separate action.

A finished image does not reconstruct its original layers; Universal VTT imports
create native scenes, not Builder projects. The VTT provides generic campaign
tools; installed systems continue to own their game-specific rules.

**[Download Gravewright 0.3.0 Alpha](https://github.com/Gravewright/gravewright/releases/tag/v0.3.0)** ·
[What's new](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/releases/0.3.0.md) ·
[Map Builder guide](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/en/map-builder.md) ·
[Universal VTT guide](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/en/universal-vtt.md)

Gravewright remains in active Alpha development. Version 0.3.0 adds database
migrations: back up existing campaigns and follow the
[upgrade instructions](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/releases/0.3.0.md#download-and-upgrade).
See the [user guide](https://github.com/Gravewright/gravewright/blob/v0.3.0/docs/en/user-guide.md)
for supported workflows.

### Choose how you play

Use maps, tokens, dice, journals and cards to run your campaign. With the included
**PDF System**, bring a familiar sheet, map its fields and connect the character
to a token. Dedicated sheets and rules automation come from independent systems;
their coverage depends on the system you install.

Choose systems and modules through the signed
[Marketplace](https://github.com/Gravewright/marketplace), or use the documented
APIs to create tools for your group.

**[Translator 0.1.2](https://github.com/Gravewright/marketplace/releases/tag/gravewright.translator-v0.1.2)**
lets each player choose English, Brazilian Portuguese or Spanish for the
supported interface. English is the default. Independent modules can use the
same official translation API; names and stories written by your group remain yours.

### Find your tools

| Project | What it brings to your table |
| --- | --- |
| [Gravewright VTT](https://github.com/Gravewright/gravewright) | The tabletop, installation guides and integration APIs. |
| [Marketplace](https://github.com/Gravewright/marketplace) | Signed releases of modules and systems. |
| [3D Dice](https://github.com/Gravewright/Gravewright-3D-Dice) | 3D dice for your rolls. |
| [Translator](https://github.com/Gravewright/translator) | Official interface localization and a shared translation API for independent modules. |
| [DnD 5e SRD](https://github.com/Gravewright/dnd-srd-5e) | One system package: [0.1.2](https://github.com/Gravewright/dnd-srd-5e/releases/tag/v0.1.2), with 2014/SRD 5.1 and 2024/SRD 5.2.1 rules, sheets, compendiums and combat automation. |
| [Savage Worlds Compatibility Package for Gravewright](https://github.com/Gravewright/Savage-Worlds-Compatibility-Package-for-Gravewright) | One system package with editable character and NPC sheets, 13 empty item templates and SWADE automation: [0.1.2](https://github.com/Gravewright/Savage-Worlds-Compatibility-Package-for-Gravewright/releases/tag/v0.1.2). |

The DnD example's partial SRD compendiums remain in English. Its **0.1.2** guide
documents installation on **VTT 0.2.3**: install the single system package from
**Systems** and select it for your table. Sheets, compendiums and automation stay
together; the GM advances combat from the table.
See its [installation guide and automation limits](https://github.com/Gravewright/dnd-srd-5e#readme).

The free Savage Worlds package includes no compendiums or rulebook text. Its
**0.1.2** guide documents installation on **VTT 0.2.3** through **Systems** and the
signed Marketplace. Select the complete system package for your table. Sheets,
item templates, assets and automation stay inside that system; the GM advances
combat from the table. Choose or create a native Action Deck in
**Extensions → Savage Worlds → Customize**, with three original deck styles
available. Its interface supports English, Brazilian
Portuguese and Spanish through the official Translator.
See the [SWADE installation guide](https://github.com/Gravewright/Savage-Worlds-Compatibility-Package-for-Gravewright#readme).

The system guides document their supported host versions; check them before upgrading a system or the VTT.

### Help shape the next session

Share feedback from your table, [report a problem](https://github.com/Gravewright/gravewright/issues)
or help improve translations, accessibility and documentation. Developers can
[build integrations](https://github.com/Gravewright/gravewright/blob/main/docs/en/api.md)
and [create modules](https://github.com/Gravewright/gravewright/blob/main/docs/en/modules.md).
See the [contribution guide](https://github.com/Gravewright/gravewright/blob/main/CONTRIBUTING.md)
and [security policy](https://github.com/Gravewright/gravewright/blob/main/SECURITY.md).

The core uses **GPL-3.0-only** with an
[Independent Module Permission](https://github.com/Gravewright/gravewright/blob/main/LICENSE-EXCEPTION).
Independently written modules may use any license, including proprietary licenses.
Copies and modifications of core implementation code remain subject to its license.
See the [licensing policy](https://github.com/Gravewright/gravewright/blob/main/LICENSING.md)
and [third-party notices](https://github.com/Gravewright/gravewright/blob/main/THIRD_PARTY_NOTICES.md).

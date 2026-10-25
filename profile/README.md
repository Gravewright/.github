# Gravewright

**Your world. Your players. Your next great session.**

[English](https://github.com/Gravewright/.github/blob/main/profile/README.md) · [Português (Brasil)](https://github.com/Gravewright/.github/blob/main/profile/README.pt-BR.md)

Gravewright is a universal virtual tabletop for RPG campaigns: free, open source
and hosted by you. Prepare maps, gather your group in the browser and keep tokens,
character sheets, dice and campaign notes together in a world you control.

**[Explore Gravewright](https://gravewright.com)** · [Download](https://github.com/Gravewright/gravewright/releases/latest) · [Getting started](https://github.com/Gravewright/gravewright/blob/main/docs/en/getting-started.md)

### A place for your campaign

- **Set the atmosphere.** Build maps and scenes with lighting, fog, walls, audio and visual effects. Add Smart Objects that respond to interaction or movement.
- **Bring your characters.** Use PDF sheets or an independent game system, with characters connected to tokens on the board.
- **Keep the session moving.** Roll dice, share notes, draw cards and follow combat without leaving the table.
- **Carry the story forward.** Prepare sessions outside the table with journals, quests, clocks, clues and mind maps. Keep journal history and campaign notes together.
- **Make the table yours.** Host your own installation and extend it with systems and modules from the Marketplace.

### Start your first table

Download the complete [0.3.3 project ZIP and checksum](https://github.com/Gravewright/gravewright/releases/tag/v0.3.3),
extract it into a writable folder and run the installer for your platform:

| Platform | Installer | Start the table |
| --- | --- | --- |
| [Windows 10 (1803+) / 11, x64](https://github.com/Gravewright/gravewright/blob/v0.3.3/docs/en/windows-runner.md) | `Install Windows.bat` | `Gravewright Runner.bat` |
| [Linux, x64 / ARM64](https://github.com/Gravewright/gravewright/blob/v0.3.3/docs/en/linux-runner.md) | `bash "./Install Linux.sh"` | `bash "./Gravewright Runner.sh"` |
| [macOS 13.5+, Intel / Apple Silicon](https://github.com/Gravewright/gravewright/blob/v0.3.3/docs/en/macos-runner.md) | `Install macOS.command` | `Gravewright Runner.command` |

The installer prepares tools, dependencies and settings and creates your Runner.
Open it, create your administrator account in the browser and start your campaign.
Missing tools and packages need an internet connection; see each platform's guide
for requirements. Configuration, campaign data and managed tools stay inside the
extracted installation by default.

The Runner starts locally on your computer. To invite players over your network
or the internet, follow the [hosting guide](https://github.com/Gravewright/gravewright/blob/v0.3.3/docs/en/deployment.md).
Your campaign data stays under your control.

### Available now: Gravewright 0.3.3 Alpha

Version **0.3.3 Alpha** adds scene audiences, clearer tokens and more tools to
create, automate and rehearse your maps:

- **Scenes for your group.** Create an empty map from a name, color, dimensions and grid choice. Activate a scene for everyone or selected players; identification dots show each player's destination.
- **Build faster.** Group objects into layers, align and distribute selections, save reusable campaign objects and paint repeated objects with a brush. Preview activation areas while editing.
- **Use your own Smart Objects.** Add behavior to uploaded artwork, define circular activation areas and connect events to lights and shader controls. Shader parameters accept fixed values or typed variable inputs.
- **Test before sharing.** Rehearse movement, vision, interactions and area events as a player in a detached map. Behavior tests roll back their changes and leave the live scene intact.
- **Clearer tokens.** Read sharper names and conditions, place bars above and below tokens, and choose bar colors, audiences, name display and turn indicators.
- **Personal controls.** Share mouse pointers in each participant's ping color, choose whether to show or share pointers, map keyboard shortcuts and add titles to local measurements.

Generate or update a private scene before sharing it. Import a finished image as
a background, or bring `.uvtt`, `.dd2vtt` and `.df2vtt` files into Builder as a
linked scene and editable project. Importing through the scene directory creates
a native scene that Builder can adopt. A finished image does not reconstruct its
original layers; Universal VTT conversion preserves the supported geometry and
lights, with format limits described in the guide.

**[Download Gravewright 0.3.3 Alpha](https://github.com/Gravewright/gravewright/releases/tag/v0.3.3)** ·
[What's new](https://github.com/Gravewright/gravewright/blob/v0.3.3/docs/releases/0.3.3.md) ·
[Map Builder guide](https://github.com/Gravewright/gravewright/blob/v0.3.3/docs/en/map-builder.md) ·
[Universal VTT guide](https://github.com/Gravewright/gravewright/blob/v0.3.3/docs/en/universal-vtt.md)

Gravewright remains in active Alpha development. Back up configuration, campaign
data and local extensions together before upgrading. See the
[upgrade instructions](https://github.com/Gravewright/gravewright/blob/v0.3.3/docs/releases/0.3.3.md#download-and-upgrade)
and the [user guide](https://github.com/Gravewright/gravewright/blob/v0.3.3/docs/en/user-guide.md)
for installation and supported workflows.

### Choose how you play

Use maps, tokens, dice, journals and cards to run your campaign. With the included
**PDF System**, bring a familiar sheet, map its fields and connect the character
to a token. Dedicated sheets and rules automation come from independent systems;
their coverage depends on the system you install.

Choose systems and modules through the signed
[Marketplace](https://github.com/Gravewright/marketplace), or use the documented
APIs to create tools for your group.

**[Translator 0.1.4](https://github.com/Gravewright/marketplace/releases/tag/gravewright.translator-v0.1.4)**
lets each player choose English, Brazilian Portuguese or Spanish for the
supported interface. English is the default. Independent modules can use the
same official translation API; names and stories written by your group remain yours.
This release includes translations for the new table and MapBuilder controls.

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

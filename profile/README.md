# Gravewright

**A self-hosted virtual tabletop for playing role-playing games in your browser.**

[English](https://github.com/Gravewright/.github/blob/main/profile/README.md) · [Português (Brasil)](https://github.com/Gravewright/.github/blob/main/profile/README.pt-BR.md)

Prepare your worlds, bring your players together and run your sessions with maps, PDF character sheets and realtime tabletop tools. Gravewright is open source, with an extensible core and documentation for both users and developers.

### Get started

**[Download Alpha 0.1.0](https://github.com/Gravewright/gravewright/releases/tag/v0.1.0-alpha.0)** · [Source code](https://github.com/Gravewright/gravewright) · [Documentation](https://github.com/Gravewright/gravewright/blob/main/docs/README.md)

On Windows, download the complete project ZIP from the release, extract it to a writable folder and double-click **`Gravewright Runner.bat`**. The Runner checks for uv, Python and Node.js/npm, installs missing tools and dependencies, builds the frontend and opens the application in your browser. A shortcut with the project icon is created beside the launcher when possible.

The Runner requires Windows 10 version 1803 or newer, or Windows 11, on x64. Downloads require internet access. Campaign data stays under `%LOCALAPPDATA%\Gravewright\data`, separately from the source files. This profile runs on the local computer; to host other players over a network, use the deployment guide.

### At the table

- **Campaigns and players:** accounts, invitations, access permissions and scene broadcasting.
- **Maps and scenes:** grids, tokens, walls, fog, lighting, measurement, drawings, pings and effects.
- **Characters:** actors, PDF sheets and field mapping through the native Gravewright PDF System.
- **Session tools:** realtime chat, dice, journals, quests, audio, cards, combat and compendiums.
- **Extensions:** module manifests, lifecycle hooks and documented Python, HTTP, WebSocket and browser interfaces.

Alpha 0.1.0 is the current release. The application UI currently supports English; project documentation is available in English and Brazilian Portuguese. Read the [user guide](https://github.com/Gravewright/gravewright/blob/main/docs/en/user-guide.md) for supported workflows and current limitations.

### Explore and contribute

| Resource | Start here |
| --- | --- |
| Installation and first login | [Getting started](https://github.com/Gravewright/gravewright/blob/main/docs/en/getting-started.md) |
| Windows launcher and backups | [Runner guide](https://github.com/Gravewright/gravewright/blob/main/docs/en/windows-runner.md) |
| Network hosting and HTTPS | [Deployment](https://github.com/Gravewright/gravewright/blob/main/docs/en/deployment.md) |
| Code structure | [Architecture](https://github.com/Gravewright/gravewright/blob/main/docs/en/architecture.md) and [code map](https://github.com/Gravewright/gravewright/blob/main/docs/en/code-map.md) |
| Integrations and extensions | [API guide](https://github.com/Gravewright/gravewright/blob/main/docs/en/api.md) and [module guide](https://github.com/Gravewright/gravewright/blob/main/docs/en/modules.md) |
| Bugs and feature proposals | [Issue tracker](https://github.com/Gravewright/gravewright/issues) |
| Code, documentation and translations | [Contributing](https://github.com/Gravewright/gravewright/blob/main/CONTRIBUTING.md) |
| Vulnerability reports | [Security policy](https://github.com/Gravewright/gravewright/blob/main/SECURITY.md) |

### Open source and independent modules

Gravewright core is licensed under **GPL-3.0-only**, with the [Independent Module Permission](https://github.com/Gravewright/gravewright/blob/main/LICENSE-EXCEPTION) under section 7. Independently written third-party modules may use **any license, including proprietary licenses**, whether or not they use the provided APIs. Copies and modifications of core implementation code remain subject to its license.

Dependencies, inherited assets and user content retain their own applicable terms. See the [licensing policy](https://github.com/Gravewright/gravewright/blob/main/LICENSING.md) and [third-party notices](https://github.com/Gravewright/gravewright/blob/main/THIRD_PARTY_NOTICES.md).

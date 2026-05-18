# Contributing to og-packs

## New Pack Submissions

**This repository is closed to new pack additions.** The packs here are the official "OG" collection that ships with peon-ping and is maintained by the core team. We are not accepting new packs into this repo.

### Want to create a sound pack?

Create your own! Community packs are first-class citizens in the peon-ping ecosystem:

1. **Create a new repo** with an `openpeon.json` manifest and a `sounds/` directory
2. **Follow the CESP spec** at [openpeon.com/create](https://openpeon.com/create)
3. **Submit to the registry** by opening a PR on [PeonPing/registry](https://github.com/PeonPing/registry) to add your pack to `index.json`

**Want an agent to do all of this for you?** Paste [AUTHOR.md](https://github.com/PeonPing/openpeon/blob/main/AUTHOR.md) into Claude Code / Codex / Cursor / opencode and it'll walk you through install → plan → scaffold → validate → publish → register, end to end.

Community packs are installable by anyone via `peon --pack <name>` — there is no functional difference between an OG pack and a community pack.

## Bug Fixes & Improvements to Existing Packs

PRs that fix bugs, improve audio quality, or update manifests for **existing** packs in this repo are welcome. Examples:

- Fixing a broken `openpeon.json` manifest
- Replacing a corrupted audio file
- Adding missing CESP event mappings to an existing pack
- Fixing metadata (author, description, license)

## Questions?

Open an issue or check [openpeon.com](https://openpeon.com).

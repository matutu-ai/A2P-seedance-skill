# A2P Seedance · 八大玩法

This public repository contains only the files required to run `lingguo-seedance-master`:

- `lingguo-seedance-master/SKILL.md` — the official entry point
- `lingguo-seedance-master/references/` — workflow and prompt references
- `lingguo-seedance-master/scripts/package_assets.py` — numbered asset packager

The example cases and media are kept outside this repository.

## Use

Install the complete `lingguo-seedance-master` directory in an agent environment that supports Skills, then invoke `$lingguo-seedance-master` with your product information, source assets, target platform, duration, aspect ratio, and constraints. The Skill first proposes a creative plan; after the plan is selected, it prepares numbered assets, a storyboard, and copy-ready Seedance prompts. Actual video generation follows only when requested and when a compatible platform is available.

Start with [SKILL.md](lingguo-seedance-master/SKILL.md). Keep `references/` and `scripts/` alongside it so its relative links and packaging workflow work.

No license has been declared for this repository. Public visibility alone does not grant permission to reuse or redistribute its contents beyond applicable law.

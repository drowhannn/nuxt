---
title: "nuxi upgrade"
description: The upgrade command upgrades Nuxt to the latest version.
links:
  - label: Source
    icon: i-simple-icons-github
    to: https://github.com/nuxt/cli/blob/main/src/commands/upgrade.ts
    size: xs
---

```bash [Terminal]
npx nuxi upgrade [--force|-f]
```

The `upgrade` command upgrades Nuxt to the latest version.

Option        | Default          | Description
-------------------------|-----------------|------------------
`--force, -f` | `false` | Removes `node_modules` and lock files before upgrade.
`--channel, -ch` | `"stable"` | Specify a channel to install from ("nightly" or "stable")

# Supaterm EMILIO — personal fork

> [!WARNING]
> This is a personal, unofficial fork maintained only for Emilio Moreno's own use.
> It is not the original Supaterm project, is not affiliated with or supported by
> the Supaterm authors, and comes with no support or compatibility guarantees.

The original project is [supabitapp/supaterm](https://github.com/supabitapp/supaterm).
Use the upstream project for official releases, documentation, issues, and support.

This fork contains a small set of personal macOS terminal behavior and appearance
changes. Ghostty submodule modifications are stored as versioned patches under
[`patches/emilio`](./patches/emilio/README.md); generated applications and local
configuration are intentionally not committed.

## Branches

- `upstream-sync`: unmodified Supaterm baseline used by this fork.
- `bugfixes`: objective fixes that can be used without personal preferences.
- `features`: `bugfixes` plus optional terminal behavior improvements; it points
  to the matching `features` branch of `EmilioMoreno/ghostty`.
- `emilio`: complete personal build, including branding and visual preferences.
- `main`: currently follows `emilio` for Emilio's own builds.

Commit prefixes make the intent explicit: `fix:` for bug fixes, `feat:` for new
behavior, `style:` for visual preferences, and `personal:` for Emilio-specific
packaging or identity.

## Original project

Supaterm is a terminal for coding agents.

![](https://supaterm.com/og.png)

## Development

- [Development](./docs/development.md)
- [Chrome styling](./docs/theming.md)
- [Coding agents integration](./docs/coding-agents-integration.md)
- [Socket control](./docs/how-socket-works.md)

## Thank you

- [Tuist](https://tuist.dev/) for sponsoring our Remote Cache.
- [Depot](https://depot.dev?utm_source=Supaterm) for providing build instances for our Docker image builds.

[![Built with Depot](https://depot.dev/badges/built-with-depot.svg)](https://depot.dev?utm_source=Supaterm)

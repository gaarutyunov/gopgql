# Vendored: @gaarutyunov/ui-kit

This directory is a vendored copy of the `src/` of
[gaarutyunov/ui-kit](https://github.com/gaarutyunov/ui-kit) — a
zero-dependency, buildless Web Components UI kit (MIT).

It is vendored (rather than installed from npm) because the package is
published to GitHub Packages, which requires authentication even for public
packages; vendoring keeps the docs build fully offline and reproducible in CI.

- Upstream version: 0.1.0
- Upstream commit: `76c389067d8300f360b0be6f2eed0fd44d00b311`

The docs playground imports components from `src/index.js` and the theme from
`src/tokens/tokens.css`. See LICENSE for the upstream MIT license.

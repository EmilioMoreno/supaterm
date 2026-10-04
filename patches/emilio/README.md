# Emilio patch series

These patches document the personal changes used by the Supaterm EMILIO builds.
They are provided for reproducibility only and are not an official Supaterm or
Ghostty distribution.

Apply the releases in order. Patches that modify Ghostty are applied from inside
the `apps/mac/ThirdParty/ghostty` submodule, as noted by each release README.

Current series:

- `1.0.0`: pane focus/click behavior, alternate-screen scrollback, and divider visibility.
- `1.0.1`: About identifier and additional alternate-scroll handling.
- `1.0.2`: unmistakable personal-build identity, removal of the official update-feed URL, and local scrollback priority over application mouse reporting.

The repository deliberately excludes compiled `.app`/`.zip` files, personal
Ghostty configuration, caches, signing material, and machine or VM data.

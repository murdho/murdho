# Cache-busting SVGs in README

The README references `terminal-dark.svg` and `terminal-light.svg` with `?v=<unix-timestamp>` query strings for cache-busting (GitHub's camo proxy caches images aggressively). When updating either SVG, replace the `v` value in `README.md` with the current unix timestamp (`date +%s`) for both references.

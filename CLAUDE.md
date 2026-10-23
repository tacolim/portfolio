# Portfolio

## Site Stack
- Portfolio and blog are static sites. The blog uses Jekyll.
- Icons come from Font Awesome. Check the loaded Font Awesome version before using any icon. If an icon needs a newer version, say so before using it, or offer to upgrade the CDN link.
- Use Font Awesome icons rather than Unicode symbols (arrows, etc.) for UI glyphs.

## Git workflow
- No issues for portfolio work. Name branches for the change (`chronicle-feed`), and PRs have no `Closes #N`.
- `master` still only changes through a PR.
- No check command (static site). Open `index.html` locally to eyeball changes.

## Infrastructure
- Blog is served from a custom subdomain (DNS already configured). Keep the RSS discovery `<link>` in the blog head.

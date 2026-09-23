# charatalk-site

Static support pages for **CharaTalk**, the on-device talking-avatar app for
macOS, iPadOS and iOS ([GrassRootAI/CharaTalk](https://github.com/GrassRootAI/CharaTalk)).
Served via GitHub Pages; these URLs are referenced from the app's App Store
listing (Mac, iPad and iPhone share one record).

## Structure

| Path | Page |
| --- | --- |
| `index.html` | Landing: links + contact |
| `support/` | Support & FAQ (the App Store "Support URL") |
| `privacy/` | Privacy policy (the App Store "Privacy Policy URL") |
| `content-policy/` | Content policy (public long form of the in-app consent gate) |
| `style.css` | Shared minimal styling (light/dark via `prefers-color-scheme`) |

Live at `https://grassrootai.github.io/charatalk-site/` (the org is `GrassRootAI`, so the
Pages host has no hyphen — `grassroot-ai.github.io` is a 404). When the
`grassroot-ai.com` custom domain is configured for the org's GitHub Pages,
these pages become reachable under it without content changes.

## Editing

Plain HTML, no build step. The canonical copy source is
`CharaTalk/Store/site/*.md` in the app repo — edit there first, mirror here.
Contact address used across pages: `charatalk-support@grassroot-ai.com`.

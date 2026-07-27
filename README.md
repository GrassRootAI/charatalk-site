# charatalk-site

Static support pages for **CharaTalk**, the on-device talking-avatar app for
macOS ([GrassRootAI/CharaTalk](https://github.com/GrassRootAI/CharaTalk)).
Served via GitHub Pages; these URLs are referenced from the app's Mac App Store
listing.

## Structure

| Path | Page |
| --- | --- |
| `index.html` | Landing: links + contact |
| `support/` | Support & FAQ (the App Store "Support URL") |
| `privacy/` | Privacy policy (the App Store "Privacy Policy URL") |
| `content-policy/` | Content policy (public long form of the in-app consent gate) |
| `style.css` | Shared minimal styling (light/dark via `prefers-color-scheme`) |

Live at `https://grassroot-ai.github.io/charatalk-site/`. When the
`grassroot-ai.com` custom domain is configured for the org's GitHub Pages,
these pages become reachable under it without content changes.

## Editing

Plain HTML, no build step. The canonical copy source is
`CharaTalk/Store/site/*.md` in the app repo — edit there first, mirror here.
Contact address used across pages: `charatalk-support@grassroot-ai.com`.

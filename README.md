# Docsify Test Blog

Minimal **Docsify** site used as the verification target for
**siyuan-plugin-publisher**'s GitHub → Docsify publisher.

## How it works

Docsify renders Markdown in the browser; there is no build step.
Publishing means committing a  file to this repo.

## Structure

| Path | Purpose |
|---|---|
| `index.html` | docsify entry (config lives here) |
| `_sidebar.md` | sidebar |
| `*.md` | pages created by the publisher |

## Preview

```bash
npx serve .
# or: python3 -m http.server 3000
```

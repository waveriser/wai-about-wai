[![Netlify Status](https://api.netlify.com/api/v1/badges/7594e39d-39ba-4589-b534-faf166e8527d/deploy-status)](https://app.netlify.com/sites/wai-about-wai/deploys)

## In context:

The wai-website repository imports this reposity as a git submodule, pages and content-images are symlinked so that 0
 can take them up.

```
╔═════════════════════════╗                      ┌─────────────────────────┐
║                         ║                      │                         │
║                         ║    git submodule     │                         │
║       wai-website       ║◀━━━━━━━━━━━━━━━━━━━━━│      wai-about-wai      │
║          ┌──────────────╢                      ├──────────────┐          │
║          │content-images║ ─  ─  symlink  ─  ─ ▶│content-images│          │
╚══════════╧══════════════╝                      └──────────────┴──────────┘
```
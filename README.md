# carlot78.github.io

Root of the `carlot78.github.io` domain. It exists mainly to serve
[`/.well-known/assetlinks.json`](.well-known/assetlinks.json), which proves to
Android that the **Aphorisms** Play Store app (`io.github.carlot78.aphorisms`)
belongs to https://carlot78.github.io/aphorisms/ — so the app opens full-screen
without a browser bar (Trusted Web Activity).

- `.nojekyll` — required, otherwise GitHub Pages skips the `.well-known` folder.
- `index.html` — sends the domain root to the app.

Project sites (`/aphorisms`, `/star-navigator`, …) live in their own repositories
and are unaffected.

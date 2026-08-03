# Sidekick Studios

The public site for [Sidekick Studios](https://github.com/kevmoore391) — company
pages, and the Privacy and Terms pages the App Store requires for each app.

```
/                  Sidekick Studios
/imaji/            Imaji
/imaji/privacy.html
/imaji/terms.html
```

Static HTML, no build step. Served by GitHub Pages from the `main` branch.

## Adding an app

Copy `imaji/` to a new folder, edit the three pages, and add a card to the
company home page.

## Editing Imaji's privacy policy

Imaji's privacy page is **generated** from `docs/legal/privacy-policy.md` in the
app repo, which is where the substance lives alongside the code it describes.
Edit it there and regenerate, so the published policy and the working document
cannot say different things.

# Kanda Apps

The public site for [Kanda Apps](https://github.com/kevmoore391) — company
pages, and the Privacy and Terms pages the App Store requires for each app.

```
/                  Kanda Apps
/imaji/            Imaji
/imaji/privacy.html
/imaji/terms.html
```

Static HTML, no build step. Served by GitHub Pages from the `main` branch.

## Adding an app

Copy `imaji/` to a new folder, edit the three pages, and add a card to the
company home page.

## Editing Imaji's privacy policy

Edit `imaji/privacy.html` directly — it is the published policy. (It was once
generated from `docs/legal/privacy-policy.md` in the app repo; that draft has been
superseded since the September 2026 rewrite and is not kept in sync.) Every
statement in it is a commitment about how the app behaves, so change the page in
the same breath as any app change that touches data.

# coffro-site

Public files for Coffro, the Android app for receipts and guarantees, served by GitHub Pages at https://riperfish.github.io/coffro-site/.

- `rules/kb.json` and `rules/kb.json.sig`: the legal rules Coffro uses to work out guarantee dates, with their Ed25519 signature. The app checks for a newer version once a week and uses it only if the signature matches the key built into the app. Both files are written by `tool/sign_rules.dart` in Coffro's source: don't edit them by hand.

Nothing here is legal advice.

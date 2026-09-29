# abccbaandy.github.io

GitHub Pages user site. Its only job is to serve Digital Asset Links at the domain root:

- `/.well-known/assetlinks.json` links the web app (https://abccbaandy.github.io/PttChrome/) with the
  PttChrome Android app (`io.github.abccbaandy.pttchrome`), so Google Password Manager shares the saved
  PTT credential between Chrome and the app.
- `.nojekyll` is required, otherwise Jekyll skips the `.well-known` directory.

See `docs/android-app.md` in https://github.com/abccbaandy/PttChrome .

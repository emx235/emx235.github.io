# emx235.github.io

Rădăcina domeniului `emx235.github.io`. Există doar pentru fișierele pe care
Android (și, mai târziu, iOS) le caută la rădăcină:

- `.well-known/assetlinks.json` — leagă linkurile
  `https://emx235.github.io/beauty-docs/s/?id=…` de aplicația
  `ro.emericmark.beauty` (App Links).
- `.nojekyll` — fără el, GitHub Pages ignoră folderele care încep cu punct.

Sursa fișierului e în proiectul aplicației, `docs/pagini/.well-known/`; acolo
se modifică și apoi se copiază aici. După publicarea în Google Play se adaugă
și amprenta din Play Console (Integritatea aplicației → Semnarea aplicației).

Documentele publice sunt în `emx235/beauty-docs`.

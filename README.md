# leibgericht-website

Website und Datenschutzerklärung für die App **Leibgericht – Kochbuch & Plan**.
Reines HTML/CSS ohne Build-Schritt, Schriften lokal eingebunden (keine Anfragen an Dritte).

## Veröffentlichen (GitHub Pages)

Repository → Settings → Pages → Source: „Deploy from a branch“, Branch `main`, Ordner `/ (root)`.
Danach erreichbar unter `https://linalarsson42.github.io/leibgericht-website/`,
die Datenschutzerklärung unter `…/datenschutz.html` (so ist sie auch in der App verlinkt).

## Vor der Veröffentlichung im Play Store

- [ ] Screenshot-Platzhalter ersetzen: Bilder nach `assets/img/screenshots/` legen und die
      `<div class="screen placeholder">` in `index.html` durch `<img src="…" alt="…">` ersetzen
      (Kommentare an den Stellen zeigen, wo).
- [x] In `datenschutz.html` Namen und Kontaktadresse ergänzen, Entwurfshinweis entfernen.
- [ ] Datenschutzerklärung rechtlich prüfen (lassen).
- [ ] Impressum klären (für eine kostenlose Hobby-App ohne Einnahmen vermutlich nicht nötig,
      aber nicht eindeutig) und ggf. ergänzen.
- [ ] „Bald bei Google Play“ durch den Store-Link ersetzen.

## Lizenzen

Schriften: Fraunces und Inter, SIL Open Font License 1.1.

# Mediennutzung reflektieren und Medienerziehung (DR-Lernpfad SPA, K7)

Querschnitts-Lernpfad für die SPA am BBZ Rendsburg-Eckernförde – gebaut mit dem Lernpfad-Baukasten.

- **Web-Version:** https://dclausen01.github.io/dr-spa-mediennutzung/
- **Moodle-Kurs (Moodle 5):** `moodle/dr-spa-mediennutzung_moodle5.mbz` (nach Freigabe) · Klickanleitung `moodle/ANLEITUNG_moodle5.md`
- **Quelle:** `kurs.yaml`, `module/`, `seiten/`, `quellen.yaml` – nur hier ändern.
- **Erzeugt:** `docs/` (GitHub Pages) und `moodle/` – nicht von Hand ändern, sondern neu bauen:

```
python3 <baukasten>/skripte/alles.py dr-spa-mediennutzung
rm -rf docs && cp -r ausgabe/web docs && touch docs/.nojekyll
cp ausgabe/moodle/*.mbz ausgabe/moodle/ANLEITUNG_moodle5.md moodle/
```

# Videografen Tirol – eigenständige Anbieterübersicht

Fertige statische Website mit HTML, CSS und JavaScript, ohne Build-Prozess. Kein Bestandteil von flywithfloekki.at.

## Lokal ansehen
`index.html` im Browser öffnen. Für eine lokale Entwicklungsumgebung optional `python -m http.server 8000` im Ordner starten und `http://localhost:8000` öffnen.

## Kostenlos mit GitHub Pages veröffentlichen
1. Auf GitHub ein **neues öffentliches Repository** anlegen, z. B. `videografen-tirol`.
2. **Alle Dateien und den Ordner `assets`** aus diesem Paket ins Stammverzeichnis des Repositorys hochladen (nicht bloß die ZIP-Datei).
3. Repository → **Settings → Pages** → unter **Build and deployment** `Deploy from a branch`, Branch `main`, Ordner `/(root)` → **Save**.
4. Die Adresse lautet dann üblicherweise `https://DEIN-GITHUB-NAME.github.io/videografen-tirol/`. Eine kostenpflichtige Domain ist nicht erforderlich.

## Vor der Veröffentlichung: unbedingt erledigen
- [ ] `impressum.html`: vollständige rechtliche Angaben einschließlich Anschrift eintragen und rechtlich prüfen.
- [ ] `datenschutz.html`: an tatsächlich verwendetes Hosting anpassen und rechtlich prüfen.
- [x] Externe Google Fonts entfernt; die Website nutzt Systemschriftarten.
- [ ] Die Anbieterprofile, Referenzen und die behauptete Projektzahl auf Richtigkeit/Aktualität prüfen.
- [ ] Bei eigenen Fotos und Filmstills nur Material mit entsprechenden Rechten einfügen.
- [ ] Wenn die endgültige URL feststeht: kanonische URLs, `og:url` und Sitemap passend zur tatsächlichen Adresse ergänzen und Suchmaschinen-Verifizierung vornehmen.
- [ ] Bei Änderungen an Drittanbieterprofilen transparent über die im Impressum genannte Kontaktadresse erreichbar sein.

## Redaktionelle Grundsätze
Die Reihenfolge ist **keine objektive Rangliste**. Der Betreiber ist selbst der vorgestellte Anbieter Flywithfloekki. Das wird direkt oberhalb der Übersicht, im FAQ, im Footer und Impressum offengelegt. Es werden keine erfundenen Kundenbewertungen oder Rankings eingesetzt.

## Quellen zum redaktionellen Gegencheck (Stand 05.11.2026)
- Flywithfloekki: https://flywithfloekki.at/
- PROVISUALS: https://www.provisuals.at/
- TIROL FILM: https://www.tirolfilm.eu/
- EUTOPIAFILM: https://www.eutopia.film/
- GitHub Pages Dokumentation: https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages

## Inhalt
- `index.html`: Website inklusive SEO-Metadaten und strukturierter ItemList-Daten
- `styles.css`: responsives Layout
- `script.js`: Filter und mobiles Menü
- `impressum.html`, `datenschutz.html`: **noch zu prüfende** Entwürfe
- `assets/favicon.svg`: eigenes Icon

Hinweis: Eine prominente Profilplatzierung allein garantiert keine bessere Platzierung in Google oder KI-Systemen.
# Cihan Mildner – Webvisitenkarte

Statische Seite für GitHub Pages. Hosting kostet nichts, nur die Domain.

## Hochladen

1. Auf GitHub ein kostenloses Konto anlegen.
2. Neues **öffentliches** Repository erstellen, zum Beispiel `cihan-mildner`.
3. Alle Dateien aus diesem Ordner in das Repository legen: `index.html`, `impressum.html`, `datenschutz.html`, Ordner `images`. Nicht diesen README vergessen ist egal, er stört nicht.
4. Im Repository: **Settings → Pages → Branch: main, Folder: / (root) → Save**.
5. Nach ein bis zwei Minuten ist die Seite unter `https://DEINNAME.github.io/cihan-mildner/` erreichbar.

## Eigene Domain

1. Domain kaufen, zum Beispiel `cihanmildner.de`.
2. Unter **Settings → Pages → Custom domain** die Domain eintragen. GitHub legt dann eine Datei `CNAME` an.
3. Beim Domain-Anbieter diese DNS-Einträge setzen:

   Für die nackte Domain (`cihanmildner.de`), vier A-Records auf `@`:

   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153

   Für `www` ein CNAME auf `DEINNAME.github.io`.

4. Wenn das Zertifikat da ist, **Enforce HTTPS** einschalten.

## Vor dem Veröffentlichen

In `impressum.html` die Platzhalter `[Straße und Hausnummer]` und `[PLZ und Ort]` durch die ladungsfähige Anschrift ersetzen.

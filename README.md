# Mau Tai - Asiatisches Restaurant Website

Eine rechtssichere, responsive Website für das asiatische Restaurant Mau Tai in Sassenberg.

## Enthaltene Features

- ✅ **Startseite** mit Hero-Bereich und Restaurant-Informationen
- ✅ **Speisekarte** mit PDF-Download-Link (Google Drive)
- ✅ **Öffnungszeiten** (inklusive Feiertage)
- ✅ **Impressum** gemäß § 5 TMG (mit Platzhaltern für fehlende Informationen)
- ✅ **Datenschutzerklärung** DSGVO-konform
- ✅ **Responsive Design** für Desktop, Tablet und Mobile
- ✅ **Moderne Navigation** mit Hamburger-Menü für Mobile
- ✅ **Smooth Scrolling** zwischen Abschnitten

## Dateien

- `index.html` - Haupt-HTML-Datei mit allen Inhalten
- `styles.css` - CSS-Styling mit responsive Design

## Rechtliche Hinweise

### Noch zu ergänzende Informationen

Im Impressum und in der Datenschutzerklärung müssen folgende Platzhalter ersetzt werden:

**Impressum:**
- [E-Mail-Adresse eintragen] - E-Mail-Adresse des Restaurants
- [USt-IdNr. eintragen] - Umsatzsteuer-Identifikationsnummer
- [Name des Verantwortlichen eintragen] - Name für § 55 Abs. 2 RStV
- [Adresse des Verantwortlichen eintragen] - Adresse für § 55 Abs. 2 RStV

**Datenschutz:**
- [E-Mail-Adresse eintragen] - E-Mail-Adresse für Datenschutzanfragen

### Wichtige rechtliche Informationen

1. **Impressum**: Erfüllt die Anforderungen nach § 5 TMG für deutsche Websites
2. **Datenschutzerklärung**: DSGVO-konform mit allen erforderlichen Abschnitten
3. **SSL/TLS**: Für den Betrieb der Website sollte HTTPS aktiviert werden
4. **Cookies**: Aktuell werden keine Cookies verwendet (optional kann Google Fonts eingebunden werden)

## Anpassungsmöglichkeiten

### Farben
Die Farben können in der `styles.css` unter `:root` angepasst werden:
- `--primary-color`: Hauptfarbe (aktuell: #c41e3a - Dunkelrot)
- `--secondary-color`: Sekundärfarbe (aktuell: #1a1a1a - Dunkelgrau)
- `--accent-color`: Akzentfarbe (aktuell: #f4a460 - Gold)

### Speisekarte
Der Download-Link für die Speisekarte ist aktuell auf Google Drive eingerichtet. Um die PDF-Datei direkt auf dem Server zu hosten:
1. Speisekarte-PDF im gleichen Ordner wie `index.html` speichern
2. Link in `index.html` anpassen:
   ```html
   <a href="speisekarte.pdf" download class="download-button">
   ```

## Starten der Website

Die Website kann einfach durch Öffnen der `index.html` im Browser gestartet werden.

Für einen produktiven Einsatz:
1. Hosting-Provider wählen (z.B. Netlify, GitHub Pages, klassischer Webhoster)
2. Dateien hochladen
3. Domain registrieren und verbinden
4. SSL-Zertifikat aktivieren (HTTPS)

## Kontaktinformationen der Website

Restaurant Mau Tai
Lappenbrink 53
48336 Sassenberg
Telefon: 02583 7531916

## Support

Bei Fragen zur Website oder Anpassungen wenden Sie sich bitte an den Entwickler.
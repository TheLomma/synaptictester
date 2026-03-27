[README.md](https://github.com/user-attachments/files/26301513/README.md)
# SynaTest – Icon-Paket

## Dateistruktur für GitHub / Webserver

```
dein-repo/
├── index.html          ← Hauptdatei (Canvas-Export)
├── site.webmanifest    ← Web App Manifest
├── icons/
│   ├── favicon.ico
│   ├── icon-16x16.png
│   ├── icon-32x32.png
│   ├── icon-48x48.png
│   ├── icon-57x57.png
│   ├── icon-60x60.png
│   ├── icon-72x72.png
│   ├── icon-76x76.png
│   ├── icon-96x96.png
│   ├── icon-114x114.png
│   ├── icon-120x120.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-167x167.png
│   ├── icon-180x180.png
│   ├── icon-192x192.png
│   └── icon-512x512.png
```

## Anleitung

### 1. GitHub Pages einrichten
1. Neues Repository erstellen (z.B. `synatest`)
2. Alle Dateien hochladen (index.html, site.webmanifest, icons/)
3. Settings → Pages → Branch: main → Save
4. URL: `https://DEINNAME.github.io/synatest/`

### 2. index.html anpassen
Den Inhalt von `HEAD_SNIPPET.html` in den `<head>` deiner index.html einfügen.
Die alten `<link rel="apple-touch-icon" href="data:image/...">` Zeilen entfernen!

### 3. iPhone Homescreen
1. URL in Safari öffnen
2. Teilen-Symbol (□↑) antippen
3. "Zum Home-Bildschirm" wählen
4. → SynaTest-Icon erscheint!

## Icon-Größen Übersicht
| Größe    | Verwendung                        |
|----------|-----------------------------------|
| 16x16    | Browser-Tab (Favicon)             |
| 32x32    | Browser-Tab (Retina)              |
| 57x57    | iPhone (alt)                      |
| 60x60    | iPhone                            |
| 72x72    | iPad                              |
| 76x76    | iPad                              |
| 96x96    | Android                           |
| 114x114  | iPhone Retina (alt)               |
| 120x120  | iPhone Retina                     |
| 144x144  | iPad Retina (alt)                 |
| 152x152  | iPad Retina                       |
| 167x167  | iPad Pro                          |
| 180x180  | iPhone Plus / Pro Max             |
| 192x192  | Android / PWA                     |
| 512x512  | PWA Splash Screen                 |

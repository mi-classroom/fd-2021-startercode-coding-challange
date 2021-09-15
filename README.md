# Startercode // Frontend Development Prüfung

Das Projekt verwendet den Static Page Generator [11ty](https://www.11ty.dev/docs/). Als Template Sprache wird [Nunjucks](https://www.11ty.dev/docs/languages/nunjucks/) eingesetzt.


## Ordnerstruktur

### `/_stuff`

Material zum Verarbeiten und Erklären … Layouts, PDF, usw.

### `/docs`

kompilierter Code … hier wird nix gemacht

### `/src`

hier wird entwickelt

```
_components         Layout- oder Funktionsschnipsel
_data               Zusätzliche Daten oder Hilfsfunktionen
_layouts            Templates
assets              SCSS, Skripts, Fonts, etc … alles was kein Content ist
compiled-assets     Kompilierte Dateien, z.B. CSS
chapters            Content
images              Bilder, die zum Content gehören
index.md            Startseite
```

### Weitere Dateien

```
.eleventy.js        Config von 11ty
.eleventyignore     Welche Folder/ Files soll 11ty ignorieren?
.gitignore          Welche Folder/ Files soll git igorieren?
```

## Funktionen

`npm install`
Installiert die erforderlichen Abhängigkeiten.

`npm run build` 
kompiliert einen Build und speichert diesen im `docs` Folder.

`npm run dev` 
Watchmode für den SASS Compiler und Browsersync, der die Inhalte inkl. livereload serviert.

`npm run live` erzeugt einen Build und startet den Webserver, der die Inhalte serviert.




# guaita.MDeditor 2.0

A Word-style Markdown editor in a single HTML file. Part of the **Guaita Apps** suite.

**Live page:** https://subi2.github.io/guaitaMDeditor/
**Download:** [`guaitaMDeditor_v2.0.html`](guaitaMDeditor_v2.0.html) — no installation, works offline.

> The application interface is currently in Catalan only. This README and the project pages are available in English and Catalan.

## Features

- **Visual (WYSIWYG) editing** of Markdown: type in a formatted A4 page; the Markdown is generated automatically and kept in sync with a code pane.
- **Dual view**: formatted document, Markdown source, or both side by side, with a draggable divider and zoom from 50 % to 200 %.
- **Word-style ribbon and drop-down menus**: File, Edit, View, Insert, Format, Paragraph, Table, Tools and Help.
- **Outline and paragraphs panel**: collapsible heading tree, move or promote/demote whole sections, and a list of all blocks.
- **Editable tables** with a context menu (insert/delete rows and columns, column alignment) and Tab navigation.
- **Smart paste**: pasting rich HTML converts it to Markdown; pasting tab-separated data opens the importer.
- **Delimited-data importer** (inspired by Ron's Data Edit): auto-detected delimiter, custom delimiters, quote qualifier, skip/trim/deduplicate options, sorting (numeric-aware) and transposition.
- **Markdown extensions**: `==highlight==` and footnotes (`[^1]`). The first time they are used, a notice explains they are an extension; the notice can be turned off.
- **Exports**: `.md`, `.html`, LaTeX (`.tex`, including `\hl` and `\footnote`) and plain text `.txt`. Print to PDF from the browser.
- **Own undo/redo stack** (500 steps) shared by the formatted and the code view.
- **Find and replace**, focus mode, full-screen mode, word/line/character counter, local image embedding.
- **Themes**: dark (Caixetí, default) and light.
- **Autosave** of the session in the browser and file open/save through the browser's file system access where available.

## Requirements

A modern browser (Chrome, Edge, Firefox or Safari). File System Access (open and save over the original file) is available in Chromium-based browsers; other browsers fall back to standard download and upload.

## Usage

Open `guaitaMDeditor_v2.0.html` in your browser. Everything is included in the file: no server, no CDN, no network connection needed.

## Development

The project is intentionally simple:

- One HTML file, vanilla JavaScript, CSS in the same file.
- Third-party libraries (marked, Turndown and its GFM plugin) are embedded and documented in [THIRD_PARTY.md](THIRD_PARTY.md).
- Changes are recorded in [CHANGELOG.md](CHANGELOG.md).

## Licence

Copyright (C) 2026 SBS BiM Consulting, Jordi Subirós.

Licensed under the **GNU Affero General Public License v3.0 only** (`AGPL-3.0-only`). See [LICENSE](LICENSE). This program comes with no warranty.

---

# guaita.MDeditor 2.0 (Català)

Editor de text Markdown estil Word en un únic fitxer HTML. Part de la suite **Guaita Apps**.

**Pàgina:** https://subi2.github.io/guaitaMDeditor/
**Descàrrega:** [`guaitaMDeditor_v2.0.html`](guaitaMDeditor_v2.0.html) — sense instal·lació, funciona sense connexió.

## Funcions

- Edició visual (WYSIWYG) de Markdown: escriviu en un full A4 formatat; el Markdown es genera automàticament i es manté sincronitzat amb el panell de codi.
- Doble vista: document formatat, codi Markdown o les dues alhora, amb divisor arrossegable i zoom del 50 % al 200 %.
- Cinta i menús desplegables estil Word: Fitxer, Edita, Visualitza, Insereix, Format, Paràgraf, Taula, Eines i Ajuda.
- Panell d'esquema i paràgrafs: arbre de títols plegable, moure o canviar el nivell de seccions senceres i llista de tots els blocs.
- Taules editables amb menú contextual (inserir i eliminar files i columnes, alineació) i navegació amb Tab.
- Enganxament intel·ligent: l'HTML enriquit es converteix a Markdown; les dades separades per tabuladors obren l'importador.
- Importador de dades delimitades (inspirat en Ron's Data Edit): detecció automàtica del delimitador, delimitadors personalitzats, qualificador de cometes, opcions d'omissió, neteja, eliminació de duplicats, ordenació i transposició.
- Extensions de Markdown: `==ressaltat==` i notes al peu (`[^1]`). La primera vegada que s'usen apareix un avís que indica que són una extensió; es pot desactivar.
- Exportacions: `.md`, `.html`, LaTeX (`.tex`, amb `\hl` i `\footnote`) i text pla `.txt`. Impressió a PDF des del navegador.
- Desfer i refer propi (500 passos) compartit per la vista formatada i la de codi.
- Cerca i substitució, mode focus, pantalla completa, comptador de paraules, línies i caràcters, i incrustació d'imatges locals.
- Temes: fosc (Caixetí, per defecte) i clar.
- Autodesat de la sessió al navegador i obertura i desat de fitxers amb l'API del sistema de fitxers del navegador quan està disponible.

## Requisits

Un navegador modern (Chrome, Edge, Firefox o Safari). L'API d'accés al sistema de fitxers (obrir i desar sobre el fitxer original) està disponible als navegadors basats en Chromium; la resta usa descàrrega i pujada estàndard.

## Ús

Obriu `guaitaMDeditor_v2.0.html` al navegador. Tot és dins del fitxer: no cal servidor, CDN ni connexió.

## Desenvolupament

- Un únic fitxer HTML, JavaScript pur i CSS al mateix fitxer.
- Les biblioteques de tercers (marked, Turndown i el seu connector GFM) hi són incrustades i documentades a [THIRD_PARTY.md](THIRD_PARTY.md).
- Els canvis es registren a [CHANGELOG.md](CHANGELOG.md).

## Llicència

Copyright (C) 2026 SBS BiM Consulting, Jordi Subirós.

Llicenciat sota la **GNU Affero General Public License v3.0 only** (`AGPL-3.0-only`). Vegeu [LICENSE](LICENSE). Aquest programa no té cap garantia.

---

© 2026 SBS BIM · Guaita Apps

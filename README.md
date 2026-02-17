# IKEA SKÅDIS Planer & 3D-Druck Konfigurator

Ein präzises, webbasiertes Tool zur Planung von IKEA SKÅDIS Lochwänden. Speziell entwickelt für **3D-Druck-Enthusiasten** und Maker, die exakte Maße, Sperrzonen für Schrauben und benutzerdefinierte Teile benötigen.

![Status](https://img.shields.io/badge/Status-Stable-green) ![Version](https://img.shields.io/badge/Version-33-blue) ![Tech](https://img.shields.io/badge/Tech-HTML%20%7C%20JS%20%7C%20SVG-orange)

## 🌟 Warum dieser Planer?

Im Gegensatz zu vereinfachten Tools simuliert dieser Planer die **physikalische Realität** der SKÅDIS-Platten mathematisch exakt.

* **Korrekte Geometrie:** Berücksichtigt das versetzte Lochmuster (*Staggered Grid*) mit exakt **27 vertikalen Reihen** (statt oft fälschlich angenommenen 14) und einem 2cm-Raster.
* **Symmetrie:** Exakte Berechnung der Ränder (2 cm oben/unten), sodass keine Löcher abgeschnitten werden.
* **Sperrzonen:** Zeigt automatisch rote Warnmarkierungen (🔴) an den Positionen der Befestigungsschrauben an, damit du dort kein Zubehör planst.
* **3D-Druck Friendly:** Erlaube das Hinzufügen von "Custom Parts" mit eigenen Maßen, Farben und Preisen.

## ✨ Features

### 📐 Präzision & Simulation
* **Realistisches Lochraster:** Simulation des 2-cm-Rasters inklusive des Ziegelstein-Versatzes (8 vs. 9 Löcher pro Reihe).
* **Montagepunkte:** Visuelle Indikatoren für die Schraubköpfe in der 1. und 27. Reihe.
* **Hilfsraster:** Einblendbares 2cm-Gitter zur Orientierung.

### 🎨 Gestaltung & Zubehör
* **Original IKEA-Maße:** Alle Standardgrößen (36x56, 56x56, 76x56) verfügbar.
* **Farbvarianten:** Wählbar zwischen Weiß, Holz (Nachbildung) und Schwarz (mit angepasstem Loch-Kontrast).
* **Vollständige Bibliothek:** Alle gängigen IKEA-Haken, Halter, Behälter, Ablagen, Gummibänder und Briefhalter.
* **Manuelles Zubehör:** Erstelle eigene Platzhalter für 3D-Druck-Teile (Definiere Breite, Höhe, Farbe und Preis).
* **Smart Contrast:** Automatische Anpassung der Textfarbe (Schwarz/Weiß) basierend auf der Helligkeit des Teils.

### 🖱️ Usability (UX)
* **Zoom & Pan:** Stufenloser Zoom per Mausrad und Verschieben der Wand per Drag-and-Drop auf dem Hintergrund.
* **Tastatursteuerung:** Bewege Teile pixelgenau mit den Pfeiltasten.
* **Editieren:** Doppelklick auf ein Teil öffnet das Bearbeiten-Fenster.

### 💾 Speichern & Export
* **Projekt speichern:** Exportiere dein Layout als `.json` Datei und lade es später wieder.
* **Druck-Export:** Generiert eine **hochwertige SVG-Vektorgrafik** für den Ausdruck, inklusive einer detaillierten Einkaufsliste und Kostenschätzung. Funktioniert zuverlässig in jedem Browser.

---

## 🚀 Installation & Start

Da der Planer als **Single-File-Application** geschrieben ist, ist keine Installation notwendig.

1.  Lade die Datei `skadis_planer.html` herunter.
2.  Öffne sie in einem modernen Browser (Chrome, Edge, Firefox, Safari).
3.  Leg los!

---

## 📖 Bedienungsanleitung

### 1. Wand einrichten
Gib oben links die Maße deiner verfügbaren Wandfläche in cm ein (z.B. 100 x 150). Der Arbeitsbereich passt sich automatisch an.

### 2. Platten platzieren
Wähle unter **"2. Basis"** die Größe und Farbe der Lochplatte und klicke auf `Platte erzeugen`. Ziehe die Platte an die gewünschte Position auf der Wand.

### 3. Zubehör hinzufügen
* **IKEA Teile:** Wähle aus der Liste unter **"3. Zubehör"** das gewünschte Teil und klicke auf `Hinzufügen` (oder ziehe es in den Bereich).
* **Custom Parts:** Wähle im Dropdown `-- Manuelles Teil --`. Gib Namen, Maße (B/H in cm), Farbe und Preis ein. Klicke auf `Teil erzeugen`.

### 4. Teile bearbeiten & bewegen
* **Verschieben:** Drag & Drop mit der Maus.
* **Feinjustierung:** Teil anklicken (roter Rahmen) und mit den **Pfeiltasten** bewegen. (Shift + Pfeil = 4cm Schritte).
* **Editieren:** **Doppelklick** auf ein Zubehörteil öffnet ein Fenster, um Namen oder Farbe nachträglich zu ändern.
* **Löschen:** Ziehe das Teil auf den Mülleimer 🗑️ oder drücke die `Entf`/`Backspace`-Taste.

### 5. Ansicht steuern
* **Zoom:** Nutze das Mausrad oder die `+` / `-` Buttons oben rechts.
* **Verschieben (Pan):** Klicke und halte auf den *leeren Hintergrund* und ziehe die Maus.
* **Reset:** Klicke auf den `⟲` Button oben rechts, um die Ansicht zurückzusetzen.

### 6. Exportieren
* **Speichern:** Klicke auf `💾 Speichern`, um den aktuellen Stand als JSON zu sichern.
* **Drucken:** Klicke auf `🖨️ Drucken / PDF`. Es öffnet sich ein neues Fenster mit der Bauzeichnung und der Einkaufsliste. Nutze die Druckfunktion des Browsers ("Als PDF speichern"), um es weiterzugeben.

---

## 🛠️ Technische Details

* **Technologie:** Vanilla HTML5, CSS3, JavaScript (ES6).
* **Keine Abhängigkeiten:** Keine externen Libraries, kein Framework, läuft komplett offline.
* **Rendering:** Nutzt DOM-Elemente für die Interaktion und generiert SVGs on-the-fly für den Druck-Export.

## 📄 Lizenz

Dieses Projekt steht zur freien Verfügung. Feel free to fork and improve! Use at own risk!

# IKEA SKÅDIS Planer & 3D-Druck Konfigurator

Ein präzises, webbasiertes Tool zur Planung von IKEA SKÅDIS Lochwänden. Speziell entwickelt für **3D-Druck-Enthusiasten** und Maker, die exakte Maße, Sperrzonen für Schrauben und benutzerdefinierte Teile benötigen.

### 🔗 [Hier geht's direkt zum Tool](https://mrwkhan.github.io/skadis-simulator/skadis.html)

![Status](https://img.shields.io/badge/Status-Stable-green) ![Version](https://img.shields.io/badge/Version-3.3-blue) ![Tech](https://img.shields.io/badge/Tech-HTML%20%7C%20JS%20%7C%20SVG-orange)

---

## 🌟 Warum dieser Planer?

Im Gegensatz zu vereinfachten Tools simuliert dieser Planer die **physikalische Realität** der SKÅDIS-Platten mathematisch exakt.

* **Korrekte Geometrie:** Berücksichtigt das versetzte Lochmuster (*Staggered Grid*) und die exakten Ränder, sodass Planung und Realität übereinstimmen.
* **Sperrzonen:** Zeigt automatisch rote Warnmarkierungen (🔴) an den Positionen der Befestigungsschrauben an, damit du dort kein Zubehör planst.
* **3D-Druck Friendly:** Erlaube das Hinzufügen von "Custom Parts" mit eigenen Maßen, Farben und Preisen.

## ✨ Features

### 📐 Präzision & Simulation
* **Realistisches Lochraster:** Exakte Simulation des Rasterversatzes.
* **Montagepunkte:** Visuelle Indikatoren für die Schraubköpfe der Wandmontage.
* **Hilfsraster:** Einblendbares 2cm-Gitter zur Orientierung.

### 🎨 Gestaltung & Zubehör
* **Original IKEA-Maße:** Alle Standardgrößen (36x56, 56x56, 76x56) verfügbar.
* **Farbvarianten:** Wählbar zwischen Weiß, Holz (Nachbildung) und Schwarz (mit angepasstem Kontrast).
* **Vollständige Bibliothek:** Alle gängigen IKEA-Haken, Halter, Behälter, Ablagen und Gummibänder.
* **Manuelles Zubehör:** Erstelle eigene Platzhalter für 3D-Druck-Teile (Definiere Breite, Höhe, Farbe und Preis).

### 🖱️ Usability (UX)
* **Zoom & Pan:** Stufenloser Zoom und Verschieben der Arbeitsfläche.
* **Feinjustierung:** Pixelgenaues Positionieren mit den Pfeiltasten.
* **Editieren:** Doppelklick auf ein Teil öffnet das Bearbeiten-Fenster.

### 💾 Speichern & Export
* **Projekt speichern:** Exportiere dein Layout als `.json` Datei.
* **Druck-Export:** Generiert eine **hochwertige SVG-Vektorgrafik** für den Ausdruck oder als Bauplan, inklusive einer detaillierten Einkaufsliste und Kostenschätzung.

---

## 🚀 Starten

Das Tool läuft direkt im Browser. Es ist keine Installation notwendig.

1.  Öffne den **[Link zum Planer](https://mrwkhan.github.io/skadis-simulator/skadis.html)**.
2.  Leg los!

*Optional: Da es sich um eine Single-File-Application handelt, kannst du die HTML-Datei auch speichern und komplett offline nutzen.*

---

## 📖 Bedienungsanleitung

### 1. Wand einrichten
Gib oben links die Maße deiner verfügbaren Wandfläche in cm ein (z.B. 100 x 150). Der Arbeitsbereich passt sich automatisch an.

### 2. Platten platzieren
Wähle unter **"2. Basis"** die Größe und Farbe der Lochplatte und klicke auf `Platte erzeugen`. Ziehe die Platte an die gewünschte Position auf der Wand.

### 3. Zubehör hinzufügen
* **IKEA Teile:** Wähle aus der Liste unter **"3. Zubehör"** das gewünschte Teil und klicke auf `Hinzufügen`.
* **Custom Parts:** Wähle im Dropdown `-- Manuelles Teil --`. Gib Namen, Maße (B/H in cm), Farbe und Preis ein und klicke auf `Teil erzeugen`.

### 4. Teile bearbeiten & bewegen
* **Verschieben:** Drag & Drop mit der Maus.
* **Feinjustierung:** Teil anklicken (roter Rahmen) und mit den **Pfeiltasten** bewegen (Shift + Pfeil = 4cm Schritte).
* **Editieren:** **Doppelklick** auf ein Zubehörteil öffnet ein Fenster, um Namen oder Farbe nachträglich zu ändern.
* **Löschen:** Ziehe das Teil auf den Mülleimer 🗑️ oder drücke die `Entf`-Taste.

### 5. Ansicht steuern
* **Zoom:** Nutze das Mausrad oder die Lupe-Icons.
* **Verschieben (Pan):** Klicke und halte auf den *leeren Hintergrund* und ziehe die Maus.
* **Reset:** Klicke auf den `⟲` Button, um die Ansicht zurückzusetzen.

### 6. Exportieren
* **Speichern:** Klicke auf `💾 Speichern`, um den aktuellen Stand als JSON zu sichern.
* **Drucken:** Klicke auf `🖨️ Drucken / PDF`. Es öffnet sich ein neues Fenster mit der Bauzeichnung und der Einkaufsliste (nutze "Als PDF speichern" im Browser).

---

## 🛠️ Technische Details

* **Technologie:** Vanilla HTML5, CSS3, JavaScript (ES6).
* **Keine Abhängigkeiten:** Keine externen Libraries, kein Framework.
* **Rendering:** DOM-Elemente für Interaktion, SVG on-the-fly für Export.

## 📄 Lizenz

Dieses Projekt steht zur freien Verfügung. Feel free to fork and improve! Use at own risk!

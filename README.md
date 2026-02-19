# IKEA SKÅDIS Planer & 3D-Druck Konfigurator

🇩🇪 [Deutsche Version](#-deutsche-version) | 🇬🇧 [English Version](#-english-version)

Ein präzises, webbasiertes Tool zur Planung von IKEA SKÅDIS Lochwänden. Speziell entwickelt für **3D-Druck-Enthusiasten** und Maker, die exakte Maße, Sperrzonen für Schrauben und benutzerdefinierte Teile benötigen.

### 🔗 [Hier geht's direkt zum Tool](https://mrwkhan.github.io/skadis-simulator/skadis.html)

![Status](https://img.shields.io/badge/Status-Stable-green) ![Version](https://img.shields.io/badge/Version-10.1-blue) ![Tech](https://img.shields.io/badge/Tech-Vanilla%20JS%20%7C%20CSS3%20%7C%20HTML5-orange)

---

<a name="-deutsche-version"></a>
## 🇩🇪 Deutsche Version

### 🌟 Warum dieser Planer?

Im Gegensatz zu vereinfachten Tools simuliert dieser Planer die **physikalische Realität** der SKÅDIS-Platten mathematisch exakt.

* **Korrekte Geometrie:** Berücksichtigt das versetzte Lochmuster (*Staggered Grid*) und die exakten Ränder, sodass Planung und Realität übereinstimmen.
* **Sperrzonen:** Zeigt automatisch rote Warnmarkierungen (🔴) an den Positionen der Befestigungsschrauben an, damit du dort kein Zubehör planst.
* **3D-Druck Friendly:** Erlaube das Hinzufügen von "Custom Parts" mit eigenen Maßen, Farben und Preisen.

### ✨ Neue Features in v10.1
* **Multilingual:** Vollständige Unterstützung für Deutsch 🇩🇪 und Englisch 🇬🇧.
* **Globale Einstellungen (⚙️):** Passe die Standardmaße und Preise aller Zubehörteile individuell an deine Bedürfnisse an.
* **Touch-Support:** Volle Unterstützung für Smartphones und Tablets (Pinch-to-Zoom, Drag & Drop per Touch).
* **Kostenkontrolle:** Echtzeit-Berechnung der Gesamtkosten für dein Projekt.

### 📐 Präzision & Gestaltung
* **Original IKEA-Maße:** Alle Standardgrößen (36x56, 56x56, 76x56) und Farbvarianten (Weiß, Holz, Schwarz) verfügbar.
* **Vollständige Bibliothek:** Haken, Halter, Behälter, Ablagen und Gummibänder.
* **Speichern & Export:** Projekt als `.json` speichern, laden oder als Bauplan inkl. Einkaufsliste direkt ausdrucken / als PDF speichern.

### 📖 Bedienungsanleitung
1. **Wand einrichten:** Gib die Maße deiner verfügbaren Wandfläche ein.
2. **Platte platzieren:** Wähle Größe und Farbe und klicke auf `Platte auf Wand werfen`.
3. **Zubehör hinzufügen:** Wähle IKEA-Teile oder erstelle manuelles Zubehör (Definiere B/H, Farbe und Preis).
4. **Steuerung:** * Bewegen per *Drag & Drop*.
   * Feinjustierung mit den **Pfeiltasten** (Shift + Pfeil = 4cm Schritte).
   * **Doppelklick** auf ein Teil öffnet das Bearbeiten-Fenster.
   * Zum Löschen das Teil auf den Mülleimer 🗑️ ziehen.
   * **Zoom & Pan:** Mausrad nutzen oder auf den Hintergrund klicken und ziehen.

---

<a name="-english-version"></a>
## 🇬🇧 English Version

### 🌟 Why this planner?

Unlike simplified tools, this planner simulates the **physical reality** of SKÅDIS boards with mathematical precision.

* **Correct Geometry:** Accounts for the staggered hole pattern and exact margins, ensuring your digital plan matches reality.
* **Keep-out Zones:** Automatically displays red warning markers (🔴) at the positions of the mounting screws to prevent hardware collisions.
* **3D-Print Friendly:** Add custom parts with your own dimensions, colors, and material costs.

### ✨ New Features in v10.1
* **Multilingual:** Full support for English 🇬🇧 and German 🇩🇪.
* **Global Settings (⚙️):** Customize the default dimensions and prices of all accessories to fit your specific 3D-printing or local store costs.
* **Touch Support:** Fully optimized for smartphones and tablets (Pinch-to-zoom, touch drag & drop).
* **Cost Tracking:** Real-time calculation of your total project cost.

### 📐 Precision & Design
* **Original IKEA Sizes:** All standard sizes (36x56, 56x56, 76x56) and colors (White, Wood, Black) are available.
* **Extensive Library:** Hooks, holders, containers, shelves, and more.
* **Save & Export:** Save your project as a `.json` file, load previous states, or print a blueprint/PDF including a complete shopping list.

### 📖 How to use
1. **Setup Wall:** Enter the dimensions of your available wall space.
2. **Place Board:** Choose size and color, then click `Throw board on wall`.
3. **Add Accessories:** Select IKEA parts or create a custom part (define W/H, color, and price).
4. **Controls:** * Move items via *Drag & Drop*.
   * Fine-tune positioning using **Arrow Keys** (Shift + Arrow = 4cm steps).
   * **Double-click** an item to edit its name or color.
   * Drag an item to the trash bin 🗑️ to delete it.
   * **Zoom & Pan:** Use the mouse wheel, or click and drag the empty background.

---

## 🛠️ Technical Details / Technik

* **Technology:** Vanilla HTML5, CSS3, JavaScript (ES6).
* **Zero Dependencies:** No external libraries, no frameworks. Keep it lightweight and fast!
* **Offline Ready:** Because it's a Single-File-Application, you can just save the `.html` file and use it completely offline.

## 📄 License

This project is open-source. Feel free to fork and improve! Use at your own risk!

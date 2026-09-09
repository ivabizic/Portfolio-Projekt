# 🎨 Interactive Particle Portrait Component

Eine interaktive HTML5-Canvas-Komponente für mein zukünftiges digitales Portfolio, inspiriert von modernen Entwickler-Portfolios. Das Tool wandelt hochgeladene Bilder clientseitig in ein Partikel-System um, das dynamisch auf Maus- und Touch-Interaktionen reagiert.

## ✨ Features

- **Clientseitiges Bild-Sampling:** Wandelt hochgeladene Fotos direkt im Browser in Farbpunkte (Partikel) um – ohne Server-Upload.
- **Interaktive Physik:** Partikel weichen dem Mauszeiger/Touch-Input aus und bewegen sich durch eine Feder-Physik (*Spring Dynamics*) an ihre ursprüngliche Position zurück.
- **Echtzeit-Anpassung:** Live-Regler für Partikeldichte (*Density*) und Transparenz (*Opacity*).
- **Export-Optionen:**
  - Download des generierten Partikel-Portraits als transparente `.png`-Datei.
  - Generierung und Export eines eigenständigen, einbettbaren HTML-Embed-Codes (Data-URL gebundelt).
- **Dark / Light Theme:** Integrierter Farbschema-Wechsler.

## 🛠️ Tech Stack & Konzepte

- **Frontend:** HTML5, CSS3 (Custom Properties, CSS Keyframe Animations)
- **Graphics & Animation:** HTML5 Canvas API, `requestAnimationFrame`
- **Physik-Algorithmen:** Vector Physics (Repulsion, Friction & Spring Mechanics)
- **AI-Assisted Development:** Generiert und optimiert in Zusammenarbeit mit Claude AI

## 💡 Hintergrund & Motivation
Ziel dieses Projekts war es, eine visuell ansprechende, interaktive UI-Komponente für mein persönliches Portfolio zu entwickeln. Ich liebe interaktive Elemente bei Websites und wollte dann, wenn ich fertig mit meinem Portfolio bin und genügend Projekte gesammelt habe, ihm dann einen gewissen Charme verleihen.

## Screenshots
<img width="400" alt="Screenshot 2026-09-09 at 23 52 04" src="https://github.com/user-attachments/assets/7e9c473b-e581-4ef3-93d3-abcfa967b2dc" />
<img width="400" alt="Screenshot 2026-09-09 at 23 51 06" src="https://github.com/user-attachments/assets/ff67a488-90c7-46fa-b27e-61050f10e5cb" />
<img width="400" alt="Screenshot 2026-09-09 at 23 50 52" src="https://github.com/user-attachments/assets/abee5126-249f-4f58-9bb9-3422574c89f7" />


## 🚀 Schnellstart

Da die gesamte Anwendung standalone im Browser läuft, wird kein Build-Step oder Node.js benötigt:

1. Repository klonen:
   ```bash
   git clone [https://github.com/ivabizic/Portfolio-Projekt.git](https://github.com/ivabizic/Portfolio-Projekt.git)

## Autor
Iva Bizic

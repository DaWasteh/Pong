# Pong Game

Ein klassisches Pong-Spiel, komplett in einer einzigen HTML-Datei implementiert. Kein Server, keine Abhängigkeiten, kein Build-Prozess – einfach im Browser öffnen und spielen.

## Spiel starten

Einfach `index.html` im Browser öffnen. Fertig.

## Features

- **vs CPU**: Spiele gegen die KI
- **2 Spieler**: Lokal gegen einen Freund am selben Gerät
- Canvas-basiertes Rendering mit 60 FPS
- Neon-Glow-Design mit Partikel-Effekten
- Ball wird bei jedem Treffer schneller (max Speed 12)
- Erster Spieler mit 5 Punkten gewinnt

## Steuerung

| Spieler 1 (links) | Spieler 2 (rechts, nur 2P-Modus) |
|-------------------|----------------------------------|
| Maus bewegen | Pfeiltasten ↑ ↓ |
| Touch bewegen | Touch rechte Canvas-Hälfte |

## Technische Details

- **Single-File**: Alle Logik, Rendering und UI in einer HTML-Datei
- **Vanilla JavaScript**: Keine Frameworks, keine Abhängigkeiten
- **HTML5 Canvas**: Direktes 2D-Rendering mit `requestAnimationFrame`
- **Responsive**: Funktioniert auf Desktop und Mobile

## Datei

- [`index.html`](index.html) – Das komplette Spiel (~400 Zeilen)

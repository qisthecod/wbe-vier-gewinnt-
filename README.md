# Vier Gewinnt - Miniprojekt

## Team
- wagnekil, staeumic

## Funktionsübersicht
Dieses Projekt implementiert das klassische Spiel "Vier Gewinnt" als Webanwendung unter Verwendung von React und der SJDON-Bibliothek.

### Features
- **Spielmechanik**: Zwei Spieler (Rot und Gelb) lassen abwechselnd Spielsteine in ein 7x6 Gitter fallen.
- **Gewinnerkennung**: Das Spiel erkennt automatisch, wenn ein Spieler 4 Steine horizontal, vertikal oder diagonal verbunden hat.
- **Persistierung**: Der Spielzustand wird im `localStorage` des Browsers gespeichert, sodass das Spiel nach einem Neuladen der Seite fortgesetzt werden kann.
- **Undo-Funktion**: Züge können beliebig oft rückgängig gemacht werden.
- **Reset**: Das Spiel kann jederzeit neu gestartet werden.

## Implementierungsdetails
- **Technologien**: HTML, CSS, JavaScript, React, SJDON.
- **State Management**: Verwendung von `useState` und `useEffect` Hooks für die Verwaltung des Spielzustands und der Persistierung.
- **UI**: Responsive Design mit CSS Grid und Flexbox.

## Screenshots
*(Fügen Sie hier Screenshots ein, wenn gewünscht)*

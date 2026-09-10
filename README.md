# Septemberlicht – GitHub Pages

## Dateistruktur

Lege diese beiden Dateien im selben Repository ab:

```text
Septemberlicht/
├── index.html
└── song.mp3
```

Der Dateiname der MP3 muss genau `song.mp3` sein, solange du im HTML nichts änderst.

## GitHub Pages aktivieren

GitHub Repository:
**Settings → Pages**

Dann:

```text
Source: Deploy from a branch
Branch: main
Folder: / (root)
```

Speichern.

Danach entsteht eine öffentliche Adresse:

```text
https://DEINUSERNAME.github.io/Septemberlicht/
```

## Musik

Die `index.html` lädt:

```text
song.mp3
```

direkt aus demselben Ordner.

## Synchronisation

Im HTML findest du:

```js
const LYRICS = [
  { time: 5, text: "Zusammen auf dem Dach, spätes Septemberlicht" },
  ...
];
```

Die `time`-Werte sind Sekunden.

Beispiel:

```js
{ time: 12.5, text: "Zwei Jahre an deiner Seite, mehr brauche ich nicht" }
```

Damit startet diese Zeile bei 12,5 Sekunden.

## Wichtig

Die ersten Zeitpunkte stammen aus der bisherigen Version. Die neu ergänzten Werte sind vorläufige Näherungen. Für wirklich exakte Synchronisation sollten die Zeiten anhand der fertigen MP3 feinjustiert werden.

## Keine Custom Domain nötig

Du kannst die kostenlose `github.io`-Adresse direkt verwenden.

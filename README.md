# Werkstatt-Status

Öffentliche Status-Datei für den Hinweis auf der Webseite. Sie wird vom Bot geschrieben.

```json
{ "hinweis": { "von": "2026-11-22", "bis": "2026-11-28", "text": "Die offene Werkstatt fällt am Sa, 28.11. aus." } }
```

- `von`: erster Tag, an dem der Hinweis angezeigt wird
- `bis`: letzter Tag, an dem der Hinweis angezeigt wird
- `text`: angezeigter Text, höchstens 160 Zeichen

Kein Hinweis:

```json
{ "hinweis": null }
```

Notfall: Falls der Bot nicht erreichbar ist, kann die Datei hier direkt bearbeitet werden. Keine Namen oder privaten Daten eintragen, die Änderungshistorie ist öffentlich.

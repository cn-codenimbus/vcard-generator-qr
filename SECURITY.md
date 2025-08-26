# Sicherheitsrichtlinie

## Unterstützte Versionen

Verwenden Sie diese Tabelle, um zu verstehen, welche Versionen von vCard Generator + QR noch Sicherheitsupdates erhalten:

| Version | Unterstützt          |
| ------- | -------------------- |
| 1.0.x   | :white_check_mark:   |
| < 1.0   | :x:                  |

## Sicherheitslücken melden

Wir nehmen die Sicherheit von vCard Generator + QR sehr ernst. Wenn Sie eine Sicherheitslücke gefunden haben, melden Sie diese bitte an uns, anstatt ein öffentliches Issue zu erstellen.

### Wie Sie eine Sicherheitslücke melden können:

1. **E-Mail**: Senden Sie eine E-Mail an [security@codenimbus.de](mailto:security@codenimbus.de)
2. **Private Issue**: Erstellen Sie ein privates Issue mit dem Label "security"
3. **GPG-Verschlüsselung**: Für besonders sensible Informationen verwenden Sie GPG-Verschlüsselung

### Was Sie in Ihrer Meldung angeben sollten:

- **Beschreibung**: Detaillierte Beschreibung der Sicherheitslücke
- **Schritte zur Reproduktion**: Wie die Lücke reproduziert werden kann
- **Auswirkung**: Welche Auswirkungen die Lücke haben könnte
- **Vorschläge**: Mögliche Lösungsansätze (falls vorhanden)
- **Kontakt**: Ihre Kontaktdaten für Rückfragen

### Was Sie erwarten können:

- **Bestätigung**: Wir bestätigen den Erhalt Ihrer Meldung innerhalb von 48 Stunden
- **Untersuchung**: Wir untersuchen die gemeldete Lücke gründlich
- **Update**: Wir veröffentlichen ein Update, sobald die Lücke behoben ist
- **Anerkennung**: Wir würdigen Ihren Beitrag in unseren Release Notes (falls gewünscht)

## Best Practices für Entwickler

### Für Mitwirkende:

- **Code-Review**: Alle Pull Requests werden auf Sicherheitsprobleme überprüft
- **Dependencies**: Regelmäßige Updates der Abhängigkeiten
- **Input Validation**: Alle Benutzereingaben werden validiert
- **HTTPS**: Verwendung von HTTPS für alle externen Ressourcen

### Für Benutzer:

- **Aktualisierungen**: Halten Sie Ihre lokale Kopie aktuell
- **HTTPS**: Verwenden Sie HTTPS beim Zugriff auf die Anwendung
- **Browser-Updates**: Halten Sie Ihren Browser aktuell
- **Offline-Nutzung**: Für maximale Sicherheit verwenden Sie die lokale Version

## Bekannte Sicherheitsaspekte

### Datenschutz:

- **Lokale Verarbeitung**: Alle Daten werden lokal im Browser verarbeitet
- **Keine Server-Kommunikation**: Keine Daten werden an externe Server gesendet
- **QR-Library**: Die QR-Library wird von vertrauenswürdigen CDNs geladen

### Empfohlene Konfiguration:

- **Content Security Policy**: Implementierung einer CSP für zusätzliche Sicherheit
- **HTTPS**: Verwendung von HTTPS im Produktionsumfeld
- **Regelmäßige Updates**: Regelmäßige Updates der QR-Library

## Sicherheits-Updates

Sicherheitsupdates werden als Patch-Versionen (z.B. 1.0.1, 1.0.2) veröffentlicht und sollten so schnell wie möglich installiert werden.

## Kontakt

Bei Fragen zur Sicherheit kontaktieren Sie uns unter:
- **E-Mail**: [security@codenimbus.de](mailto:security@codenimbus.de)
- **PGP-Key**: [Unser öffentlicher PGP-Schlüssel](https://codenimbus.de/pgp-key.asc)

---

**Hinweis**: Diese Sicherheitsrichtlinie basiert auf bewährten Praktiken der Open-Source-Community und wird regelmäßig aktualisiert. 
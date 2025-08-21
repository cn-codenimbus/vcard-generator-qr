# Beitragen zu vCard Generator + QR

Vielen Dank für Ihr Interesse an diesem Projekt! Beiträge sind sehr willkommen.

## 🚀 Schnellstart

1. **Fork** das Repository
2. **Clone** Ihren Fork: `git clone https://github.com/IHR_USERNAME/vcard-generator-qr.git`
3. **Branch** erstellen: `git checkout -b feature/amazing-feature`
4. **Änderungen** committen: `git commit -m 'Add amazing feature'`
5. **Push** zum Branch: `git push origin feature/amazing-feature`
6. **Pull Request** erstellen

## 📋 Richtlinien

### Code-Stil

- **JavaScript**: ES6+ Syntax, 2 Spaces Einrückung
- **CSS**: BEM-Methodologie für CSS-Klassen
- **HTML**: Semantische Struktur, valides HTML5
- **Kommentare**: Deutsche Kommentare für bessere Verständlichkeit

### Commit-Nachrichten

Verwenden Sie das konventionelle Commit-Format:

```
type(scope): description

feat: neue Funktion hinzufügen
fix: Bug beheben
docs: Dokumentation aktualisieren
style: Code-Formatierung
refactor: Code umstrukturieren
test: Tests hinzufügen
chore: Wartungsarbeiten
```

### Pull Request Checkliste

- [ ] Code folgt den Stil-Richtlinien
- [ ] Selbst-Test durchgeführt
- [ ] Dokumentation aktualisiert (falls nötig)
- [ ] Keine neuen Abhängigkeiten hinzugefügt (ohne Diskussion)
- [ ] Responsive Design getestet
- [ ] Browser-Kompatibilität geprüft

## 🛠️ Entwicklung

### Lokale Entwicklung

1. Repository klonen
2. QR-Library herunterladen:
   ```bash
   curl -o qrcode.min.js https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js
   ```
3. Lokalen Server starten:
   ```bash
   # Mit Python
   python3 -m http.server 8000
   
   # Oder mit Node.js
   npx serve .
   ```
4. Browser öffnen: `http://localhost:8000`

### Testen

- **Funktionalität**: Alle Features testen
- **Responsive**: Mobile und Desktop-Ansicht prüfen
- **Browser**: Chrome, Firefox, Safari, Edge testen
- **Offline**: Lokale QR-Library testen

## 🎯 Bereiche für Beiträge

### Priorität: Hoch
- [ ] Verbesserte Fehlerbehandlung
- [ ] Zusätzliche vCard-Felder (Geburtstag, Social Media)
- [ ] Dark/Light Mode Toggle
- [ ] Lokalisierung (mehrsprachig)

### Priorität: Mittel
- [ ] QR-Code Styling-Optionen
- [ ] Batch-Export (mehrere Kontakte)
- [ ] Import von bestehenden vCards
- [ ] Progressive Web App (PWA)

### Priorität: Niedrig
- [ ] Zusätzliche Export-Formate
- [ ] Erweiterte QR-Code-Optionen
- [ ] Analytics/Statistiken
- [ ] Plugin-System

## 🐛 Bug Reports

Bitte verwenden Sie die Issue-Vorlage und geben Sie an:

- **Browser**: Version und Betriebssystem
- **Schritt-für-Schritt**: Wie der Bug reproduziert werden kann
- **Erwartetes Verhalten**: Was sollte passieren
- **Tatsächliches Verhalten**: Was passiert stattdessen
- **Screenshots**: Falls relevant

## 💡 Feature Requests

- Beschreiben Sie das gewünschte Feature
- Erklären Sie den Nutzen
- Zeigen Sie Beispiele (falls möglich)
- Diskutieren Sie mit der Community

## 📞 Support

- **Issues**: Für Bugs und Feature-Requests
- **Discussions**: Für Fragen und Diskussionen
- **Wiki**: Für Dokumentation und Tutorials

## 🙏 Danksagung

Jeder Beitrag wird wertgeschätzt! Danke für Ihre Zeit und Mühe.

---

**Hinweis**: Bitte respektieren Sie den [Code of Conduct](CODE_OF_CONDUCT.md) und bleiben Sie freundlich und konstruktiv. 
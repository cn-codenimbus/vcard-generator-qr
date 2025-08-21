# Changelog

Alle wichtigen Änderungen an diesem Projekt werden in dieser Datei dokumentiert.

Das Format basiert auf [Keep a Changelog](https://keepachangelog.com/de/1.0.0/),
und dieses Projekt folgt [Semantic Versioning](https://semver.org/lang/de/).

## [Unreleased]

### Geplant
- Dark/Light Mode Toggle
- Zusätzliche vCard-Felder (Geburtstag, Social Media)
- Progressive Web App (PWA) Support
- Lokalisierung (mehrsprachig)

## [1.0.0] - 2024-01-XX

### Hinzugefügt
- Vollständige vCard-Unterstützung (vCard 3.0, vCard 4.0, MECARD)
- QR-Code-Generierung mit verschiedenen ECC-Levels
- Moderne, responsive Benutzeroberfläche
- Mehrere Export-Optionen (Download, Kopieren, PNG)
- Offline-Funktionalität mit lokaler QR-Library
- UTF-8 Support für Umlaute und Sonderzeichen
- Automatisches Laden der QR-Library von verschiedenen CDNs
- Live-Vorschau der generierten vCard/MECARD-Daten
- Responsive Design für Desktop und Mobile
- GitHub Pages Deployment Workflow

### Technische Details
- Vanilla JavaScript ohne Frameworks
- CSS Grid und Flexbox für Layout
- Inter Font für moderne Typografie
- CSS-Variablen für einfache Anpassung
- Debounced Input-Handling für bessere Performance
- Error Handling für QR-Library-Loading
- Cross-Browser-Kompatibilität

### Dokumentation
- Umfassende README.md
- CONTRIBUTING.md mit Beitragsrichtlinien
- CODE_OF_CONDUCT.md
- Sicherheitsrichtlinien (SECURITY.md)
- GitHub Issue und PR Templates
- Changelog

---

## Versionsschema

- **MAJOR**: Breaking Changes
- **MINOR**: Neue Features (rückwärtskompatibel)
- **PATCH**: Bug Fixes (rückwärtskompatibel)

## Änderungstypen

- **Added**: Neue Features
- **Changed**: Änderungen an bestehenden Funktionalitäten
- **Deprecated**: Funktionalitäten, die bald entfernt werden
- **Removed**: Entfernte Funktionalitäten
- **Fixed**: Bug Fixes
- **Security**: Sicherheitsverbesserungen 
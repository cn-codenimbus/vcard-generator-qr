# vCard Generator + QR

Ein moderner, browserbasierter Generator für vCard-Dateien mit integriertem QR-Code. Perfekt für digitale Visitenkarten und Kontaktverwaltung.

## ✨ Features

- **Vollständige vCard-Unterstützung**: vCard 3.0, vCard 4.0 und MECARD-Format
- **QR-Code Integration**: Automatische QR-Code-Generierung mit verschiedenen ECC-Levels
- **Moderne UI**: Dunkles Design mit responsivem Layout
- **Mehrere Export-Optionen**: Download als .vcf/.txt, QR als PNG, Kopieren in Zwischenablage
- **Offline-fähig**: Funktioniert ohne externe Abhängigkeiten (mit lokaler QR-Library)
- **UTF-8 Support**: Vollständige Unterstützung für Umlaute und Sonderzeichen

## 🚀 Live Demo

[Demo ansehen](https://cn-codenimbus.github.io/V-Card-Generator_QR/)

## 📋 Verwendung

1. **Daten eingeben**: Fülle die Kontaktfelder aus
2. **Format wählen**: vCard 3.0/4.0 für .vcf-Download, MECARD für beste QR-Erkennung
3. **QR-Einstellungen**: ECC-Level und Größe anpassen
4. **Exportieren**: Download, Kopieren oder QR als PNG speichern

## 🛠️ Installation

### Einfache Installation (Empfohlen)

1. Repository klonen:
```bash
git clone https://github.com/cn-codenimbus/V-Card-Generator_QR.git
cd vcard-generator-qr
```

2. QR-Library herunterladen:
```bash
curl -o qrcode.min.js https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js
```

3. `index.html` im Browser öffnen

### Mit lokaler QR-Library

Die Anwendung lädt automatisch die QR-Library von verschiedenen Quellen:
- Lokale Datei: `./qrcode.min.js`
- CDN-Fallbacks: jsdelivr, unpkg, cdnjs

## 📁 Projektstruktur

```
vcard-generator-qr/
├── index.html          # Hauptanwendung
├── qrcode.min.js       # QR-Code Library (optional)
├── README.md           # Diese Datei
├── LICENSE             # Lizenz
└── .gitignore          # Git-Ignore
```

## 🔧 Konfiguration

### QR-Code Einstellungen

- **ECC-Level**: L (7%), M (15%), Q (25%), H (30%) - höhere Werte = bessere Fehlerkorrektur
- **Größe**: 256px, 320px, 384px - größere Codes sind besser lesbar
- **Format**: 
  - **vCard 3.0/4.0**: Standard für .vcf-Dateien
  - **MECARD**: Optimiert für Kamera-Apps und bessere QR-Erkennung

### Browser-Kompatibilität

- ✅ Chrome/Edge (Chromium) 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Mobile Browser (iOS Safari, Chrome Mobile)

## 🎨 Anpassung

### Styling

Das Design verwendet CSS-Variablen für einfache Anpassung:

```css
:root {
  --bg: #0f172a;        /* Hintergrund */
  --card: #111827ee;    /* Karten-Hintergrund */
  --muted: #94a3b8;     /* Abgeschwächte Texte */
  --fg: #e5e7eb;        /* Haupttext */
  --acc: #22d3ee;       /* Akzentfarbe 1 */
  --acc2: #a78bfa;      /* Akzentfarbe 2 */
  --ring: #334155;      /* Rahmen */
}
```

### Funktionen erweitern

Die Anwendung ist modular aufgebaut:

- `buildPayload()`: Generiert vCard/MECARD-Text
- `renderAll()`: Rendert QR-Code und Vorschau
- `ensureQR()`: Lädt QR-Library

## 📄 Lizenz

MIT License - siehe [LICENSE](LICENSE) Datei.

## 🤝 Beitragen

Beiträge sind willkommen! Bitte:

1. Fork erstellen
2. Feature-Branch erstellen (`git checkout -b feature/AmazingFeature`)
3. Änderungen committen (`git commit -m 'Add some AmazingFeature'`)
4. Branch pushen (`git push origin feature/AmazingFeature`)
5. Pull Request erstellen

## 🐛 Bekannte Probleme

- **Umlaute in vCard 3.0**: Bei Problemen vCard 4.0 oder MECARD verwenden
- **QR-Erkennung**: MECARD wird von den meisten Kamera-Apps am besten erkannt
- **Offline-Modus**: Lokale `qrcode.min.js` Datei erforderlich

## 📞 Support

Bei Fragen oder Problemen:
- [Issue erstellen](https://github.com/cn-codenimbus/V-Card-Generator_QR/issues)
- [Wiki durchsuchen](https://github.com/cn-codenimbus/V-Card-Generator_QR/wiki)

## 🙏 Danksagungen

- [QRCode.js](https://github.com/davidshimjs/qrcodejs) - QR-Code Library
- [Inter Font](https://rsms.me/inter/) - Typografie
- [Tailwind CSS](https://tailwindcss.com/) - Design-Inspiration

---

⭐ Wenn dieses Projekt hilfreich ist, gib ihm einen Stern! 
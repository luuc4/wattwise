# WattWise - Beta Landing Page

## Übersicht

WattWise ist eine innovative Landing Page für ein intelligentes Energiemanagement-System. Die Seite nutzt moderne Web-Technologien und Formspree für die Beta-Anmeldung.

## Features

### Landing Page
- ✅ Responsive Design mit Bootstrap 5.3.2
- ✅ Modernes UI mit Poppins-Schriftart
- ✅ Animationen und interaktive Elemente
- ✅ Google Analytics Integration
- ✅ Custom Logo und Favicon
- ✅ Fixed Navbar mit smartem Scrolling

### Formspree-Integration
- ✅ Automatische Verarbeitung von Beta-Anmeldungen
- ✅ Newsletter-Anmeldungen
- ✅ Spam-Schutz durch Formspree
- ✅ E-Mail-Benachrichtigungen
- ✅ Keine Server-side Logik erforderlich

## Technische Details

### Dateien
- `index.html` - Hauptseite mit allen Sektionen
- `impressum.html` - Impressum gemäß österreichischem Recht
- `admin.html` - Dashboard (Passwort-geschützt)
- `logo.png` - WattWise Logo
- `favicon.ico` - Browser-Icon
- `BRANDING.md` - Vollständige Branding-Dokumentation

### Design-System
- **Primärfarbe**: #00c389 (Grün)
- **Sekundärfarbe**: #0073e6 (Blau)
- **Schriftart**: Poppins (Google Fonts)
- **Icons**: Font Awesome 6.4.2

Detaillierte Branding-Informationen siehe `BRANDING.md`.

## Deployment

### Server-Anforderungen
- Webserver (Apache/Nginx)
- Keine PHP erforderlich
- Statische Dateien

### Schnell-Deployment
```bash
# Dateien hochladen
scp *.html *.png *.ico your-server:/var/www/html/

# Berechtigungen setzen
chmod 644 *.html *.png *.ico
```

## Formspree-Konfiguration

### Endpoint
- **URL**: https://formspree.io/f/xqaypoal
- **Formular-ID**: xqaypoal
- **Methode**: POST

### Dashboard-Zugriff
- Admin-Dashboard: `admin.html`
- Passwort: `wattwise2025`
- Formspree Dashboard: https://formspree.io/forms/xqaypoal

## Sicherheitshinweise

### Formspree
- HTTPS für alle Formulare
- Integrierte Spam-Filterung
- DSGVO-konforme Datenverarbeitung

### Website
- HTTPS-Zertifikat verwenden
- Admin-Dashboard passwortgeschützt
- Regelmäßige Updates

## Branding & Design

Vollständige Branding-Dokumentation in `BRANDING.md`:
- Farbpalette (#00c389, #0073e6)
- Typografie (Poppins)
- Logo-Verwendung (logo.png, favicon.ico)
- UI-Elemente und Richtlinien

## Rechtliches

- Impressum: `impressum.html`
- Medieninhaber: Fachhochschule Vorarlberg GmbH
- Projektverantwortung: Marc Reutz
- Gemäß österreichischem Recht (§5 E-Commerce Gesetz, §25 Mediengesetz)

## Änderungshistorie

**2025-01-14**:
- ✅ Logo und Favicon integriert (logo.png, favicon.ico)
- ✅ Navbar-Hintergrund für mobile Ansicht optimiert
- ✅ Smooth-Scrolling-Offset für Fixed Navbar korrigiert
- ✅ README.md auf aktuellen Stand gebracht
- ✅ Branding-Dokumentation aktualisiert

**Frühere Änderungen**:
- ✅ Formspree-Integration implementiert
- ✅ Admin-Dashboard mit Basic Authentication
- ✅ Impressum nach österreichischem Recht
- ✅ Google Analytics Integration
- ✅ Responsive Design optimiert
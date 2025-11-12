# Kurzanleitung: CI-PowerPoint-Skill für Ratiodata

Laden Sie einfach eine Ratiodata CI-gestaltete PowerPoint-Präsentation in Ihr KI-Tool hoch (Skills und Skill Generator sollten aktiviert sein).

Dann verwenden Sie den nachfolgenden Prompt:

```
Ich habe eine PowerPoint-Vorlage, die ich für alle meine CI-Präsentationen bei Ratiodata verwende.

Lies die offizielle pptx-Fähigkeit und erstelle eine neue Fähigkeit namens „ratiodata-ci-powerpoint", die sie mit dem Stil meiner Vorlage erweitert.

Die neue Fähigkeit sollte:

Ausgelöst werden, wenn der Benutzer Ratiodata-Präsentationen, CI-Folien, Kundenpräsentationen oder Pitch-Decks anfordert.

Verwendungsbeispiele:

„Erstelle eine Präsentation für einen Bankkunden im Ratiodata CI"

„Erstelle ein 10-seitiges Pitch-Deck für Managed Services mit unserer CI-Vorlage"

„Erstelle eine Kundenpräsentation für Cybersecurity-Lösungen im CI-Stil"

„Erstelle eine Service-Dokumentation im Ratiodata Design"

Richtlinien:

Farben, Schriftarten und Layoutmuster aus meiner hochgeladenen Vorlage extrahieren

Logo-Platzierung und Master-Folienstruktur beibehalten

Alle Abstands- und Größenregeln befolgen, die du in der Vorlage identifizierst

Eine konsistente visuelle Hierarchie beibehalten

Ratiodata-Werte berücksichtigen: Innovation, Zuverlässigkeit, Qualität, Sicherheit, Kundenorientierung

Branchenspezifische Anforderungen beachten (Finanzsektor, Healthcare, öffentliche Verwaltung)

Beziehe dich auf die übergeordnete pptx-Fähigkeit, um eine Duplizierung der Präsentationslogik zu vermeiden.
Stelle sicher, dass du die skill-creator-Fähigkeit verwendest, um eine korrekte Formatierung sicherzustellen.
Gib das Ergebnis als ratiodata-powerpoint-skill.zip aus, das für die Installation bereit ist (benenne die gepackte .skill-Datei in .zip um).
```

---

# Tutorial: Erstellen eines CI-PowerPoint-Skills für Ratiodata

## Übersicht

Dieses Tutorial zeigt Ihnen Schritt für Schritt, wie Sie einen eigenen PowerPoint-Skill erstellen, der automatisch Präsentationen im Corporate Design von Ratiodata generiert. Am Ende haben Sie einen wiederverwendbaren Skill, den Ihr gesamtes Team für professionelle Kundenpräsentationen, interne Berichte und Pitch-Decks nutzen kann.

## Was Sie erreichen werden

- ✅ Einen Skill namens "ratiodata-branded-deck", der CI-konforme Präsentationen erstellt
- ✅ Automatische Anwendung der Ratiodata-Farben (#0066CC, #00A3E0, #003D82), -schriftarten und -layouts
- ✅ Konsistente Logo-Platzierung und visuelle Hierarchie nach Ratiodata-Standards
- ✅ Ein installationsfähiges .skill-Paket für Ihr Team
- ✅ Branchenspezifische Vorlagen für Banking, Healthcare und öffentliche Verwaltung

## Voraussetzungen

### Was Sie benötigen

1. **Ihre Ratiodata PowerPoint-Vorlage**: Eine .pptx-Datei mit dem aktuellen Corporate Design
2. **Zugriff auf ein KI-Tool**: Mit aktivierter Computer-Use-Funktion oder entsprechenden Skills
3. **Grundlegendes Verständnis**: Von Farben (Hex-Codes) und Schriftarten
4. **Optional**: Ratiodata Logo-Dateien (falls nicht bereits in der Vorlage integriert)

### Was die Vorlage enthalten sollte

- Master-Folien mit Ratiodata-Layout
- Ratiodata-Logo (korrekt platziert)
- Definierte Farben: Primärblau (#0066CC), Cyan (#00A3E0), Dunkelblau (#003D82)
- Schriftarten: 'Segoe UI', 'Open Sans' oder Arial
- Verschiedene Folienlayouts (Titel, Inhalt, Zwei-Spalten, etc.)
- Optional: Branchenspezifische Vorlagen für Banking/Finance, Healthcare

---

## Schritt 1: Verstehen der Ausgangssituation

### Was ist ein Skill?

Ein Skill ist ein modulares Paket, das Ihrem KI-Assistenten neue Fähigkeiten gibt. In unserem Fall:
- **Input**: "Erstelle eine Kundenpräsentation für Managed Services im Ratiodata CI"
- **Output**: Professionelle PowerPoint-Präsentation mit Ratiodata Corporate Design

### Typische Ratiodata-Anwendungsfälle

**Vertrieb:**
- Kundenpräsentationen für Software-, Hardware- und Servicelösungen
- Produkt-Pitch-Decks für IT-Systemhaus-Lösungen
- Angebotspräsentationen für Managed Services
- Technische Solution-Design-Präsentationen

**Marketing:**
- Event-Präsentationen für Messen und Konferenzen
- Produktmarketing-Decks
- Social Media Kampagnen-Präsentationen
- Newsletter-Vorlagen

**Service & Support:**
- Service-Level-Agreement (SLA) Dokumentationen
- Incident-Reports und Statusberichte
- Wissensdatenbank-Präsentationen
- Kundenschulungen

**Software/Produktmanagement:**
- Produkt-Roadmap-Präsentationen
- Feature-Release-Notes
- Technische Spezifikationen
- User Story Workshops

**Hardware-Entwicklung:**
- Produktspezifikationen für Hardware-Lösungen
- Competitive Intelligence Reports
- Marktanalysen
- Testkonzept-Dokumentationen

### Projektstruktur verstehen

Ein fertiger Skill sieht so aus:

```
ratiodata-branded-deck/
├── SKILL.md                        # Hauptanweisungen für KI-Assistent
├── assets/
│   ├── template.pptx               # Ihre Ratiodata CI-Vorlage
│   └── logo-ratiodata.png          # Optional: Logo-Dateien
└── references/
    ├── design-system.md            # Extrahierte Design-Informationen
    └── compliance-guidelines.md    # DSGVO & IT-Sicherheit
```

---

## Schritt 2: Vorbereitung - Design-Informationen sammeln

### 2.1 Vorlage analysieren

Laden Sie Ihre Ratiodata PowerPoint-Vorlage hoch und bitten Sie Ihr KI-Tool:

```
Bitte analysiere diese PowerPoint-Vorlage und extrahiere:
1. Alle verwendeten Farben (als Hex-Codes) - insbesondere Ratiodata Blautöne
2. Alle Schriftarten (Name und wo sie verwendet werden)
3. Logo-Position und -Größe
4. Typische Folienlayouts
5. Abstände und Größenverhältnisse
6. Besondere Gestaltungselemente (Farbverläufe, Trennlinien)
```

### 2.2 Design-System dokumentieren

Das Sprachmodell wird etwas Ähnliches erstellen:

```markdown
# Design-System: Ratiodata SE

## Brand Identity
**Unternehmen**: Ratiodata SE  
**Branche**: IT-Systemhaus, Managed Services, Bankentechnologie  
**Brand Values**: Innovation, Zuverlässigkeit, Qualität, Sicherheit, Kundenorientierung  
**Muttergesellschaft**: Atruvia AG

## Farben - Ratiodata Corporate Identity

### Primärfarben (Professional IT/Tech Palette)
- **Ratiodata Hauptblau**: #0066CC - Technologie & Vertrauen (Headers, CTAs)
- **Helles Cyan**: #00A3E0 - Innovation (Highlights, Akzente)
- **Dunkelblau**: #003D82 - Stabilität (Titel, wichtige Informationen)

### Sekundärfarben
- **Erfolg Grün**: #00AA4F - Service Excellence & Erfolg
- **Warning Orange**: #FF8C00 - Wichtige Hinweise, Handlungsaufforderungen

### Textfarben
- **Dunkel**: #1a1a1a - Haupttext
- **Mittel**: #4a4a4a - Sekundärtext
- **Hell**: #6a6a6a - Captions, Fußnoten

### Hintergrund
- **Weiß**: #ffffff - Haupthintergrund
- **Hell**: #f5f7fa - Sekundärhintergrund
- **Sehr Hell**: #f9fafb - Card-Hintergründe
- **Border**: #e0e4e8 - Trennlinien

### Spezielle Effekte
- **Gradient**: linear-gradient(90deg, #0066CC 0%, #00A3E0 50%, #003D82 100%) - Für Trennlinien und Header

## Schriftarten

### Font Families (IT-Professional Look)
- **Primär**: Segoe UI (Windows Standard, professionell)
- **Alternativ**: Open Sans (Web-optimiert)
- **Fallback**: Arial, sans-serif

### Überschriften
- **H1 Titel**: Segoe UI Bold, 44pt, #0066CC
- **H1 Content**: Segoe UI Semibold, 32pt, #1a1a1a
- **H2**: Segoe UI Semibold, 24pt, #003D82
- **H3**: Segoe UI Semibold, 18pt, #0066CC

### Fließtext
- **Body**: Segoe UI Regular, 16pt, #4a4a4a
- **Caption**: Segoe UI Regular, 12pt, #6a6a6a
- **Footer**: Segoe UI Regular, 10pt, #6a6a6a

### Line Heights
- **Überschriften**: 1.2
- **Fließtext**: 1.7
- **Listen**: 1.8

## Logo Spezifikationen

### Ratiodata Logo
- **Position**: Obere rechte Ecke (Standard) oder zentriert (Titelfolie)
- **Standardgröße**: 140px × 50px
- **Titelfolie**: 200px × 70px
- **Abstand**: 24px von oben, 24px von rechts
- **Mindestabstand**: 12px Clear Space auf allen Seiten
- **Format**: PNG oder SVG bevorzugt

### Atruvia AG Logo (optional)
- **Position**: Fußzeile rechts oder zusammen mit Ratiodata Logo
- **Größe**: 80px × 30px
- **Verwendung**: Bei Präsentationen für die Genossenschaftliche FinanzGruppe

## Layout System

### Slide Dimensions
- **Aspect Ratio**: 16:9 (Standard für moderne Präsentationen)
- **Breite**: 960px
- **Höhe**: 540px

### Grid System
- **Columns**: 12-Spalten-Raster
- **Gutter**: 24px
- **Margins**: 48px (links/rechts), 40px (oben/unten)

### Safe Zones
- **Header Zone**: Obere 80px (Header + Logo)
- **Footer Zone**: Untere 40px (Seitenzahlen, Copyright, Atruvia-Logo)
- **Content Area**: Mittlere 420px (Hauptinhalt)

## Folienlayouts

### 1. Titelfolie (Kundenpräsentationen)
**Layout**: Zentriert mit Gradient-Header
**Elemente**:
- Gradient-Header (linear-gradient(135deg, #0066CC 0%, #0052A3 100%))
- Ratiodata Logo (zentriert oder oben, 200px Breite)
- H1 Titel (zentriert, weiß auf blauem Hintergrund)
- Untertitel (zentriert, #e6f2ff)
- Präsentator/Datum (unten)
- Gradient-Trennlinie am unteren Rand (3px)
**Background**: Gradient oder Weiß

### 2. Standard-Inhaltsfolie
**Layout**: Einspaltig
**Elemente**:
- Ratiodata Logo (oben rechts, 140px)
- H2 Titel (linksbündig, mit 3px Unterstreichung in #0066CC)
- Body Content (Aufzählungen oder Absätze)
- Footer (Seitenzahl links, © Ratiodata SE rechts)
**Background**: Weiß
**Border**: Optional 6px linker Rand in #0066CC

### 3. Zwei-Spalten-Layout (Lösungsvergleich)
**Layout**: 50/50 oder 60/40 Split
**Verwendung**: Problem/Solution, Before/After, Feature-Vergleiche
**Elemente**:
- Logo (oben rechts)
- H2 Titel (über beiden Spalten)
- Linke Spalte: Text oder Liste
- Rechte Spalte: Grafik, Chart oder Bild
**Divider**: 1px vertikale Linie in #e0e4e8

### 4. Chart/Diagramm-Folie
**Layout**: Vollbreiter Content-Bereich
**Verwendung**: Datenvisualisierung, Metriken, KPIs
**Elemente**:
- Logo (oben rechts)
- H2 Titel
- Großes Chart (zentriert)
- Caption/Quelle (unten links, klein)
**Chart-Farben**: Ratiodata-Primärpalette für Datenreihen

### 5. Service-Level/Timeline-Folie
**Layout**: Horizontale Timeline oder Stufen
**Verwendung**: Managed Services, Projektphasen, Roadmaps
**Elemente**:
- Milestone-Marker (Orange Kreise #FF8C00)
- Phasen-Labels (Tech Blue)
- Verbindungslinien (Gradient)
**Highlight**: Aktuelle Phase in #0066CC

### 6. Section Divider (Kapiteltrennung)
**Layout**: Full-bleed mit Gradient
**Elemente**:
- Großes H1 (zentriert, weiß)
- Kapitelnummer (Orange #FF8C00)
- Optional: Icon für Themenbereich
**Background**: Deep Navy Gradient (#003D82 → #0066CC)

### 7. Branchenspezifische Folien

#### Banking/Finance Template
- Zusätzliche Compliance-Hinweise im Footer
- Gedämpftere Farben für konservatives Auftreten
- Platz für regulatorische Disclaimers

#### Healthcare Template
- HIPAA/DSGVO-Hinweise
- Patientendaten-Anonymisierung betonen
- Medizinische Icons und Farbschema

#### Öffentliche Verwaltung Template
- Behörden-konforme Gestaltung
- E-Government-Icons
- Barrierefreiheits-Hinweise

## Component Patterns

### Headers und Titel
```
H1 (Titelfolie): Segoe UI Bold, 44pt, Weiß auf #0066CC
H1 (Content): Segoe UI Semibold, 32pt, #1a1a1a, mit 3px Unterstreichung in #0066CC
H2: Segoe UI Semibold, 24pt, #003D82
H3: Segoe UI Semibold, 18pt, #0066CC
```

### Aufzählungen (Listen)
- **Bullet Style**: Runde Punkte in #0066CC oder #00A3E0
- **Indent**: 24px
- **Line Spacing**: 1.8
- **Font**: Segoe UI Regular, 16pt
- **Verschachtelte Listen**: Dunkleres Blau für Sub-Items

### Tabellen (für technische Specs)
- **Header Row**: #0066CC Hintergrund, weißer Text
- **Alternierende Zeilen**: Weiß / #f9fafb
- **Border**: 1px solid #e0e4e8
- **Cell Padding**: 12px
- **Hover-Effect**: Leichter Schatten

### Charts und Diagramme
- **Primäre Daten**: Tech Blue (#0066CC)
- **Sekundäre Daten**: Vibrant Cyan (#00A3E0)
- **Tertiäre Daten**: Success Green (#00AA4F)
- **Warnung/Kritisch**: Orange (#FF8C00)
- **Grid Lines**: #f5f7fa
- **Achsenbeschriftungen**: #4a4a4a, 12pt

### Info-Boxen

#### Tipp-Box (💡 Best Practices)
```
Background: linear-gradient(135deg, #e6f2ff, #d9ebff)
Border: 2px solid #00A3E0
Icon: 💡 (positioniert absolut, top: -15px)
Titel: #003D82, Segoe UI Semibold, 18pt
Text: #4a4a4a
```

#### Sicherheits-Box (🔒 IT-Security)
```
Background: linear-gradient(135deg, #f0f8f0, #e6f5e6)
Border: 2px solid #00AA4F
Icon: 🔒 (positioniert absolut)
Titel: #006633, Segoe UI Semibold, 18pt
Verwendung: DSGVO, IT-Sicherheit, Compliance
```

#### Warnung-Box (⚠️ Compliance)
```
Background: linear-gradient(135deg, #fff5e6, #ffe6cc)
Border: 2px solid #FF8C00
Icon: ⚠️ (positioniert absolut)
Titel: #CC5500, Segoe UI Semibold, 18pt
Verwendung: Regulatorische Hinweise, Wichtige Bedingungen
```

### Abteilungsspezifische Boxen

#### Vertrieb-Box
```
Icon: 💼
Border: #0066CC
Verwendung: Sales-relevante Informationen, ROI, Pricing
```

#### Service-Box
```
Icon: 🛠️
Border: #00AA4F
Verwendung: Support-Informationen, SLAs, Incident Management
```

#### Hardware-Box
```
Icon: 🖥️
Border: #003D82
Verwendung: Technische Spezifikationen, Hardware-Features
```

## Spacing Rules (Whitespace Management)

### Margins
- **Slide Edges**: 48px minimum
- **Zwischen Elementen**: 24px Standard
- **Zwischen Sektionen**: 32px
- **Titel zu Content**: 32px

### Padding
- **Text Boxes**: 16px alle Seiten
- **Info Boxes**: 25px alle Seiten
- **Tabellen**: 12px Cell Padding
- **Shapes**: 20px alle Seiten

## Accessibility (Barrierefreiheit)

### Kontrastverhältnisse (WCAG 2.1 Level AA)
- **Body Text**: Minimum 7:1 (#4a4a4a auf #ffffff)
- **Headers**: Minimum 4.5:1 (#0066CC auf #ffffff)
- **Charts**: Muster zusätzlich zu Farben verwenden

### Font Sizes (Mindestgrößen)
- **Minimum Body Text**: 16pt (niemals kleiner)
- **Minimum Caption**: 12pt
- **Präsentationen vor Publikum**: 24pt minimum für Lesbarkeit

### Screenreader-Kompatibilität
- Alternative Texte für Bilder
- Logische Reihenfolge der Elemente
- Aussagekräftige Link-Texte

## Branchenspezifische Design-Anpassungen

### Finanzsektor (Banking)
**Farbpalette**: Konservativer
- Dunkleres Blau bevorzugen (#003D82)
- Weniger Orange, mehr Grau
**Footer**: 
- Compliance-Hinweise (BaFin, etc.)
- "Eine Tochtergesellschaft der Atruvia AG"
**Icons**: Traditionell, seriös

### Healthcare
**Farbpalette**: Beruhigend
- Grün-Akzente für Healthcare (#00AA4F)
- Hellere Hintergründe
**Hinweise**:
- DSGVO/HIPAA-Compliance
- Patientendaten-Anonymisierung
**Icons**: Medizinisch, vertrauenswürdig

### Öffentliche Verwaltung
**Farbpalette**: Neutral
- Primärfarben beibehalten, aber gedämpfter
**Footer**:
- Behörden-Konformität
- Barrierefreiheits-Statement
**Icons**: Behördlich, klar

## Common Patterns (Häufige Muster)

### Managed Services Success Story
- Grüner Akzentbalken links (#00AA4F)
- Kunden-Logo (oben links, kleine Größe)
- Service-Metriken in großen Zahlen (#0066CC)
- Testimonial in Segoe UI Medium, 20pt

### Problem/Solution Pattern
- Zwei-Spalten-Layout
- Problem (links): Roter Akzent (#CC0000)
- Lösung (rechts): Grüner Akzent (#00AA4F)
- Pfeil zwischen Spalten (Orange #FF8C00)

### Produkt-Roadmap / Timeline
- Horizontale Timeline über Folie
- Meilensteine mit orangefarbenen Kreisen markiert (#FF8C00)
- Vergangene Meilensteine: Dunkelgrau (#6a6a6a)
- Zukünftige Meilensteine: Tech Blue (#0066CC)
- Aktuelle Phase: Hervorgehoben mit Glow-Effekt

### Service-Level-Matrix
- Tabellen-Layout
- 3 Service-Level: Basic, Professional, Enterprise
- Header in Gradient-Blau
- Checkmarks (✓) in Grün (#00AA4F)
- Cross-marks (✗) in Grau (#6a6a6a)

## Don'ts ❌ (Ratiodata-spezifisch)

- ❌ **Niemals** das Logo verzerren oder Proportionen ändern
- ❌ **Niemals** Farben außerhalb der Palette verwenden
- ❌ **Niemals** andere Schriftarten als Segoe UI/Open Sans/Arial nutzen
- ❌ **Niemals** Text über unruhigen Hintergründen ohne Overlay platzieren
- ❌ **Niemals** unter Mindest-Schriftgrößen gehen (Barrierefreiheit!)
- ❌ **Niemals** Safe Zones ignorieren
- ❌ **Niemals** mehr als 3 Schriftgrößen pro Folie verwenden
- ❌ **Niemals** "Atruvia AG" vergessen im Footer (rechtliche Anforderung)
- ❌ **Niemals** vertrauliche Kundendaten in öffentlichen Präsentationen
- ❌ **Niemals** Wettbewerber-Logos ohne Genehmigung verwenden
- ❌ **Niemals** Marketing-Claims ohne Abstimmung mit Legal

## Compliance & Datenschutz

### DSGVO-Anforderungen
- Keine personenbezogenen Daten ohne Anonymisierung
- Kunden-Logos nur mit schriftlicher Genehmigung
- Projekt-Details nur mit NDA
- Testimonials nur mit Einverständniserklärung

### IT-Sicherheit
- Keine Screenshots mit sensiblen Daten
- Keine Systemarchitekturen mit Security-Details
- Keine Zugangsdaten oder Credentials
- Wasserzeichen bei vertraulichen Präsentationen

### Regulatorische Hinweise
**Banking**: BaFin-Anforderungen beachten  
**Healthcare**: HIPAA/GDPR-Compliance  
**Öffentliche Verwaltung**: E-Government-Standards

## Review Checklist (Qualitätssicherung)

Vor Finalisierung jeder Ratiodata-Präsentation:
- [ ] Ratiodata Logo auf allen Folien (außer ggf. Titelfolie)
- [ ] Alle Farben aus der genehmigten Palette
- [ ] Font-Hierarchie konsistent (Segoe UI/Open Sans)
- [ ] Ausreichend Whitespace (nicht überladen)
- [ ] Keine Text-Abschnitte oder übergelaufener Content
- [ ] Lesbare Kontrastverhältnisse (WCAG 2.1 Level AA)
- [ ] Am Grid-System ausgerichtet
- [ ] Seitenzahlen vorhanden (außer Titelfolie)
- [ ] Footer mit "© 2025 Ratiodata SE" und "Eine Tochtergesellschaft der Atruvia AG"
- [ ] Branchenspezifische Compliance-Hinweise (falls erforderlich)
- [ ] Keine vertraulichen/personenbezogenen Daten
- [ ] Rechtschreibung und Grammatik geprüft
- [ ] Technische Begriffe korrekt und konsistent verwendet
```

**💡 Tipp**: Speichern Sie diese Design-System-Informationen - sie werden in `references/design-system.md` Ihres Skills verwendet.

---

## Schritt 3: Skill initialisieren

### 3.1 Skill-Struktur erstellen

Bitten Sie Ihr KI-Tool:

```
Bitte initialisiere einen neuen Skill namens "ratiodata-branded-deck" mit dem init_skill.py Skript.
```

Das Tool führt aus:

```bash
python /mnt/skills/public/skill-creator/scripts/init_skill.py ratiodata-branded-deck --path /home/claude/ratiodata-branded-deck
```

Dies erstellt die Grundstruktur:

```
ratiodata-branded-deck/
├── SKILL.md (Template mit TODOs)
├── scripts/
│   └── example_script.py
├── references/
│   └── example_reference.md
└── assets/
    └── example_asset.txt
```

### 3.2 Unnötige Dateien entfernen

Die Beispieldateien können gelöscht werden:

```bash
rm ratiodata-branded-deck/scripts/example_script.py
rm ratiodata-branded-deck/references/example_reference.md
rm ratiodata-branded-deck/assets/example_asset.txt
```

---

## Schritt 4: Design-Informationen integrieren

### 4.1 Vorlage speichern

Ihre Ratiodata PowerPoint-Vorlage muss in den `assets/` Ordner:

```
Bitte kopiere meine hochgeladene Vorlage "Ratiodata_Template.pptx" 
nach /home/claude/ratiodata-branded-deck/assets/template.pptx
```

**Optional**: Speichern Sie auch Logo-Dateien:
```bash
# Ratiodata Logo
cp Ratiodata-Logo.png ratiodata-branded-deck/assets/logo-ratiodata.png

# Atruvia AG Logo (für Footer)
cp Atruvia-Logo.png ratiodata-branded-deck/assets/logo-atruvia.png
```

### 4.2 Design-System dokumentieren

Erstellen Sie `references/design-system.md` mit den vorher gesammelten Informationen:

```
Bitte erstelle /home/claude/ratiodata-branded-deck/references/design-system.md 
mit den vorher extrahierten Design-Informationen für Ratiodata.
```

**Wichtig**: Diese Datei sollte alle Details enthalten:
- Exakte Hex-Codes für Ratiodata-Farben (#0066CC, #00A3E0, #003D82)
- Font-Namen (Segoe UI, Open Sans) und -Größen
- Präzise Abstände und Positionen
- Layout-Muster für verschiedene Anwendungsfälle
- Branchenspezifische Anpassungen

### 4.3 Compliance-Richtlinien dokumentieren

Erstellen Sie zusätzlich `references/compliance-guidelines.md`:

```markdown
# Compliance-Richtlinien für Ratiodata-Präsentationen

## Datenschutz (DSGVO)

### Personenbezogene Daten
- ❌ Keine Namen ohne Einwilligung
- ❌ Keine E-Mail-Adressen
- ❌ Keine Telefonnummern
- ❌ Keine Adressen
- ✅ Anonymisierte Beispiele verwenden

### Kundendaten
- Kunden-Logos nur mit schriftlicher Genehmigung
- Projekt-Details nur mit NDA
- Keine Screenshots aus Kundensystemen
- Testimonials nur mit dokumentierter Einwilligung

## IT-Sicherheit

### Sensible Informationen
- ❌ Keine Systemarchitekturen mit Security-Details
- ❌ Keine IP-Adressen oder Netzwerk-Topologien
- ❌ Keine Zugangsdaten oder API-Keys
- ❌ Keine Vulnerability-Details
- ✅ Abstrahierte Diagramme verwenden

### Vertraulichkeit
- Interne Präsentationen: "Vertraulich - Nur für internen Gebrauch"
- Kunden-Präsentationen: NDA-Status im Footer
- Wasserzeichen bei sensiblen Inhalten

## Branchenspezifische Compliance

### Banking/Finanzsektor
- BaFin-Anforderungen beachten
- Finanzmarktaufsicht-Compliance
- Keine ungenehmigten Performance-Claims
- Footer: Disclaimer zu regulatorischen Themen

### Healthcare
- HIPAA-Compliance (US) / GDPR (EU)
- Keine Patientendaten (auch anonymisiert nur mit Genehmigung)
- Medizinprodukte-Regulierung beachten
- Healthcare-spezifische Sicherheitsstandards

### Öffentliche Verwaltung
- E-Government-Gesetze beachten
- Barrierefreiheits-Anforderungen (BITV 2.0)
- Transparenz-Pflichten
- Vergaberecht bei Ausschreibungen

## Marketing-Claims

### Genehmigte Aussagen
- "Über 50 Jahre Erfahrung als IT-Dienstleister"
- "Tochtergesellschaft der Atruvia AG"
- "Systemhauspartner der Genossenschaftlichen FinanzGruppe"
- "Mehrfach ausgezeichneter Innovator des Jahres"

### Nicht genehmigte Aussagen
- Superlative ohne Beleg ("bester", "größter", "führender")
- Ungeprüfte Wettbewerbervergleiche
- Technische Claims ohne Validierung
- ROI-Versprechen ohne Fallback

## Rechtliche Anforderungen

### Copyright
- Nur lizenzierte oder selbst erstellte Bilder verwenden
- Korrekte Bildnachweise im Footer
- Keine urheberrechtlich geschützten Icons ohne Lizenz
- Font-Lizenzen prüfen (Segoe UI, Open Sans sind OK)

### Markenrecht
- Ratiodata® und Atruvia® korrekt verwenden
- Partner-Logos nur nach Freigabe
- Produkt-Namen von Drittanbietern korrekt schreiben
- Keine Verwechslungsgefahr mit Wettbewerbern

### Impressumspflicht
Footer sollte enthalten:
- © 2025 Ratiodata SE
- "Eine Tochtergesellschaft der Atruvia AG"
- Optional: Website-Link (www.ratiodata.de)

## Best Practices

### Vor Finalisierung prüfen
- [ ] Keine personenbezogenen Daten
- [ ] Keine vertraulichen System-Informationen
- [ ] Alle Kunden-Referenzen genehmigt
- [ ] Marketing-Claims abgestimmt
- [ ] Branchenspezifische Compliance beachtet
- [ ] Copyright und Lizenzen geklärt
- [ ] Footer vollständig und korrekt
- [ ] Qualitätssicherung durchgeführt

### Bei Unsicherheit
- Rücksprache mit Legal/Compliance
- Marketing-Team konsultieren
- Datenschutzbeauftragten einbeziehen
- Lieber konservativ als riskant
```

---

## Schritt 5: SKILL.md schreiben

### 5.1 Frontmatter definieren

Der Kopf von SKILL.md definiert, wann der Skill aktiviert wird:

```yaml
---
name: ratiodata-branded-deck
description: Erstellt professionelle PowerPoint-Präsentationen im Corporate Design von Ratiodata SE. Verwenden bei: Kundenpräsentationen, CI-Folien, Pitch-Decks, Service-Dokumentationen, technische Präsentationen. Wendet automatisch Ratiodata-Farben (#0066CC, #00A3E0, #003D82), Schriftarten (Segoe UI/Open Sans), Logo-Platzierung und Layout-Standards an. Berücksichtigt branchenspezifische Anforderungen (Banking, Healthcare, öffentliche Verwaltung) und Compliance-Richtlinien (DSGVO, IT-Sicherheit).
---
```

**Trigger-Begriffe** (wann der Skill aktiviert wird):
- "Ratiodata CI-Präsentation"
- "Kundenpräsentation im Corporate Design"
- "Managed Services Pitch-Deck"
- "IT-Systemhaus Präsentation"
- "Bankentechnologie-Präsentation"
- "Service-Level-Dokumentation"
- "Ratiodata-gebrandete Folien"
- "Präsentation für [Banking/Healthcare/Verwaltung]"

### 5.2 Haupt-Anweisungen schreiben

Der Body von SKILL.md enthält die Arbeitsanweisungen:

```markdown
# Ratiodata Branded Deck Creator

## Überblick

Erstelle PowerPoint-Präsentationen, die dem Corporate Design von Ratiodata SE folgen.
Verwende die bereitgestellte Vorlage und das Design-System für konsistente, professionelle Ergebnisse.

Ratiodata SE ist ein führender IT-Dienstleister und Systemhauspartner der Genossenschaftlichen FinanzGruppe (Tochter der Atruvia AG) mit Fokus auf:
- IT-Systemhaus-Lösungen
- Managed Services
- Bankentechnologie
- Cybersecurity
- Cloud-Services
- Modern Workplace

## Wann diesen Skill verwenden

Verwende diesen Skill, wenn der Benutzer fragt nach:
- Kundenpräsentationen für IT-Lösungen
- Pitch-Decks für Managed Services, Hardware, Software
- CI-konforme Ratiodata-Folien
- Service-Level-Dokumentationen
- Produktpräsentationen (IT-Systemhaus-Portfolio)
- Interne Berichte und Status-Updates
- Branchenspezifische Präsentationen (Banking, Healthcare, öffentliche Verwaltung)
- Angebotspräsentationen und Solution Designs
- Schulungsmaterialien und Wissensdatenbank-Content

## Workflow

### 1. Kontext verstehen und Design-System laden

**Schritt 1a: Benutzeranfrage analysieren**
Identifiziere:
- **Zielgruppe**: Kunde (extern) oder intern?
- **Branche**: Banking, Healthcare, öffentliche Verwaltung, Mittelstand?
- **Zweck**: Pitch, Schulung, Report, Angebot?
- **Umfang**: Anzahl Folien, Detailgrad
- **Besonderheiten**: Compliance-Anforderungen, vertrauliche Inhalte?

**Schritt 1b: Design-System laden**
Lies IMMER zuerst:
- Datei: `references/design-system.md`
- Enthält: Ratiodata-Farben, Schriftarten, Logo-Specs, Layouts
- Besonders beachten: Farbverläufe, Branding-Elemente, Atruvia-Logo-Platzierung

**Schritt 1c: Compliance-Richtlinien prüfen**
Lies: `references/compliance-guidelines.md`
Prüfe auf:
- DSGVO-Anforderungen
- Branchenspezifische Regulierung
- Vertraulichkeits-Level
- Genehmigte vs. nicht genehmigte Aussagen

### 2. Entscheidung: Vorlage vs. HTML2PPTX

**Verwende die Vorlage** (`assets/template.pptx`), wenn:
- Standard-Kundenpräsentation (5-20 Folien)
- Layouts aus der Vorlage ausreichend
- Schnelle Erstellung wichtig
- **EMPFOHLEN für 90% der Ratiodata-Präsentationen**

**Verwende HTML2PPTX**, wenn:
- Sehr spezifische, hochkomplexe Layouts
- Interaktive Elemente erforderlich
- Mehr als 30 Folien mit vielen Variationen
- Komplexe Datenvisualisierungen mit Custom Charts

### 3. Vorlage-basierter Workflow (Standard)

#### 3.1 Vorlage laden und analysieren

```bash
# Text extrahieren
python -m markitdown assets/template.pptx > workspace/template-content.md

# Thumbnails erstellen für visuelle Referenz
python /mnt/skills/public/pptx/scripts/thumbnail.py assets/template.pptx workspace/template-thumbnails
```

#### 3.2 Folien-Inventar erstellen

Erstelle `workspace/template-inventory.md` mit:
- **Liste ALLER Folien** (0-indiziert!)
- **Gruppierung nach Typ**:
  - Titelfolien (mit/ohne Gradient-Header)
  - Standard-Inhaltsfolien (einspaltig)
  - Zwei-Spalten-Layouts
  - Chart-Folien
  - Section Dividers
  - Branchenspezifische Vorlagen (Banking, Healthcare, etc.)
- **Beschreibung** jeder Folie: Layout, Platzhalter, Verwendungszweck

**Beispiel Inventar**:
```markdown
# Ratiodata Template Inventory

## Titelfolien
- **Folie 0**: Haupttitelfolie mit Gradient-Header
  - Platzhalter: Haupttitel, Untertitel, Präsentator, Datum
  - Logo: Zentriert, groß (200px)
  - Verwendung: Start jeder Präsentation

- **Folie 1**: Alternative Titelfolie (weiß)
  - Logo: Oben rechts
  - Verwendung: Interne Präsentationen

## Inhaltsfolien
- **Folie 2**: Standard-Content (einspaltig)
  - Platzhalter: Titel, Body-Text/Aufzählung
  - 6px blauer linker Rand
  - Verwendung: Standard-Inhalte

- **Folie 3**: Content mit Info-Box
  - Wie Folie 2, aber mit vorformatierter Tip-Box
  - Verwendung: Best Practices, Hinweise

## Spezialfolien
- **Folie 10**: Service-Level-Matrix
  - 3-Spalten-Tabelle für Service-Tiers
  - Verwendung: Managed Services, SLA-Präsentationen

- **Folie 11**: Banking Compliance-Folie
  - Footer mit BaFin-Disclaimer
  - Gedämpfte Farbpalette
  - Verwendung: Finanzsektor-Präsentationen
```

#### 3.3 Präsentations-Outline erstellen

Erstelle `workspace/presentation-outline.md`:

```markdown
# Präsentation: [Titel] - Outline

## Metadaten
- **Kunde/Empfänger**: [Name]
- **Branche**: [Banking/Healthcare/Mittelstand/etc.]
- **Zweck**: [Pitch/Schulung/Report]
- **Vertraulichkeit**: [Öffentlich/Intern/Vertraulich/NDA]
- **Zielfolien**: [Anzahl]

## Folienliste

### Folie 1: Titelfolie
- **Vorlage**: Folie 0 (Gradient-Header)
- **Titel**: "Managed Services für die Bankentechnologie"
- **Untertitel**: "Ihre IT-Sicherheit in den besten Händen"
- **Präsentator**: Max Mustermann, Senior Account Manager
- **Datum**: 12. November 2025

### Folie 2: Über Ratiodata
- **Vorlage**: Folie 2 (Standard-Content)
- **Titel**: "Ratiodata SE – Ihr Partner für IT-Exzellenz"
- **Inhalt**: 
  - Über 50 Jahre Erfahrung als IT-Dienstleister
  - Tochtergesellschaft der Atruvia AG
  - Systemhauspartner der Genossenschaftlichen FinanzGruppe
  - 4 Geschäftsfelder: IT-Systemhaus, Managed Services, Bankentechnologie, Cybersecurity

### Folie 3: Herausforderung im Bankensektor
- **Vorlage**: Folie 5 (Zwei-Spalten)
- **Titel**: "Herausforderungen moderner Banken-IT"
- **Links**: Problem-Liste (mit roten Akzenten)
  - Steigende regulatorische Anforderungen (BaFin, EBA)
  - Cyber-Bedrohungen nehmen zu
  - Legacy-Systeme binden Ressourcen
- **Rechts**: Bild oder Icon (Banken-IT, Sicherheitsschloss)

### Folie 4: Unsere Lösung – Managed Services
- **Vorlage**: Folie 10 (Service-Level-Matrix)
- **Titel**: "Managed Services - Maßgeschneidert für Ihre Bank"
- **Tabelle**:
  - Spalte 1: Basic (Monitoring 24/7)
  - Spalte 2: Professional (+ Proaktive Wartung)
  - Spalte 3: Enterprise (+ Dedicated Team)

### Folie 5: Compliance & Sicherheit
- **Vorlage**: Folie 11 (Banking Compliance)
- **Titel**: "Höchste Sicherheitsstandards & Compliance"
- **Inhalt**:
  - ISO 27001 zertifiziert
  - BaFin-konforme Prozesse
  - DSGVO-compliant
  - Penetrationstests & Security Audits
- **Footer**: BaFin-Disclaimer
  
[... weitere Folien ...]

### Letzte Folie: Call-to-Action
- **Vorlage**: Folie 15 (CTA mit Kontakt)
- **Titel**: "Lassen Sie uns Ihre IT-Sicherheit gemeinsam stärken"
- **Inhalt**: Kontaktdaten, QR-Code zur Website
```

#### 3.4 Folien duplizieren und anpassen

Für jede Folie im Outline:

```python
from pptx import Presentation

# Vorlage laden
prs = Presentation('assets/template.pptx')

# Folie duplizieren (verwende korrekten 0-basierten Index aus Inventar!)
source_slide = prs.slides[0]  # Beispiel: Titelfolie
new_slide = duplicate_slide(prs, source_slide)

# Platzhalter mit Outline-Content füllen
for shape in new_slide.shapes:
    if shape.has_text_frame:
        if shape.text == "HAUPTTITEL":
            shape.text = "Managed Services für die Bankentechnologie"
        elif shape.text == "Untertitel":
            shape.text = "Ihre IT-Sicherheit in den besten Händen"
        # ... weitere Platzhalter

# Speichern
prs.save('workspace/ratiodata-presentation.pptx')
```

**Wichtige Hinweise**:
- **0-basierte Indizierung**: Folie 1 in PowerPoint = Index 0 in Python!
- **Platzhalter-Namen** aus Inventar verwenden
- **Formatierung beibehalten**: Nicht neu formatieren, sondern Vorlage nutzen
- **Logo-Platzierung**: Wird automatisch von Vorlage übernommen

#### 3.5 Branding-Elemente hinzufügen

Stelle sicher:
- **Ratiodata Logo** auf allen Folien (außer ggf. Titelfolie nach Vorlage)
- **Atruvia AG Logo** im Footer (rechtliche Anforderung)
- **Footer-Text**: "© 2025 Ratiodata SE | Eine Tochtergesellschaft der Atruvia AG"
- **Seitenzahlen**: Auf allen Folien außer Titelfolie
- **Gradient-Trennlinien**: Zwischen Sektionen (wenn nicht schon in Vorlage)

#### 3.6 Compliance-Prüfung

**Checkliste vor Finalisierung**:
- [ ] Keine personenbezogenen Daten (DSGVO)
- [ ] Keine vertraulichen System-Informationen (IT-Sicherheit)
- [ ] Kunden-Logos und -Referenzen genehmigt
- [ ] Marketing-Claims geprüft (nur genehmigte Aussagen)
- [ ] Branchenspezifische Compliance beachtet (BaFin, HIPAA, etc.)
- [ ] Footer vollständig: © Ratiodata SE + Atruvia AG
- [ ] Rechtschreibung und Fachbegriffe korrekt
- [ ] Barrierefreiheit: Kontraste, Schriftgrößen

**Bei Finanzsektor-Präsentationen zusätzlich**:
- [ ] BaFin-Disclaimer im Footer (wenn erforderlich)
- [ ] Keine ungenehmigten Performance-Claims
- [ ] Regulatorische Hinweise korrekt

**Bei Healthcare-Präsentationen zusätzlich**:
- [ ] HIPAA/GDPR-Compliance
- [ ] Keine Patientendaten (auch nicht anonymisiert ohne Genehmigung)
- [ ] Medizinprodukte-Regulierung beachtet

#### 3.7 Qualitätssicherung

**Visuelle Prüfung**:
- [ ] Alle Texte vollständig sichtbar (kein Overflow)
- [ ] Bilder in hoher Qualität (mindestens 150 DPI)
- [ ] Farben konsistent (Ratiodata-Palette)
- [ ] Schriftarten konsistent (Segoe UI/Open Sans)
- [ ] Abstände einheitlich
- [ ] Keine Rechtschreibfehler

**Technische Prüfung**:
```python
# Präsentation auf Fehler prüfen
from pptx import Presentation

prs = Presentation('workspace/ratiodata-presentation.pptx')

# Anzahl Folien
print(f"Anzahl Folien: {len(prs.slides)}")

# Prüfe jede Folie
for i, slide in enumerate(prs.slides):
    print(f"\n--- Folie {i+1} ---")
    
    # Prüfe auf leere Text-Boxen
    for shape in slide.shapes:
        if shape.has_text_frame:
            if not shape.text.strip():
                print(f"⚠️ WARNUNG: Leere Text-Box auf Folie {i+1}")
    
    # Prüfe auf fehlende Bilder
    # ... weitere Checks
```

### 4. HTML2PPTX Workflow (für komplexe Fälle)

**Nur verwenden, wenn unbedingt nötig!**

Für sehr komplexe Layouts oder mehr als 30 Folien:

```python
from pptx_builder import create_presentation, add_slide, apply_ratiodata_branding

# Erstelle Präsentation programmatisch
prs = create_presentation()

# Füge Ratiodata-Branding hinzu
apply_ratiodata_branding(prs, 
    primary_color='#0066CC',
    secondary_color='#00A3E0',
    accent_color='#003D82',
    logo_path='assets/logo-ratiodata.png'
)

# Erstelle Folien mit HTML-ähnlicher Syntax
slide1 = add_slide(prs, 'title', 
    title='Managed Services für Banken',
    subtitle='Ihre IT-Sicherheit in den besten Händen',
    presenter='Max Mustermann'
)

# ... weitere Folien

prs.save('workspace/ratiodata-complex-presentation.pptx')
```

## Ratiodata-spezifische Best Practices

### Für Vertrieb (Sales)
- **Nutzenorientiert**: ROI, TCO, Business Value hervorheben
- **Referenzen**: Erfolgsgeschichten und Case Studies einbauen (mit Genehmigung!)
- **Produkt-USPs**: Ratiodata-Alleinstellungsmerkmale betonen
- **Call-to-Action**: Klare nächste Schritte definieren

**Beispiel-Phrasen**:
- "Über 50 Jahre Erfahrung als verlässlicher IT-Partner"
- "Systemhauspartner der Genossenschaftlichen FinanzGruppe"
- "Mehrfach ausgezeichnet als Innovator des Jahres"

### Für Marketing
- **Brand-konsistent**: Immer Ratiodata CI einhalten
- **Zielgruppen-gerecht**: Sprache an Branche anpassen
- **Storytelling**: Kundenprobleme → Ratiodata Lösungen
- **Visuals**: Hochwertige Bilder und Infografiken

### Für Service & Support
- **Prozess-orientiert**: Klare Abläufe und SLAs darstellen
- **Incident Management**: Transparenz über Prozesse
- **Response Times**: Reaktionszeiten und Verfügbarkeiten
- **Eskalationswege**: Klar definierte Ansprechpartner

**Service-Level-Darstellung**:
- Basic: 8×5 Support, Reaktionszeit 4h
- Professional: 24×7 Support, Reaktionszeit 1h
- Enterprise: Dedicated Team, Reaktionszeit 15min

### Für Software/Produktmanagement
- **Feature-fokussiert**: Neue Features und Vorteile hervorheben
- **Roadmap**: Transparenz über Produkt-Entwicklung
- **User Stories**: Anwenderfälle konkret beschreiben
- **Release Notes**: Änderungen und Verbesserungen strukturiert

### Für Hardware-Entwicklung
- **Technische Specs**: Detaillierte Produktspezifikationen
- **Competitive Analysis**: Marktvergleiche (mit Compliance-Check!)
- **Quality Assurance**: Testkonzepte und Zertifizierungen
- **Partner-Logos**: Hersteller-Kooperationen (mit Genehmigung)

## Fehlervermeidung

### Häufige Fehler

**1. Falsche Folien-Indizierung**
❌ Falsch: `prs.slides[1]` für erste Folie  
✅ Richtig: `prs.slides[0]` (0-basiert!)

**2. Logo fehlt oder falsch platziert**
❌ Falsch: Logo vergessen oder verzerrt  
✅ Richtig: Logo aus Vorlage übernehmen, nie manuell skalieren

**3. Farben außerhalb der Palette**
❌ Falsch: Zufällige Hex-Codes verwenden  
✅ Richtig: Nur Ratiodata-Palette (#0066CC, #00A3E0, #003D82, #00AA4F, #FF8C00)

**4. Atruvia AG im Footer vergessen**
❌ Falsch: "© 2025 Ratiodata SE"  
✅ Richtig: "© 2025 Ratiodata SE | Eine Tochtergesellschaft der Atruvia AG"

**5. Compliance-Verstöße**
❌ Falsch: Kundendaten ohne Genehmigung, Wettbewerber-Bashing  
✅ Richtig: `compliance-guidelines.md` prüfen, Legal konsultieren

### Debug-Tipps

```python
# Präsentation debuggen
import logging
logging.basicConfig(level=logging.DEBUG)

# Überprüfe Vorlage vor Duplikation
prs = Presentation('assets/template.pptx')
print(f"Anzahl Vorlagen-Folien: {len(prs.slides)}")

for i, slide in enumerate(prs.slides):
    print(f"\nFolie {i}:")
    for shape in slide.shapes:
        if shape.has_text_frame:
            print(f"  Text: {shape.text[:50]}...")  # Erste 50 Zeichen
        elif hasattr(shape, 'image'):
            print(f"  Bild: {shape.image.filename}")
```

## Zusammenfassung

✅ **Immer Design-System und Compliance-Richtlinien laden**  
✅ **Vorlage-basiert arbeiten (90% der Fälle)**  
✅ **Inventar erstellen vor Duplikation**  
✅ **0-basierte Indizierung beachten!**  
✅ **Ratiodata CI strikt einhalten**  
✅ **Atruvia AG im Footer nicht vergessen**  
✅ **Compliance-Checkliste vor Finalisierung**  
✅ **Qualitätssicherung durchführen**

## Support & Fragen

Bei Problemen:
1. **Skill-Owner kontaktieren**: [Name des Skill-Verantwortlichen]
2. **IT-Support**: Ticket erstellen
3. **Legal/Compliance**: Bei Unsicherheiten bzgl. Inhalten
4. **Marketing**: Bei Fragen zum Branding

---

**Hinweis**: Dieser Skill wurde entwickelt für die ADG KI-Community bei Ratiodata SE.
```

---

## Schritt 6: Skill paketieren und validieren

### 6.1 Skill validieren

Bevor Sie paketieren, validieren Sie den Skill:

```bash
# Navigiere zum Skill-Verzeichnis
cd /home/claude/ratiodata-branded-deck

# Validiere Struktur
python /mnt/skills/public/skill-creator/scripts/validate_skill.py .
```

**Was wird geprüft**:
- ✅ SKILL.md vorhanden und korrekt formatiert?
- ✅ Frontmatter valid?
- ✅ Alle referenzierten Dateien vorhanden?
- ✅ Assets im korrekten Ordner?
- ✅ Keine verdächtigen oder zu großen Dateien?

### 6.2 Skill paketieren

Wenn Validierung erfolgreich:

```bash
# Erstelle .skill Datei
python /mnt/skills/public/skill-creator/scripts/package_skill.py ratiodata-branded-deck

# Ausgabe: ratiodata-branded-deck.skill
```

**Optional**: Umbenennen zu .zip für einfacheres Teilen:
```bash
cp ratiodata-branded-deck.skill ratiodata-branded-deck.zip
```

### 6.3 Skill-Paket herunterladen

```
Bitte kopiere ratiodata-branded-deck.skill nach /mnt/user-data/outputs/ 
damit ich es herunterladen kann.
```

---

## Schritt 7: Installation und Testing

### 7.1 Skill installieren

**In Ihrem KI-Tool**:
1. Öffnen Sie die Skills-Verwaltung
2. Klicken Sie auf "Upload Skill" oder "Skill hochladen"
3. Wählen Sie `ratiodata-branded-deck.skill`
4. Bestätigen Sie die Installation

**Alternative (Admin-Installation)**:
```bash
# Für teamweite Bereitstellung
cp ratiodata-branded-deck.skill /mnt/skills/user/
```

### 7.2 Skill aktivieren

Nach Installation:
1. Gehen Sie zu Einstellungen → Skills
2. Finden Sie "ratiodata-branded-deck"
3. Aktivieren Sie den Skill
4. Bestätigen Sie mit "Speichern"

### 7.3 Erster Test

**Test 1: Einfache Kundenpräsentation**

```
Erstelle eine Ratiodata-Präsentation für einen Bankkunden:

Titel: "Managed Services für die Sparkasse Norddeutschland"
Folien: 8
Inhalt:
- Titelfolie mit Ratiodata CI
- Über Ratiodata (Firmenprofil)
- Herausforderungen im Bankensektor
- Unsere Managed Services Lösung (Service-Level-Matrix)
- IT-Sicherheit & Compliance (BaFin-konform)
- Referenzen (anonymisiert)
- Technologie-Stack
- Call-to-Action mit Kontaktdaten
```

**Was zu prüfen**:
- [ ] Skill wird automatisch aktiviert (ohne explizite Nennung)
- [ ] Ratiodata CI wird korrekt angewendet (Farben, Logo)
- [ ] Atruvia AG erscheint im Footer
- [ ] Banking-spezifische Compliance-Hinweise enthalten
- [ ] Folien-Layouts aus Vorlage verwendet
- [ ] Präsentation ist vollständig und fehlerfrei

**Test 2: Service-Dokumentation**

```
Erstelle eine interne Service-Dokumentation im Ratiodata CI:

Titel: "IT-Support SLA - Q1 2025"
Folien: 5
Inhalt:
- Titelfolie (intern)
- Übersicht Service-Levels (Tabelle)
- Response Times nach Priorität
- Eskalationsprozess
- Kontakte und Ansprechpartner
```

**Was zu prüfen**:
- [ ] Interne Vorlage wird verwendet (falls vorhanden)
- [ ] Service-Level-Matrix korrekt dargestellt
- [ ] Prozessdiagramme oder Flowcharts integriert
- [ ] Keine vertraulichen Informationen in unsicheren Bereichen

**Test 3: Healthcare-Präsentation**

```
Erstelle eine Präsentation für einen Healthcare-Kunden:

Titel: "IT-Lösungen für moderne Kliniken"
Branche: Healthcare
Folien: 10
Compliance: DSGVO, HIPAA-bewusst

Inhalt:
- Titelfolie
- Herausforderungen im Gesundheitswesen
- Ratiodata Healthcare-Lösungen
- Datenschutz & Sicherheit (DSGVO/HIPAA)
- Krankenhaus-IT-Infrastruktur
- Praxisbeispiel (anonymisiert)
- Technologie-Partner
- Implementierungs-Roadmap
- Support & Service
- Nächste Schritte
```

**Was zu prüfen**:
- [ ] Healthcare-spezifische Vorlage verwendet (falls vorhanden)
- [ ] DSGVO/HIPAA-Hinweise integriert
- [ ] Keine Patientendaten (auch nicht als Beispiel)
- [ ] Medizinische Icons und Farbschema passend

### 7.4 Fehlerbehandlung

**Problem 1: Skill wird nicht aktiviert**

```
# Trigger explizit testen
Bitte verwende den ratiodata-branded-deck Skill und erstelle...
```

**Lösung**: 
- Prüfe `description` im Frontmatter auf korrekte Trigger-Begriffe
- Stelle sicher, dass Skill aktiviert ist in den Einstellungen

**Problem 2: Vorlage wird nicht gefunden**

```
Error: FileNotFoundError: assets/template.pptx
```

**Lösung**:
```bash
# Prüfe, ob Vorlage vorhanden ist
ls -la ratiodata-branded-deck/assets/

# Kopiere Vorlage erneut
cp Ratiodata_Template.pptx ratiodata-branded-deck/assets/template.pptx

# Paketiere neu
python /mnt/skills/public/skill-creator/scripts/package_skill.py ratiodata-branded-deck
```

**Problem 3: Farben sind falsch**

**Lösung**:
- Prüfe `design-system.md` auf korrekte Hex-Codes
- Ratiodata-Farben: #0066CC, #00A3E0, #003D82
- Re-validiere und paketiere neu

**Problem 4: Logo fehlt**

**Lösung**:
```bash
# Prüfe Logo-Datei
file ratiodata-branded-deck/assets/logo-ratiodata.png

# Falls fehlt, füge hinzu
cp Ratiodata-Logo.png ratiodata-branded-deck/assets/logo-ratiodata.png

# Aktualisiere design-system.md mit korrektem Pfad
```

---

## Schritt 8: Skill ans Team verteilen

### 8.1 Dokumentation erstellen

Erstellen Sie ein Quick-Start-Guide für Ihr Team:

```markdown
# Ratiodata CI PowerPoint Skill - Quick Start

## Installation

1. Lade `ratiodata-branded-deck.skill` herunter (Link im Intranet)
2. Öffne dein KI-Tool → Einstellungen → Skills
3. Klicke "Upload Skill" und wähle die .skill-Datei
4. Aktiviere "ratiodata-branded-deck"
5. Fertig! Der Skill ist einsatzbereit.

## Verwendung

### Einfache Kundenpräsentation erstellen

```
Erstelle eine Ratiodata-Präsentation für [Kundenname]:
Titel: "[Titel]"
Folien: [Anzahl]
Inhalt: [Beschreibung der gewünschten Folien]
Branche: [Banking/Healthcare/Mittelstand]
```

### Beispiele

**Vertrieb - Pitch-Deck**:
```
Erstelle ein Pitch-Deck für Managed Services im Ratiodata CI:
10 Folien, Zielgruppe: Mittelständisches Unternehmen
```

**Service - SLA-Dokumentation**:
```
Erstelle eine Service-Level-Dokumentation für Q1 2025 im Ratiodata CI
5 Folien, intern
```

**Marketing - Event-Präsentation**:
```
Erstelle eine Präsentation für die IT-Messe Frankfurt im Ratiodata CI
15 Folien, Fokus: Cybersecurity-Lösungen
```

## Wichtige Hinweise

### ✅ Do's
- Immer "Ratiodata CI" oder ähnliche Trigger-Begriffe verwenden
- Branche angeben (Banking, Healthcare, etc.) für spezifische Anpassungen
- Vertraulichkeits-Level definieren (öffentlich, intern, NDA)
- Compliance-Anforderungen nennen

### ❌ Don'ts
- Keine personenbezogenen Daten ohne Anonymisierung
- Keine Kunden-Logos ohne schriftliche Genehmigung
- Keine ungenehmigten Marketing-Claims
- Keine vertraulichen System-Informationen

## Compliance-Checkliste

Vor Finalisierung jeder Präsentation:
- [ ] Keine DSGVO-relevanten Daten
- [ ] Keine IT-Sicherheits-sensiblen Informationen
- [ ] Kunden-Referenzen genehmigt
- [ ] Atruvia AG im Footer vorhanden
- [ ] Branchenspezifische Compliance beachtet

## Support

Bei Fragen oder Problemen:
- **Skill-Owner**: [Name, E-Mail]
- **IT-Support**: [Ticket-System-Link]
- **Compliance**: [Legal/Compliance-Kontakt]

## FAQ

**Q: Kann ich die Farben anpassen?**
A: Nein, Ratiodata CI muss strikt eingehalten werden. Bei besonderen Anforderungen kontaktiere Marketing.

**Q: Funktioniert der Skill auch offline?**
A: Nein, eine Internetverbindung ist für KI-Tools erforderlich.

**Q: Wie viele Folien kann ich erstellen?**
A: Empfohlen: 5-20 Folien. Bei mehr als 30 Folien bitte Skill-Owner kontaktieren.

**Q: Kann ich eigene Vorlagen hinzufügen?**
A: Ja, kontaktiere den Skill-Owner für Custom-Templates.
```

### 8.2 Schulung durchführen

**Quick-Start Session** (20 Minuten):

1. **Demo** (5 Minuten):
   - Live-Erstellung einer Beispiel-Präsentation
   - Zeige verschiedene Anwendungsfälle (Vertrieb, Service, Marketing)

2. **Hands-on** (10 Minuten):
   - Jeder Teilnehmer erstellt eine Test-Präsentation
   - Verschiedene Szenarien testen:
     - Kundenpräsentation
     - Interne Dokumentation
     - Branchenspezifische Präsentation

3. **Q&A** (5 Minuten):
   - Fragen beantworten
   - Tipps & Tricks teilen
   - Compliance-Hinweise betonen

**Schulungsmaterialien**:
- Dieses Tutorial als PDF
- Video-Tutorial (Screen-Recording der Demo)
- Quick-Start-Guide (siehe oben)
- FAQ-Dokument
- Compliance-Checkliste als Printout

### 8.3 Support-Struktur etablieren

**Skill-Owner definieren**:
- **Verantwortlich**: [Name, Abteilung]
- **Aufgaben**: Updates, Troubleshooting, Feature-Requests
- **Verfügbarkeit**: [Kontaktzeiten]

**Support-Kanäle**:
- **Primär**: Intranet-Wiki oder Confluence-Seite
- **Sekundär**: Slack/Teams-Channel #ratiodata-ki-skills
- **Eskalation**: IT-Support-Ticket-System

**Feedback-Prozess**:
1. **Feature-Requests**: Formular im Intranet
2. **Bug-Reports**: IT-Support-Ticket mit Label "Skill-Bug"
3. **Verbesserungsvorschläge**: Slack/Teams-Channel

**Regelmäßige Reviews**:
- **Monatlich**: Nutzungsstatistiken prüfen
- **Quartalsweise**: Feedback auswerten und Skill updaten
- **Jährlich**: Umfassende Überarbeitung (neue Features, Design-Updates)

### 8.4 Monitoring und Optimierung

**Metriken sammeln**:
- **Nutzungsrate**: Wie oft wird der Skill verwendet?
- **Zufriedenheit**: User-Feedback (1-5 Sterne)
- **Häufigste Anwendungsfälle**: Vertrieb? Marketing? Service?
- **Fehlerrate**: Wie oft gibt es Probleme?

**Optimierung basierend auf Feedback**:

**Beispiel 1: Mehr Vorlagen gewünscht**
```
Feedback: "Ich brauche eine Vorlage für Produktvergleiche"

Lösung:
1. Neue Folie in template.pptx erstellen (Produktvergleich-Layout)
2. Inventar updaten (neue Folie dokumentieren)
3. SKILL.md erweitern (Anwendungsfall hinzufügen)
4. Neu paketieren und verteilen (v1.1)
```

**Beispiel 2: Compliance-Erweiterung**
```
Feedback: "Wir brauchen spezielle Folien für öffentliche Ausschreibungen"

Lösung:
1. compliance-guidelines.md erweitern (Vergaberecht-Sektion)
2. Neue Vorlage erstellen (öffentliche Verwaltung)
3. SKILL.md updaten (neue Trigger für "Ausschreibung", "Vergabe")
4. Schulung für betroffene Teams (Beschaffung, Vertrieb öffentlicher Sektor)
```

---

## Zusammenfassung

Sie haben jetzt gelernt:

✅ **Konzept**: Was Skills sind und wie sie für Ratiodata funktionieren  
✅ **Vorbereitung**: Design-System für Ratiodata SE dokumentieren  
✅ **Erstellung**: Skill-Struktur aufbauen mit CI-konformen Vorlagen  
✅ **Compliance**: DSGVO, IT-Sicherheit und branchenspezifische Anforderungen integrieren  
✅ **Paketierung**: Skill validieren und als .skill File paketieren  
✅ **Installation**: Skill hochladen, aktivieren und testen  
✅ **Testing**: Verschiedene Anwendungsfälle prüfen (Banking, Healthcare, etc.)  
✅ **Rollout**: Skill ans Team verteilen, schulen und supporten  
✅ **Optimierung**: Feedback sammeln und Skill kontinuierlich verbessern

### Nächste Schritte für Ratiodata

1. **Starten Sie klein**: 
   - Erstellen Sie zuerst einen Basis-Skill mit Standard-Vorlage
   - Testen Sie mit einer Pilotgruppe (z.B. Vertrieb oder Marketing)

2. **Iterieren Sie**: 
   - Sammeln Sie Feedback aus echten Anwendungsfällen
   - Erweitern Sie Vorlagen basierend auf Bedarf
   - Optimieren Sie Compliance-Richtlinien

3. **Erweitern Sie**: 
   - Fügen Sie branchenspezifische Vorlagen hinzu (Banking, Healthcare, Verwaltung)
   - Integrieren Sie Abteilungs-spezifische Layouts (Vertrieb, Service, Hardware)
   - Erstellen Sie Custom-Skills für spezielle Anwendungsfälle

4. **Skalieren Sie**: 
   - Rollen Sie den Skill unternehmensweit aus
   - Schulen Sie alle relevanten Abteilungen
   - Etablieren Sie Best Practices und Guidelines

### Erweiterte Anwendungsfälle

**Skill-Varianten für verschiedene Bereiche**:
- `ratiodata-sales-deck`: Spezialisiert auf Vertriebspräsentationen
- `ratiodata-service-docs`: Für Service-Dokumentationen und SLAs
- `ratiodata-technical-specs`: Technische Spezifikationen und Produktdokumentationen
- `ratiodata-banking-compliance`: Speziell für regulierte Finanzsektor-Präsentationen

**Integration mit anderen Tools**:
- Export zu Canva für weitere Bearbeitung
- Integration mit CRM für automatische Kundendaten (DSGVO-konform!)
- Anbindung an Marketing Automation (HubSpot, etc.)

### Weitere Ressourcen

- **Skill Creator Dokumentation**: `/mnt/skills/public/skill-creator/SKILL.md`
- **PPTX Skill Dokumentation**: `/mnt/skills/public/pptx/SKILL.md`
- **Ratiodata Intranet**: [Link zur internen Skill-Dokumentation]
- **ADG KI-Community**: [Link zum internen KI-Forum oder Slack-Channel]
- **Compliance-Team**: [Kontaktdaten für Fragen zu DSGVO, IT-Sicherheit]

---

## Anhang: Vollständiges Beispiel für Ratiodata

### Beispiel: Komplettes `ratiodata-branded-deck/` für Service-Präsentation

```
ratiodata-branded-deck/
├── SKILL.md (siehe Schritt 5.2)
├── assets/
│   ├── template.pptx (Ratiodata CI-Vorlage)
│   ├── logo-ratiodata.png (Hauptlogo)
│   └── logo-atruvia.png (Für Footer)
└── references/
    ├── design-system.md (siehe Schritt 2.2)
    └── compliance-guidelines.md (siehe Schritt 4.3)
```

### Beispiel-Anfrage und erwartetes Ergebnis

**Benutzer-Anfrage**:
```
Erstelle eine Ratiodata-Präsentation für einen neuen Managed Services Kunden:

Kunde: Sparkasse Ostsee (Finanzsektor)
Titel: "Managed Services für zukunftssichere Banken-IT"
Folien: 12
Vertraulichkeit: NDA

Inhalt:
1. Titelfolie mit Ratiodata & Atruvia Branding
2. Über Ratiodata SE (Firmenprofil, FinanzGruppe)
3. Herausforderungen moderner Banken-IT
4. Unsere Managed Services (Service-Level-Matrix: Basic, Professional, Enterprise)
5. IT-Sicherheit & Compliance (BaFin, ISO 27001)
6. Cybersecurity-Lösungen
7. 24/7 Monitoring & Support
8. Disaster Recovery & Business Continuity
9. Success Story (anonymisiert: Sparkasse Norddeutschland)
10. Technologie-Partner (Microsoft, Cisco, etc.)
11. Implementierungs-Roadmap (3 Phasen)
12. Kontakt & nächste Schritte

Besondere Anforderungen:
- BaFin-konforme Darstellung
- Keine vertraulichen Kundendaten
- Atruvia AG prominent im Footer
- Banking-spezifische Icons und Farbschema (konservativ)
```

**Erwartetes Ergebnis**:
- ✅ 12 Folien im Ratiodata CI (Farben: #0066CC, #00A3E0, #003D82)
- ✅ Banking-spezifische Vorlage verwendet (gedämpftere Farben)
- ✅ Ratiodata Logo auf allen Folien (außer Titelfolie)
- ✅ Atruvia AG Logo im Footer jeder Folie
- ✅ Footer-Text: "© 2025 Ratiodata SE | Eine Tochtergesellschaft der Atruvia AG | Systemhauspartner der Genossenschaftlichen FinanzGruppe"
- ✅ BaFin-Compliance-Hinweis auf relevanten Folien
- ✅ Service-Level-Matrix mit 3 Tiers
- ✅ Anonymisierte Success Story (keine echten Kundendaten)
- ✅ NDA-Vermerk auf Titelfolie
- ✅ Professionelles, bankentaugliches Design

### Beispiel-Output-Qualität

**Folie 1: Titelfolie**
```
[Gradient-Header: #0066CC → #0052A3]
[Ratiodata Logo: zentriert, 200px Breite]

Managed Services für zukunftssichere Banken-IT
Ihre IT-Sicherheit in den besten Händen

[Atruvia AG Logo: klein, unten rechts]
[Footer: NDA - Vertraulich | Für Sparkasse Ostsee]
[Gradient-Trennlinie: 3px, am unteren Rand]
```

**Folie 4: Service-Level-Matrix**
```
[Ratiodata Logo: oben rechts, 140px]

Managed Services – Maßgeschneidert für Ihre Bank

[Tabelle: 3 Spalten]
-----------------------------------------------------
| Basic           | Professional      | Enterprise    |
-----------------------------------------------------
| 8×5 Support     | 24×7 Support      | 24×7 + Dedicated |
| Reaktion: 4h    | Reaktion: 1h      | Reaktion: 15min  |
| Monitoring      | + Proaktiv        | + Strategic Advisor |
| ab 2.500€/Monat | ab 5.000€/Monat   | Individuell      |
-----------------------------------------------------

[Footer: © 2025 Ratiodata SE | Atruvia AG Tochter | Seite 4]
```

---

## Abschluss

Dieser Ratiodata-spezifische CI-PowerPoint-Skill ermöglicht es Ihrem Team:

🚀 **Effizienz**: Präsentationen in Minuten statt Stunden erstellen  
🎨 **Konsistenz**: Einheitliches Ratiodata CI über alle Abteilungen  
🔒 **Compliance**: Automatische Einhaltung von DSGVO, IT-Sicherheit und Branchen-Regulierungen  
📊 **Qualität**: Professionelle, fehlerfreie Präsentationen auf Knopfdruck  
🤝 **Teamwork**: Wiederverwendbare Templates für das gesamte Unternehmen  

**Starten Sie jetzt** und bringen Sie Ihre Präsentationen auf das nächste Level!

Bei Fragen oder Unterstützungsbedarf wenden Sie sich an die ADG KI-Community.

---

**Ein Tutorial der ADG KI-Community**

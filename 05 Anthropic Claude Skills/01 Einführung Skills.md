# 🎯 KI Skills - Einfach erklärt

**Für Mitarbeiter der Ratiodata SE - Praktischer Einstieg für alle Abteilungen**

---

## 💡 Was sind KI Skills?

Stellen Sie sich vor, Sie haben für jede wiederkehrende Aufgabe eine **perfekt vorbereitete Arbeitsvorlage** - genau das sind Skills! Sie sind **wiederverwendbare Anleitungen**, die Ihr KI-Assistent automatisch verwendet, wenn Sie etwas Bestimmtes von ihm möchten.

### 🔄 Der Skills-Workflow

```
┌─────────────┐      ┌─────────────┐      ┌─────────────┐      ┌─────────────┐
│     👤      │      │     🤖      │      │     📚      │      │     ✨      │
│             │      │             │      │             │      │             │
│ Sie fragen  │  →   │  Ihr KI-    │  →   │ Skill lädt  │  →   │  Ergebnis   │
│             │      │ Assistent   │      │    Ihre     │      │             │
│  "Erstelle  │      │  erkennt    │      │  Vorlagen   │      │  Perfekt    │
│ Produkt-    │      │ relevantes  │      │             │      │ formatiert! │
│  datenblatt"│      │    Skill    │      │             │      │             │
└─────────────┘      └─────────────┘      └─────────────┘      └─────────────┘
```

---

## 🏗️ Skill-Struktur (vereinfacht)

```
📁 Meine Skills/
├── 📄 Produktdatenblatt-Skill/
│   └── SKILL.md (Ihre Vorlagen & Standards)
│
├── 📄 Kundenpräsentation-Skill/
│   └── SKILL.md (Ihre Präsentationsregeln)
│
└── 📄 Servicedokumentation-Skill/
    └── SKILL.md (Ihre Ticket-Templates)
```

**Wichtig:** Skills sind einfache Textdateien (Markdown), die Ihre Regeln, Vorlagen und Best Practices enthalten.

---

## 🎯 Vorteile für Ratiodata-Teams

### ⚡ Zeitersparnis
Keine wiederholten Anweisungen mehr. Ihr KI-Assistent kennt Ihre Standards automatisch.

### 🎨 Konsistenz
Alle Dokumente folgen dem Ratiodata Corporate Design und unserer Qualität.

### 🔄 Wiederverwendbar
Einmal erstellt, in jedem Projekt nutzbar - kein Copy & Paste mehr.

### 👥 Team-fähig
Teilen Sie Best Practices mit Kollegen durch Skills - Innovation durch Wissensaustausch.

---

## 💼 Praktische Beispiele für Ratiodata-Teams

### 📝 Beispiel 1: Produktdatenblatt-Skill (Vertrieb & Marketing)

**Sie erstellen ein Skill mit Ihren Vorgaben:**

- ✅ Ratiodata-Tonalität und Corporate Wording
- ✅ Technische Spezifikationen strukturiert
- ✅ Sicherheits- und Compliance-Hinweise
- ✅ USPs und Differenzierungsmerkmale
- ✅ Zielgruppengereche Formulierungen

**Ergebnis:** Sie sagen nur "Erstelle Produktdatenblatt für Managed Firewall Service" - der KI-Assistent nutzt automatisch Ihr Skill!

---

### 🎤 Beispiel 2: Kundenpräsentations-Skill (Vertrieb & Presales)

**Einmalige Definition Ihrer Präsentations-Standards:**

- ✅ Ratiodata-Storyline (Problem → Lösung → Wert)
- ✅ Technische Tiefe angepasst an Zielgruppe
- ✅ Sicherheit und Compliance prominent platziert
- ✅ ROI-Berechnungen und Business Cases
- ✅ Referenzen aus regulierten Branchen

---

### 🛠️ Beispiel 3: Service-Dokumentations-Skill (Service & Support)

**Für Tickets, Incidents und Wissensdatenbank:**

- ✅ Strukturierte Problemanalyse
- ✅ Lösungsschritte dokumentieren
- ✅ Eskalationspfade berücksichtigen
- ✅ SLA-relevante Informationen
- ✅ Kundenkommunikation professionell

---

### 📊 Beispiel 4: Requirements-Engineering-Skill (Software/Produktmanagement)

**Für User Stories und Spezifikationen:**

- ✅ Strukturierte User Stories (As a... I want... So that...)
- ✅ Akzeptanzkriterien definieren
- ✅ Technische Machbarkeit berücksichtigen
- ✅ Sicherheitsanforderungen integrieren
- ✅ Testfälle ableiten

---

## 🆚 Skills vs. normale Prompts

| Aspekt | ❌ Normale Prompts | ✅ Mit Skills |
|--------|-------------------|---------------|
| **Wiederverwendung** | Jedes Mal neu eingeben | Automatisch geladen |
| **Konsistenz** | Kann variieren | Immer gleicher Standard |
| **Teamarbeit** | Schwer teilbar | Einfach im Team nutzbar |
| **Aktualisierung** | Überall manuell ändern | Einmal ändern, überall aktiv |
| **Komplexität** | Begrenzt durch Nachrichtenlänge | Kann sehr umfangreich sein |

---

## 📊 Technische Details: Wie Skills funktionieren

### Der 7-Schritte-Prozess:

1. **Mount Points** - Skills liegen in `/mnt/skills/` (schreibgeschützt)
2. **Skill Discovery** - KI scannt verfügbare Skills beim Chat-Start
3. **Metadata Parsing** - Jedes Skill hat ein `SKILL.md` mit Beschreibung
4. **Pattern Matching** - KI erkennt, welches Skill relevant ist
5. **Dynamic Loading** - KI lädt das passende SKILL.md
6. **Context Injection** - Skill-Anweisungen werden dem Kontext hinzugefügt
7. **Instruction Following** - KI arbeitet nach den Skill-Vorgaben

---

## 🚀 Erste Schritte - So starten Sie:

### Schritt 1: Wiederkehrende Aufgabe identifizieren
z.B. Produktdatenblätter, Kundenpräsentationen, Servicedokumentation, Technical Specs

### Schritt 2: Den "Skill Creator" nutzen
Ihr KI-Assistent hat einen eingebauten Assistenten, der Ihnen beim Erstellen hilft

**So aktivieren Sie den Skill Creator:**
1. Gehen Sie zu **Einstellungen** → **Capabilities** → **Skills**
2. Aktivieren Sie das Skill **"skill-creator"**
3. Klicken Sie auf **"Try in chat"**

### Schritt 3: Ihre Standards definieren
- Tonalität (professionell, technisch versiert, kundenorientiert)
- Format (Struktur, Gliederung)
- Pflichtangaben (Sicherheit, Compliance, Datenschutz)
- Corporate Identity (Ratiodata-Werte, Design)

### Schritt 4: Skill hochladen
- Über **Einstellungen** → **Capabilities** → **Upload Skill**
- Dateiformat: `.skill` (wird vom Skill Creator erzeugt)

### Schritt 5: Testen und verfeinern
Probieren Sie es aus und passen Sie nach Bedarf an

---

## 💡 Profi-Tipp für Ratiodata-Teams

### Erstellen Sie ein "Master-Ratiodata-Skill"

Ein zentrales Skill mit allen wichtigen Infos über Ratiodata:

```
╔════════════════════════════════════════════════════════════╗
║         📋 Master-Ratiodata-Skill Inhalt                   ║
╠════════════════════════════════════════════════════════════╣
║                                                            ║
║  🏢 Unternehmenswerte                                      ║
║     → Innovation, Zuverlässigkeit, Qualität, Sicherheit   ║
║     → Kundenorientierung, Partnerschaftlichkeit           ║
║                                                            ║
║  💎 Unsere Expertise                                       ║
║     → IT-Systemhaus mit 50+ Jahren Erfahrung              ║
║     → Managed Services & Cloud-Lösungen                   ║
║     → Bankentechnologie & regulierte Branchen             ║
║     → Cybersecurity & Compliance                          ║
║     → Modern Workplace & Collaboration                    ║
║                                                            ║
║  📍 Standorte und Struktur                                 ║
║     → Teil der Atruvia-Gruppe                             ║
║     → Systemhauspartner der FinanzGruppe                  ║
║     → Bundesweite Präsenz                                 ║
║                                                            ║
║  🎯 Zielgruppen                                            ║
║     → Banken und Sparkassen                               ║
║     → Healthcare-Organisationen                           ║
║     → Öffentliche Verwaltung                              ║
║     → Mittelständische Unternehmen                        ║
║                                                            ║
║  ⭐ Differenzierungsmerkmale                               ║
║     → IT-Sicherheit "Made in Germany"                     ║
║     → Regulatorische Compliance (BaFin, DSGVO)            ║
║     → Zertifizierte Qualitätsstandards (ISO 27001)        ║
║     → 24/7 Support & Service Excellence                   ║
║                                                            ║
╚════════════════════════════════════════════════════════════╝
```

→ Ihr KI-Assistent kann dann **jede Aufgabe** mit diesem Hintergrundwissen bearbeiten!

---

## 📈 Wann Skills sinnvoll sind

### Ideal für:

✅ **Web UI Umgebung** (kein API-Zugriff)  
✅ **Häufig wechselnde Anforderungen** (Skills sofort aktualisierbar)  
✅ **Team-Kollaboration** (Skills sind teilbare Dateien)  
✅ **Multiple Spezial-Kontexte** (verschiedene Skills pro Aufgabe)  
✅ **Deterministische Ausgabestruktur** (Skills erzwingen Templates)

### Weniger geeignet für:

❌ **API-Aufrufe mit hoher Frequenz** (System Prompts sind schneller)  
❌ **Dynamisches Verhalten basierend auf Runtime-State** (Skills sind statisch)  
❌ **Komplexe Logik mit Bedingungen** (Skills haben keine Programmierung)  
❌ **Secrets oder Credentials** (Skills sind von KI lesbar)  
❌ **Echtzeit-Datenzugriff** (Skills können keine APIs aufrufen)

### Gemessener Overhead:

- **Skill Loading:** 80-150ms Durchschnitt
- **Context Consumption:** 200-2.000 Tokens je nach Skill-Größe
- **Pattern Matching:** ~20-40ms (vernachlässigbar)
- **Total Latency Impact:** 100-190ms pro geladenem Skill

---

## 🛠️ Skill-Erstellung: Schritt-für-Schritt

### Option A: Mit dem Skill Creator (Empfohlen für Anfänger)

```
Sie: "Hey - ich habe den skill-creator aktiviert. 
     Erstelle mir ein Skill für Produktdatenblätter."

KI-Assistent: [Stellt Ihnen Fragen zu Ihren Anforderungen]

Sie: [Beantworten die Fragen]

KI-Assistent: [Erstellt das Skill und bietet Download an]
```

### Option B: Manuell erstellen (Für Fortgeschrittene)

**Dateistruktur:**
```markdown
---
name: produktdatenblatt-skill
description: Erstellt professionelle Produktdatenblätter für 
             IT-Lösungen nach Ratiodata Standards
---

# Produktdatenblatt-Skill für Ratiodata SE

## Tonalität
- Professionell, aber verständlich
- Technisch versiert ohne Buzzword-Bingo
- Kundennutzen vor Features
- Sicherheit und Compliance betonen

## Pflichtangaben
- Produktbezeichnung und Version
- Technische Spezifikationen
- Sicherheitsfeatures
- Compliance-Zertifizierungen
- Support-Level und SLA
- Lizenzmodell

## Struktur
1. Executive Summary (2-3 Sätze Kundennutzen)
2. Technische Übersicht (Architektur, Features)
3. Sicherheit & Compliance
4. Integration & Kompatibilität
5. Support & Services
6. Wirtschaftlichkeit (TCO, ROI)

## Key Benefits (immer einbauen)
- Höchste IT-Sicherheitsstandards
- Regulatorische Compliance (DSGVO, BaFin)
- 24/7 Professional Support
- Zertifizierte Qualität (ISO 27001)
- Made in Germany
- Nahtlose Integration in bestehende Infrastruktur

## Beispiel-Formulierungen
- "Maximale Sicherheit für kritische Geschäftsprozesse"
- "Compliance-konform nach aktuellen Standards"
- "Bewährt in regulierten Branchen"
- "Investitionssicherheit durch langfristige Roadmap"
```

---

## 🎯 Konkrete Skill-Ideen für Ratiodata-Teams

### 1. 📊 Vertrieb: Angebots-Skill
**Trigger:** "Erstelle Angebot", "Kundenangebot für..."

**Inhalt:**
- Ratiodata-Angebotstruktur
- Preismodelle und Lizenzierung
- Leistungsbeschreibungen
- SLA-Definitionen
- Vertragsbedingungen

---

### 2. 🎤 Presales: Solution-Design-Skill
**Trigger:** "Erstelle Solution Design", "Architektur-Vorschlag"

**Varianten:**
- Infrastructure-as-a-Service
- Managed Security Services
- Cloud Migration Scenarios
- Hybrid Cloud Architekturen
- Modern Workplace Konzepte

---

### 3. 📱 Marketing: Content-Creation-Skill
**Trigger:** "LinkedIn Post", "Blog-Artikel", "Newsletter-Beitrag"

**Plattform-spezifisch:**
- LinkedIn (B2B IT-Entscheider)
- Blog-Artikel (SEO-optimiert)
- Newsletter (Kundenbindung)
- Case Studies (Referenzen)

---

### 4. 💻 Software: User-Story-Skill
**Trigger:** "Erstelle User Story", "Feature-Spezifikation"

**Generiert:**
- Strukturierte User Stories
- Akzeptanzkriterien
- Technische Constraints
- Sicherheitsanforderungen

---

### 5. 🛠️ Service: Incident-Report-Skill
**Trigger:** "Dokumentiere Incident", "Service-Report"

**Enthält:**
- Problemanalyse
- Root Cause Analysis
- Lösungsschritte
- Präventivmaßnahmen
- Lessons Learned

---

### 6. 🔧 Hardware: Technical-Spec-Skill
**Trigger:** "Technische Spezifikation", "Hardware-Datenblatt"

**Analysiert:**
- Produktspezifikationen
- Kompatibilitätsmatrix
- Leistungsparameter
- Zertifizierungen
- Einsatzszenarien

---

## 📈 Best Practices für Skills

### DO's ✅

- **Spezifisch sein:** Je detaillierter, desto besser die Ergebnisse
- **Beispiele einbauen:** Zeigen Sie konkrete Formulierungen
- **Regelmäßig aktualisieren:** Skills leben von Aktualität
- **Im Team teilen:** Kollegen profitieren von Ihren Skills
- **Testen:** Probieren Sie das Skill aus und verfeinern Sie es

### DON'Ts ❌

- **Zu generisch:** "Schreibe professionell" ist zu vage
- **Sensible Daten:** Keine Passwörter, Credentials oder Kundendaten
- **Zu komplex:** Lieber mehrere kleine Skills als ein riesiges
- **Widersprüche:** Achten Sie auf konsistente Anweisungen
- **Compliance ignorieren:** DSGVO und Sicherheit immer beachten

---

## 🔒 Sicherheit & Compliance bei Skills

### Wichtige Hinweise für Ratiodata-Mitarbeiter:

⚠️ **Niemals in Skills aufnehmen:**
- Kundendaten (Namen, Adressen, Kontakte)
- Zugangsdaten (Passwörter, API-Keys)
- Interne Systemkonfigurationen
- Vertrauliche Geschäftsinformationen
- Personenbezogene Daten

✅ **Skills dürfen enthalten:**
- Allgemeine Vorlagen und Strukturen
- Öffentliche Produktinformationen
- Formatierungsrichtlinien
- Best Practices und Prozesse
- Tonalität und Sprachstil

### DSGVO-Konformität:
- Skills sind im KI-Kontext sichtbar
- Keine personenbezogenen Daten verwenden
- Beispieldaten immer anonymisieren
- Bei Unsicherheit: Datenschutzbeauftragten fragen

---

## 🔍 Troubleshooting

### Problem: Skill wird nicht automatisch geladen

**Lösung:**
1. Prüfen Sie die `description` im SKILL.md - ist sie aussagekräftig?
2. Verwenden Sie eindeutige Trigger-Begriffe in Ihrer Anfrage
3. Erwähnen Sie das Skill explizit: "Nutze mein Produktdatenblatt-Skill"

---

### Problem: Ergebnisse entsprechen nicht den Erwartungen

**Lösung:**
1. Fügen Sie mehr Beispiele ins Skill ein
2. Formulieren Sie Anweisungen klarer und direkter
3. Nutzen Sie Listen und Strukturen statt Fließtext
4. Testen Sie verschiedene Formulierungen

---

### Problem: Skill ist zu lang / verbraucht zu viele Tokens

**Lösung:**
1. Teilen Sie das Skill in mehrere kleinere auf
2. Entfernen Sie redundante Informationen
3. Nutzen Sie prägnante Formulierungen
4. Überlegen Sie, ob alle Infos wirklich nötig sind

---

## 🎓 Weiterführende Ressourcen

### Offizielle Dokumentation
- KI Skills Documentation
- Skill Creator Guide
- Best Practices für Enterprise Skills

### Ratiodata-intern
- IT-Community Channel im Intranet
- KI-Academy Schulungsangebote
- Best-Practice-Sammlung im Sharepoint
- Monatliche KI-Sprechstunden

---

## 📋 Zusammenfassung

### Skills in einem Satz:
**Skills sind wiederverwendbare Wissensbausteine, die Ihr KI-Assistent automatisch lädt, wenn Sie relevante Aufgaben stellen.**

### Die 5 wichtigsten Vorteile:

1. ⚡ **Zeitersparnis** - Keine wiederholten Anweisungen
2. 🎯 **Konsistenz** - Immer gleiche Qualität nach Ratiodata-Standards
3. 👥 **Teamwork** - Teilbar und gemeinsam nutzbar
4. 🔄 **Wartbarkeit** - Zentral aktualisierbar
5. 📊 **Skalierbar** - Beliebig viele Skills kombinierbar

### Ihre nächsten Schritte:

```
┌─────────────────────────────────────────────────┐
│ 1️⃣  Skill Creator aktivieren                    │
│                                                  │
│ 2️⃣  Erstes Skill erstellen                      │
│     (z.B. für Ihre häufigste Aufgabe)           │
│                                                  │
│ 3️⃣  Testen und verfeinern                       │
│                                                  │
│ 4️⃣  Mit Team teilen                             │
│                                                  │
│ 5️⃣  Weitere Skills aufbauen                     │
│     (für verschiedene Anwendungsfälle)          │
└─────────────────────────────────────────────────┘
```

---

## 🎉 Fazit

**Skills verwandeln Ihren KI-Assistenten in einen perfekt eingearbeiteten Ratiodata-Kollegen!**

Statt bei jeder Anfrage alle Details zu erklären, haben Sie einen digitalen Partner, der Ihre Standards, Ihre Tonalität und Ihre Qualitätsansprüche bereits kennt.

Für Ratiodata-Teams bedeutet das:
- ✅ Schnellere Projektumsetzung durch effizientere Prozesse
- ✅ Konsistente Qualität über alle Abteilungen hinweg
- ✅ Mehr Zeit für strategische Aufgaben statt Routinearbeit
- ✅ Innovation durch geteiltes Wissen im Team
- ✅ Höhere Kundenzufriedenheit durch professionelle Outputs

### 💼 Abteilungsspezifische Vorteile:

**Vertrieb & Presales:**
- Schnellere Angebotserstellung
- Konsistente Solution Designs
- Professionelle Kundenpräsentationen

**Marketing:**
- Effiziente Content-Produktion
- SEO-optimierte Texte
- Kanalübergreifende Konsistenz

**Software/Produktmanagement:**
- Strukturierte User Stories
- Klare Feature-Spezifikationen
- Effiziente Dokumentation

**Service:**
- Schnellere Problemlösung
- Professionelle Kundenkommunikation
- Systematische Wissenssicherung

**Hardware-Entwicklung:**
- Präzise technische Specs
- Strukturierte Produktdokumentation
- Effiziente Marktanalysen

---

**Ein Tutorial der ADG KI-Community**

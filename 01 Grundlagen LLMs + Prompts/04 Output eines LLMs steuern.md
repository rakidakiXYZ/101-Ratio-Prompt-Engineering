# Tutorial: KI-Ausgaben strukturieren und optimieren

**Von der Rohausgabe zum präzisen IT-Ergebnis**

---

## Einführung: Was Sie in diesem Tutorial lernen

Dieses Tutorial zeigt Ihnen Schritt für Schritt, wie Sie KI-Ausgaben so steuern, dass sie **strukturiert, professionell und sofort einsetzbar** sind – z. B. für technische Dokumentationen, Produktspezifikationen, Kundenpräsentationen, Marketing-Content oder Service-Dokumentationen.

**Nach diesem Tutorial können Sie:**

* KI-Ausgaben klar strukturieren und effizient nachbearbeiten
* Tonalität, Stil und technische Präzision gezielt steuern
* Texte für unterschiedliche Zielgruppen (Kunden, Management, technische Teams) optimieren
* Typische Fehler erkennen und beheben
* Ihre Prompt-Effizienz um bis zu **80 %** steigern
* Ausgaben DSGVO-konform und sicherheitsbewusst gestalten

**⏱️ Zeitaufwand:** 30-40 Minuten | **📚 Niveau:** Anfänger | **🎯 Ziel:** Professionelle, strukturierte KI-Ausgaben erstellen

---

## Teil 1: Grundlagen der Ausgabestruktur

### 1.1 Das Struktur-Framework für IT-Profis

Jede gute KI-Ausgabe beginnt mit einer klaren Struktur. Diese besteht aus drei Ebenen:

**1. Container** – Hauptabschnitte (z. B. Hintergrund, Technische Spezifikation, Implementierung)
**2. Komponenten** – Unterelemente (z. B. Features, Voraussetzungen, Risiken)
**3. Constraints** – Einschränkungen (z. B. Wortanzahl, Stil, Zielgruppe)

#### Beispiel: Produktbeschreibung für Managed-Services-Angebot

**Version 1 (Basis):**

```
Schreibe über die Vorteile von Managed Services für mittelständische Banken.
```

*Ergebnis: Unstrukturierter Fließtext – schwer weiterverwendbar, zu allgemein.*

---

**Version 2 (Mit Container):**

```
Schreibe über Managed Services für Banken mit folgenden Abschnitten:
- Executive Summary
- Technische Vorteile
- Compliance und Sicherheit
- Business Value
```

*Ergebnis: Bessere Struktur, aber noch zu allgemein für IT-Entscheider.*

---

**Version 3 (Mit Komponenten und IT-Fokus):**

```
Erstelle eine strukturierte Produktbeschreibung für Managed Services im Banking-Sektor:

[Executive Summary]
- 3 Hauptargumente für IT-Entscheider
- 1 Satz Zusammenfassung mit messbarem Nutzen
- Positionierung gegenüber Eigenbetreuung

[Technische Vorteile]
- 24/7-Monitoring und Incident Management (konkrete SLAs)
- Automatisierte Patch-Management-Prozesse
- Redundante Infrastruktur und Ausfallsicherheit (99,9% Verfügbarkeit)
- Integration in bestehende IT-Landschaften (3 Beispiele)

[Compliance und Sicherheit]
- BaFin-konforme Prozesse und Dokumentation
- ISO 27001-zertifizierte Rechenzentren
- DSGVO-konforme Datenverarbeitung
- Regelmäßige Security Audits und Penetrationstests

[Business Value]
- TCO-Optimierung (Einsparungspotenzial in %)
- Skalierbarkeit für Wachstum
- Fokus auf Kerngeschäft statt IT-Betrieb
- Planbare Kosten durch Service-Level-Agreements
```

*Ergebnis: 75 % bessere Nutzbarkeit, sofort als Basis für Angebote oder Präsentationen verwendbar.*

---

### 💡 Praxis-Tipp für Ratiodata-Teams

**Für Vertrieb:** Verwenden Sie strukturierte Ausgaben als Basis für Kundenworkshops und Angebotserstellung. Die klare Gliederung erleichtert die Abstimmung mit Solution Architects.

**Für Marketing:** Strukturierte Content-Vorlagen lassen sich schnell in verschiedene Formate überführen (Blog, Social Media, Case Studies).

**Für Service:** Nutzen Sie das Framework für Wissensdatenbank-Artikel – die Struktur hilft Kunden bei der Selbsthilfe.

---

### Übung 1: Struktur entwickeln

**Aufgabe:** Nehmen Sie ein eigenes Thema aus Ihrem Arbeitsbereich (z. B. Produktspezifikation, Servicebeschreibung, technische Dokumentation) und entwickeln Sie es in drei Versionen wie oben gezeigt.

**Ziel:** Ihre Nachbearbeitungszeit sinkt von Version 1 zu 3 um mindestens 50 %.

**Beispielthemen:**
- Vertrieb: Cybersecurity-Lösung für Industriekunden
- Marketing: Landing Page für Cloud-Migration-Services
- Software: Feature-Dokumentation für neues Release
- Service: Troubleshooting-Guide für häufige Netzwerkprobleme
- Hardware: Produktvergleich verschiedener Server-Konfigurationen

---

## Teil 2: Format-Kontrolle für IT-Dokumentation

### 2.1 Die Format-Palette für IT-Profis

| Format       | Verwendung                             | Beispiel-Prompt                                                           |
| ------------ | -------------------------------------- | ------------------------------------------------------------------------- |
| **Tabelle**  | Systemvergleiche, Feature-Matrix | "Erstelle eine Vergleichstabelle mit Spalten: Feature, Standard, Premium, Enterprise" |
| **Liste**    | Requirements, Checklisten              | "Nummerierte Liste mit max. 8 Punkten, priorisiert nach Wichtigkeit"                                    |
| **Template** | Ticket-Vorlagen, E-Mail-Responses       | "Verwende Platzhalter in {{geschweiften Klammern}} für variable Werte"                       |
| **Markdown** | Technische Dokumentation, READMEs             | "Formatiere in Markdown mit H2-Überschriften und Code-Blöcken"                             |
| **JSON**     | API-Dokumentation, Konfigurationen         | "Ausgabe als JSON-Struktur mit Schema-Validierung"                                   |
| **Diagramm-Code** | Architektur, Prozesse | "Erstelle Mermaid-Syntax für Systemarchitektur-Diagramm" |

---

### 2.2 Beispiel: Onboarding-Dokumentation für neue Service-Mitarbeitende

**Iteration 1 – Einfache Liste:**

```
Liste die wichtigsten Schritte für neue Service-Mitarbeitende auf.
```

**Iteration 2 – Strukturierte Tabelle:**

```
Erstelle eine Onboarding-Tabelle für den IT-Service:
| Woche | Aufgabe | Verantwortlich | Tools/Systeme | Status |
```

**Iteration 3 – Technische Checkliste mit Systemzugriffen:**

```
Onboarding-Checkliste für neue Service-Mitarbeitende im Technical Support:

## Woche 1: System-Setup und Grundlagen
[ ] Zugang zu Ticketsystem (ServiceNow/JIRA) eingerichtet  
[ ] VPN-Zugang und Security-Token konfiguriert  
[ ] Remote-Desktop-Zugriff auf Testsysteme aktiviert  
[ ] Einweisung in Incident-Management-Prozesse (ITIL-konform)  
[ ] Knowledge Base durchgearbeitet (Top 20 Incidents)

## Woche 2–4: Fachliche Vertiefung
[ ] Shadowing bei erfahrenem Kollegen (min. 3 Tickets)  
[ ] Erste eigenständige Ticket-Bearbeitung (Level 1)  
[ ] DSGVO- und IT-Sicherheits-Schulung absolviert  
[ ] Zugang zu Monitoring-Systemen (Nagios/Zabbix)  
[ ] Teilnahme am Team-Meeting und Feedback-Gespräch

## Woche 5–8: Spezialisierung
[ ] Level 2-Support-Freigabe durch Teamleiter  
[ ] Schulung auf spezifische Produkte (z.B. Firewall-Management)  
[ ] Einarbeitung in Eskalationsprozesse  
[ ] Erste On-Call-Bereitschaft mit Mentor

Format:
- Checkboxen [ ] für Tracking
- Zeitrahmen fett markiert  
- Max. 5 Punkte pro Abschnitt
- Am Ende jeder Phase: Erfolgskriterium und Freigabe-Meeting
- Links zu internen Dokumentationen in {{Platzhaltern}}
```

**Ergebnis:** Übersichtlicher, kontrollierbarer Prozess – auch als Vorlage für verschiedene Abteilungen nutzbar.

---

### 🔒 Sicherheitshinweis: Sensible Daten in Prompts

**Wichtig für alle Ratiodata-Mitarbeitenden:**
- Geben Sie KEINE Kundennamen, IP-Adressen oder System-Credentials in KI-Tools ein
- Anonymisieren Sie Beispiele (Kunde A, System X, etc.)
- Verwenden Sie Platzhalter für sensible Informationen
- Prüfen Sie Output vor dem Teilen auf versehentlich enthaltene Daten
- Bei Unsicherheit: Rücksprache mit IT-Sicherheit oder Datenschutzbeauftragten

---

## Teil 3: Stil und Tonalität für IT-Kommunikation steuern

### 3.1 Das Stil-Spektrum für IT-Dienstleister

```
Stil-Parameter für IT-Dokumentation:
- Formalität: [technisch | business-orientiert | kundennah]
- Komplexität: [einfach | mittel | hochspezialisiert]
- Perspektive: [wir | Sie | neutral/technisch]
- Detailgrad: [Executive Summary | Standard | Deep Dive]
- Tonalität: [sachlich | lösungsorientiert | beratend]
```

---

### 3.2 Zielgruppenprofile für Ratiodata

**Beispiel A: Technische Dokumentation (interne Teams)**

```
ZIELGRUPPE:
- Empfänger: Software-Entwickler, System-Engineers, Produktmanager
- Fokus: Technische Präzision, Reproduzierbarkeit, Best Practices

STIL:
- Tonalität: Technisch präzise, objektiv, faktenbasiert
- Länge: 300-500 Wörter (je nach Komplexität)
- Struktur: Problem → Lösung → Implementierung → Testing
- Format: Markdown mit Code-Beispielen

TABUS:
- Keine Marketing-Sprache oder übertriebene Adjektive
- Keine ungenauen technischen Begriffe
- Keine Vermischung von Anforderungen und Implementierung

MUST-HAVES:
- Versionsnummern, System-Requirements
- Konkrete Beispiele mit Code oder CLI-Befehlen
- Verlinkung zu relevanten Dokumentationen
```

---

**Beispiel B: Kundenpräsentation (Vertrieb/Presales)**

```
ZIELGRUPPE:
- IT-Entscheider, C-Level bei mittelständischen Unternehmen
- Fokus: Business Value, ROI, strategische Vorteile

STIL:
- Tonalität: Beratend, lösungsorientiert, vertrauenswürdig
- Perspektive: "Sie profitieren von..." / "Wir bieten..."
- Struktur: Herausforderung → Lösung → Nutzen → Next Steps
- Länge: 150-250 Wörter pro Abschnitt

INTEGRATION:
- Ratiodata-Werte: Innovation, Zuverlässigkeit, Sicherheit
- Konkrete Zahlen: Einsparungen, Performance-Steigerungen
- Referenzen: "Wie bei einem unserer Kunden aus dem Banking-Sektor..."
- Call-to-Action: Workshop, Proof of Concept, Beratungsgespräch

VERMEIDEN:
- Technischer Jargon ohne Erklärung
- Unspezifische Versprechen
- Konkurrenz-Bashing
```

---

**Beispiel C: Service-Dokumentation (Wissensdatenbank)**

```
ZIELGRUPPE:
- Kunden im Self-Service, Support-Mitarbeitende (Level 1)
- Fokus: Schnelle Problemlösung, Schritt-für-Schritt-Anleitung

STIL:
- Tonalität: Klar, unterstützend, präzise
- Perspektive: "Sie" (direkte Ansprache)
- Format: Nummerierte Schritte mit Screenshots/Placeholders
- Länge: 100-200 Wörter + visuelle Elemente

STRUKTUR:
1. Problem-Beschreibung (Was wird gelöst?)
2. Voraussetzungen (Rechte, Software-Versionen)
3. Schritt-für-Schritt-Anleitung (max. 8 Schritte)
4. Überprüfung (Wie erkennt man, dass es funktioniert?)
5. Troubleshooting (Was tun, wenn es nicht klappt?)
6. Weiterführende Informationen (Links zu verwandten Artikeln)

BESONDERHEITEN:
- Warnhinweise bei kritischen Schritten (z.B. Datenverlust-Risiko)
- Zeitangaben ("Dauer: ca. 5 Minuten")
- Schwierigkeitsgrad ("Einfach" / "Fortgeschritten")
```

---

**Beispiel D: Marketing-Content (Website, Social Media)**

```
ZIELGRUPPE:
- Potenzielle Kunden, Interessenten, Partner
- Fokus: Aufmerksamkeit, Interesse wecken, Kompetenz zeigen

STIL:
- Tonalität: Professionell, modern, lösungsorientiert
- Länge: 80-120 Wörter (Social Media), 200-300 Wörter (Blog)
- Struktur: Hook → Mehrwert → Call-to-Action
- Perspektive: "Sie" / "Ihr Unternehmen"

RATIODATA-POSITIONIERUNG:
- Innovation: "Als mehrfach ausgezeichneter IT-Innovator..."
- Erfahrung: "Über 50 Jahre IT-Expertise für den Mittelstand..."
- Sicherheit: "Höchste Security-Standards und Zertifizierungen..."
- Branchen-Expertise: "Spezialisiert auf Banking, Healthcare, Public Sector..."

KANÄLE:
- LinkedIn: Fachlicher, lösungsorientierter Content
- Blog: Ausführliche Erklärungen, Thought Leadership
- Newsletter: Kompakte Updates, News, Events
```

---

### Übung 2: Stil-Transformation

**Aufgabe:** Transformieren Sie eine technische Information (z. B. neue Cloud-Backup-Lösung) in vier Versionen:

1. Für interne Entwickler (technische Spezifikation)
2. Für Vertriebs-Team (Verkaufsargumente)
3. Für Kunden-Self-Service (Anleitung)
4. Für Marketing (Social Media Post)

**Ausgangsmaterial:**
"Unsere neue Cloud-Backup-Lösung bietet automatisierte, inkrementelle Backups mit AES-256-Verschlüsselung, Integration in VMware und Hyper-V, sowie Retention-Policies von 7-365 Tagen."

---

## Teil 4: Qualitätssicherung mit KI

### 4.1 Das Validierungs-Framework für IT-Content

```
[IHRE ANFRAGE]

QUALITÄTSPRÜFUNG:
☐ Sind alle geforderten technischen Details enthalten?  
☐ Stimmt die Tonalität für die Zielgruppe?  
☐ Ist die Länge angemessen (max. X Wörter)?  
☐ Wurden Fachbegriffe korrekt verwendet und ggf. erklärt?  
☐ Enthält der Text einen klaren Handlungsimpuls/Next Step?
☐ Sind Versionsnummern, System-Requirements oder URLs korrekt?

SICHERHEITSPRÜFUNG:
☐ Keine sensiblen Kundendaten enthalten?
☐ Keine internen System-Details oder Credentials?
☐ DSGVO-konform formuliert?
☐ Keine Sicherheitslücken beschrieben, die ausgenutzt werden könnten?

SELBSTPRÜFUNG:
1. Ist die Hauptaussage in 10 Sekunden verständlich?  
2. Könnte ein Kollege aus einer anderen Abteilung damit arbeiten?  
3. Ist der Text frei von unnötigem Marketing-Sprech?
4. Würde ich selbst nach dieser Anleitung vorgehen können?
```

---

### 4.2 Schrittweise Optimierung für IT-Dokumentation

```
Schritt 1: Erste KI-Ausgabe erstellen (mit strukturiertem Prompt)
Schritt 2: Gegen Qualitäts-Checkliste prüfen  
Schritt 3: Technische Präzision validieren (Fachbegriffe, Versionen, Links)
Schritt 4: Zielgruppenspezifische Anpassungen vornehmen
Schritt 5: Sicherheits- und Compliance-Check durchführen
Schritt 6: Endversion in Ratiodata-Standard formatieren (max. 2 Iterationen)
```

---

### ⚠️ Wichtig: Compliance und Regulatorik

Bei Dokumentationen für regulierte Branchen (Banking, Healthcare, Public Sector) beachten:

**BaFin-Anforderungen (Banking):**
- Dokumentation muss audit-sicher und nachvollziehbar sein
- Änderungshistorie erforderlich
- Vier-Augen-Prinzip bei kritischen Dokumenten

**DSGVO (alle Branchen):**
- Keine personenbezogenen Daten in Beispielen
- Anonymisierung von Kundendaten
- Recht auf Löschung berücksichtigen

**IT-Sicherheitsgesetz 2.0 (KRITIS):**
- Sichere Dokumentation von Sicherheitsmaßnahmen
- Incident-Response-Prozesse dokumentiert
- Regelmäßige Überprüfung der Dokumentation

---

## Teil 5: Komplexe IT-Projekte orchestrieren

### Beispiel: Vorbereitung eines Cloud-Migration-Projekts

```
PROJEKT: Cloud-Migration für mittelständische Bank (Core-Banking-Systeme)

PROMPT-SEQUENZ:

1. "Erstelle eine Executive Summary für ein Cloud-Migration-Projekt im Banking:
   - Zielsetzung und Business Value
   - Hochrangige technische Anforderungen
   - Compliance-Aspekte (BaFin, DSGVO)
   - Grobe Zeitplanung und Meilensteine
   Max. 200 Wörter."
   → Speichern als {EXEC_SUMMARY}

2. "Entwickle auf Basis von {EXEC_SUMMARY} drei Migrationsszenarien:
   - Szenario A: Lift & Shift (schnell, mittleres Risiko)
   - Szenario B: Re-Platform (optimiert, balanced)
   - Szenario C: Re-Architect (langfristig, cloud-native)
   
   Für jedes Szenario:
   - Zeitrahmen und Aufwand
   - Technische Anforderungen
   - Vor- und Nachteile
   - Kosten-Nutzen-Analyse (qualitativ)
   
   Format: Vergleichstabelle mit 8-10 Zeilen"
   → Speichern als {SZENARIEN}

3. "Für Szenario B (Re-Platform) erstelle:
   - Detaillierte technische Roadmap (6 Phasen)
   - Risikoanalyse mit Mitigation-Strategien (Top 5 Risiken)
   - Ressourcenplanung (Rollen, Aufwände)
   - Testing- und Rollback-Strategie
   
   Format: Strukturiertes Dokument mit Markdown-Überschriften"

4. "Erstelle ein Stakeholder-Kommunikations-Dokument:
   - Für IT-Leitung (technischer Fokus)
   - Für Business (ROI und Mehrwerte)
   - Für Compliance (regulatorische Anforderungen)
   
   Jeweils max. 150 Wörter, unterschiedliche Tonalität"
```

---

### 💡 Best Practice: Prompt-Ketten für komplexe Aufgaben

**Warum Prompt-Sequenzen besser sind:**
- Jeder Schritt baut auf validierten Ergebnissen auf
- Zwischenergebnisse können geprüft und angepasst werden
- Fehler werden früh erkannt und korrigiert
- Komplexität bleibt handhabbar

**Typische Sequenzen bei Ratiodata:**

**Vertrieb:** Research → Anforderungsanalyse → Lösungskonzept → Angebot → Präsentation
**Produktmanagement:** Marktanalyse → Requirements → Spezifikation → Roadmap → Release Notes
**Service:** Incident-Analyse → Root Cause → Lösung → Dokumentation → Knowledge Base
**Marketing:** Zielgruppenanalyse → Content-Ideen → Textentwurf → SEO-Optimierung → Distribution-Plan

---

## Teil 6: Troubleshooting-Guide für IT-Dokumentation

| Problem                    | Ursache                    | Lösung                                   | Erfolgsquote |
| -------------------------- | -------------------------- | ---------------------------------------- | ------------ |
| **Zu technisch/unklar**           | Zielgruppe nicht definiert         | "Erkläre für [Zielgruppe], vermeide [Fachbegriffe]"                   | 85 %         |
| **Unprofessioneller IT-Stil** | Fehlende Stil-Vorgaben | "Tonalität: technisch präzise, keine Marketing-Sprache"                 | 90 %         |
| **Falsches Format**        | Keine Format-Angabe         | "Ausgabe als Markdown-Tabelle mit Spalten: X, Y, Z" | 85 %         |
| **Zu generisch**           | Keine konkreten Anforderungen   | "Nutze Beispiele aus Managed Services für Banken"                       | 90 %         |
| **Fehlende technische Details**           | Unvollständiger Prompt          | "Ergänze: Versionsnummern, System-Requirements, CLI-Befehle"              | 80 %         |
| **Sicherheitsprobleme** | Sensible Daten im Output | "Anonymisiere alle Kundennamen und IP-Adressen" | 95 % |

---

### Debug-Methode für IT-Content

```
DEBUG-PROMPT für technische Dokumentation:
"Die vorherige Ausgabe war zu allgemein und nicht technisch präzise genug.  
Bitte überarbeite:

1. Ergänze konkrete Versionsnummern und System-Requirements
2. Füge Code-Beispiele oder CLI-Befehle hinzu (wo relevant)
3. Ersetze generische Begriffe durch spezifische (z.B. statt 'Monitoring-Tool' → 'Zabbix 6.0')
4. Strukturiere als Markdown mit H2/H3-Überschriften
5. Kürze auf max. 300 Wörter
6. Markiere Änderungen mit → am Zeilenanfang

Zielgruppe: System-Engineers mit mittlerem Erfahrungslevel"
```

---

### Spezielle Debugging-Szenarien

**Szenario 1: Output ist zu marketing-lastig**
```
"Überarbeite den Text:
- Entferne alle Adjektive wie 'revolutionär', 'einzigartig', 'optimal'
- Ersetze durch messbare Fakten (Zahlen, Metriken, Benchmarks)
- Tonalität: sachlich, objektiv, faktenbasiert
- Fokus auf technische Vorteile statt emotionaler Benefits"
```

**Szenario 2: Fachbegriffe nicht korrekt**
```
"Prüfe und korrigiere folgende technische Begriffe:
- [Begriff 1]
- [Begriff 2]
- [Begriff 3]

Erkläre Änderungen und gib die korrekten Definitionen an.
Quelle: Offizielle Dokumentation bevorzugen."
```

**Szenario 3: Struktur passt nicht zum Use Case**
```
"Aktuelle Struktur ist [beschreiben].
Zielstruktur sollte sein:
1. [Abschnitt 1]
2. [Abschnitt 2]
3. [Abschnitt 3]

Behalte den Inhalt, reorganisiere nur die Struktur.
Markiere, welche Inhalte verschoben wurden."
```

---

## Teil 7: Grenzen von KI-Assistenten im IT-Kontext

### Was KI-Modelle gut können:
✅ Strukturierung von Informationen
✅ Erste Entwürfe für Dokumentationen
✅ Formatierung und Konsistenz-Checks
✅ Generierung von Beispielen und Templates
✅ Zusammenfassungen langer technischer Dokumente
✅ Übersetzung technischer Inhalte in Business-Sprache

### Was KI-Modelle NICHT können:
❌ **Aktuelle Ratiodata-spezifische Informationen**
   → Lösung: Interne Dokumentationen manuell ergänzen

❌ **Zugriff auf interne Systeme oder Kundenportale**
   → Lösung: Relevante Daten kopieren und anonymisiert bereitstellen

❌ **Exakte Produkt-Versionen oder Preise**
   → Lösung: Immer mit aktuellen Produktinformationen abgleichen

❌ **Regulatorische Details (BaFin, IT-SiG 2.0, spezifische Compliance-Anforderungen)**
   → Lösung: Compliance-Team oder Rechtsabteilung einbinden

❌ **Sensible Unternehmens- oder Kundendaten verarbeiten**
   → Lösung: Daten vor der Eingabe anonymisieren, Platzhalter verwenden

❌ **Sicherheitslücken oder Exploits beschreiben**
   → Lösung: Nur allgemeine Security-Best-Practices anfragen

❌ **Kontext über mehrere Projekte hinweg behalten**
   → Lösung: Kurzes Briefing oder Zusammenfassung im Prompt

---

### 🔒 Sicherheit und Datenschutz: Absolute No-Gos

**Niemals in KI-Tools eingeben:**
- Kunden-Namen, Unternehmensnamen (außer mit expliziter Freigabe)
- IP-Adressen, Server-Namen, Domain-Namen
- Passwörter, API-Keys, Credentials, Tokens
- Personenbezogene Daten (Namen, E-Mails, Telefonnummern)
- Interne System-Architekturen im Detail
- Sicherheitslücken oder Schwachstellen
- Vertrauliche Vertragsinformationen
- Unveröffentlichte Produkt-Roadmaps

**Immer anonymisieren:**
- Kunde A, Kunde B statt reale Namen
- System X, System Y statt konkrete Hostnamen
- {{PLACEHOLDER}} für variable Werte
- Beispiel-IPs (192.0.2.x, 198.51.100.x) statt reale Adressen

**Bei Unsicherheit:**
- Rücksprache mit IT-Sicherheitsbeauftragten
- Prüfung durch Datenschutzbeauftragten
- Vier-Augen-Prinzip bei sensiblen Themen

---

## Schnellreferenz: Prompt-Bausteine für IT-Profis

### Struktur-Elemente

```
[HAUPTABSCHNITT]           # Primäre Gliederung
- Unterpunkt               # Detaillierung
  - Sub-Unterpunkt         # Noch feinere Ebene
| Spalte | Spalte |        # Tabellenelement
```html/```json/```python   # Code-Blöcke
```

### Stil-Vorgaben

```
Tonalität: [technisch | business | kundennah | neutral]
Zielgruppe: [Entwickler | IT-Manager | Kunde | Support | C-Level]
Perspektive: [wir | Sie | neutral (technisch)]
Komplexität: [einfach | mittel | advanced | expert]
```

### Format-Angaben

```
Format: [Markdown | Tabelle | Liste | JSON | YAML | Code]
Struktur: [H2-Überschriften | nummeriert | verschachtelt]
Länge: [Max. X Wörter | Kompakt | Ausführlich]
```

### Constraints (Einschränkungen)

```
Max. [X] Wörter
Ausschließen: [Marketing-Sprache, Adjektive, Füllwörter, Jargon]
Einschließen: [Code-Beispiele, CLI-Befehle, Links, Metriken]
Compliance: [DSGVO-konform, BaFin-tauglich, ISO 27001]
```

### Validierung

```
Prüfe: [Vollständigkeit, Technische Korrektheit, Zielgruppen-Angemessenheit]
Wenn [zu technisch], dann [Begriffe erklären]
Wenn [zu lang], dann [auf Kernaussagen reduzieren]
Bestätige: [Version | System | Framework] korrekt genannt
```

### Ratiodata-spezifische Ergänzungen

```
Kontext: [Managed Services | Cloud | Cybersecurity | Modern Workplace]
Branche: [Banking | Healthcare | Public Sector | Mittelstand]
Werte: [Innovation, Zuverlässigkeit, Sicherheit, Qualität]
Positionierung: [50+ Jahre IT-Expertise | Atruvia-Tochter | Systemhauspartner]
```

---

## Beispiel-Prompts für typische Ratiodata-Aufgaben

### Vertrieb: Angebotsvorbereitung

```
Erstelle eine strukturierte Lösungsbeschreibung für ein Cloud-Backup-Angebot:

ZIELGRUPPE: IT-Leiter eines mittelständischen Produktionsunternehmens (50-200 MA)
KONTEXT: Aktuell Tape-Backup, suchen moderne Lösung nach Ransomware-Vorfall

STRUKTUR:
[Executive Summary] (max. 100 Wörter)
- Business Value in einem Satz
- Hauptvorteile gegenüber Tape-Backup (3 Punkte)

[Technische Lösung] (200-250 Wörter)
- Architektur (Cloud + On-Premise Komponente)
- Backup-Frequenz und RPO/RTO
- Verschlüsselung und Compliance
- Integration in bestehende Systeme

[Business Case] (150 Wörter)
- TCO-Vergleich (Tape vs. Cloud)
- Einsparungspotenziale
- Skalierbarkeit

[Next Steps] (50 Wörter)
- Workshop-Angebot
- Proof of Concept
- Kontaktdaten Ansprechpartner

STIL: Beratend, lösungsorientiert, faktenbasiert
VERMEIDEN: Technischer Jargon ohne Erklärung, Marketing-Floskeln
LÄNGE: Max. 1 A4-Seite (ca. 500 Wörter)
```

---

### Software/Produktmanagement: Feature-Dokumentation

```
Dokumentiere das neue "Automated Patch Management"-Feature:

FORMAT: Markdown mit Abschnitten

[Feature Overview]
- Was ist das Feature? (2 Sätze)
- Hauptnutzen (3 Bullet Points)
- Target User: IT-Administratoren, Managed Services

[Technical Specification]
- Unterstützte Betriebssysteme und Versionen
- Integration in bestehende Tools (WSUS, SCCM, etc.)
- API-Endpoints (wenn relevant)
- System Requirements

[Use Cases]
1. Rollout monatlicher Windows-Patches
2. Emergency-Patching bei kritischen Vulnerabilities
3. Patch-Compliance-Reporting

[Implementation Guide]
- Schritt-für-Schritt (max. 8 Schritte)
- CLI-Befehle und Code-Beispiele
- Zeitaufwand pro Schritt

[Testing & Rollback]
- Test-Szenarien (3-5 Stück)
- Rollback-Prozedur
- Bekannte Limitationen

[FAQ] (5 häufigste Fragen)

STIL: Technisch präzise, aber verständlich
ZIELGRUPPE: IT-Profis mit mittlerem Level
LÄNGE: 800-1000 Wörter
```

---

### Service: Troubleshooting-Guide

```
Erstelle einen Troubleshooting-Guide für "VPN-Verbindung schlägt fehl":

ZIELGRUPPE: Level 1 Support + Self-Service-Portal
FORMAT: Schritt-für-Schritt-Anleitung

[Problem-Beschreibung]
- Symptome (was sieht der User?)
- Betroffene Systeme/Versionen
- Häufigkeit/Priorität

[Quick Fixes] (Die ersten 3 Dinge, die man prüft)
1. [Check 1] - erwartetes Ergebnis: [...]
2. [Check 2] - erwartetes Ergebnis: [...]
3. [Check 3] - erwartetes Ergebnis: [...]

[Detaillierte Diagnose]
Schritt 1: [Aktion]
  - Wie: [genauer Weg, ggf. Screenshot-Platzhalter]
  - Was prüfen: [...]
  - Wenn OK: → Schritt 2
  - Wenn Problem: → Lösungsweg A

[Lösungswege]
A. [Häufigstes Problem]
B. [Zweithäufigstes Problem]
C. [Selteneres Problem]

[Eskalation]
- Wann an Level 2 weiterleiten?
- Welche Informationen sammeln?
- Template für Eskalations-Ticket

[Prävention]
- Wie kann man das Problem vermeiden?

STIL: Klar, unterstützend, keine Fachbegriffe ohne Erklärung
LÄNGE: Max. 400 Wörter (ohne Code/Screenshots)
ERGÄNZUNGEN: Platzhalter für Screenshots {{SCREENSHOT_VPN_SETTINGS}}
```

---

### Marketing: Blog-Artikel

```
Erstelle einen Blog-Artikel über "Zero Trust Security für den Mittelstand":

ZIELGRUPPE: IT-Entscheider in KMU, wenig Security-Expertise
ZIEL: Thought Leadership, Leads generieren
LÄNGE: 800-1000 Wörter

STRUKTUR:
[Hook] (50 Wörter)
- Aktuelle Bedrohungslage (1-2 prägnante Statistiken)
- Warum klassische Perimeter-Security nicht mehr reicht

[Was ist Zero Trust?] (150 Wörter)
- Einfache Erklärung ohne Buzzwords
- Kernprinzip: "Never trust, always verify"
- Abgrenzung zu traditionellen Ansätzen

[Warum ist Zero Trust für KMU relevant?] (200 Wörter)
- Hybrid Work und Cloud-Nutzung
- Steigende Cyber-Bedrohungen auch für kleine Unternehmen
- Compliance-Anforderungen (DSGVO, IT-SiG 2.0)
- 2-3 konkrete Beispiel-Szenarien

[Praktische Umsetzung] (250 Wörter)
- 5 Schritte zum Zero Trust Model
- Quick Wins, die sofort umsetzbar sind
- Typische Herausforderungen und Lösungen
- Budgetfreundliche Ansätze für KMU

[Ratiodata als Partner] (100 Wörter)
- Wie Ratiodata unterstützt (ohne zu verkaufen)
- Managed Security Services als Enabler
- Erfolgsstory (anonymisiert): "Kunde aus dem Gesundheitswesen..."

[Call-to-Action] (50 Wörter)
- Angebot: Kostenloses Security-Assessment
- Link zur Landing Page: {{CTA_LINK}}

STIL: Professionell, aber zugänglich; beratend statt verkäuferisch
RATIODATA-WERTE: Sicherheit, Zuverlässigkeit, Expertise
SEO: Keywords: "Zero Trust", "KMU Cybersecurity", "Managed Security"
TONE: Informativ, nicht alarmistisch; lösungsorientiert
```

---

## Zusammenfassung: Ihr Workflow für strukturierte KI-Ausgaben

### Phase 1: Vorbereitung (2 Minuten)
1. Zielgruppe definieren (wer liest es?)
2. Zweck klären (was soll erreicht werden?)
3. Format festlegen (Tabelle, Liste, Fließtext?)
4. Länge bestimmen (Wortanzahl)

### Phase 2: Prompt erstellen (3 Minuten)
1. Container definieren (Hauptabschnitte)
2. Komponenten spezifizieren (Details pro Abschnitt)
3. Constraints setzen (Stil, Tonalität, Tabus)
4. Validierungskriterien einbauen

### Phase 3: Ausgabe generieren und prüfen (5 Minuten)
1. Prompt an KI-Assistent senden
2. Ausgabe gegen Checkliste prüfen
3. Technische Korrektheit validieren
4. Sicherheit und Compliance checken

### Phase 4: Optimierung (2-5 Minuten)
1. Bei Bedarf: Debug-Prompt für Anpassungen
2. Zielgruppenspezifische Feinschliff
3. Ratiodata-Werte und -Kontext integrieren
4. Finale Freigabe (bei sensiblen Themen: Vier-Augen-Prinzip)

**Gesamtzeit: 12-15 Minuten** statt 45-60 Minuten manuelle Erstellung

---

## Ihre nächsten Schritte

### ✅ Sofort umsetzbar:
1. Wählen Sie eine typische Aufgabe aus Ihrem Arbeitsalltag
2. Erstellen Sie einen strukturierten Prompt nach dem Framework
3. Testen Sie verschiedene Detaillierungsgrade (Version 1, 2, 3)
4. Dokumentieren Sie: Wie viel Zeit haben Sie gespart?

### 📚 Weiterführende Ressourcen:
- **Intranet**: Ratiodata KI-Guidelines und Best Practices
- **Teams**: KI-Community Channel für Fragen und Austausch
- **Wiki**: Template-Bibliothek mit bewährten Prompt-Vorlagen
- **Training**: Vertiefende KI-Workshops (siehe Learning-Kalender)

### 🎯 Übungsaufgaben für verschiedene Abteilungen:

**Vertrieb:**
- Erstellen Sie eine strukturierte Competitive Analysis (Ratiodata vs. Wettbewerber)
- Entwickeln Sie ein Angebotstemplate für Cloud-Services

**Marketing:**
- Planen Sie eine Content-Serie über "KI im IT-Service"
- Erstellen Sie Social-Media-Posts für LinkedIn (Professional Tone)

**Software/Produktmanagement:**
- Dokumentieren Sie ein neues Feature nach dem Schema oben
- Erstellen Sie Release Notes für ein Quartalsupdates

**Service:**
- Bauen Sie eine FAQ-Sektion für häufige Kundenanfragen auf
- Optimieren Sie einen bestehenden Knowledge-Base-Artikel

**Hardware-Entwicklung:**
- Erstellen Sie eine Produktvergleichstabelle (3 Server-Modelle)
- Entwickeln Sie ein Test-Protokoll für neue Hardware-Komponenten

---

## Feedback und Community

**Ihre Erfahrungen sind wertvoll!**
- Teilen Sie erfolgreiche Prompts im Teams-Channel "KI-Community"
- Melden Sie Probleme oder unerwartete Ergebnisse
- Schlagen Sie Verbesserungen für dieses Tutorial vor

**Bei Fragen wenden Sie sich an:**
- KI-Community Channel (Teams)
- Ihr Abteilungs-Lead für spezifische Use Cases
- IT-Sicherheit bei Compliance-Fragen
- Datenschutz bei DSGVO-Themen

---

**Ein Tutorial der ADG KI-Community**

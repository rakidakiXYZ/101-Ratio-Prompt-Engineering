# 🎯 Anleitung: Wie man einen Skill-Prompt erstellt

---

## 📚 Was ist ein Skill-Prompt?

Ein **Skill-Prompt** ist eine strukturierte Anleitung, die Sie einem KI-Assistenten geben, damit er ein wiederverwendbares Skill für Sie erstellt. 

**Denken Sie daran wie an ein Skript für IT-Prozesse:**
- Sie dokumentieren einmal genau, WAS das Skill können soll
- Das Sprachmodell erstellt daraus ein fertiges Skill
- Danach können Sie das Skill immer wieder nutzen – wie eine Funktion in der Softwareentwicklung

**Für Ratiodata-Mitarbeiter bedeutet das:**
Als IT-Profis kennen Sie bereits das Konzept der Wiederverwendbarkeit und Automatisierung. Skills funktionieren nach dem gleichen Prinzip – nur dass Sie statt Code strukturierte Anweisungen verwenden.

---

## 🔍 Analyse des "Hook Creator" Beispiel-Prompts

Schauen wir uns an, wie der Beispiel-Prompt aufgebaut ist und WARUM:

### 1️⃣ Klare Zielsetzung am Anfang

```markdown
Help me create a Skill called "Hook Creator" that generates 
attention-grabbing headlines and hooks for marketing content.
```

**Was passiert hier?**
- ✅ Gibt dem Skill einen **eindeutigen Namen** ("Hook Creator")
- ✅ Erklärt in **einem Satz**, was das Skill macht
- ✅ Definiert den **Anwendungsbereich** (Marketing Content)

**💡 Lernen Sie daraus:**
Beginnen Sie immer mit einer klaren, prägnanten Beschreibung. Das Sprachmodell muss sofort verstehen, wofür das Skill da ist – ähnlich wie eine Funktionsdokumentation im Code.

**Bei Ratiodata könnte das sein:**
```markdown
Erstelle ein Skill namens "Technical Proposal Generator", 
das Lösungsvorschläge für IT-Infrastruktur-Projekte 
unserer Kunden erstellt.
```

---

### 2️⃣ Skill Purpose (Zweck des Skills)

```markdown
## Skill Purpose
This skill should help me quickly generate 5-10 hook options 
for any marketing content using proven copywriting frameworks...
```

**Was passiert hier?**
- ✅ Erklärt das **Hauptziel** detaillierter
- ✅ Gibt **konkrete Zahlen** an (5-10 Optionen)
- ✅ Nennt **Methoden** (Copywriting Frameworks)

**💡 Lernen Sie daraus:**
Dieser Abschnitt ist das "Warum". Er erklärt, welches Problem das Skill löst und wie es das tut – wie Requirements in einem Software-Projekt.

**Für Ratiodata IT-Service:**
```markdown
## Zweck des Skills
Dieses Skill soll Service-Mitarbeitern helfen, strukturierte 
Incident-Berichte zu erstellen, die alle relevanten technischen 
Details enthalten und für Kundenreporting sowie interne 
Eskalation geeignet sind.
```

---

### 3️⃣ When to Use This Skill (Wann wird es genutzt?)

```markdown
## When to Use This Skill
Invoke this skill whenever I need to:
- Write email subject lines
- Create social media hooks
- Draft ad headlines
...
```

**Was passiert hier?**
- ✅ Listet **konkrete Anwendungsfälle** auf
- ✅ Hilft dem Sprachmodell zu erkennen, **wann** das Skill relevant ist
- ✅ Gibt dem Nutzer **Orientierung** für die Verwendung

**💡 Lernen Sie daraus:**
Je klarer Sie definieren, WANN das Skill verwendet wird, desto besser kann das System es automatisch erkennen und vorschlagen.

**Für Ratiodata Vertrieb wäre das:**
```markdown
## When to Use This Skill
Invoke this skill whenever I need to:
- Erstelle Angebote für Cloud-Migration-Projekte
- Schreibe technische Lösungsbeschreibungen für Presales
- Formuliere ROI-Berechnungen für IT-Infrastruktur
- Erstelle Executive Summaries für CIO-Präsentationen
```

**Für Ratiodata Produktmanagement:**
```markdown
## When to Use This Skill
Invoke this skill whenever I need to:
- Schreibe User Stories für Software-Features
- Erstelle Release Notes für Produktupdates
- Formuliere technische Anforderungen für Entwickler
- Dokumentiere API-Spezifikationen
```

**Für Ratiodata Hardware-Entwicklung:**
```markdown
## When to Use This Skill
Invoke this skill whenever I need to:
- Erstelle technische Produktspezifikationen
- Schreibe Marktanalysen für neue Hardware-Lösungen
- Formuliere Testszenarien für Quality Assurance
- Dokumentiere Competitive Intelligence Reports
```

---

### 4️⃣ Required Inputs (Benötigte Eingaben)

```markdown
## Required Inputs
When I invoke this skill, ask me for:
1. [Content type] - email, social post, ad, landing page, etc.
2. [Target audience] - who I'm writing for
3. [Main benefit or promise] - what the content delivers
4. [Tone] - professional, casual, urgent, playful, etc.
```

**Was passiert hier?**
- ✅ Definiert, welche **Informationen** das Sprachmodell vom Nutzer braucht
- ✅ Gibt **Beispiele** für jede Eingabe
- ✅ Macht das Skill **interaktiv** – das System stellt gezielte Fragen

**💡 Lernen Sie daraus:**
Das ist der wichtigste Teil! Sie sagen dem Sprachmodell genau, welche Informationen es VOR der Arbeit vom Nutzer erfragen soll – wie Parameter in einer Funktion.

**Für ein Ratiodata Angebots-Skill wäre das:**
```markdown
## Required Inputs
When I invoke this skill, ask me for:
1. [Kundenbranche] - Finanzdienstleistung, Healthcare, Öffentliche Verwaltung, Mittelstand
2. [Projektumfang] - Cloud-Migration, Managed Services, Cybersecurity, Modern Workplace
3. [Systemlandschaft] - On-Premise, Hybrid, Public Cloud (Azure/AWS)
4. [Budget-Range] - < 50k, 50-100k, 100-250k, > 250k
5. [Zeitrahmen] - Quick-Win (3 Monate), Standard (6-12 Monate), Transformation (> 12 Monate)
6. [Compliance-Anforderungen] - DSGVO, KRITIS, BSI IT-Grundschutz, branchenspezifische Regulierung
```

**Für ein Ratiodata Incident-Report-Skill:**
```markdown
## Required Inputs
When I invoke this skill, ask me for:
1. [Incident-Kategorie] - Hardware-Ausfall, Software-Bug, Sicherheitsvorfall, Performance-Problem
2. [Betroffene Systeme] - Server, Storage, Netzwerk, Client, Cloud-Services
3. [Kritikalität] - Critical (P1), High (P2), Medium (P3), Low (P4)
4. [Kundenkontext] - Banken-IT, Healthcare-Infrastruktur, Verwaltung, Standard-Kunde
5. [Auswirkung] - Anzahl betroffener User, Business Impact, SLA-Relevanz
```

---

### 5️⃣ Output Format (Wie soll das Ergebnis aussehen?)

```markdown
## Output Format
Generate 10 hook options using at least 5 different frameworks. 
For each hook:
- Present the hook text
- Label which framework was used in parentheses
- Keep hooks under 100 characters when possible
```

**Was passiert hier?**
- ✅ Definiert die **Struktur** der Ausgabe
- ✅ Gibt **Formatierungsvorgaben** (z.B. Zeichenlimit)
- ✅ Erklärt, wie die Ergebnisse **präsentiert** werden sollen

**💡 Lernen Sie daraus:**
Je präziser Sie das Format beschreiben, desto konsistenter sind Ihre Ergebnisse – wie bei der Definition von Datenstrukturen in der Programmierung.

**Für ein Ratiodata IT-Lösungsvorschlag-Skill:**
```markdown
## Output Format
Erstelle einen technischen Lösungsvorschlag mit folgender Struktur:

**1. Executive Summary (3-4 Sätze)**
- Kundenherausforderung
- Vorgeschlagene Lösung
- Hauptnutzen (ROI/TCO)

**2. Ist-Situation (4-6 Bulletpoints)**
- Aktuelle IT-Landschaft
- Identifizierte Pain Points
- Technische und wirtschaftliche Herausforderungen

**3. Soll-Konzept (detaillierte Architektur)**
- Technologie-Stack
- Infrastruktur-Komponenten
- Integration in Bestandssysteme
- Sicherheitskonzept

**4. Ratiodata Services (5-7 Bulletpoints)**
- Managed Services Komponenten
- Support-Level (SLA)
- Monitoring & Reporting
- Backup & Disaster Recovery

**5. Migrations-/Implementierungsplan**
- Phasenmodell mit Zeitrahmen
- Ressourcenplanung
- Risikomanagement
- Go-Live Strategie

**6. Business Case**
- Investitionskosten (CAPEX)
- Betriebskosten (OPEX)
- ROI-Berechnung über 3 Jahre
- TCO-Vergleich Alt vs. Neu

**7. Next Steps**
- Konkreter Projektfahrplan
- Entscheidungspunkte
- Ansprechpartner bei Ratiodata
```

**Für ein Ratiodata Software-Dokumentations-Skill:**
```markdown
## Output Format
Erstelle eine API-Dokumentation mit folgender Struktur:

**1. Übersicht**
- Zweck der API/Funktion
- Version und Änderungshistorie

**2. Technische Spezifikation**
- Endpoint/Funktionsname
- Parameter (mit Datentypen)
- Return Values
- Error Codes

**3. Authentifizierung & Security**
- Auth-Methode (OAuth, API Key, etc.)
- Erforderliche Berechtigungen
- Rate Limits

**4. Code-Beispiele**
- Request-Beispiel (curl/REST)
- Response-Beispiel (JSON/XML)
- Error-Response-Beispiel

**5. Best Practices**
- Empfohlene Nutzungsmuster
- Performance-Hinweise
- Fehlerbehandlung
```

---

### 6️⃣ Frameworks/Methoden (Welche Techniken werden verwendet?)

```markdown
## Hook Frameworks to Use
- Curiosity Gap (incomplete information that demands resolution)
- Pain-Agitation-Solution (call out pain, make it worse, hint at solution)
- Benefit-Driven (lead with clear value)
...
```

**Was passiert hier?**
- ✅ Listet **konkrete Methoden** auf, die das Sprachmodell nutzen soll
- ✅ Erklärt jede Methode **kurz** in Klammern
- ✅ Gibt dem System ein **Werkzeug-Set** an die Hand

**💡 Lernen Sie daraus:**
Wenn Sie möchten, dass das Sprachmodell bestimmte bewährte Techniken nutzt, listen Sie diese explizit auf – wie Design Patterns in der Software-Architektur.

**Für Ratiodata Vertriebstexte:**
```markdown
## Argumentations-Frameworks
- ROI-fokussiert (Quantifizierbare Einsparungen/Mehrwerte)
- Risiko-Minimierung (Ausfallsicherheit, Compliance, Security)
- Innovation-getrieben (Wettbewerbsvorteil, Zukunftssicherheit)
- Effizienz-Steigerung (Prozessoptimierung, Automatisierung)
- Expertise-basiert (Ratiodata Referenzen, Zertifizierungen, Awards)
- Total Cost of Ownership (Transparente Kostenrechnung über Lebenszyklus)
```

**Für Ratiodata Service-Dokumentation:**
```markdown
## Dokumentations-Frameworks
- Problem-Symptom-Lösung (Strukturierte Fehleranalyse)
- Root Cause Analysis (5-Why-Methodik für tiefere Ursachen)
- ITIL-konform (Incident/Problem/Change Management Standards)
- Eskalations-Matrix (Wann welche Stakeholder informieren)
- Lessons Learned (Präventive Maßnahmen für die Zukunft)
```

**Für Ratiodata Produktmanagement:**
```markdown
## Spezifikations-Frameworks
- User Story Format (Als [Rolle] möchte ich [Funktion] um [Nutzen])
- Acceptance Criteria (Given-When-Then für Testbarkeit)
- MoSCoW-Priorisierung (Must/Should/Could/Won't)
- NFR-Standards (Performance, Security, Usability, Maintainability)
- API-First Design (OpenAPI/Swagger Spezifikationen)
```

---

### 7️⃣ Additional Guidelines (Zusätzliche Richtlinien)

```markdown
## Additional Guidelines
- Avoid clickbait that doesn't deliver on promises
- Test different lengths (short punchy vs. longer descriptive)
- Include at least 2 options that break category norms
- Make hooks specific rather than generic
- Ensure hooks align with brand voice
```

**Was passiert hier?**
- ✅ Gibt **Do's und Don'ts**
- ✅ Definiert **Qualitätskriterien**
- ✅ Verhindert **unerwünschte Ergebnisse**

**💡 Lernen Sie daraus:**
Dieser Abschnitt ist Ihre Qualitätskontrolle. Hier verhindern Sie häufige Fehler – wie Code Reviews und Quality Gates in der Softwareentwicklung.

**Für Ratiodata IT-Lösungsvorschläge:**
```markdown
## Additional Guidelines
- **DSGVO-Konformität**: Alle Lösungen müssen EU-Datenschutz erfüllen
- **IT-Sicherheit**: BSI IT-Grundschutz oder vergleichbare Standards berücksichtigen
- **Vendor-Neutralität**: Mehrere Technologie-Optionen aufzeigen (kein Vendor Lock-in)
- **TCO-Transparenz**: Versteckte Kosten (Lizenzen, Support, Schulung) offenlegen
- **SLA-Definition**: Klare Service Level Agreements definieren
- **Skalierbarkeit**: Wachstumspfade für 3-5 Jahre berücksichtigen
- **Compliance**: Branchenspezifische Anforderungen (BaFin, KRITIS, etc.) einbeziehen
- **Ratiodata-Werte**: Innovation, Zuverlässigkeit, Qualität, Sicherheit, Kundenorientierung
- **Fachsprache**: Technisch präzise, aber auch für nicht-IT-Entscheider verständlich
- **Referenzen**: Auf ähnliche erfolgreiche Ratiodata-Projekte verweisen
```

**Für Ratiodata Service-Dokumentation:**
```markdown
## Additional Guidelines
- **Objektivität**: Sachlich bleiben, keine Schuldzuweisungen
- **Vollständigkeit**: Alle relevanten Log-Dateien, Timestamps, Error-Codes dokumentieren
- **Nachvollziehbarkeit**: Jeder Schritt der Problemlösung muss reproduzierbar sein
- **Eskalationspfade**: Bei kritischen Incidents (P1/P2) immer Management informieren
- **Datenschutz**: Keine Kundendaten oder sensible Systemdetails in Tickets
- **ITIL-Standards**: Incident-Reports müssen ITIL-konform strukturiert sein
- **Knowledge Base**: Lösungen so dokumentieren, dass sie in Wissensdatenbank übernommen werden können
```

**Für Ratiodata Produktdokumentation:**
```markdown
## Additional Guidelines
- **Versionierung**: Jede Änderung muss mit Versionsnummer und Datum versehen sein
- **API-Stabilität**: Breaking Changes klar kennzeichnen und Migrationspfade aufzeigen
- **Code-Beispiele**: Immer funktionierende, getestete Beispiele verwenden
- **Security**: Keine Hardcoded Credentials oder unsichere Praktiken in Beispielen
- **Accessibility**: Dokumentation muss für Menschen mit Behinderungen zugänglich sein
- **Internationalisierung**: Bei global genutzten Produkten englische Dokumentation erstellen
```

---

### 8️⃣ Call-to-Action am Ende

```markdown
Create this skill now and save it so I can invoke it whenever 
I need compelling hooks.
```

**Was passiert hier?**
- ✅ Gibt dem Sprachmodell eine **klare Handlungsanweisung**
- ✅ Erklärt, was mit dem Skill passieren soll

**💡 Lernen Sie daraus:**
Beenden Sie immer mit einer direkten Aufforderung, damit das System weiß, dass es jetzt aktiv werden soll – wie ein EXECUTE-Befehl.

---

## 🏗️ Die perfekte Skill-Prompt-Struktur für Ratiodata

Hier ist die **universelle Vorlage**, die Sie für JEDES Skill verwenden können:

```markdown
Erstelle ein Skill namens "[SKILL-NAME]" für [RATIODATA-ABTEILUNG/ANWENDUNGSBEREICH].

## Skill Purpose
[Detaillierte Beschreibung des Zwecks, welches IT/Business-Problem das Skill löst]
[Bezug zu Ratiodata-Services: Managed Services, Cloud, Cybersecurity, etc.]

## When to Use This Skill
Invoke this skill whenever I need to:
- [IT-spezifischer Anwendungsfall 1]
- [IT-spezifischer Anwendungsfall 2]
- [IT-spezifischer Anwendungsfall 3]
[Berücksichtige: Vertrieb, Marketing, Service, Software/Produktmanagement, Hardware-Entwicklung]

## Required Inputs
When I invoke this skill, ask me for:
1. [Input 1] - [Erklärung mit IT-spezifischen Beispielen]
2. [Input 2] - [Erklärung mit IT-spezifischen Beispielen]
3. [Input 3] - [Erklärung mit IT-spezifischen Beispielen]
[Wichtig: Compliance-Anforderungen, Sicherheitsaspekte, Branchenkontext abfragen]

## Output Format
[Beschreibe genau, wie die Ausgabe strukturiert sein soll]
- [Format-Regel 1: z.B. Technische Spezifikationen]
- [Format-Regel 2: z.B. Business Case / ROI]
- [Format-Regel 3: z.B. Sicherheits- und Compliance-Hinweise]

## Methoden/Frameworks
[Liste bewährte IT-Frameworks/Standards auf:]
- [Framework 1] - [Kurzbeschreibung]
- [Framework 2] - [Kurzbeschreibung]
- [Framework 3] - [Kurzbeschreibung]
[Beispiele: ITIL, TOGAF, BSI IT-Grundschutz, ISO 27001, Scrum/Agile]

## Additional Guidelines
- **IT-Sicherheit:** [Sicherheitsanforderungen]
- **Datenschutz:** [DSGVO-Aspekte]
- **Compliance:** [Regulatorische Anforderungen]
- **Ratiodata-Standards:** [Qualitätsrichtlinien]
- **Technologie:** [Präferenzen für Tech-Stack]
- **Dokumentation:** [Standards für technische Dokumentation]

## Ratiodata-Spezifika
- Berücksichtige unsere Werte: Innovation, Zuverlässigkeit, Qualität, Sicherheit, Kundenorientierung
- Referenziere Ratiodata Expertise: IT-Systemhaus, Managed Services, Bankentechnologie, Cybersecurity
- Integriere Branchenkontexte: Finanzsektor, Healthcare, Öffentliche Verwaltung, Mittelstand
- Betone Mehrfach-Auszeichnungen: Innovator des Jahres, Qualitätszertifizierungen

Erstelle dieses Skill jetzt und speichere es für die Nutzung im Ratiodata-Kontext.
```

---

## 💼 Abteilungsspezifische Skill-Beispiele für Ratiodata

### 🎯 Für Vertrieb: "Technical Proposal Generator"

```markdown
Erstelle ein Skill namens "Technical Proposal Generator" für den Ratiodata Vertrieb.

## Skill Purpose
Dieses Skill unterstützt Vertriebsmitarbeiter bei der Erstellung technisch fundierter 
und kundenspezifischer IT-Lösungsvorschläge. Es kombiniert Ratiodata-Services 
(Managed Services, Cloud-Lösungen, Cybersecurity) mit kundenindividuellen 
Anforderungen und erstellt professionelle Angebotsdokumente für CIOs und IT-Leiter.

## When to Use This Skill
Invoke this skill whenever I need to:
- Erstelle technische Angebote für Cloud-Migration-Projekte
- Formuliere Managed Services Proposals
- Schreibe Cybersecurity-Lösungskonzepte
- Erstelle ROI-Berechnungen für IT-Infrastruktur-Projekte
- Bereite CIO-Präsentationen für Banken, Healthcare oder Verwaltung vor

## Required Inputs
When I invoke this skill, ask me for:
1. [Kundenbranche] - Finanzdienstleistung, Healthcare, Öffentliche Verwaltung, Mittelstand
2. [IT-Herausforderung] - Legacy-Modernisierung, Cloud-Migration, Sicherheits-Upgrade, Compliance
3. [Systemlandschaft] - On-Premise, Hybrid-Cloud, Public Cloud (Azure/AWS/GCP)
4. [Projektbudget] - < 50k, 50-100k, 100-250k, > 250k EUR
5. [Zeitrahmen] - Quick-Win (3 Monate), Standard (6-12 Monate), Transformation (> 12 Monate)
6. [Compliance] - DSGVO, BaFin, KRITIS, BSI IT-Grundschutz, branchenspezifisch
7. [Kritikalität] - Business-Critical, High Availability required, Standard

## Output Format
Erstelle einen Lösungsvorschlag mit folgenden Abschnitten:

**1. Executive Summary (Management-Level)**
- Kundenherausforderung in 2-3 Sätzen
- Ratiodata-Lösungsansatz
- Quantifizierbarer Business Value (ROI/TCO)

**2. Ist-Analyse**
- Aktuelle IT-Infrastruktur (5-7 Bulletpoints)
- Identifizierte Schwachstellen und Risiken
- Technische Schulden und Ineffizienzen
- Compliance-Lücken

**3. Soll-Konzept (Technische Architektur)**
- Vorgeschlagene Technologie-Komponenten
- Ratiodata Managed Services Integration
- Sicherheitsarchitektur (Defense in Depth)
- Hochverfügbarkeit und Disaster Recovery
- Cloud-Strategie (wenn relevant)

**4. Ratiodata Services & Support**
- Managed Services Level (24/7 Support, SLA 99,9%)
- Monitoring, Alerting & Reporting
- Backup & Business Continuity
- Security Operations Center (SOC)
- Patch Management & Updates

**5. Implementierungs-Roadmap**
- Phasenmodell mit Meilensteinen
- Ressourcenplanung (Ratiodata + Kunde)
- Risikomanagement & Mitigationsstrategien
- Testing & Quality Assurance
- Go-Live Plan mit Rollback-Szenarien

**6. Business Case**
- CAPEX: Einmalige Investitionskosten
- OPEX: Laufende Betriebskosten (3 Jahre)
- TCO-Vergleich: Alt-System vs. Neu-Lösung
- ROI-Berechnung mit Break-Even-Point
- Soft Benefits (Agilität, Skalierbarkeit, Innovation)

**7. Referenzen & Credentials**
- Ähnliche Ratiodata-Projekte (anonymisiert)
- Relevante Zertifizierungen und Awards
- Partner-Status (Microsoft, AWS, VMware, etc.)

**8. Next Steps**
- Detaillierter Workshop-Vorschlag
- Proof of Concept (falls sinnvoll)
- Vertragsmodell (Fixed Price, Time & Material, Managed Service)
- Entscheidungs-Timeline
- Ansprechpartner: Sales, Presales, Projektleitung

## Argumentations-Frameworks
- **ROI-First**: Quantifizierbare Einsparungen innerhalb 12-24 Monaten
- **Risk-Mitigation**: Ausfallsicherheit, Compliance, Cyber-Risiken minimieren
- **Innovation-Enable**: Wettbewerbsvorteil durch moderne IT-Architektur
- **TCO-Transparency**: Vollständige Kostenrechnung über 3-5 Jahre Lebenszyklus
- **Expertise-Proof**: Ratiodata Track Record, Zertifizierungen, Awards
- **Scalability**: Wachstumsfähigkeit der Lösung für 3-5 Jahre

## Additional Guidelines

**IT-Sicherheit:**
- Jede Lösung muss BSI IT-Grundschutz oder vergleichbare Standards erfüllen
- Verschlüsselung: in Transit (TLS 1.3) und at Rest (AES-256)
- Multi-Faktor-Authentifizierung für administrative Zugriffe
- Zero-Trust-Prinzipien wo möglich
- Security by Design, nicht als Add-on

**Datenschutz & Compliance:**
- DSGVO-Konformität ist nicht verhandelbar
- Datenspeicherung innerhalb EU (GDPR-konform)
- Für Banken: BaFin-Anforderungen (BAIT, MaRisk)
- Für Healthcare: Patientendatenschutz nach DSGVO und SGB
- Für KRITIS: BSI KRITIS-Verordnung

**Technologie-Standards:**
- Bevorzuge Open Standards und vermei Vendor Lock-in
- Multi-Cloud-fähige Architekturen wo sinnvoll
- API-First für Integrationsfähigkeit
- Moderne Deployment-Methoden (CI/CD, IaC)

**Ratiodata-Differenzierung:**
- Betone über 50 Jahre IT-Dienstleistungserfahrung
- Mehrfach ausgezeichnet als "Innovator des Jahres"
- Tochter der Atruvia AG – Teil der Genossenschaftlichen FinanzGruppe
- Spezialisierung auf regulierte Branchen (Banken, Healthcare, Verwaltung)
- 24/7 Service mit deutschsprachigem Support

**Sprache & Tonalität:**
- Technisch präzise, aber auch für Business-Entscheider verständlich
- Keine Marketing-Floskeln, sondern sachliche Argumentation
- Quantitative Aussagen wo möglich (Zahlen, Prozente, Zeiträume)
- Risiken transparent ansprechen, nicht verschleiern
- Kundenorientierung: "Ihre Herausforderung" statt "Unser Produkt"

**Qualitätssicherung:**
- Jede technische Aussage muss faktisch korrekt sein
- ROI-Berechnungen müssen nachvollziehbar und realistisch sein
- Keine unrealistischen Versprechen (z.B. "100% Ausfallsicherheit")
- Compliance-Aussagen müssen durch Zertifikate gedeckt sein

Erstelle dieses Skill jetzt und speichere es für Ratiodata Vertriebsmitarbeiter.
```

---

### 🛠️ Für Service: "Incident Report Generator"

```markdown
Erstelle ein Skill namens "Incident Report Generator" für Ratiodata Service-Teams.

## Skill Purpose
Dieses Skill unterstützt Service-Mitarbeiter bei der strukturierten Dokumentation 
von IT-Incidents nach ITIL-Standards. Es erstellt vollständige Incident-Reports 
für Kundenkommunikation, interne Eskalation und Knowledge-Base-Einträge unter 
Berücksichtigung von SLA-Relevanz und Compliance-Anforderungen.

## When to Use This Skill
Invoke this skill whenever I need to:
- Dokumentiere Hardware-Ausfälle bei Kunden-Infrastruktur
- Erstelle Incident-Reports für kritische Software-Bugs
- Schreibe Post-Mortem-Analysen für Major Incidents
- Formuliere Kundenkommunikation bei Service-Unterbrechungen
- Bereite Eskalations-Reports für Management vor
- Erstelle Knowledge-Base-Artikel aus gelösten Incidents

## Required Inputs
When I invoke this skill, ask me for:
1. [Incident-ID] - Ticket-Nummer aus Service Management System
2. [Kategorie] - Hardware, Software, Netzwerk, Cloud, Security, Performance
3. [Priorität] - P1 (Critical), P2 (High), P3 (Medium), P4 (Low)
4. [Betroffene Systeme] - Server, Storage, Network, Firewall, Cloud-Services, Clients
5. [Kunde/Branche] - Banken-IT, Healthcare, Verwaltung, Mittelstand (für Kontext)
6. [Auswirkung] - Anzahl betroffener User, Business Impact, SLA-Breach
7. [Status] - Investigating, Workaround applied, Resolved, Closed
8. [Zeitstempel] - Start des Incidents, Detektion, Mitigation, Resolution

## Output Format
Erstelle einen ITIL-konformen Incident Report mit folgenden Abschnitten:

**1. Incident Summary**
- Incident-ID und Titel (prägnant, technisch korrekt)
- Priorität und Kategorie
- Betroffene Systeme und Services
- Zeitstempel: Detection, Response, Mitigation, Resolution
- SLA-Status: Eingehalten / Gefährdet / Verletzt

**2. Impact Analysis**
- Anzahl betroffener User/Systeme
- Business Impact (quantifiziert)
- Betroffene Geschäftsprozesse
- Finanzielle Auswirkung (falls kalkulierbar)
- Compliance/Regulatorische Auswirkungen

**3. Timeline of Events (chronologisch)**
- [HH:MM] Incident Detection (wie wurde es entdeckt?)
- [HH:MM] Initial Response (wer wurde informiert?)
- [HH:MM] Diagnostics (erste Analyseschritte)
- [HH:MM] Workaround Implementation (falls applicable)
- [HH:MM] Root Cause identified
- [HH:MM] Permanent Fix applied
- [HH:MM] Verification & Closure

**4. Root Cause Analysis**
- Technische Ursache (detailliert)
- Beitragende Faktoren
- Warum wurde es nicht früher erkannt? (falls relevant)
- Kategorisierung: Human Error, Technical Failure, Process Gap, External Factor

**5. Resolution Details**
- Durchgeführte Maßnahmen (Schritt-für-Schritt)
- Verwendete Tools und Befehle (für Reproduzierbarkeit)
- Beteiligte Teams/Personen
- Dokumentation relevanter Log-Dateien und Error-Codes

**6. Preventive Measures**
- Kurzfristige Maßnahmen (implementiert)
- Mittelfristige Empfehlungen (nächste 3-6 Monate)
- Langfristige Verbesserungen (Architektur, Prozesse)
- Monitoring & Alerting Anpassungen
- Runbook/Playbook Updates

**7. Customer Communication**
- Kunde informiert: Ja/Nein, wann, durch wen
- Communication-Log (zusammengefasst)
- Kundenzufriedenheit: Feedback dokumentiert?
- Kompensation/Kulanz: falls SLA-Breach

**8. Knowledge Base Entry** (optional)
- Zusammenfassung für KB (max. 200 Wörter)
- Tags/Keywords für Suchbarkeit
- Kategorie für KB-Struktur

## Dokumentations-Frameworks
- **ITIL Incident Management**: Strukturierte Incident-Klassifikation
- **Root Cause Analysis**: 5-Why-Methodik für tiefergehende Ursachenforschung
- **Timeline-Driven**: Chronologische Dokumentation aller Aktivitäten
- **SLA-Aware**: Klare Dokumentation von SLA-Einhaltung/-Verletzung
- **Lessons Learned**: Extraktion von Präventivmaßnahmen für Zukunft
- **Knowledge-Driven**: Dokumentation so aufbereiten, dass andere daraus lernen können

## Additional Guidelines

**ITIL-Konformität:**
- Verwende ITIL-Terminologie korrekt (Incident vs. Problem vs. Change)
- Priorisierung nach Impact + Urgency Matrix
- Eskalationspfade gemäß ITIL Best Practices
- Clear Ownership (Assigned To, Resolved By)

**Technische Präzision:**
- Exakte Timestamps (mit Zeitzone)
- Vollständige System-Identifikatoren (Hostname, IP, Service-Name)
- Error-Codes und Log-Auszüge (anonymisiert)
- Verwendete Diagnose-Tools und Befehle dokumentieren

**Datenschutz & Security:**
- KEINE Kundendaten in Incident-Reports (anonymisieren!)
- Keine Passwörter, API-Keys oder Credentials
- Keine sensiblen Business-Informationen des Kunden
- Bei Security-Incidents: Vertraulichkeit wahren

**Kundenorientierung:**
- Sachlicher, professioneller Ton (keine Schuldzuweisungen)
- Verständliche Sprache für nicht-technische Stakeholder
- Transparenz über Ursachen und Maßnahmen
- Proaktive Kommunikation von Präventivmaßnahmen

**Eskalations-Kriterien:**
- P1-Incidents: Sofortige Eskalation an Service Manager + Kunde
- SLA-Breach: Dokumentation und Management-Information innerhalb 1h
- Security-Incidents: CISO und Legal informieren
- Multi-Kunden-Impact: Account Management informieren

**Quality Assurance:**
- Jeder Incident Report muss Peer-Review durchlaufen (bei P1/P2)
- Vollständigkeit prüfen: Alle Pflichtfelder ausgefüllt?
- Nachvollziehbarkeit: Kann ein Kollege den Incident aus der Doku verstehen?
- Knowledge Transfer: Ist der Report geeignet für KB?

**Compliance & Regulatory:**
- Für Banken-Kunden: BaFin-Reporting-Pflichten beachten
- Für Healthcare: Patientendaten-Incident? → Datenschutzbeauftragten informieren
- Für KRITIS: BSI-Meldepflicht bei kritischen Störungen
- DSGVO-Breach: Innerhalb 72h dokumentieren und melden

Erstelle dieses Skill jetzt und speichere es für Ratiodata Service-Teams.
```

---

### 💻 Für Produktmanagement: "User Story Generator"

```markdown
Erstelle ein Skill namens "User Story Generator" für Ratiodata Produktmanagement.

## Skill Purpose
Dieses Skill unterstützt Produktmanager bei der Formulierung technisch präziser 
und testbarer User Stories für Software-Entwicklung. Es erstellt User Stories 
nach Best Practices (Scrum/Agile), inkl. Acceptance Criteria, technischen 
Anforderungen und NFRs (Non-Functional Requirements) für IT-Lösungen im 
Enterprise-Kontext.

## When to Use This Skill
Invoke this skill whenever I need to:
- Erstelle User Stories für neue Software-Features
- Formuliere technische Anforderungen für Entwickler-Teams
- Schreibe Acceptance Criteria für QA-Testing
- Dokumentiere API-Spezifikationen
- Erstelle epics und breche sie in Stories herunter
- Formuliere NFRs (Performance, Security, Usability)

## Required Inputs
When I invoke this skill, ask me for:
1. [Feature-Bereich] - Cloud Management, Monitoring, Automation, Security, Reporting
2. [User-Rolle] - Admin, End-User, API-Consumer, DevOps-Engineer, Security-Officer
3. [Hauptziel] - Was soll der User erreichen können?
4. [Business Value] - Warum ist dieses Feature wichtig? (Kundennutzen, Effizienz)
5. [Technischer Kontext] - Betroffene Systeme, APIs, Datenbanken
6. [Priorität] - Must-Have (P1), Should-Have (P2), Nice-to-Have (P3)
7. [Story Points] - Schätzung der Komplexität (1, 2, 3, 5, 8, 13)

## Output Format
Erstelle eine User Story nach folgendem Standard-Format:

**User Story**
```
Als [Rolle]
möchte ich [Funktion/Capability]
um [Business Value/Nutzen] zu erreichen.
```

**Business Context**
- Warum ist diese Story wichtig?
- Welches Problem löst sie?
- Welcher Kundennutzen entsteht?
- Wie fügt sie sich in die Produkt-Roadmap ein?

**Acceptance Criteria (Given-When-Then Format)**
```
Szenario 1: [Haupt-Use-Case]
  GIVEN [Vorbedingung/State]
  WHEN [Aktion des Users]
  THEN [Erwartetes Ergebnis]
  AND [Zusätzliche Validierung]

Szenario 2: [Edge Case]
  GIVEN [...]
  WHEN [...]
  THEN [...]

Szenario 3: [Error Handling]
  GIVEN [...]
  WHEN [...]
  THEN [Fehlerbehandlung]
```

**Technical Requirements**
- API Endpoints (falls relevant): GET/POST/PUT/DELETE /api/v1/...
- Data Models: Welche Entities betroffen? JSON Schema?
- Authentication/Authorization: Welche Permissions erforderlich?
- Integration Points: Welche Systeme/Services müssen angebunden werden?
- Database Changes: Neue Tables, Columns, Indices?

**Non-Functional Requirements (NFRs)**
- **Performance**: Response Time < [X]ms, Throughput [Y] requests/sec
- **Security**: Authentication-Methode, Verschlüsselung, Input-Validation
- **Usability**: UX-Anforderungen, Accessibility (WCAG 2.1)
- **Reliability**: Uptime-Anforderung, Error Handling, Graceful Degradation
- **Scalability**: Concurrent Users, Data Volume, Growth projections
- **Maintainability**: Code Quality, Documentation, Testing Coverage

**Dependencies**
- Abhängigkeiten zu anderen Stories/Epics
- Externe Dependencies (Third-Party APIs, Services)
- Infrastructure Dependencies (DB-Setup, Cloud-Resources)
- Team Dependencies (benötigt Input von anderen Teams?)

**Definition of Done (DoD)**
- [ ] Code implementiert und reviewed
- [ ] Unit Tests geschrieben (Coverage >= 80%)
- [ ] Integration Tests erfolgreich
- [ ] API-Dokumentation aktualisiert (Swagger/OpenAPI)
- [ ] Security Review abgeschlossen
- [ ] Performance Tests erfolgreich (alle NFRs erfüllt)
- [ ] User Acceptance Testing (UAT) durch Product Owner
- [ ] Deployment-Dokumentation erstellt
- [ ] Release Notes geschrieben

**Risks & Mitigation**
- Technische Risiken identifizieren
- Performance-Bottlenecks
- Security-Concerns
- Mitigation-Strategien

**Estimation**
- Story Points: [Fibonacci-Zahl]
- Schätzungs-Rationale: Warum diese Komplexität?

## Spezifikations-Frameworks
- **User Story Format**: Als-Möchte-Um Struktur für klare Nutzerorientierung
- **Given-When-Then**: Behavior-Driven Development (BDD) für testbare Acceptance Criteria
- **MoSCoW-Priorisierung**: Must/Should/Could/Won't für Scope-Management
- **INVEST-Kriterien**: Independent, Negotiable, Valuable, Estimable, Small, Testable
- **API-First Design**: OpenAPI/Swagger für API-Spezifikationen
- **NFR-Taxonomie**: ISO 25010 (Softwarequalität) für strukturierte NFRs

## Additional Guidelines

**Agile Best Practices:**
- User Stories müssen innerhalb eines Sprints (2 Wochen) abgeschlossen werden können
- Wenn Story > 8 Story Points: In kleinere Stories aufteilen
- Jede Story muss unabhängig deploybar sein (soweit möglich)
- Business Value muss messbar/nachvollziehbar sein

**Technische Präzision:**
- API-Spezifikationen nach RESTful-Prinzipien
- Alle Datentypen explizit definieren (nicht "String", sondern "ISO-8601 DateTime")
- Error-Cases dokumentieren (HTTP Status Codes, Error Messages)
- Versionierung berücksichtigen (Breaking Changes kennzeichnen)

**Security by Design:**
- Bei allen User-Input: Input-Validation und Sanitization
- Authentication + Authorization explizit definieren
- Sensible Daten: Verschlüsselung at Rest und in Transit
- OWASP Top 10 berücksichtigen
- Für Enterprise-Kunden: SSO/SAML-Integration prüfen

**Accessibility & Usability:**
- WCAG 2.1 Level AA als Minimum-Standard
- Keyboard-Navigation muss funktionieren
- Screen-Reader-Kompatibilität
- Mobile-Responsive für alle Features (falls applicable)

**Documentation Standards:**
- Jede User Story muss mit API-Dokumentation einhergehen
- Code-Kommentare für komplexe Business-Logik
- README aktualisieren bei neuen Features
- Architecture Decision Records (ADRs) für wichtige Design-Entscheidungen

**Quality Assurance:**
- Test Coverage >= 80% für neuen Code
- Performance Tests für kritische Pfade
- Security Scanning (SAST/DAST) vor Deployment
- Peer Review durch mindestens einen anderen Developer

**Ratiodata-Kontext:**
- Für Managed Services: Monitoring und Alerting mitdenken
- Für Multi-Tenant-Systeme: Tenant-Isolation sicherstellen
- Für regulierte Branchen: Audit-Logging implementieren
- Compliance: DSGVO-Konformität in allen Features

Erstelle dieses Skill jetzt und speichere es für Ratiodata Produktmanager.
```

---

## 📊 Vergleich: Marketing Hook vs. IT-Lösungsvorschlag

| Aspekt | Hook Creator | Technical Proposal Generator |
|--------|-------------|------------------------------|
| **Zielgruppe** | Marketing-Profis | IT-Vertrieb bei Systemhäusern |
| **Output** | 10 Hook-Varianten | 1 vollständiger Lösungsvorschlag |
| **Komplexität** | Mittel (kreativ) | Hoch (technisch + kaufmännisch) |
| **Frameworks** | 10 Copywriting-Methoden | 6 IT-Argumentations-Frameworks |
| **Rechtl. Relevanz** | Niedrig | Sehr hoch (Verträge, SLAs, Compliance) |
| **Anpassbarkeit** | Hoch (viele Varianten) | Mittel (kundenspezifisch) |
| **Fachkompetenz** | Marketing-Know-how | IT-Architektur + Business-Acumen |

---

## 🎓 Was Sie gelernt haben

Nach dieser Anleitung können Sie:

✅ Die **Anatomie eines Skill-Prompts** für IT-Anwendungsfälle verstehen  
✅ **Eigene Skills** für Ratiodata-Prozesse erstellen (Vertrieb, Service, Produktmanagement)  
✅ **Best Practices** für technische Dokumentation in Skills anwenden  
✅ Skills für Ihr **Team teilen** und Ratiodata-Standards einhalten  
✅ Den Unterschied zwischen **generischen und IT-spezifischen** Prompts erkennen  
✅ **Compliance- und Sicherheitsaspekte** in Skills integrieren  
✅ **Wiederverwendbare Vorlagen** für typische Ratiodata-Aufgaben erstellen

---

## 🚀 Ihr nächster Schritt

1. **Wählen Sie einen Use Case** aus Ihrem Arbeitsbereich:
   - Vertrieb: Angebotserstellung, ROI-Berechnungen, CIO-Präsentationen
   - Marketing: Produktmarketing, Content Creation, Event-Beschreibungen
   - Service: Incident Reports, Knowledge-Base-Artikel, Kundenkommunikation
   - Produktmanagement: User Stories, API-Docs, Release Notes
   - Hardware-Entwicklung: Produktspezifikationen, Marktanalysen, Testszenarien

2. **Kopieren Sie die Ratiodata-Vorlage** (siehe oben)

3. **Füllen Sie die Vorlage aus** mit Ihren spezifischen Anforderungen:
   - Welche Informationen benötigt das Skill von mir?
   - Wie soll die Ausgabe strukturiert sein?
   - Welche Ratiodata-Standards müssen eingehalten werden?
   - Welche Compliance-/Sicherheitsaspekte sind relevant?

4. **Geben Sie den Prompt an Ihren KI-Assistenten**

5. **Testen Sie das generierte Skill** mit einem echten Beispiel aus Ihrer Arbeit

6. **Verfeinern Sie bei Bedarf** – Skills sind iterativ!

7. **Teilen Sie Ihr Skill** mit Kollegen über die Ratiodata KI-Community

---

## 💡 Best Practices für Ratiodata-Skills

**DO:**
✅ Ratiodata-Werte in Skills integrieren (Innovation, Zuverlässigkeit, Qualität, Sicherheit)  
✅ Compliance-Anforderungen explizit machen (DSGVO, BaFin, KRITIS)  
✅ Branchenkontexte berücksichtigen (Banken, Healthcare, Verwaltung)  
✅ Technische Präzision mit Business-Verständlichkeit kombinieren  
✅ Referenzen auf Ratiodata-Expertise und Track Record  
✅ SLA-Definitionen und Service-Levels klar definieren  
✅ Sicherheit und Datenschutz als Grundprinzipien, nicht als Add-on

**DON'T:**
❌ Keine generischen Marketing-Floskeln ("dynamisch", "innovativ")  
❌ Keine unrealistischen Versprechen ("100% Uptime", "Zero Downtime")  
❌ Keine Vendor Lock-in Strategien (immer Alternativen aufzeigen)  
❌ Keine unsicheren Code-Beispiele oder Best Practices  
❌ Keine Kundendaten oder sensible Informationen in Prompts  
❌ Keine rechtlich unkorrekte oder diskriminierende Sprache  
❌ Keine Abkürzungen ohne Erklärung (auch IT-Laien lesen mit)

---

## 🏢 Ratiodata-Spezifische Vorteile von Skills

**Für Ihr Team:**
- **Konsistenz**: Alle nutzen die gleichen hochwertigen Vorlagen
- **Effizienz**: Weniger Zeit für Routine-Dokumentation, mehr Zeit für strategische Arbeit
- **Qualität**: Standards (ITIL, TOGAF, BSI) sind direkt in Skills eingebaut
- **Onboarding**: Neue Mitarbeiter lernen Best Practices durch Skill-Nutzung
- **Knowledge Sharing**: Expertise von Senior-Kollegen wird in Skills kodifiziert

**Für Ratiodata:**
- **Professionalisierung**: Einheitliche, hochwertige Dokumente nach außen
- **Compliance**: Sicherheits- und Datenschutz-Standards automatisch eingehalten
- **Skalierbarkeit**: Mehr Projekte mit gleichen Ressourcen
- **Innovation**: Zeit für Wertschöpfung statt Administration
- **Kundenzufriedenheit**: Schnellere, präzisere Reaktionszeiten

---

## 📝 Zusätzliche Ressourcen

**Ratiodata Intranet:**
- Templates für Angebote, Service-Reports, Produktdokumentation
- Compliance-Checklisten (DSGVO, BaFin, KRITIS)
- Referenzarchitekturen und Solution Blueprints

**IT-Standards zum Nachschlagen:**
- ITIL 4 Foundation (Service Management)
- BSI IT-Grundschutz (Security Baseline)
- TOGAF (Enterprise Architecture)
- ISO/IEC 27001 (Information Security)
- Scrum/SAFe (Agile Frameworks)

**Best Practice Guides:**
- Ratiodata Styleguide für technische Dokumentation
- Angebots-Guideline für Vertrieb
- Incident Management Playbook
- Security Best Practices

---

**Viel Erfolg beim Erstellen Ihrer ersten Skills für Ratiodata!** 🎉

*Skills sind wie wiederverwendbare Funktionen in der Softwareentwicklung – einmal gut gebaut, immer wieder einsetzbar. Investieren Sie Zeit in gute Skill-Prompts, und Sie sparen ein Vielfaches dieser Zeit in Ihrer täglichen Arbeit.*

---

**Ein Tutorial der ADG KI-Community**

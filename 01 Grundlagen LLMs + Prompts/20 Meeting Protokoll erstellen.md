# Meeting-Protokolle mit KI erstellen
## Effiziente Dokumentation für IT-Profis bei Ratiodata

---

## 📋 Einführung: Warum KI-gestützte Meeting-Protokolle?

In einem IT-Systemhaus wie Ratiodata finden täglich zahlreiche Meetings statt – von Kundengesprächen über Projekt-Reviews bis zu internen Abstimmungen. Die manuelle Protokollierung kostet wertvolle Zeit und wichtige Details gehen oft verloren.

Sprachmodelle können Meeting-Transkripte in wenigen Sekunden analysieren und strukturierte, professionelle Protokolle erstellen. Diese Anleitung zeigt, wie Sie KI-Assistenten nutzen, um aus Meeting-Aufzeichnungen aussagekräftige Dokumentationen zu generieren – für Vertrieb, Service, Produktmanagement und alle anderen Bereiche bei Ratiodata.

**⏱️ Zeitaufwand:** 10-15 Minuten | **📚 Niveau:** Anfänger | **🎯 Ziel:** Professionelle Meeting-Protokolle mit KI erstellen

---

## 🎯 Was Sie lernen werden

Nach diesem Tutorial können Sie:
- Meeting-Transkripte automatisch in strukturierte Protokolle umwandeln
- Aufgaben, Entscheidungen und Verantwortlichkeiten extrahieren
- Professionelle Dokumentationen für verschiedene Stakeholder erstellen
- Datenschutz- und Compliance-Anforderungen bei der Protokollierung beachten
- Die Protokolle für verschiedene Ratiodata-Abteilungen anpassen

---

## 🔒 Sicherheitshinweis: Datenschutz bei Meeting-Transkripten

**Wichtig für Ratiodata-Mitarbeiter:**

- **Keine sensiblen Kundendaten:** Entfernen Sie Kundennamen, IP-Adressen, Zugangsdaten oder vertrauliche Projektdetails aus Transkripten
- **DSGVO-Konformität:** Anonymisieren Sie personenbezogene Daten vor der Verarbeitung
- **Vertrauliche Informationen:** Bei hochsensiblen Meetings (z.B. Banken-Projekte, Sicherheitsarchitekturen) keine externen KI-Tools nutzen
- **Interne Richtlinien:** Beachten Sie die IT-Sicherheitsrichtlinien der Ratiodata und der Atruvia AG
- **Vier-Augen-Prinzip:** Lassen Sie KI-generierte Protokolle immer von einem Menschen prüfen

---

## 📝 Grundlagen: Vom Transkript zum Protokoll

### Was ist ein Meeting-Transkript?

Ein Transkript ist die wörtliche Verschriftlichung eines Meetings. Es kann erstellt werden durch:
- **Automatische Tools:** Zoom, Microsoft Teams, Google Meet (integrierte Transkription)
- **KI-Transkriptionstools:** Wie Whisper, Otter.ai, oder ähnliche Dienste
- **Manuelle Aufzeichnung:** Notizen während des Meetings

### Was kann ein Sprachmodell daraus machen?

Ein KI-Assistent kann aus dem Rohtranskrip automatisch extrahieren:
- **Kernaussagen:** Die wichtigsten Diskussionspunkte
- **Entscheidungen:** Getroffene Beschlüsse mit Begründungen
- **Aufgaben:** Action Items mit Verantwortlichen und Deadlines
- **Risiken:** Identifizierte Probleme und Herausforderungen
- **Kennzahlen:** Genannte Zahlen, KPIs und Metriken

---

## 💼 Einsatzgebiete bei Ratiodata

### Für Vertrieb und Presales
- **Kundengespräche dokumentieren:** Anforderungen, technische Spezifikationen und Kundenanforderungen strukturiert festhalten
- **Angebotsnachbereitung:** Alle besprochenen Features und Preisvereinbarungen erfassen
- **Opportunity Management:** Nächste Schritte und Follow-ups klar definieren

### Für Service und Support
- **Incident-Meetings:** Problemanalysen, Lösungswege und Verantwortlichkeiten dokumentieren
- **Eskalations-Calls:** Kritische Informationen strukturiert aufbereiten
- **Customer Success Reviews:** Feedback und Verbesserungsmaßnahmen festhalten

### Für Software- und Produktmanagement
- **Sprint-Reviews:** Feature-Diskussionen und Entscheidungen protokollieren
- **Roadmap-Meetings:** Priorisierungen und strategische Weichenstellungen dokumentieren
- **Stakeholder-Meetings:** Requirements und Change Requests erfassen

### Für Hardware-Entwicklung
- **Produktspezifikations-Meetings:** Technische Anforderungen und Design-Entscheidungen
- **Lieferanten-Calls:** Vereinbarungen und technische Details festhalten
- **Quality Assurance Reviews:** Testberichte und Maßnahmen dokumentieren

---

## 🚀 Prompt-Variante 1: Detailliertes IT-Protokoll

Diese Variante eignet sich besonders für **technische Meetings** und **Projekt-Reviews**, bei denen präzise Dokumentation wichtig ist.

### Der Prompt

```
**Rolle**
Du bist ein professioneller Meeting-Analyst für IT-Systemhäuser. Du erstellst aus Transkripten präzise, umsetzbare Protokolle für IT-Profis und Führungskräfte. Schreibe auf Deutsch, neutral und knapp.

**Kontext**
Du erhältst ein vollständiges Meeting-Transkript (mehrere Sprecher, informell, Themenwechsel möglich). Destilliere daraus ein strukturiertes, revisionssicheres Protokoll für die Ratiodata SE.

**Instruktionen**

1. Lies das gesamte Transkript.
2. Erfasse Meeting-Metadaten (Titel, Datum, Uhrzeit, Dauer, Teilnehmer mit Rollen, Abwesende, Quelle, Vertraulichkeitsstufe „Intern – Ratiodata SE").
3. Liste Hauptthemen/Agenda.
4. Erstelle pro Thema eine kurze Zusammenfassung (max. 3–5 Bulletpoints) und das Decision Log.
5. Extrahiere Schlüsselerkenntnisse/Key Takeaways (geschäftsrelevant, messbar).
6. Erfasse Aufgaben (Action Items) tabellarisch.
7. Liste Follow-ups und Open Issues (inkl. offene Fragen).
8. Dokumentiere Risiken/Abhängigkeiten/Annahmen.
9. Führe Unsicherheiten/Unverständlichkeiten mit Zeitstempel und Vertrauenslevel (H/M/L) auf.
10. Schlage optional nächstes Meeting (Datum/Agenda-Entwurf) vor, falls erwähnt.
11. Redaktion/Compliance: Schwärze sensible Daten (Kundennamen, IP-Adressen, Zugangsdaten, vertrauliche Projektdetails) als „[redacted]". Keine Spekulation, keine Inhalte außerhalb des Transkripts.
12. Normen:
    - Datumsformat YYYY-MM-DD (oder „tbd")
    - Namen als „Vorname Nachname (Rolle/Team)"
    - Zeiten als HH:MM:SS referenzieren
    - Bei fehlenden Infos klar „unbekannt"/„tbd" notieren

**Ausgabeformat (Markdown)**

### Meeting-Metadaten
- Titel: …
- Datum/Uhrzeit: … – … (Dauer: …)
- Teilnehmer: …
- Abwesend: …
- Quelle/Version: …
- Vertraulichkeit: Intern – Ratiodata SE

### Hauptthemen
- …

### Zusammenfassungen & Entscheidungen

**Thema A**
- Kurzfassung: …
- **Decision Log**

| ID  | Entscheidung | Entscheider | Gültig ab  | Betroffene Bereiche | Timestamp |
|-----|--------------|-------------|-----------|---------------------|-----------|
| D-1 | …            | …           | 2025-10-23| …                   | 00:42:15  |

### Key Takeaways
- …

### Aufgaben (Action Items)

| ID  | Aufgabe | Owner (Rolle)        | Fällig         | Prio | Abhängigkeiten | Status | Quelle   |
|-----|---------|---------------------|----------------|------|----------------|--------|----------|
| A-1 | …       | Max Mustermann (PM) | 2025-11-05     | M    | A-0            | Neu    | 00:37:02 |

### Follow-ups
- …

### Open Issues
- …

### Risiken & Annahmen
- …

### Unsicherheiten & Klärungsbedarf
- 00:18:47 – unverständlich – Vertrauenslevel: M – möglicher Sprecher: …

### Nächstes Meeting (falls vorhanden)
- Datum/Ziel/Agenda-Entwurf: …

**Eingabeaufforderung:**
Bitte füge das Meeting-Transkript ein (Text oder Datei). Optional: gewünschte Priorisierungsskala und ob Punkt 11 bereits bereinigt ist.
```

### Anwendungsbeispiel: Service-Incident-Meeting

**Szenario:** Ein kritischer Systemausfall bei einem Managed-Services-Kunden wurde in einem Emergency-Call besprochen. Das Team muss die Ursache, die Sofortmaßnahmen und die langfristigen Verbesserungen dokumentieren.

**So wenden Sie den Prompt an:**

1. **Transkript vorbereiten:** Exportieren Sie das Transkript aus Ihrem Meeting-Tool (z.B. Teams)
2. **Sensible Daten entfernen:** Ersetzen Sie Kundennamen durch "Kunde A", IP-Adressen durch "[IP]", etc.
3. **Prompt + Transkript einfügen:** Kopieren Sie den Prompt in Ihr KI-Tool und fügen das bereinigte Transkript darunter ein
4. **Protokoll generieren lassen:** Die KI erstellt automatisch ein strukturiertes Protokoll
5. **Manuelle Prüfung:** Kontrollieren Sie alle technischen Details und Action Items
6. **Verteilen:** Senden Sie das Protokoll an alle Beteiligten

---

## 📊 Prompt-Variante 2: Management-Summary-Fokus

Diese Variante ist ideal für **Führungskräfte** und **Stakeholder-Kommunikation**, wenn eine kompakte Executive Summary wichtiger ist als alle Details.

### Der Prompt

```
TRANSKRIPT = [Füge hier das vollständige Meeting-Transkript ein]
MEETING_TYP = [Art des Meetings, z.B. Projekt-Review, Verkaufsgespräch, Sprint-Planning, Eskalations-Call, Roadmap-Meeting]
ZIELGRUPPE = [Zielgruppe des Dokuments, z.B. Geschäftsführung, Bereichsleitung, Projektteam, Kunde]

Analysiere das bereitgestellte TRANSKRIPT des MEETING_TYP.
Identifiziere die wichtigsten Teilnehmenden, ihre Funktionen und Rollen. Beschreibe kurz den Ablauf und die Struktur des Meetings (Einleitung, Themenblöcke, Abschluss).

**1. Hauptthemen und Diskussionen**
- Fasse die zentralen Diskussionspunkte prägnant zusammen.
- Stelle den Zusammenhang zwischen den Themenblöcken her.

**2. Entscheidungen und Beschlüsse**
- Liste alle getroffenen Entscheidungen und deren Begründungen auf.
- Notiere ggf. offene Punkte oder vertagte Entscheidungen.

**3. Aufgaben und Verantwortlichkeiten (Action Items)**
- Erstelle eine übersichtliche Liste aller vereinbarten Maßnahmen.
- Gib jeweils den/die Verantwortliche(n) und die Frist/Deadline an.

**4. Ziele und Ergebnisse des Meetings**
- Fasse die übergeordneten Ziele des Meetings zusammen.
- Erläutere, inwieweit diese Ziele erreicht oder weiterverfolgt werden.

**5. Kennzahlen, KPIs und relevante Daten**
- Extrahiere alle im TRANSKRIPT genannten Zahlen, Kennzahlen oder Leistungsindikatoren.
- Stelle sie in klarer, strukturierter Form dar (z.B. Tabelle oder Aufzählung).

**6. Risiken, Herausforderungen und Maßnahmen**
- Identifiziere alle Risiken, Probleme oder Bedenken, die während des Meetings genannt wurden.
- Ergänze, falls vorhanden, die besprochenen Lösungsansätze oder Gegenmaßnahmen.

**7. Ressourcen und Werkzeuge**
- Liste alle erwähnten Dokumente, Tools, Systeme oder benötigten Ressourcen auf.

**8. Nächste Schritte (Next Steps)**
- Fasse die unmittelbar nach dem Meeting anstehenden Schritte zusammen.
- Verknüpfe diese mit Verantwortlichkeiten und Terminen.

**9. Fortschritt laufender Projekte (falls zutreffend)**
- Beschreibe den aktuellen Status laufender Initiativen oder Programme, sofern im TRANSKRIPT besprochen.

**10. Executive Summary (Management-Zusammenfassung)**
- Erstelle eine kurze, prägnante Zusammenfassung für die ZIELGRUPPE.
- Hebe die wichtigsten Ergebnisse, Entscheidungen und nächsten Schritte hervor.
- Achte auf klare, sachliche und professionelle IT-Sprache (neutral, technisch präzise, business-orientiert).

**11. Vertraulichkeit und Qualitätssicherung**
- Überprüfe den finalen Text auf Klarheit, Einheitlichkeit und Relevanz für die ZIELGRUPPE.
- Stelle sicher, dass vertrauliche Informationen (Kundendaten, Sicherheitsarchitekturen, strategische Informationen, Zugangsdaten) korrekt behandelt und nicht unbefugt offengelegt werden.
- Beachte die Datenschutzrichtlinien der Ratiodata SE, Atruvia AG und DSGVO-Konformität.
- Berücksichtige regulatorische Anforderungen (besonders bei Banken-Projekten, Healthcare, öffentliche Verwaltung).

**12. Struktur und Formatierung**
- Erstelle eine klare, logisch gegliederte Dokumentstruktur mit Überschriften.
- Nutze Markdown für professionelle Formatierung.

Zum Schluss:
Erstelle eine kurze Zusammenfassung des gesamten Dokuments, die den Zweck und Mehrwert für die ZIELGRUPPE erläutert.
```

### Anwendungsbeispiel: Vertriebsgespräch mit Neukunde

**Szenario:** Ein Solution Architect und ein Account Manager haben ein erstes Beratungsgespräch mit einem potenziellen Kunden aus dem Bankensektor geführt. Die Geschäftsführung benötigt eine kompakte Zusammenfassung der Opportunity.

**So wenden Sie den Prompt an:**

```
TRANSKRIPT = [Bereinigtes Transkript des Kundengesprächs]
MEETING_TYP = Erstes Beratungsgespräch / Solution Discovery
ZIELGRUPPE = Geschäftsführung Ratiodata SE, Vertriebsleitung

[Dann den Prompt mit ausgefüllten Platzhaltern an die KI übergeben]
```

**Das Ergebnis:**
- Kompakte Executive Summary für die Geschäftsführung
- Technische Requirements für das Solution Design
- Budgetrahmen und Zeitplan
- Nächste Schritte und Verantwortlichkeiten
- Risiken (z.B. Compliance-Anforderungen im Bankensektor)

---

## 💡 Best Practices: So erstellen Sie optimale Protokolle

### 1. Transkript-Qualität ist entscheidend

**Gute Ausgangsbasis:**
- Verwenden Sie hochwertige Audio-Aufnahmen
- Nutzen Sie Headsets bei virtuellen Meetings
- Vermeiden Sie Hintergrundgeräusche
- Lassen Sie Sprecher sich zu Beginn kurz vorstellen

**Transkript nachbearbeiten:**
- Entfernen Sie Füllwörter und Versprecher nur, wenn nötig
- Korrigieren Sie Eigennamen, Fachbegriffe und Produktbezeichnungen
- Markieren Sie unverständliche Passagen

### 2. Datenschutz von Anfang an mitdenken

**Vor der KI-Verarbeitung:**
- Erstellen Sie eine Checkliste sensibler Informationen
- Nutzen Sie Suchen-und-Ersetzen für wiederkehrende sensible Begriffe
- Anonymisieren Sie systematisch (Kunde A, System B, IP-[1], etc.)

**Typische sensible Daten bei Ratiodata:**
- Kundennamen (besonders bei Banken, Healthcare)
- IP-Adressen, Server-Namen, Netzwerk-Topologien
- Zugangsdaten, API-Keys, Zertifikate
- Preise, Margen, Vertragsdetails
- Sicherheitslücken oder Schwachstellen
- Personenbezogene Daten von Mitarbeitern oder Endkunden

### 3. Die richtige Variante für den richtigen Zweck

**Nutzen Sie Variante 1 (Detailliert) für:**
- Technische Projekt-Reviews
- Incident Post-Mortems
- Sprint-Plannings und Retrospektiven
- Compliance-relevante Meetings

**Nutzen Sie Variante 2 (Management-Fokus) für:**
- Kundengespräche mit Sales-Beteiligung
- Strategiemeetings
- Führungskräfte-Briefings
- Quartals-Reviews

### 4. Nachbearbeitung ist Pflicht

**Prüfen Sie immer:**
- ✅ Sind alle Action Items realistisch und klar formuliert?
- ✅ Sind die Verantwortlichkeiten eindeutig zugeordnet?
- ✅ Sind Deadlines plausibel?
- ✅ Wurden technische Details korrekt erfasst?
- ✅ Sind alle sensiblen Daten entfernt?
- ✅ Ist die Tonalität angemessen für die Zielgruppe?

**Typische Fehler von KI-Tools:**
- Missverständnisse bei Fachbegriffen
- Verwechslung von Sprechern
- Fehlende Kontexte bei Akronymen
- Überinterpretation von informellen Aussagen

---

## ⚠️ Compliance & Rechtliches: Was Sie beachten müssen

### DSGVO-konforme Protokollierung

**Personenbezogene Daten minimieren:**
- Protokollieren Sie nur, was geschäftlich notwendig ist
- Anonymisieren Sie, wo möglich
- Löschen Sie Aufzeichnungen nach definierter Frist

**Rechtsgrundlage sicherstellen:**
- Bei Kundenmeeting: Einwilligung zur Aufzeichnung einholen
- Bei internem Meeting: Betriebsvereinbarung beachten
- Informieren Sie alle Teilnehmer über die Aufzeichnung

### Besondere Anforderungen bei regulierten Branchen

**Bankensektor (wichtig für Ratiodata):**
- Strengere Dokumentationspflichten (MaRisk, BAIT)
- Protokolle können aufsichtsrechtlich relevant sein
- Besondere Vertraulichkeit bei Sicherheitsthemen

**Healthcare:**
- Keine Patientendaten in externen KI-Tools
- Verschlüsselte Speicherung von Protokollen
- Zugriffsbeschränkungen implementieren

**Öffentliche Verwaltung:**
- Transparenzpflichten beachten
- Archivierungsfristen einhalten
- Datenschutz-Folgenabschätzung prüfen

---

## 🎯 Praktische Übung: Erstellen Sie Ihr erstes KI-Protokoll

### Schritt 1: Meeting vorbereiten
Wählen Sie ein vergangenes Meeting aus (z.B. Team-Meeting, Kundenabstimmung, Projekt-Review). Wenn Sie ein Transkript haben, nutzen Sie dieses. Ansonsten erstellen Sie eine kurze Zusammenfassung des Meetings mit den wichtigsten Aussagen.

### Schritt 2: Sensible Daten entfernen
Gehen Sie das Transkript durch und ersetzen Sie:
- Kundennamen → "Kunde A", "Kunde B"
- Systemnamen → "System 1", "System 2"
- IP-Adressen → "[IP]"
- Zugangsdaten → "[redacted]"

### Schritt 3: Passenden Prompt wählen
Entscheiden Sie, welche Variante für Ihr Meeting besser geeignet ist:
- Technisches Projekt-Meeting? → Variante 1
- Stakeholder-Kommunikation? → Variante 2

### Schritt 4: Prompt anpassen
Füllen Sie die Platzhalter aus:
- MEETING_TYP: z.B. "Sprint-Review Software-Entwicklung"
- ZIELGRUPPE: z.B. "Produktmanagement und Entwicklungsteam"

### Schritt 5: KI generieren lassen
Kopieren Sie Prompt + bereinigtes Transkript in Ihr KI-Tool (z.B. ein Sprachmodell Ihrer Wahl).

### Schritt 6: Qualitätskontrolle
Prüfen Sie das generierte Protokoll:
- Sind die Action Items vollständig und korrekt?
- Sind alle Entscheidungen nachvollziehbar dokumentiert?
- Ist die Sprache angemessen für die Zielgruppe?
- Sind alle sensiblen Daten geschwärzt?

### Schritt 7: Finalisieren und verteilen
Nehmen Sie letzte Anpassungen vor und versenden Sie das Protokoll an die Teilnehmer.

---

## 📈 Erweiterte Techniken

### 1. Protokolle für verschiedene Stakeholder erstellen

Aus einem Meeting können Sie mehrere Versionen des Protokolls erstellen:

**Für die Geschäftsführung:**
- Fokus auf Executive Summary
- Budgetauswirkungen hervorheben
- Strategische Entscheidungen betonen
- Risiken und Chancen

**Für das Projektteam:**
- Detaillierte Action Items
- Technische Spezifikationen
- Abhängigkeiten und Blocker
- Nächste Schritte

**Für den Kunden:**
- Professionelle, reduzierte Sprache
- Fokus auf Ergebnisse und Mehrwert
- Interne Details weglassen
- Positive, lösungsorientierte Tonalität

### 2. Follow-up-Prompts für spezifische Aufgaben

Nach der Erstellung des Protokolls können Sie mit Follow-up-Prompts arbeiten:

```
Erstelle aus den Action Items eine formatierte E-Mail an das Team 
mit einer Erinnerung an die Deadlines und Verantwortlichkeiten.
```

```
Generiere eine kompakte Folie (Textformat) für das Management-Board 
mit den Top-3-Erkenntnissen und Top-3-Risiken aus diesem Meeting.
```

```
Erstelle eine Checkliste für das nächste Follow-up-Meeting, 
basierend auf den offenen Punkten und Aufgaben.
```

### 3. Templates für wiederkehrende Meeting-Typen

Wenn Sie regelmäßig ähnliche Meetings haben, erstellen Sie angepasste Prompt-Templates:

**Sprint-Review-Template:**
- Standardisierte Struktur: Demo, Backlog, Team-Feedback
- Vordefinierte Kategorien für User Stories
- Automatische Velocity-Berechnung

**Customer-Success-Review-Template:**
- NPS-Score und Kundenfeedback
- Support-Tickets und Lösungszeiten
- Upselling-Potenziale
- Renewal-Wahrscheinlichkeit

---

## 🔄 Integration in den Ratiodata-Workflow

### Empfohlener Prozess für Teams

1. **Meeting-Aufzeichnung aktivieren** (mit Einwilligung aller Teilnehmer)
2. **Transkript exportieren** (automatisch nach Meeting-Ende)
3. **Sensible Daten bereinigen** (durch Meeting-Leiter oder Protokollant)
4. **KI-Protokoll generieren** (mit passendem Prompt)
5. **Qualitätskontrolle** (durch Meeting-Leiter)
6. **Protokoll verteilen** (E-Mail oder in Confluence/SharePoint ablegen)
7. **Action Items ins Ticketsystem** (Jira, Azure DevOps, etc.)

### Tool-Integrationen

**Für optimale Ergebnisse können Sie kombinieren:**
- **Meeting-Tool:** Microsoft Teams, Zoom (für Transkription)
- **KI-Assistent:** Beliebiges Sprachmodell (für Protokollerstellung)
- **Dokumentenverwaltung:** Confluence, SharePoint (für Ablage)
- **Ticketsystem:** Jira, Azure DevOps (für Action Items)
- **Kalender:** Outlook, Google Calendar (für Follow-up-Meetings)

---

## ⚡ Quick Reference: Die wichtigsten Dos and Don'ts

### ✅ DOs

- **Immer Datenschutz priorisieren** – lieber zu vorsichtig als zu nachlässig
- **Protokolle manuell gegenlesen** – KI macht Fehler bei Fachbegriffen
- **Klare Verantwortlichkeiten** – jedes Action Item braucht einen Owner
- **Deadlines realistisch setzen** – KI kann Zeitaufwand nicht einschätzen
- **Für die Zielgruppe schreiben** – Geschäftsführung braucht andere Infos als Entwickler
- **Transkripte aufbewahren** – falls Rückfragen zum Protokoll kommen
- **Feedbackschleife etablieren** – lernen Sie aus jeder Protokoll-Erstellung

### ❌ DON'Ts

- **Niemals ungeprüfte Protokolle versenden** – Qualitätskontrolle ist Pflicht
- **Keine sensiblen Daten in externen KI-Tools** – Compliance-Risiko
- **Nicht blind auf KI-Entscheidungen vertrauen** – technische Details prüfen
- **Keine unvollständigen Transkripte verwenden** – Qualität des Inputs = Qualität des Outputs
- **Nicht ohne Einwilligung aufzeichnen** – rechtliche Risiken
- **Keine Protokolle ohne Kontext** – immer Meeting-Typ und Zielgruppe definieren

---

## 🎓 Zusammenfassung

KI-gestützte Meeting-Protokolle können bei Ratiodata erheblich Zeit sparen und die Dokumentationsqualität verbessern. Die beiden vorgestellten Prompt-Varianten decken unterschiedliche Anforderungen ab:

- **Variante 1** für detaillierte, technische Dokumentation
- **Variante 2** für kompakte Management-Summaries

Entscheidend für den Erfolg sind:
1. **Hochwertige Transkripte** als Ausgangsbasis
2. **Konsequente Datenschutz-Prüfung** vor KI-Verarbeitung
3. **Manuelle Qualitätskontrolle** nach der Generierung
4. **Anpassung an Zielgruppe** und Meeting-Typ

Mit etwas Übung werden Sie schnell routiniert im Umgang mit KI-Protokollen und können diese Technik zu einem wertvollen Werkzeug in Ihrem Arbeitsalltag machen.

---

## 📚 Weiterführende Ressourcen

**Interne Ratiodata-Dokumentation:**
- IT-Sicherheitsrichtlinien der Ratiodata SE
- DSGVO-Leitfaden für Mitarbeiter
- Compliance-Anforderungen bei Banken-Projekten
- Dokumentations-Templates (Confluence)

**Externe Quellen:**
- Datenschutz-Grundverordnung (DSGVO)
- BaFin-Richtlinien für IT-Dienstleister (MaRisk)
- Best Practices für Meeting-Management

---

**Ein Tutorial der ADG KI-Community**

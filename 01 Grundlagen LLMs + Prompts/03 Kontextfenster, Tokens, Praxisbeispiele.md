# 📚 Teil A: Grundverständnis – Wie KI mit Sprache arbeitet 

## Kapitel 1: Wie „denkt" eine KI? 🟢 Basis

### Die Wahrscheinlichkeits-Maschine

Stellen Sie sich ein Wort-Ergänzungsspiel vor. Genau das macht ein Sprachmodell – nur mit Statistik.

**Beispiel (vereinfacht):**

```
"Der Kunde benötigt eine IT-Sicherheitslösung für..."
→ KI berechnet Wahrscheinlichkeiten:
   - Endpoint Protection (38 %)
   - Netzwerksicherheit (27 %)
   - Cloud-Security (22 %)
   - Backup-Lösung (9 %)
```

Die KI hat aus sehr vielen Texten gelernt, **welche Wörter typischerweise aufeinander folgen**. Sie „versteht" nicht wie ein Mensch – sie **erkennt und reproduziert Muster**.

### 🎯 Merksätze

* KI = Mustererkennung + Wahrscheinlichkeiten, kein echtes Verständnis.
* Antworten sind **Token für Token** berechnete Vorschläge.
* Wer **klare Vorgaben** macht, bekommt **klare Ergebnisse**.

**Praktisches Ratiodata-Beispiel:**

```
Prompt: "Erstelle eine Betreffzeile für eine Kunden-E-Mail zur neuen Managed Service-Lösung."
KI denkt u.a.:
- "Ihre neue Managed Service-Lösung: Alle Details im Überblick"
- "Managed Services von Ratiodata – Ihr Mehrwert ab sofort"
```

---

## Kapitel 2: Tokens – Die Bausteine der KI-Kommunikation 🟢 Basis

### Was sind Tokens?

Tokens sind kleinste Spracheinheiten (ähnlich Silben/Wortteile). Denken Sie an **Legosteine**.

**Visualisierung (vereinfachend):**

```
"Systemintegration" → [Sys][tem][in][te][gra][tion]  ≈ 6 Tokens
"Bankentechnologie" → [Ban][ken][tech][no][lo][gie]  ≈ 6 Tokens
"Cybersecurity-Lösung" → [Cy][ber][se][cu][ri][ty][-][Lö][sung] ≈ 9 Tokens
```

**Grobe Faustregel (Deutsch):**

* **1 Token ≈ 4 Zeichen**
* **100 Tokens ≈ 70–80 Wörter**
* **Eine A4-Seite ≈ 500–700 Tokens** (je nach Dichte)

**Kostenbewusstsein (modellabhängig):**

```
Kurzer Betreff (10 Wörter)   ≈ 15 Tokens
Mail-Absatz (100 Wörter)     ≈ 130 Tokens
Eine Seite (500 Wörter)      ≈ 650 Tokens
Kapitel (2.000 Wörter)       ≈ 2.600 Tokens
```

**Übung 1 – Token schätzen**

1. „DSGVO" → ___ Tokens
2. „Systemintegration" → ___ Tokens
3. „Bankentechnologie" → ___ Tokens

*Lösung (typisch):* 1) 1–2  |  2) 4–5  |  3) 5–6

**Warum wichtig?**

* **Jeder Token kostet** (Zeit & Geld).
* **Kürzer & strukturierter** = schneller & günstiger.
* **Limits** begrenzen, wie viel Kontext die KI gleichzeitig „im Kopf" hat.

---

## Kapitel 3: Das Kontextfenster – das Arbeitsgedächtnis der KI 🟢 Basis

Die KI arbeitet mit einem **Notizblock**. Alles, was Sie eingeben (und was die KI ausgibt), muss auf diesen Block passen.

**Richtwerte (modell-/anbieterabhängig, ändern sich laufend):**

```
Typische Größen: ~128.000 bis >1.000.000 Tokens
→ von „mehreren Dutzend" bis „vielen Hundert" A4-Seiten
```

**Wenn der Block voll ist:**

```
[Frühere Angebote] → [Zwischenergebnisse] → [Aktuelles] → [VOLL]
         ↑                                    ↑
     wird verdrängt                      bleibt erhalten
```

**Token sparen – Beispiel:**

```
Schlecht:
"Ich hoffe, Sie haben einen schönen Tag. Ich hätte da eine Anfrage ... könnten Sie mir bitte mal auflisten ..."
→ viele Füllwörter, hohe Kosten

Gut:
"Liste: 5 Vorteile von Managed Services für mittelständische Banken. Je Punkt max. 20 Wörter."
→ präzise, günstig
```

---

## Kapitel 4: Den Token-Fluss verstehen 🟡 Mittel

So verarbeitet die KI Ihren Text:

```
1) EINGABE (Prompt)
2) TOKENISIERUNG  → Zerlegung in Tokens
3) VERARBEITUNG   → Musterabgleich
4) GENERIERUNG    → Ausgabe Token für Token
5) AUSGABE        → fertiger Text
```

**Generierung geschieht sequenziell (vereinfacht):**

```
Schritt 1: "Die" 
Schritt 2: "Die Lösung" 
Schritt 3: "Die Lösung bietet" 
Schritt 4: "Die Lösung bietet maximale..." 
```

**Übung 2 – Prompt kürzen**

* „Könntest du bitte so freundlich sein und mir erklären…"
  → „Erkläre kurz…"
* „Ich würde gerne von dir wissen, falls es möglich ist…"
  → „Nenne bitte…"
* „Es wäre super, wenn du mir sagen könntest…"
  → „Sag mir…"

---

# 📝 Teil B: Erste Schritte – Prompts für den Ratiodata-Alltag

## Kapitel 5: Die 4-K-Formel 🟢 Basis

1. **K**ontext – Worum geht's?
2. **K**onkrete Aufgabe – Was genau tun?
3. **K**riterien – Tonalität, Tiefe, Umfang, Prüfschritte
4. **K**ontrolle – Format (Liste/Tabelle), Länge, Zielgruppe

**Beispiel (Vertriebskonzept):**

```
Kontext: Kundenpräsentation für Sparkasse, Thema "Cloud-Migration für Kernbanksysteme".
Aufgabe: 3 Migrationsszenarien mit Pro/Contra.
Kriterien: Technisch fundiert, DSGVO-konform, BaFin-Anforderungen berücksichtigen.
Kontrolle: Tabelle, max. 10 Zeilen, am Ende 1 Empfehlungssatz.
```

---

## Kapitel 6: Kontext aufbauen und halten 🟡 Mittel

**Technik „Roter Faden"**

```
P1: "Thema: Planung Cybersecurity-Kampagne Q1/2026. Ziele: KMU, Banken, öffentliche Verwaltung."
P2: "Empfiehl 5 Marketingkanäle, je 1 Satz Nutzen für die Zielgruppe."
P3: "Für Kanal 2: Entwurf eines 3-Monats-Content-Plans."
```

**Technik „Zwischenbilanz"**

```
"Fasse zusammen:
- Ziele (Stichpunkte)
- Entscheidungen offen
- Nächste Schritte (verantwortlich + Termin)"
```

**Technik „Checkpoint"**

```
"Checkpoint:
Wir arbeiten an [Thema].
Bisher: [Ergebnisse].
Fehlt: [Lücken].
Nächster Schritt: [Aufgabe + Format]."
```

**Übung 3 – Kontext-Kette (Kundenbindung)**

1. „Nenne 3 Hauptgründe für Kundenabwanderung im IT-Systemhaus-Geschäft."
2. „Entwickle für Grund 1 drei Gegenmaßnahmen (Ratiodata-Kontext)."
3. „Erstelle To-do-Liste 90 Tage, Verantwortliche & Meilensteine."

---

## Kapitel 7: Token-Sparstrategien 🟡 Mittel

**1) Abkürzungen definieren**

```
"Ab jetzt:
MS = Managed Services
SLA = Service Level Agreement
ISMS = Information Security Management System
Erstelle MS-Angebot mit ISMS-Zertifizierung und 99,9% SLA."
```

**2) Struktur erzwingen**

```
"Ausgabe als Tabelle:
Spalte: Lösung | Nutzen | Aufwand | Zielgruppe | Lieferzeit"
```

**3) Inkrementell arbeiten**

```
Schritt 1: "Liste 5 Herausforderungen bei der IT-Modernisierung von Banken."
Schritt 2: "Detailliere Herausforderung 3 (Ursache/Wirkung/Lösung)."
Schritt 3: "Erstelle Maßnahmenplan (Owner + Termin)."
```

**Mini-Tabelle**

| Technik                        | Vorher | Nachher | Ersparnis |
| ------------------------------ | ------ | ------- | --------- |
| Abkürzungen & Glossar          | 150    | 90      | ~40%      |
| Listen/Tabelle statt Fließtext | 300    | 120     | ~60%      |
| Präzise Längen-Vorgaben        | 500    | 200     | ~60%      |

---

## Kapitel 8: Häufige Anfängerfehler 🟢 Basis

* **Romansprache** → direkt, kurz, sachlich.
* **„Erzähl mir alles…"** → lieber modular (Teilthemen).
* **Kontextverlust** → regelmäßig **Zusammenfassen lassen**.
* **Format vergessen** → **Liste/Tabelle** explizit verlangen.

**Checkliste vor dem Senden**

* [ ] präzise Aufgabe?
* [ ] ein Thema?
* [ ] Format + Länge vorgegeben?
* [ ] Kundendaten/vertrauliche Informationen entfernt/anonymisiert?

---

# 🚀 Teil C: Praxis im Ratiodata-Alltag

## Kapitel 9: Mini-Projekt – Vertriebskampagne erstellen 🟡 Mittel

**Phase 1 – Grundlagen (Token-Budget ~100)**

```
Prompt 1.1:
"Erstelle 3 Personas für IT-Entscheider (CIO Mittelstandsbank / IT-Leiter Kommune / Geschäftsführer KMU).
Je Persona: Rolle | Hauptziel | Bedenken | Entscheidungskriterium (je max. 8 Wörter)."
```

**Phase 2 – Strategie (Token-Budget ~150)**

```
Prompt 2.1:
"Für Persona 'CIO Mittelstandsbank': 3 Maßnahmen zur Steigerung der IT-Sicherheit mit Ratiodata.
Format: Überschrift + 1 Satz Nutzen."
```

**Phase 3 – Inhalte (Token-Budget ~200)**

```
Prompt 3.1:
"Entwirf Executive Summary für Geschäftsleitung (max. 120 Wörter).
Ton: professionell, lösungsorientiert, technisch versiert. Am Ende 1 Handlungsempfehlung."
```

**Ihre Aufgabe:**
Dokumentieren Sie je Schritt: geschätzte Tokens, Qualität (Schulnote), Verbesserungsideen.

---

## Kapitel 10: Fortgeschrittene Techniken 🔴

**1) Denkkette anfordern (ohne sensible Daten)**

```
"Leite Schritt für Schritt her:
1) Problemdefinition
2) Annahmen
3) Optionen
4) Entscheidungskriterien
5) Empfehlung (1 Satz)"
```

**2) Few-Shot (mit Muster)**

```
"Beispiel-Angebotsbeschreibung:
- Lösung: Managed Firewall Service
- Nutzen: 24/7-Überwachung, automatische Updates
- Zielgruppe: Mittelständische Banken
- Preis: ab 2.500 €/Monat

Erstelle 2 ähnliche Beschreibungen für 'Backup-as-a-Service' und 'Security Operations Center'."
```

**3) Rollenwechsel**

```
"Du bist Solutions Architect bei der Ratiodata SE.
Ziel: 60-Minuten-Agenda für Kundenpräsentation 'Cloud-Migration Kernbanksystem'.
Erstelle Ablauf + Zeitboxen + Output je Abschnitt."
```

**4) Iteration**

```
Runde 1: "Grobkonzept Cybersecurity-Kampagne für KMU."
Runde 2: "Verdichte auf 1 Seite, Tabelle statt Fließtext."
Runde 3: "Prüfe auf DSGVO/BSI-Compliance; ergänze Sicherheitshinweise."
```

---

## Kapitel 11: Token-Optimierung für Profis 🔴

**80/20-Regel:**
Die **Qualität** hängt vor allem von **Ziel, Format, Länge** ab.

**Prioritäten**

* **Hoch:** Ziel, Format/Struktur, Länge
* **Mittel:** Zielgruppe, Tonalität, Beispiele
* **Niedrig:** Floskeln, Wiederholungen

**Hacks**

```
Batch:
"Für Vertrieb, Marketing, Service:
je: Ziel (6 Wörter) | 3 KPIs | Frist (Datum)."

Template:
"[Thema]: [Ziel], [KPI], [Deadline], [Owner]."

Komprimierung:
Statt "Bitte erstelle ...": "Erstelle ..."
```

---

## Kapitel 12: Workshop mit Lösungen 🟢–🔴

**🟢 Aufgabe 1 – Token-Bewusstsein (Thema: Produktbeschreibung)**

* Lang (50+): „Ich würde sehr gerne eine ausführliche, leicht verständliche Beschreibung…"
* Mittel (≈20): „Produktbeschreibung Managed Services, 5 Sätze, B2B-Ton."
* Kurz (≈10): „Produktbeschreibung Managed Services – 5 Sätze."

**🟡 Aufgabe 2 – Kontext-Management (Kundenzufriedenheit)**

1. „Nenne 3 Gründe für sinkende Kundenzufriedenheit im Service-Geschäft."
2. „Für Grund 1: 3 Verbesserungsmaßnahmen."
3. „Maßnahme 2: Umsetzungsplan 6 Monate."
4. „Rollen/Owner + Meilensteine."
5. „KPIs (5) + Zielwerte."

**🔴 Aufgabe 3 – Prompt-Architektur (Budget ~500 Tokens)**

```
PROJEKT: Vertriebskonzept "Cybersecurity für Banken"

PHASE 1 – Analyse (~120):
- Matrix: 3 Bankgrößen × 3 Bedrohungsszenarien
- je Feld: Risiko (≤6 Wörter)

PHASE 2 – Lösungen (~150):
- 3 Security-Pakete (Basic/Professional/Enterprise)
- je: Leistungen (kurz), Investition (3), SLA (3)

PHASE 3 – Umsetzung (~150):
- Roadmap 4 Quartale, Meilensteine, Verantwortliche

PHASE 4 – Entscheidung (~80):
- Entscheidungskriterien (5) + Empfehlung (1 Satz)
Format: Tabellen + Stichpunkte.
```

---

# 🧰 Teil D: Ratiodata-spezifische Use-Cases & Prompt-Vorlagen

## 1) Vertrieb – Lösungskonzept für Kundenpräsentation

```md
Kontext: Lösungskonzept "[Thema]" für [Kunde], Präsentation am [Datum].
Aufgabe: 3 Lösungsoptionen mit Pro/Contra/Investition.
Kriterien: Technisch fundiert, kundenspezifisch, DSGVO-konform, keine Preisdetails ohne Freigabe.
Kontrolle: Tabelle (Option | Nutzen | Risiko | Investition | Lieferzeit | Ansprechpartner).
```

## 2) Service – Ticket-Analyse und Lösungsvorschlag

```md
Kontext: Komplexes Support-Ticket von [Kunde], Thema [Problem].
Aufgabe: Analysiere Problem, priorisiere 3 Lösungsansätze.
Kriterien: Technisch korrekt, keine Kundendaten preisgeben, eskalationsfähig.
Kontrolle: Liste + Lösungstabelle (Ansatz | Aufwand | Risiko | SLA-Auswirkung).
```

## 3) Marketing – Kampagnenplanung für neue Lösung

```md
Kontext: Produktlaunch [Lösung], Zielgruppe [Branche/Unternehmensgröße].
Aufgabe: 5-Kanal-Strategie mit Budgetvorschlag.
Kriterien: Messbar, B2B-fokussiert, Ratiodata-Markenwerte integriert.
Kontrolle: Tabelle (Kanal | Maßnahmen | Budget | KPIs | Owner | Zeitplan).
```

## 4) Software/Produktmanagement – User Story Template

```md
Kontext: Feature-Request für [Produkt], Stakeholder [Team/Kunde].
Aufgabe: Erstelle 3 User Stories im Format "Als [Rolle] möchte ich [Ziel], damit [Nutzen]".
Kriterien: Klar, testbar, priorisierbar, Akzeptanzkriterien enthalten.
Kontrolle: Story-Format + Akzeptanzkriterien-Tabelle (Story | Akzeptanzkriterien | Priorität | Aufwand).
```

## 5) Hardware-Entwicklung – Competitive Analysis

```md
Kontext: Marktanalyse für [Hardware-Produkt], Vergleich mit Wettbewerbern.
Aufgabe: Feature-Matrix (5 Produkte × 8 Kriterien).
Kriterien: Objektiv, messbar, Quellen angeben, keine Abwertung von Wettbewerbern.
Kontrolle: Matrix-Tabelle + Zusammenfassung (3 Stichpunkte Differenzierung).
```

## 6) IT-Sicherheit – Risikoanalyse für Kundenprojekt

```md
Kontext: IT-Modernisierungsprojekt bei [Kunde], regulierte Branche.
Aufgabe: Risiko-Register (5 Hauptrisiken) mit Ursache, Wirkung, Mitigation.
Kriterien: BSI-Grundschutz-orientiert, konservativ, keine Spekulation.
Kontrolle: Tabelle (ID | Risiko | Eintrittswahrscheinlichkeit | Impact | Maßnahme | Owner | Termin).
```

---

# 🔐 Teil E: Compliance & Qualität im Ratiodata-Arbeitsalltag

## Datenschutz-Quickcheck (DSGVO-Sensibilität)

* **Keine** personenbezogenen Kundendaten eingeben (Namen, Kontaktdaten, Vertragsinformationen etc.).
* Interne Dokumente nur in **freigegebenen** Tools/Umgebungen nutzen.
* **Anonymisieren/Pseudonymisieren**: „Kunde A", „Bank B", „Sparkasse X".
* **Quellenpflicht**: Bei Zahlen/Regeln **Quelle/Datum** als Platzhalter einfordern.
* **Freigabewege respektieren**: Kundenpräsentationen und Preise **immer** intern freigeben lassen.
* **Besonders sensibel bei Banken**: BaFin-Anforderungen, Bankgeheimnis, MaRisk-Konformität beachten.

**Prompt-Baustein (Schutz):**

```
"Arbeite ohne personenbezogene Daten und Kundeninformationen. 
Wenn Informationen fehlen, frage nicht nach Klarnamen oder Details, sondern nutze Platzhalter.
Kennzeichne Annahmen eindeutig als [Annahme]."
```

## IT-Sicherheit & Vertraulichkeit

* **Keine technischen Details** zu Kunden-Infrastrukturen in öffentliche KI-Tools eingeben.
* **Keine Credentials, IP-Adressen, Systemkonfigurationen** preisgeben.
* **Security-by-Design**: Bei Lösungskonzepten immer IT-Sicherheit mitdenken.
* **Incident-Management**: Bei sicherheitsrelevanten Tickets besondere Vorsicht.

**Sicherheits-Prompt-Baustein:**

```
"Berücksichtige IT-Sicherheit und Datenschutz.
Keine konkreten Systemdetails, Credentials oder Konfigurationen verwenden.
Bei Sicherheitsthemen: Verweis auf BSI-Grundschutz und Best Practices."
```

## Halluzinationen vermeiden (Reality-Check)

* **Format erzwingen**: „Nur, wenn Quelle vorhanden → ausgeben, sonst 'keine belastbare Quelle' schreiben."
* **Unbekannt kenntlich**: „Wenn unsicher, markiere [unsicher] und stoppe."
* **Verifikationsschritt**: Immer **„Prüfschritt"** miterzeugen lassen.
* **Technische Spezifikationen**: Herstellerangaben immer prüfen, nicht auf KI-Output verlassen.

**Beispiel:**

```md
"Erstelle 5 Trends im Bereich Bankentechnologie 2025.
Für jeden Trend: Quelle (Fachpublikation, Datum), Linkplatzhalter.
Wenn keine verlässliche Quelle → 'keine belastbare Quelle – manuelle Recherche erforderlich'."
```

## Qualitäts-Sicherung (QA) – schneller Review

```md
"Prüfe den Text nach:
1) Ziel / Botschaft klar?
2) Technische Aussagen korrekt?
3) Zahlen mit Quelle/Datum?
4) DSGVO/IT-Sicherheit ok?
5) Ratiodata-Markenwerte erkennbar (Innovation, Zuverlässigkeit, Qualität)?
6) Format konsistent (Tabelle/Listen)?
7) Max. Länge eingehalten?

Gib nur eine Fehlerliste mit Korrekturvorschlägen aus."
```

## Branchen-spezifische Compliance

**Finanzsektor (Banken, Sparkassen):**
* BaFin-Anforderungen (BAIT, MaRisk)
* Bankgeheimnis und Vertraulichkeit
* Regulatorische Meldepflichten
* Audit-Anforderungen

**Öffentliche Verwaltung:**
* Vergaberecht und Ausschreibungen
* BSI-Grundschutz verpflichtend
* E-Government-Standards
* Barrierefreiheit (BITV)

**Healthcare (über Partner):**
* Medizinprodukterecht
* Patientendatenschutz
* Gesetzliche Aufbewahrungspflichten

---

# 🗂️ Appendix

## Glossar (kompakt)

* **Completion** – KI-Antwort
* **Kontextfenster** – „Arbeitsgedächtnis" (Token-Limit)
* **Few-Shot** – Per Beispiel anleiten
* **Halluzination** – Erfundene „Fakten"
* **Prompt** – Ihre Anweisung
* **Temperature** – Kreativität (niedrig = präziser)
* **Token** – kleinste Recheneinheit für Text
* **Sprachmodell** – KI-System zur Textverarbeitung (z.B. GPT, Claude, LLaMA)
* **KI-Assistent** – Allgemeine Bezeichnung für konversationelle KI-Tools

## Nützliche Ressourcen (intern ergänzen)

* Token-Zähler/Tokenizer des genutzten Anbieters
* Interne Freigaberegeln & Vorlagen (Vertrieb/Marketing/Service)
* Ratiodata Styleguide (Corporate Language, Markenwerte)
* ISMS-Richtlinien und IT-Sicherheitsstandards
* Compliance-Checklisten für regulierte Branchen

## Ratiodata-Werte in Prompts integrieren

**Innovation:**
```
"Entwickle innovative Lösungsansätze für [Problem].
Berücksichtige neue Technologien und Best Practices aus der Branche."
```

**Zuverlässigkeit:**
```
"Erstelle einen robusten Implementierungsplan mit Fallback-Szenarien.
SLA-Anforderungen: 99,9% Verfügbarkeit."
```

**Qualität:**
```
"Beschreibe Qualitätssicherungsmaßnahmen für [Projekt].
Orientierung an ISO 27001 und ITIL-Standards."
```

**Sicherheit:**
```
"Integriere IT-Sicherheit in alle Phasen.
Berücksichtige BSI-Grundschutz und Zero-Trust-Prinzipien."
```

**Kundenorientierung:**
```
"Formuliere aus Kundenperspektive.
Fokus auf Business Value und messbare Vorteile für [Kundentyp]."
```

---

# 🧪 Übungsteil (für das Seminar)

### Ü1 – Kundenanschreiben (5 Min)

```
Thema: "Neue Cybersecurity-Services für mittelständische Unternehmen"
Erzeuge 5 Betreffvarianten (≤70 Zeichen), professionell, mehrwertig.
```

### Ü2 – Executive Summary (10 Min)

```
Kontext: Geschäftsleitung benötigt Kurzlage zu "Cloud-Strategie 2026".
Aufgabe: 5 Sätze, je ≤20 Wörter, am Ende 1 Handlungsempfehlung.
```

### Ü3 – Ticket-Analyse (10 Min)

```
Eingabe: (Trainer-Text/Ticket-Beschreibung)
Ausgabe: Problem (3 Sätze), 3 Lösungsansätze, Empfehlung mit Begründung.
```

### Ü4 – QA-Check (5 Min)

```
Prüfe Ü2 mit QA-Checkliste. Nenne nur Abweichungen + Korrektur.
```

### Ü5 – Abteilungsspezifische Anwendung (15 Min)

**Vertrieb:**
```
Erstelle Elevator Pitch (30 Sekunden) für Managed Services bei Sparkassen.
Zielgruppe: IT-Leiter. Nutzen-fokussiert, keine Technik-Details.
```

**Marketing:**
```
Entwickle LinkedIn-Post-Konzept zu "5 Jahre Ratiodata Cybersecurity Excellence".
3 Post-Varianten, je mit Storytelling-Element und Call-to-Action.
```

**Service:**
```
Verfasse Eskalations-E-Mail an Lieferanten wegen verspäteter Hardware.
Professionell, klar, mit konkreten Erwartungen und Frist.
```

**Software/Produktmanagement:**
```
Erstelle Release Notes für Version 2.5 unseres Monitoring-Tools.
5 neue Features, je mit User Benefit und technischem Hinweis.
```

**Hardware-Entwicklung:**
```
Schreibe Produktvergleich: Unsere ThinClient-Lösung vs. 2 Wettbewerber.
Matrix: 5 Kriterien, objektiv, Quellen angeben, Differenzierung aufzeigen.
```

---

# 📎 Schnellstart-Karten (zum Ausdrucken)

**1) 4-K-Formel**

```
Kontext | Konkrete Aufgabe | Kriterien | Kontrolle
```

**2) Standard-Kontrollsätze**

```
"Keine Kundendaten, DSGVO-konform arbeiten."
"Quellen & Datum angeben; sonst 'keine belastbare Quelle'."
"Ausgabe als Tabelle/Liste, max. [Länge]."
"IT-Sicherheit beachten, keine Systemdetails/Credentials."
"Ratiodata-Werte integrieren: Innovation, Zuverlässigkeit, Qualität."
```

**3) Mini-Vertriebsprompt**

```
"Executive Summary [Lösung] für [Kunde]:
5 Sätze, professionell, B2B-Ton, 1 Handlungsempfehlung am Ende."
```

**4) Branchen-Prompts**

```
Banking: "Berücksichtige BaFin-Anforderungen und Bankgeheimnis."
Public Sector: "BSI-Grundschutz-konform, Vergaberecht beachten."
KMU: "Pragmatisch, kosteneffizient, schnell umsetzbar."
```

---

# 💼 Abteilungsspezifische Best Practices

## Vertrieb

**Prompt-Struktur für Kundenakquise:**
```
"Rolle: Account Manager bei Ratiodata SE
Ziel: Erstelle Ansprache für [Branche/Unternehmensgröße]
Kontext: [Aktuelle Herausforderung der Zielgruppe]
Aufgabe: Value Proposition in 3 Sätzen
Kriterien: Nutzen-orientiert, keine Technik-Flut, mit Erfolgsbeispiel
Kontrolle: Max. 150 Wörter, Call-to-Action am Ende"
```

**Typische Use Cases:**
* Angebotserstellung und Lösungskonzepte
* Kundenpräsentationen und Pitch-Decks
* Competitive Analysis und Marktanalysen
* Verkaufsargumentationen und ROI-Berechnungen
* Follow-up-E-Mails und Vertragsverhandlungen

## Marketing

**Prompt-Struktur für Content Creation:**
```
"Rolle: Content Manager bei Ratiodata SE
Zielgruppe: [IT-Entscheider/C-Level/Fachabteilungen]
Kanal: [LinkedIn/Website/Newsletter]
Thema: [Trend/Lösung/Success Story]
Ton: Professionell, thought-leadership, B2B
Format: [Blogpost/Social Media/Whitepaper]
Länge: [Wortanzahl]
CTA: [Gewünschte Handlung]"
```

**Typische Use Cases:**
* Social Media Content und Kampagnen
* Blog-Artikel und Thought Leadership
* Case Studies und Success Stories
* Newsletter und E-Mail-Marketing
* Event-Marketing und Messeplanung
* SEO-Optimierung und Landingpages

## Software / Produktmanagement

**Prompt-Struktur für Requirements:**
```
"Kontext: Feature-Entwicklung für [Produkt]
Stakeholder: [Entwicklung/Kunde/Management]
Aufgabe: User Story / Technical Specification
Akzeptanzkriterien: [Messbare Kriterien]
Technische Constraints: [Plattform/Standards/APIs]
Format: Agile User Story Format
Priorisierung: [MoSCoW/Story Points]"
```

**Typische Use Cases:**
* User Stories und Epics formulieren
* Produktdokumentation erstellen
* Release Notes und Changelogs
* Feature-Spezifikationen
* Roadmap-Kommunikation
* Bug Reports und Incident Documentation

## Service

**Prompt-Struktur für Support:**
```
"Kontext: Support-Anfrage [Ticket-ID]
Problem: [Symptombeschreibung ohne Kundendaten]
System: [Allgemeine Systemkategorie, keine Details]
Ziel: Lösungsvorschläge entwickeln
Kriterien: SLA-konform, eskalationsfähig, dokumentierbar
Ausgabe: Priorisierte Lösungsschritte mit Aufwandsschätzung"
```

**Typische Use Cases:**
* Ticket-Analyse und Lösungsfindung
* Wissensdatenbank-Artikel erstellen
* Kundenkommunikation (E-Mails, Telefonnotizen)
* Incident Reports und Postmortems
* Service-Dokumentation und SOPs
* Eskalationsmanagement

## Hardware-Entwicklung

**Prompt-Struktur für Produktmanagement:**
```
"Kontext: Hardware-Produkt [Kategorie]
Zielmarkt: [Segment/Branche]
Aufgabe: [Spezifikation/Marktanalyse/Konzept]
Technische Basis: [Standards/Anforderungen]
Wettbewerb: [Anonymisiert: Hersteller A, B, C]
Format: [Datenblatt/Vergleichsmatrix/Konzept]
Quellen: [Herstellerdaten/Marktforschung]"
```

**Typische Use Cases:**
* Technische Spezifikationen erstellen
* Competitive Intelligence und Marktanalysen
* Produktdatenblätter und Datenblätter
* Testkonzepte und Quality Assurance
* Produktbeschreibungen für Vertrieb
* Herstellerkommunikation und Partnermanagement

---

# 🎯 Branchenspezifische Prompts

## Bankentechnologie

**DSGVO + BaFin:**
```
"Erstelle [Dokument] für Bankenkunden.
WICHTIG: 
- BaFin-Anforderungen (BAIT, MaRisk) berücksichtigen
- Bankgeheimnis wahren
- Audit-Trail-fähig dokumentieren
- Keine Kundennamen oder Bankdaten verwenden
- Compliance-Hinweis am Ende ergänzen"
```

## Öffentliche Verwaltung

**BSI + Vergaberecht:**
```
"Erstelle [Dokument] für öffentliche Auftraggeber.
WICHTIG:
- BSI-Grundschutz-konform
- Vergaberecht beachten (neutrale Formulierung)
- E-Government-Standards
- Barrierefreiheit (BITV 2.0)
- Datenschutz nach DSGVO"
```

## Mittelstand / KMU

**Pragmatisch + Kosteneffizient:**
```
"Erstelle [Lösung] für mittelständisches Unternehmen.
WICHTIG:
- Pragmatisch und schnell umsetzbar
- Transparente Kostenstruktur
- Geringer Administrationsaufwand
- Skalierbarkeit berücksichtigen
- Business Value klar kommunizieren"
```



---

**Ein Tutorial der ADG KI-Community**

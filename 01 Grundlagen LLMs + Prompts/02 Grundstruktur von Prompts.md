# 💼 Prompt Engineering Grundlagen für IT-Profis

---

## 💡 Was ist ein Prompt?

Ein **Prompt** ist deine Anweisung an ein KI-Sprachmodell – wie eine präzise technische Anforderung an ein intelligentes System.
Je klarer du formulierst, was du brauchst, desto präziser und nützlicher ist das Ergebnis für deinen IT-Arbeitsalltag bei Ratiodata.

---

## 🧩 Der Prompt-Baukasten

Ein guter Prompt besteht aus fünf klaren Bausteinen:

```
┌─────────────┐
│   1. ROLLE  │ → Wer soll die KI sein? (IT-Berater, Technical Writer, Solution Architect)
├─────────────┤
│  2. KONTEXT │ → Worum geht's genau? (Projekt, Zielgruppe, technischer Rahmen)
├─────────────┤
│  3. AUFGABE │ → Was soll getan werden? (Dokumentieren, Analysieren, Konzipieren)
├─────────────┤
│   4. FORMAT │ → Wie soll das Ergebnis aussehen? (Mail, Tabelle, technische Spezifikation)
├─────────────┤
│ 5. QUALITÄT │ → Stil & Ton (technisch präzise, verständlich, kundenorientiert)
└─────────────┘
```

---

## ✉️ Beispiel: Der Unterschied macht's!

**❌ Schwacher Prompt:**
„Schreib mir was über Cloud-Migration."

**✅ Starker Prompt:**
„Erkläre in 3 Stichpunkten, welche technischen Vorteile eine Hybrid-Cloud-Lösung für mittelständische Banken im Bereich Managed Services bietet."

**🤖 Mögliche KI-Antwort:**

> 1. Skalierbare Infrastruktur mit On-Premises-Kontrolle für kritische Bankdaten (DSGVO-konform)
> 2. Optimierte Kosten durch bedarfsgerechte Cloud-Ressourcen bei gleichzeitiger lokaler Datenhaltung
> 3. Erhöhte Ausfallsicherheit durch redundante Systeme und professionelles Backup-Management

---

### 🎯 Mini-Übung 1

Formuliere einen Prompt, der nach den **3 wichtigsten Vorteilen** einer Zero-Trust-Architektur für Banken fragt.

<details>
<summary>💡 Lösung anzeigen</summary>

„Nenne die 3 größten Vorteile einer Zero-Trust-Security-Architektur für Finanzinstitute im Bereich IT-Sicherheit und Compliance."

</details>

---

## 🧠 Level 1: Einfache Prompts meistern

### Grundregel: Sei konkret!

| ❌ Vage                               | ✅ Konkret                                                                               |
| ------------------------------------ | --------------------------------------------------------------------------------------- |
| „Schreibe über Cybersecurity"        | „Formuliere 5 Best Practices für Endpoint-Security in mittelständischen Banken."       |
| „Hilf mir bei einer Produktbeschreibung" | „Erstelle 4 USP-Bullet-Points für unsere Managed-Firewall-Lösung für KMU."         |
| „Erkläre Cloud-Services"             | „Erkläre in 3 Sätzen, wie Infrastructure-as-a-Service die IT-Kosten senkt."            |

---

### 🎯 Mini-Übung 2

Verbessere diesen Prompt:
„Erzähl was über Software-Updates."

<details>
<summary>💡 Lösung anzeigen</summary>

„Erkläre in 5 Sätzen, warum regelmäßige Patch-Management-Prozesse für die IT-Sicherheit in Banken kritisch sind und wie Ratiodata Managed Services dabei unterstützt."

</details>

---

## 🎭 Level 2: Rollen clever nutzen

Wenn du dem Sprachmodell eine **Rolle** gibst, bekommst du Antworten aus einer bestimmten technischen Perspektive.

**Frage:** „Wie kann ich eine Cloud-Migrations-Strategie entwickeln?"

**Prompt 1 (Rolle: Cloud-Architekt):**
„Du bist ein erfahrener Cloud-Architekt für Banken-IT. Erstelle eine Checkliste für eine sichere Cloud-Migration unter Berücksichtigung von BaFin-Anforderungen."

**Prompt 2 (Rolle: IT-Security-Experte):**
„Du bist ein IT-Security-Consultant mit Fokus auf Finanzinstitute. Beschreibe Schritt für Schritt, wie du ein Zero-Trust-Konzept für 50 Remote-Arbeitsplätze implementierst."

---

### 🎯 Mini-Übung 3

Schreibe 2 Rollen-Prompts zum Thema „Incident Response verbessern".

<details>
<summary>💡 Lösung anzeigen</summary>

1. „Du bist ein SIEM-Spezialist. Wie entwickelst du einen automatisierten Incident-Response-Workflow für kritische Security-Events?"
2. „Du bist ein Service-Manager. Wie gestaltest du ein Eskalationsprozess-Konzept für P1-Incidents im 24/7-Betrieb?"

</details>

---

## 🏗️ Level 3: Kontext macht den Unterschied

Je mehr technischen Hintergrund du gibst, desto genauer versteht das Sprachmodell deine Anforderung.

**Version 1 (ohne Kontext):**
„Schreib eine Mail an Kunden."

**Version 2 (mit etwas Kontext):**
„Schreib eine Mail an Kunden über ein geplantes Wartungsfenster."

**Version 3 (voller Kontext):**
„Du bist Service-Manager bei Ratiodata SE. Erstelle eine kundenfreundliche E-Mail an Bank-Kunden über ein geplantes Wartungsfenster für Core-Banking-Systeme (Samstag, 02:00-06:00 Uhr). Ziel: Transparenz schaffen, Auswirkungen minimieren. Ton: professionell, vertrauenswürdig, technisch präzise. Länge: 150 Wörter. Wichtig: DSGVO-konform, keine sensiblen Systemdetails."

---

### 🎯 Mini-Übung 4

Füge Kontext hinzu:
„Formuliere eine Produktbeschreibung."

<details>
<summary>💡 Lösung anzeigen</summary>

„Formuliere eine Produktbeschreibung für unsere Managed-Security-Lösung 'CyberShield Enterprise' für mittelständische Banken. Zielgruppe: IT-Leiter und CISOs. Ziel: Technische Vorteile und Compliance-Vorteile kommunizieren. Fokus: SOC-as-a-Service, 24/7-Monitoring, automatisierte Threat Detection. Länge: 120 Wörter, Ton: technisch kompetent aber verständlich."

</details>

---

## 🧾 Format definieren

Sag dem Sprachmodell **genau**, wie du die Antwort brauchst.

| Format                  | Beispiel-Prompt                                                                            | Wann nützlich      |
| ----------------------- | ------------------------------------------------------------------------------------------ | ------------------ |
| **Liste**               | „Liste 5 Vorteile von Software-Defined Networking für Rechenzentren."                     | Schnellüberblick   |
| **Tabelle**             | „Erstelle eine Vergleichstabelle: On-Premises vs. Cloud vs. Hybrid (Kosten, Security, Skalierung)." | Entscheidungshilfe |
| **E-Mail**              | „Schreibe eine technische Statusmail an den Kunden über den Projektfortschritt der Firewall-Migration." | Kundenkommunikation |
| **Schritt-für-Schritt** | „Erkläre Schritt für Schritt die Implementierung eines Backup-Konzepts nach 3-2-1-Regel." | Dokumentation      |
| **Zusammenfassung**     | „Fasse die wichtigsten Punkte aus dem Security-Audit-Report in 5 Bullet Points zusammen." | Management-Reporting |

---

### 🎯 Mini-Übung 5

Formuliere einen Prompt, der eine Antwort als Tabelle liefert.

<details>
<summary>💡 Lösung anzeigen</summary>

„Erstelle eine Vergleichstabelle mit den Spalten: Firewall-Modell | Max. Durchsatz | Anzahl VPN-Tunnel | Lizenzkosten (jährlich) | Einsatzbereich – für 3 Enterprise-Firewall-Lösungen."

</details>

---

## 🧰 Troubleshooting: Wenn die KI nicht versteht, was du meinst

| Problem                    | Ursache            | Bessere Formulierung                                                                                            |
| -------------------------- | ------------------ | --------------------------------------------------------------------------------------------------------------- |
| „Antwort ist zu allgemein" | Kein Kontext       | „Erkläre 3 Vorteile von Kubernetes für Container-Orchestrierung in hochverfügbaren Banking-Umgebungen."       |
| „Antwort zu lang"          | Keine Längenangabe | „Fasse die wichtigsten Punkte der ISO 27001-Zertifizierung in 100 Wörtern zusammen."                          |
| „Antwort unpassend"        | Fehlende Rolle     | „Du bist ein erfahrener Solution Architect. Erstelle ein technisches Konzept für eine Multi-Cloud-Strategie." |

---

## ⚠️ Grenzen der KI kennen – IT-Sicherheit & Compliance

**WICHTIG für Ratiodata-Mitarbeiter:** Ein Sprachmodell kann **nicht wissen**, was intern bei Ratiodata gilt oder welche spezifischen Kundenanforderungen existieren.

### 🔒 Was du NIEMALS in ein KI-Tool eingeben darfst:

* ❌ Kundendaten (Namen, Firmen, Verträge, Projekte)
* ❌ IP-Adressen, Netzwerktopologien, Systemkonfigurationen
* ❌ Passwörter, API-Keys, Zugangsdaten, Zertifikate
* ❌ Interne Preisinformationen, Kalkulationen, Margen
* ❌ Vertrauliche Projektdetails oder Security-Schwachstellen
* ❌ Personenbezogene Daten von Mitarbeitern oder Kunden

### ✅ Das KI-Tool kann helfen bei:

* ✅ Allgemeinen technischen Konzepten und Best Practices
* ✅ Code-Snippets für wiederkehrende Aufgaben (anonymisiert)
* ✅ Strukturierung von Dokumentationen und Präsentationen
* ✅ Formulierungshilfen für technische Texte
* ✅ Ideen für Marketing-Content und Produktbeschreibungen

**Immer prüfen bei:**

* Technischen Spezifikationen (Fakten-Check erforderlich!)
* Compliance-relevanten Inhalten (BaFin, DSGVO, IT-Sicherheitsgesetz)
* Sicherheitsempfehlungen (mit internen Security-Standards abgleichen)
* Kundenkommunikation (Freigabeprozess beachten)

---

## 🧩 Komplett-Prompt für den Ratiodata-Arbeitsalltag

Hier ein Beispiel für einen professionellen Prompt mit allen 5 Bausteinen:

```
ROLLE: Du bist ein Technical Presales Consultant für IT-Security-Lösungen im Bankenumfeld.

KONTEXT:
- Projekt: Firewall-Modernisierung für mittelständische Regionalbank
- Zielgruppe: IT-Leiter und CISO des Kunden
- Anforderungen: Next-Generation Firewall mit IPS, Application Control, SSL-Inspection
- Budget-Rahmen: Enterprise-Segment
- Compliance: BaFin-Anforderungen, DSGVO, IT-Sicherheitsgesetz

AUFGABE:
Erstelle eine strukturierte Produktpräsentation mit 3 Firewall-Lösungen (Entry, Mid, High-End),
inklusive technischer Highlights, Lizenzmodell und typischer Einsatzszenarien.

FORMAT:
Tabelle mit den Spalten: Modell | Durchsatz | Key-Features | Lizenz-Typ | Zielgruppe

QUALITÄT:
Technisch präzise, herstellerneutral, lösungsorientiert – passend zur Ratiodata-Beratungsqualität.
Wichtig: Keine konkreten Preise, keine Herstellernamen (vertraulich).
```

---

## 📊 Beispielausgabe

| Modell          | Durchsatz | Key-Features                                  | Lizenz-Typ        | Zielgruppe               |
| --------------- | --------- | --------------------------------------------- | ----------------- | ------------------------ |
| Entry-Solution  | 2 Gbit/s  | Stateful Firewall, Basic IPS, 50 VPN-Tunnel  | Subscription 3J   | Zweigstellen, KMU        |
| Mid-Solution    | 10 Gbit/s | NGFW, Advanced Threat Protection, SSL-Inspect | Subscription 5J   | Mittelstand, Branch-Office |
| High-End-Solution | 40 Gbit/s | NGFW, Sandboxing, Zero-Day-Protection, HA    | Perpetual + Support | Rechenzentrum, Core-Systeme |

---

## 🧠 Übungsaufgabe zum Abschluss

Erstelle deinen eigenen Prompt mit allen 5 Bausteinen zum Thema:
**„Incident-Management-Prozess für kritische Banking-Systeme dokumentieren"**

<details>
<summary>💡 Beispiel</summary>

```
ROLLE: Du bist ein ITIL-zertifizierter Service-Manager mit Spezialisierung auf Finanzdienstleister.

KONTEXT:
Ratiodata betreut Core-Banking-Systeme eines Kunden im 24/7-Managed-Service.
Ziel: Strukturierte Dokumentation für P1-Incidents (kritische Systemausfälle).
Anforderungen: Reaktionszeit max. 15 Minuten, Eskalationspfade, Kommunikationsketten.

AUFGABE:
Entwickle eine Prozessdokumentation mit 5 Hauptschritten: Detection → Triage → 
Escalation → Resolution → Post-Incident-Review.

FORMAT:
Schritt-für-Schritt-Anleitung mit Verantwortlichkeiten, Zeitfenstern und Kommunikationswegen (1-2 Sätze pro Schritt).

QUALITÄT:
ITIL-konform, praxisnah, sofort umsetzbar – orientiert an Ratiodata Service-Standards.
```

</details>

---

## 📚 Prompt-Vorlagen für den Ratiodata-Arbeitsalltag

### 🗂️ Vertrieb & Presales

```
"Erstelle eine Produkt-Feature-Matrix für 3 Managed-Backup-Lösungen (Entry/Mid/Enterprise)."
"Formuliere 5 technische USPs unserer Cybersecurity-Services für Bank-Kunden."
"Schreibe eine Antwort auf eine RFI-Anfrage zum Thema 'Multi-Cloud-Management'."
```

### 🧾 Kundenkommunikation & Service

```
"Schreibe eine Service-Status-Mail über ein geplantes Patch-Management-Fenster."
"Formuliere eine professionelle Incident-Notification für einen Ausfall (P2-Severity)."
"Erstelle ein FAQ-Dokument zu den häufigsten VPN-Verbindungsproblemen."
```

### 📈 Marketing & Content Creation

```
"Entwickle 3 LinkedIn-Posts über die Vorteile von SOC-as-a-Service für KMU."
"Erstelle 5 Headlines für eine Whitepaper-Kampagne zum Thema 'Zero Trust Security'."
"Formuliere einen Newsletter-Text über unsere neuen Managed-Cloud-Services (200 Wörter)."
```

### 🎯 Software & Produktmanagement

```
"Schreibe 5 User Stories für ein Self-Service-Portal für Managed-Services-Kunden."
"Erstelle Release Notes für ein Software-Update unseres Monitoring-Tools (Version 3.2)."
"Formuliere eine technische Produktbeschreibung für eine neue Backup-Appliance."
```

### 📊 Analyse & Strategie

```
"Fasse die wichtigsten Trends im Bereich 'Cloud Security 2025' in 5 Bullet Points zusammen."
"Erstelle eine SWOT-Analyse für unseren Einstieg in den Kubernetes-Managed-Services-Markt."
"Liste die 3 größten Herausforderungen bei der IT-Sicherheit für Banken nach NIS2-Richtlinie."
```

### 🔧 Technische Dokumentation

```
"Erstelle eine Schritt-für-Schritt-Anleitung für die Konfiguration eines VPN-Tunnels (IPsec)."
"Dokumentiere den Prozess für ein Disaster-Recovery-Szenario in 7 Schritten."
"Schreibe eine technische Spezifikation für eine Firewall-Regel (Port 443, HTTPS, spezifische IP-Range)."
```

---

## ✅ Checkliste für deinen perfekten IT-Prompt

* [ ] **Rolle** definiert (z. B. Solution Architect, Technical Writer, Security Consultant)?
* [ ] **Kontext** vorhanden (Projekt, Zielgruppe, technischer Rahmen)?
* [ ] **Aufgabe** klar (Was soll entstehen)?
* [ ] **Format** definiert (Mail, Tabelle, Dokumentation)?
* [ ] **Ton & Länge** festgelegt (technisch, verständlich, präzise)?
* [ ] **Sicherheits-Check:** Keine vertraulichen Daten enthalten?
* [ ] **Prüfen:** Würde ein Kollege verstehen, was du willst?

---

## 🎓 Fazit: Dein Weg zur KI-Kompetenz bei Ratiodata

1. **Klar formulieren** statt raten lassen
2. **Rolle + Kontext** immer mitgeben
3. **Struktur schaffen** mit Format & Ton
4. **Prompt iterativ verbessern**, bis das Ergebnis passt
5. **IT-Sicherheit beachten** – keine sensiblen Daten!
6. **KI als technischer Assistent** nutzen, nicht als Ersatz für Expertise

> 💬 **Merke:** Ein Sprachmodell ist dein digitaler Assistent – aber du führst die technische Verantwortung!

---

## 🔒 Ratiodata-Sicherheitshinweise

**Vor jeder Nutzung beachten:**

✅ **Erlaubt:**
- Allgemeine technische Konzepte und Best Practices
- Anonymisierte Code-Beispiele und Konfigurationen
- Strukturierungshilfe für Dokumentationen
- Formulierungshilfe für Marketing-Texte

❌ **Verboten:**
- Kundennamen, Projektnamen, interne Codes
- IP-Adressen, Systemkonfigurationen, Netzwerkpläne
- Zugangsdaten, Credentials, API-Keys
- Vertrauliche Preis- und Vertragsinformationen

**Bei Unsicherheit:** Frage deinen Team-Lead oder den Datenschutzbeauftragten!

---

Du bist jetzt bestens gerüstet, um KI-Sprachmodelle als echten Mehrwert in deiner Rolle bei Ratiodata einzusetzen – effizient, sicher und mit technischer Präzision.

**Ein Tutorial der ADG KI-Community**

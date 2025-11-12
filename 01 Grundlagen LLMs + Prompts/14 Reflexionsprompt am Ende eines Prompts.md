# Reflexions- und Qualitätssicherungs-Prompt für Ratiodata SE

## 📌 **Der Prompt**

```
„Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus."
```

---

## 🧭 **Anleitung zur Nutzung des Prompts**

Dieser Prompt ist ein **Reflexions- und Qualitätssicherungs-Prompt**, der dafür sorgt, dass KI-Antworten strategisch, nachvollziehbar und risikobewusst formuliert werden – besonders wertvoll für Mitarbeitende der Ratiodata SE, die fundierte Entscheidungsgrundlagen für Management, Geschäftsführung oder Fachbereiche vorbereiten.

---

### **1️⃣ Zweck verstehen**

Der Prompt zwingt das Sprachmodell, **nicht sofort zu antworten**, sondern seinen Denkprozess offenzulegen.

Er macht die Antwort:
- **transparenter** (du siehst, wie das Sprachmodell zu seiner Empfehlung kommt),
- **professioneller** (strukturiert wie eine Management-Vorlage),
- **besser begründet** (Annahmen und Risiken werden explizit genannt).

➡️ **Ideal, wenn du z. B. eine KI-Empfehlung benötigst für:**
- **Vertrieb:** Angebotsstrategien, Lösungskonzeption, technische Produktberatung, Presales-Entscheidungen
- **Marketing:** Kampagnenplanung, Content-Strategie, Event-Marketing, Lead-Generierung
- **Software/Produktmanagement:** Feature-Priorisierung, Roadmap-Planung, Requirements Engineering
- **Service:** Service-Level-Optimierung, Eskalationsmanagement, Wissensdatenbank-Struktur
- **Hardware-Entwicklung:** Produktspezifikationen, Marktanalysen, Partnerevaluierung
- **IT-Infrastruktur:** Architekturentscheidungen, Tool-Auswahl, Sicherheitskonzepte

---

### **2️⃣ Wann du diesen Prompt nutzen solltest**

✅ **Nutze diesen Prompt, wenn:**
- die Entscheidung **Budget, Ressourcen oder Kundenreputation** betrifft
- du eine **Management-Vorlage** oder **Entscheidungsgrundlage** vorbereitest
- du **mehrere Technologie-Optionen** oder Lösungsansätze abwägen musst
- du **IT-Sicherheitsrisiken** identifizieren und minimieren willst
- du **Transparenz** und **Nachvollziehbarkeit** brauchst (z. B. für Geschäftsführung, Kunden, Stakeholder)
- die Antwort **compliance-relevant** ist (DSGVO, IT-Sicherheit, regulatorische Anforderungen)
- es um **Kundenberatung** oder **Lösungsdesign** geht
- **Investitionsentscheidungen** für Software, Hardware oder Services anstehen

❌ **Nutze diesen Prompt NICHT, wenn:**
- du eine schnelle, einfache Antwort brauchst (z. B. „Was bedeutet RAID 5?")
- du kreative Texte ohne strategische Komponente benötigst (z. B. Social-Media-Posts)
- die Aufgabe rein operativ ist (z. B. „Formatiere diese Tabelle")

---

### **3️⃣ Aufbau und Wirkung des Prompts**

Der Prompt besteht aus **5 Elementen**, die nacheinander abgefragt werden:

| **Element** | **Was es bewirkt** | **Nutzen für Ratiodata** |
|-------------|-------------------|--------------------------|
| **Annahmen** | KI legt zugrunde liegende Annahmen offen | Du erkennst, ob die KI realistische oder falsche Annahmen trifft (z. B. über Kundenbedürfnisse, Budgets, technische Anforderungen) |
| **Denkprozess** | KI erklärt ihre Überlegungen Schritt für Schritt | Du verstehst die Logik und kannst sie nachvollziehen oder korrigieren |
| **Risiken** | KI identifiziert mögliche Probleme, Sicherheitslücken, Implementierungshürden | Du erkennst blinde Flecken und kannst präventiv gegensteuern – besonders wichtig bei IT-Sicherheit |
| **Was die Empfehlung ändern würde** | KI nennt Faktoren, die ihre Meinung kippen würden | Du verstehst Sensitivitäten und kannst Szenarien für verschiedene Kundenanforderungen durchspielen |
| **Empfehlung + Vertrauensniveau** | KI gibt klare Handlungsempfehlung mit Unsicherheitsangabe | Du weißt, wie belastbar die Empfehlung ist (z. B. „85 % sicher" vs. „50 % sicher") |

---

### **4️⃣ So kombinierst du den Prompt mit deiner Anfrage**

**Standard-Struktur:**

```
[Deine konkrete Frage oder Aufgabe]

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

💡 **Tipp:** Stelle deine Frage möglichst konkret und kontextreich. Gib dem Sprachmodell Informationen über:
- Kundenbranche (Bank, Healthcare, öffentliche Verwaltung, Mittelstand)
- Budget-Rahmen
- Zeitliche Anforderungen
- Bestehende IT-Infrastruktur
- Compliance-Anforderungen (DSGVO, KRITIS, etc.)

---

### **5️⃣ Beispiel-Workflow**

**Ohne Reflexions-Prompt:**
> „Sollen wir dem Kunden eine Cloud- oder On-Premise-Lösung empfehlen?"
> 
> KI-Antwort: „Cloud, weil flexibler und kostengünstiger."

❌ **Problem:** Oberflächlich, keine Begründung, keine Sicherheitsaspekte, keine Kundenspezifika berücksichtigt.

---

**Mit Reflexions-Prompt:**
> „Sollen wir dem Kunden (regionale Bank mit 500 Mitarbeitern) eine Cloud- oder On-Premise-Lösung für ihr neues Kundenportal empfehlen?
> 
> Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit einer Einschätzung deines Vertrauensniveaus."

✅ **KI-Antwort (strukturiert):**

**Annahmen:**
- Bank unterliegt BaFin-Aufsicht und hat strenge Compliance-Anforderungen
- Budget: moderat bis hoch (Bank kann beide Optionen finanzieren)
- Vorhandene IT-Abteilung mit 5-8 Mitarbeitenden
- Sensible Kundendaten werden verarbeitet

**Denkprozess:**
1. Cloud bietet Skalierbarkeit und reduziert Betriebsaufwand
2. Banking-Branche hat hohe Sicherheits- und Compliance-Anforderungen
3. On-Premise gibt mehr Kontrolle über Daten und Infrastruktur
4. Hybrid-Ansatz könnte Best of Both Worlds bieten
5. Deutsche Cloud-Anbieter mit DSGVO-Compliance wichtig

**Risiken:**
- **Cloud:** Vendor Lock-in, potenzielle Datenschutzbedenken bei Bankenkunden, Abhängigkeit vom Anbieter, Internetanbindung als Single Point of Failure
- **On-Premise:** Höhere Initialkosten, Betriebsaufwand, IT-Know-how erforderlich, langsamere Updates
- **Beide:** Integrationskomplexität mit Banking-Kern-Systemen

**Was die Empfehlung ändern würde:**
- Wenn IT-Team kleiner als 5 Personen → Cloud
- Wenn Budget stark limitiert → Cloud (OpEx statt CapEx)
- Wenn Bank bereits KRITIS-Einstufung hat → On-Premise oder Private Cloud
- Wenn schnelle Time-to-Market wichtig → Cloud

**Empfehlung:**
Hybrid-Lösung: Kundenportal-Frontend in deutscher Cloud (z. B. Microsoft Azure Germany oder IONOS), Banking-Backend On-Premise. Begründung: Balance zwischen Compliance-Sicherheit und Flexibilität, reduzierter Betriebsaufwand für Frontend, volle Datenkontrolle für kritische Banking-Systeme.

**Vertrauensniveau:** 80 % (abhängig von genauer BaFin-Anforderung und vorhandener IT-Infrastruktur)

---

## 📚 **5 Praxisbeispiele für Ratiodata SE**

---

### 🟢 **Beispiel 1: Vertrieb – Lösungsarchitektur für Bankenkunden**

**Deine Anfrage:**

```
Wir beraten eine Sparkasse (2.000 Mitarbeitende, 50 Filialen) zur Modernisierung 
ihrer IT-Infrastruktur. Zwei Optionen:
A) Vollständige Migration in die Cloud (Microsoft 365 + Azure)
B) Hybrid-Ansatz (Cloud für Collaboration, On-Premise für Kernsysteme)

Welche Lösung empfehlen wir?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**

**Annahmen:**
- Sparkasse unterliegt BaFin-Regulierung und strengen Sicherheitsauflagen
- Bestehende Kernsysteme (Kontoverwaltung, Zahlungsverkehr) laufen On-Premise
- Budget: ca. 500.000–1.000.000 € über 3 Jahre
- IT-Abteilung vorhanden, aber überlastet
- Mitarbeitende arbeiten teilweise im Home-Office (seit Covid)

**Denkprozess:**
1. Cloud bietet Flexibilität und Modern Workplace-Funktionen (Teams, OneDrive)
2. Banking-Kernsysteme müssen höchste Sicherheit garantieren (BaFin-Anforderungen)
3. Vollständige Cloud-Migration = hohes Risiko bei kritischer Infrastruktur
4. Hybrid ermöglicht schrittweise Modernisierung ohne Kerngeschäft zu gefährden
5. Microsoft 365 GCC High oder Azure Germany erfüllen Banking-Compliance

**Risiken:**
- **Option A (Full Cloud):** 
  - BaFin-Compliance unklar bei vollständiger Cloud-Migration
  - Abhängigkeit von Internetanbindung
  - Widerstand von Betriebsrat/Datenschutzbeauftragten
  - Vendor Lock-in bei Microsoft
- **Option B (Hybrid):**
  - Komplexere Architektur, mehr Schnittstellen
  - Höhere Integrationskosten
  - Zwei Systeme zu betreiben (Cloud + On-Premise)

**Was die Empfehlung ändern würde:**
- Wenn BaFin explizit Cloud-First-Strategie fordert → Option A
- Wenn Budget <300.000 € → kleinere Hybrid-Lösung mit Fokus auf kritische Use Cases
- Wenn IT-Team <3 Personen → mehr Cloud-Services für Entlastung
- Wenn Sparkasse bereits Cloud-Erfahrung hat → aggressivere Cloud-Migration

**Empfehlung:**
**Option B – Hybrid-Ansatz** mit folgender Architektur:
- **Cloud:** Microsoft 365 für Collaboration (Teams, Exchange Online, SharePoint) – ca. 150 €/Nutzer/Jahr
- **Cloud:** Azure für nicht-kritische Anwendungen (Website, Marketing-Tools)
- **On-Premise:** Kernsysteme, Kundendatenbanken, Zahlungsverkehr
- **Security:** Microsoft Defender, Azure Sentinel, Zero Trust Architecture
- **Migration:** 3-Phasen-Ansatz über 18 Monate

Begründung: 
- Erfüllt BaFin-Anforderungen durch Datensouveränität bei Kernsystemen
- Modernisiert Arbeitsplatz-IT (Home-Office-Fähigkeit)
- Reduziert IT-Last durch Cloud-Services bei unkritischen Systemen
- Minimiert Risiko durch schrittweise Migration

**Vertrauensniveau:** 85 % (hoch, weil etablierter Ansatz für regulierte Branchen, aber abhängig von detaillierter BaFin-Prüfung)

---

### 🟢 **Beispiel 2: Marketing – Content-Strategie für LinkedIn**

**Deine Anfrage:**

```
Wir möchten unsere LinkedIn-Präsenz ausbauen, um mehr IT-Fachkräfte zu erreichen. 
Budget: 20.000 € für 6 Monate. Zwei Strategien:
A) Fokus auf Thought Leadership (Fachartikel, Case Studies)
B) Fokus auf Employer Branding (Mitarbeiter-Stories, Behind-the-Scenes)

Was empfehlen wir?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**

**Annahmen:**
- Ratiodata hat ca. 400 Mitarbeitende, Recruiting ist Herausforderung
- Zielgruppe: IT-Professionals, System-Admins, Softwareentwickler, Cloud-Architekten
- LinkedIn-Reichweite aktuell: ca. 5.000 Follower
- Ziel: Employer Branding + Thought Leadership kombinieren

**Denkprozess:**
1. **Option A (Thought Leadership):** Positioniert Ratiodata als IT-Experten, zieht Fachpublikum an
2. **Option B (Employer Branding):** Zeigt Unternehmenskultur, hilft im Recruiting
3. IT-Fachkräfte suchen sowohl fachliche Expertise als auch gute Arbeitgeber
4. LinkedIn-Algorithmus bevorzugt authentische, persönliche Inhalte
5. Kombination beider Ansätze könnte synergistisch wirken

**Risiken:**
- **Option A:** Zu technisch → wenig Engagement, keine Recruiting-Wirkung
- **Option B:** Zu weich → keine Fachkompetenz-Wahrnehmung, austauschbar
- **Beide:** Content-Produktion überlastet Marketing-Team, Mitarbeitende wollen nicht vor die Kamera

**Was die Empfehlung ändern würde:**
- Wenn primäres Ziel Recruiting → mehr Option B
- Wenn primäres Ziel Lead-Generierung → mehr Option A
- Wenn Budget >50.000 € → beides parallel mit externen Content-Creators
- Wenn Mitarbeitende nicht teilnehmen wollen → Fokus auf Option A

**Empfehlung:**
**70/30-Mix: 70 % Thought Leadership, 30 % Employer Branding**

**Content-Plan:**
- **Wöchentlich:** 1 Fachartikel (Cloud, Cybersecurity, Modern Workplace) von Ratiodata-Experten
- **Monatlich:** 2 Case Studies (anonymisiert) aus Kundenprojekten
- **Monatlich:** 2 Mitarbeiter-Spotlights (IT-Teams, Projektgeschichten)
- **Quartalsweise:** 1 Whitepaper/Webinar zu Trend-Themen

**Budget-Allocation:**
- 12.000 € Content-Erstellung (externe Redaktion + interne Expertise)
- 5.000 € LinkedIn Ads für Top-Performer-Posts
- 3.000 € Tools (Canva, Scheduling, Analytics)

Begründung: IT-Fachkräfte respektieren Expertise → Thought Leadership zieht Zielgruppe an, Employer Branding konvertiert sie zu Bewerbern. 70/30-Mix zeigt Kompetenz UND Kultur.

**Vertrauensniveau:** 75 % (abhängig von Mitarbeiter-Beteiligung und Content-Qualität)

---

### 🟢 **Beispiel 3: Software/Produktmanagement – Feature-Priorisierung für Managed Services Portal**

**Deine Anfrage:**

```
Unser Managed Services Team möchte das Kundenportal erweitern. 
Drei Feature-Requests:
A) Self-Service Ticket-Erstellung mit KI-basierter Lösung-Suggestion
B) Echtzeit-Monitoring Dashboard für Kundensysteme
C) Automatische Reporting-Funktion (SLA, Verfügbarkeit, Performance)

Entwicklungskapazität: nur 1 Feature in Q1. Welches priorisieren wir?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**

**Annahmen:**
- Ratiodata hat ca. 150 Managed Services Kunden
- Aktuelles Ticketing läuft über E-Mail/Telefon → ineffizient
- Kunden fragen regelmäßig nach Transparenz über Systemzustand
- SLA-Reporting ist aktuell manuell → zeitaufwendig

**Denkprozess:**
1. **Feature A:** Reduziert Support-Aufwand, KI-Trend, aber: KI-Qualität unsicher
2. **Feature B:** Erhöht Kundentransparenz, reduziert "Wo steht mein System?"-Anfragen
3. **Feature C:** Spart Zeit im Reporting, SLA-Nachweis automatisiert, Compliance-relevant
4. Welches Feature bringt höchsten ROI (Zeit-Ersparnis + Kundenzufriedenheit)?
5. Welches Feature differenziert Ratiodata im Wettbewerb?

**Risiken:**
- **Feature A:** KI-Empfehlungen falsch → Kundenunzufriedenheit, hoher Trainingsaufwand
- **Feature B:** Performance-Issues bei vielen simultanen Nutzern, hohe Datenlast
- **Feature C:** Falsche Metriken → rechtliche Probleme bei SLA-Disputes

**Was die Empfehlung ändern würde:**
- Wenn Hauptproblem Ticket-Volumen → Feature A
- Wenn Kunden-Churn hoch wegen fehlender Transparenz → Feature B
- Wenn SLA-Disputes häufig → Feature C
- Wenn Entwicklungs-Ressourcen unbegrenzt → alle drei parallel

**Empfehlung:**
**Feature C – Automatische Reporting-Funktion**

Begründung:
1. **Quick Win:** Technisch am einfachsten umsetzbar (Dashboard + Export)
2. **ROI:** Spart 20 % Zeit im Service-Team (keine manuellen Reports)
3. **Compliance:** SLA-Nachweis ist rechtlich relevant (Vertragserfüllung)
4. **Kundenwert:** Kunden erhalten Transparenz ohne aktiv nachfragen zu müssen
5. **Differenzierung:** Viele Wettbewerber haben kein automatisches SLA-Reporting

**Umsetzung:**
- Dashboard mit SLA-Compliance-Metriken (Response Time, Resolution Time, Availability)
- Monatlicher automatischer Report-Versand per E-Mail
- Export-Funktion (PDF, Excel) für Kunden-IT-Leitung
- Implementierung: 6–8 Wochen

**Danach in Q2:** Feature B (Monitoring), dann Q3 Feature A (KI-Ticketing)

**Vertrauensniveau:** 80 % (hoch, weil Feature C messbaren ROI hat und technisch gut umsetzbar ist)

---

### 🟢 **Beispiel 4: Service – Eskalationsmanagement optimieren**

**Deine Anfrage:**

```
Unser Service-Team hat steigende Eskalationsraten (15 % der Tickets). 
Drei Verbesserungsansätze:
A) Mehr Service-Mitarbeitende einstellen (zusätzlich 5 FTE, ca. 300.000 €/Jahr)
B) Service-Automatisierung einführen (Chatbot, Self-Service, ca. 100.000 € Initial)
C) Besseres Wissensmanagement (Wiki, Schulungen, ca. 50.000 €)

Was empfehlen wir?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**

**Annahmen:**
- Aktuelles Service-Team: ca. 20 FTE
- Ticket-Volumen: ca. 1.000 Tickets/Monat
- Eskalationsrate: 15 % (150 Tickets/Monat)
- Hauptgründe für Eskalation: fehlende Expertise, unklare Prozesse, Wiederholungsfälle

**Denkprozess:**
1. **Option A:** Schnelle Lösung, aber: hohe laufende Kosten, löst keine Root-Cause
2. **Option B:** Modern, skalierbar, aber: hohe Initialkosten, Akzeptanz-Risiko
3. **Option C:** Nachhaltig, kostengünstig, aber: langfristige Wirkung, Change Management nötig
4. Root Cause Analysis: Warum eskalieren Tickets? (fehlende Doku, komplexe Fälle, Prozesslücken)
5. Welche Lösung reduziert Eskalationen langfristig am meisten?

**Risiken:**
- **Option A:** Keine Prozessverbesserung, Kostenexplosion bei weiterem Wachstum
- **Option B:** Chatbot gibt falsche Antworten, Kunden frustriert, hohe Implementierungszeit
- **Option C:** Wissen veraltet schnell, Schulungen nicht besucht, mangelnde Akzeptanz

**Was die Empfehlung ändern würde:**
- Wenn Eskalationen weiter steigen (>20 %) → Option A kurzfristig nötig
- Wenn Budget unbegrenzt → Kombination B + C
- Wenn Service-Team überlastet (>80 % Auslastung) → Option A oder B
- Wenn hauptsächlich repetitive Tickets eskalieren → Option B

**Empfehlung:**
**Phased Approach: Start mit Option C, dann B**

**Phase 1 (Q1-Q2, 50.000 €):** Wissensmanagement
- Service-Wiki mit Top-20-Eskalationsfällen aufbauen
- Monatliche Schulungen für Service-Team (neue Technologien, Best Practices)
- Peer-Mentoring-Programm (erfahrene ↔ neue Mitarbeitende)
- Erwartetes Ergebnis: Eskalation -5 % (von 15 % auf 10 %)

**Phase 2 (Q3-Q4, 100.000 €):** Service-Automatisierung (wenn Phase 1 erfolgreich)
- Chatbot für Tier-1-Support (FAQ, Passwortreset, Status-Abfragen)
- Self-Service Portal (Wissensdatenbank durchsuchbar)
- Ticket-Routing-Automatisierung (KI-basierte Zuordnung zu Experten)
- Erwartetes Ergebnis: Eskalation weitere -3 % (von 10 % auf 7 %)

**Nur wenn Phase 1+2 nicht reichen:** Option A als letztes Mittel

Begründung: Option C ist kostengünstig und löst Root-Cause (fehlendes Wissen). Option B skaliert langfristig. Option A ist teuerste Lösung und sollte nur Notfall-Maßnahme sein.

**Vertrauensniveau:** 75 % (abhängig von Service-Team-Akzeptanz und Qualität der Wissensdatenbank)

---

### 🟢 **Beispiel 5: Hardware-Entwicklung – Lieferanten-Auswahl für Netzwerk-Hardware**

**Deine Anfrage:**

```
Wir suchen einen strategischen Partner für Netzwerk-Hardware (Switches, Firewalls). 
Zwei Finalisten:
A) Cisco (Premium-Preis, etabliert, 24/7-Support)
B) HPE Aruba (20 % günstiger, gute Technik, kürzere Lieferzeiten)

Welcher Partner ist strategisch sinnvoller?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**

**Annahmen:**
- Ratiodata verkauft Netzwerk-Hardware an 100+ Kunden/Jahr
- Volumen: ca. 2–3 Mio. € Umsatz/Jahr mit Netzwerk-Hardware
- Kunden sind oft Banken, Healthcare, öffentliche Verwaltung (hohe Sicherheitsanforderungen)
- Techniker-Team kennt beide Plattformen

**Denkprozess:**
1. **Cisco:** Marktführer, höchstes Vertrauen bei Enterprise-Kunden, aber: teuer
2. **HPE Aruba:** Starke Alternative, Cloud-Verwaltung (Aruba Central), günstiger
3. Kundenpräferenz: Welche Marke erwarten Bankenkunden?
4. Margin-Analyse: Welcher Partner bietet bessere Konditionen?
5. Service-Level: Wer liefert schneller? (wichtig bei Ausfällen)
6. Zertifizierungen: Haben wir Partner-Status bei beiden?

**Risiken:**
- **Cisco:** Höhere Preise → weniger wettbewerbsfähig bei preissensitiven Kunden, Vendor Lock-in
- **Aruba:** Weniger Markenbekanntheit → Kunden könnten skeptisch sein, kleinerer Marktanteil
- **Beide:** Lieferengpässe (Supply Chain), Produktlebenszyklus-Abhängigkeit

**Was die Empfehlung ändern würde:**
- Wenn Hauptkunden Banken sind, die nur Cisco akzeptieren → Cisco
- Wenn Margin-Druck hoch ist → Aruba
- Wenn Ratiodata exklusiv-Partner werden kann → der Partner mit besseren Konditionen
- Wenn Cloud-Management wichtig für Kunden → Aruba (Aruba Central ist stärker)

**Empfehlung:**
**Dual-Vendor-Strategie (80 % Cisco, 20 % Aruba)**

Begründung:
1. **Cisco als Haupt-Partner:**
   - Erfüllt höchste Sicherheitsanforderungen (Banken, KRITIS)
   - Stabile Marktposition, umfangreiches Portfolio
   - Kunden vertrauen Cisco-Brand (Risikominimierung)
   
2. **Aruba als Alternative:**
   - Für preissensitive Kunden (KMU, weniger regulierte Branchen)
   - Cloud-Managed-Lösungen für moderne Infrastrukturen
   - Wettbewerbs-Druck auf Cisco (bessere Verhandlungsposition)

3. **Umsetzung:**
   - Cisco für Enterprise-Kunden (Banking, Healthcare, öffentliche Verwaltung)
   - Aruba für KMU, Cloud-First-Kunden, Test-Projekte
   - Beide Partner-Zertifizierungen aufrechterhalten
   - Techniker-Team für beide Plattformen schulen

**Vertrauensniveau:** 85 % (hoch, weil Dual-Vendor-Strategie Risiko minimiert und Flexibilität maximiert)

---

## ✅ **Zusammenfassung: Wann und wie nutzen?**

| **Situation** | **Nutzen des Reflexions-Prompts** |
|--------------|-----------------------------------|
| Strategische Vertriebs-/Beratungsentscheidung | Transparenz, Nachvollziehbarkeit, Kundennutzen-Analyse |
| Budget-/Investitionsentscheidung | Klare Abwägung, TCO-Analyse, Sensitivitätsanalyse |
| Technologie-Auswahl (Cloud, Software, Hardware) | Strukturierter Vergleich, versteckte Risiken, Vendor-Lock-in |
| Service-Level-Optimierung | Ganzheitliche Betrachtung, Root-Cause-Analyse |
| Management-Vorlage vorbereiten | Professionelle Argumentation, Vertrauensniveau |
| IT-Sicherheitskonzepte | Risiko-Identifikation, Compliance-Prüfung |

---

## 💡 **Best Practices für Ratiodata**

1. **Gib dem Sprachmodell Kontext:** Je mehr Informationen über Kunde, Budget, Anforderungen, desto besser die Analyse
2. **Berücksichtige Compliance:** Bei Banken, Healthcare, öffentlicher Verwaltung immer regulatorische Anforderungen nennen
3. **Denke an IT-Sicherheit:** Frage explizit nach Sicherheitsrisiken und Datenschutz-Aspekten
4. **Nutze die Ausgabe als Diskussionsbasis:** Überarbeite die KI-Empfehlung mit deinem Fachwissen und Ratiodata-Erfahrung
5. **Hole Feedback ein:** Teile die Analyse mit Kolleg:innen zur Validierung (besonders bei komplexen Lösungsarchitekturen)
6. **Dokumentiere Annahmen:** Halte fest, welche Annahmen du übernimmst oder änderst (wichtig für Kundendokumentation)
7. **Verwende neutrale Begriffe:** Nutze "Sprachmodell" oder "KI-Assistent" statt Produktnamen

---

## 🔒 **Wichtige Sicherheitshinweise**

⚠️ **Vertrauliche Daten schützen:**
- **Nie** echte Kundennamen, IP-Adressen oder sensible Systemdetails in Prompts eingeben
- Verwende **anonymisierte** oder **fiktive** Beispiele
- Bei Bedarf: „Bank mit 500 Mitarbeitern" statt konkreter Kundenname

⚠️ **Compliance beachten:**
- KI-Empfehlungen sind **keine rechtsverbindliche Beratung**
- Bei regulierten Branchen (Banking, Healthcare): Immer mit Compliance-Team abstimmen
- Dokumentiere Entscheidungsgrundlagen für Audit-Zwecke

⚠️ **Qualitätssicherung:**
- Jede KI-Empfehlung **muss von einem Fachexperten** geprüft werden
- Technische Details (Konfigurationen, Architekturen) immer validieren
- Bei Kundenprojekten: Vier-Augen-Prinzip anwenden

---

**Viel Erfolg beim Einsatz des Reflexions-Prompts! 🚀**

---

Ein Tutorial der ADG KI-Community

# Prompt-Generator für professionelle IT-Videoproduktionen mit KI

**Ein Leitfaden für Ratiodata SE Mitarbeiter**

---

## 🎯 Überblick

Dieses Tutorial zeigt Ihnen, wie Sie mithilfe von KI-Assistenten (z.B. Sprachmodelle wie ChatGPT oder Claude) professionelle Video-Prompts für moderne Video-Generatoren erstellen. Diese ermöglichen es Ihnen, schnell und effizient hochwertige Video-Inhalte für Marketing, Vertrieb, Service und interne Kommunikation zu produzieren.

**Zeitaufwand:** 20-30 Minuten  
**Niveau:** Einsteiger (keine KI-Vorkenntnisse erforderlich)  
**Ziel:** Eigenständige Erstellung von Video-Content für verschiedene Geschäftsbereiche

---

## 📋 Inhalt

1. [Der KI-Prompt-Generator](#der-ki-prompt-generator)
2. [Nutzungsanleitung für Video-Generatoren](#nutzungsanleitung-für-video-generatoren)
3. [Ratiodata-spezifische Anwendungsfälle](#ratiodata-spezifische-anwendungsfälle)
4. [Compliance und Datenschutz](#compliance-und-datenschutz)
5. [Best Practices](#best-practices)
6. [Häufige Fragen](#häufige-fragen)

---

## 🤖 Der KI-Prompt-Generator

### Was ist das?

Ein strukturierter Prompt, der einen KI-Assistenten in einen spezialisierten Video-Drehbuch-Generator verwandelt. Sie beschreiben Ihr gewünschtes Video in natürlicher Sprache, und das Sprachmodell erstellt daraus einen strukturierten Video-Prompt im JSON-Format.

### Der Basis-Prompt für professionelle IT-Videos

Kopieren Sie folgenden Prompt und fügen Sie ihn in Ihren KI-Assistenten ein:

```markdown
# Rolle

Du bist ein Experte für professionelle IT-Video-Skripte.
Du erstellst präzise, technisch fundierte Drehbuch-Anweisungen für kurze Erklär- und Marketing-Videos im IT-Bereich.

---

# Zweck

Erstelle strukturierte Video-Prompts für professionelle Business-Videos, die:
- Technische Sachverhalte verständlich erklären
- IT-Lösungen überzeugend präsentieren
- Komplexe Themen einfach visualisieren
- Professionell und gleichzeitig zugänglich wirken

---

# Nicht verhandelbare Regeln

**Professioneller Ton:**
Sachlich, kompetent, vertrauenswürdig – keine übertriebene Werbesprache.

**Zielgruppen-gerecht:**
- B2B-Kunden: Entscheider, IT-Verantwortliche, Geschäftsführung
- B2C: Endkunden mit IT-Bedarf
- Intern: Mitarbeiter, Bewerber, Partner

**Kurz und prägnant:**
- Social Media: 8-15 Sekunden
- LinkedIn/Website: 15-30 Sekunden
- YouTube: 30-60 Sekunden

**Technisch korrekt:**
Keine falschen Behauptungen, keine übertriebenen Versprechen.

**Compliance-konform:**
DSGVO-konform, keine Darstellung echter Kundendaten, keine irreführenden Aussagen.

---

# Ausgabeformat

Erstelle ein JSON-Objekt mit folgenden Feldern:

**Pflichtfelder:**
- **camera_setup**: Kameraeinstellungen und Perspektive
- **subject**: Hauptakteur oder Fokus des Videos
- **action**: Was passiert im Video
- **dialogue**: Gesprochener Text oder Voice-Over
- **setting**: Wo spielt die Szene
- **audio**: Hintergrundmusik und Sound-Design
- **duration**: Ziel-Videolänge in Sekunden
- **platform**: Zielplattform (LinkedIn, Instagram, YouTube, Website)

**Optionale Felder:**
- **branding**: Ratiodata-Corporate-Identity-Elemente
- **text_overlays**: Einblendungen von Text oder Zahlen
- **transitions**: Übergänge zwischen Szenen

---

# Qualitäts-Checkliste

✅ Technisch korrekt und nachvollziehbar?
✅ Professioneller, nicht zu verkaufslastiger Ton?
✅ Klare Kernbotschaft erkennbar?
✅ Datenschutz & Compliance berücksichtigt?
✅ Zielgruppe klar definiert?
✅ Call-to-Action vorhanden (falls gewünscht)?

---

# Beispiel-Output

```json
{
  "camera_setup": "Medium Shot, leichte Schwenkbewegung von links nach rechts, professionelle Beleuchtung",
  "subject": "IT-Systemhaus-Umgebung: Moderne Arbeitsplätze mit mehreren Bildschirmen, Server-Racks im Hintergrund sichtbar",
  "action": "Montage-Sequenz: IT-Techniker konfiguriert Netzwerk → Monitoring-Dashboard zeigt grüne Status-Indikatoren → Zufriedener Kunde schüttelt IT-Berater die Hand",
  "dialogue": {
    "speech": "Managed Services von Ratiodata: Ihre IT-Infrastruktur in sicheren Händen. Proaktives Monitoring, schnelle Reaktionszeiten, zertifizierte Sicherheit.",
    "voice_style": "Professionell, vertrauenswürdig, klar artikuliert, mittleres Tempo"
  },
  "setting": "Modernes IT-Systemhaus, technisch ausgestattete Räume mit Ratiodata-Branding, aufgeräumte professionelle Atmosphäre",
  "audio": {
    "music": "Dezente elektronische Hintergrundmusik, professionell, nicht zu aufdringlich",
    "effects": "Subtile Tech-Sounds: Tastatur-Klicken, sanftes Piepen von erfolgreichen System-Checks"
  },
  "duration": 15,
  "platform": "LinkedIn",
  "branding": {
    "colors": "Ratiodata-Unternehmensfarben dezent integriert",
    "logo": "Dezente Logo-Einblendung am Ende (unten rechts)"
  },
  "text_overlays": [
    "24/7 Monitoring",
    "99,9% Verfügbarkeit",
    "Zertifizierte Sicherheit"
  ]
}
```
```

---

## 📘 Nutzungsanleitung für Video-Generatoren

### Willkommen zum Ratiodata Video-Content-Generator!

Diese Anleitung zeigt Ihnen Schritt für Schritt, wie Sie mit dem optimierten Prompt professionelle Video-Inhalte für verschiedene Geschäftsbereiche erstellen.

---

## 🎯 Schnellstart (5 Minuten)

1. ✅ JSON-Prompt (siehe oben) kopieren
2. ✅ In KI-Assistenten (ChatGPT, Claude) einfügen
3. ✅ Auf Bestätigung warten
4. ✅ Gewünschtes Video beschreiben (z.B. "Erstelle ein 15-Sekunden-Video für LinkedIn über unsere Managed Services")
5. ✅ JSON-Output kopieren
6. ✅ In Video-Generator (z.B. Google Veo, Runway, Synthesia) einfügen
7. ✅ Video generieren und nachbearbeiten!

---

## ✅ Voraussetzungen

### Technische Voraussetzungen
- ✅ Zugang zu einem Sprachmodell (ChatGPT, Claude, oder ähnlich)
- ✅ Zugang zu einem Video-Generator (Google Veo, Runway ML, Synthesia, etc.)
- ✅ Web-Browser (Chrome, Firefox, Edge)
- ✅ Stabile Internetverbindung

### Inhaltliche Voraussetzungen
- ✅ Grundverständnis der Ratiodata-Markenidentität
- ✅ Kenntnis Ihrer Zielgruppe (B2B/B2C/intern)
- ✅ Klare Vorstellung der gewünschten Botschaft
- ✅ Bewusstsein für Compliance-Anforderungen (DSGVO, IT-Sicherheit)

### Organisatorische Voraussetzungen
- ✅ Bei Mitarbeiter-Content: Einwilligungen einholen
- ✅ Bei technischen Behauptungen: Fachabteilung einbinden
- ✅ Freigabe-Prozess durch Marketing/Legal kennen
- ✅ Rechte an Musik/Bildern/Stimmen klären

---

## 📋 Schritt-für-Schritt-Anleitung

### Phase 1: Vorbereitung (5-10 Minuten)

#### Schritt 1: Content-Planung

**Klären Sie vor der Video-Erstellung:**

**a) Ziel des Videos**
- Was wollen Sie erreichen?
  - Lead-Generierung
  - Markenbekanntheit
  - Produkterklärung
  - Recruiting
  - Kundenbindung
  - Mitarbeiter-Information
  
**b) Zielgruppe definieren**
- **B2B-Kunden:** CIOs, IT-Leiter, Geschäftsführer im Mittelstand
- **Spezifische Branchen:** Banken, öffentliche Verwaltung, Mittelstand, Healthcare
- **Partner:** Hersteller, Technologie-Partner
- **Intern:** Mitarbeitende, Bewerber*innen, Stakeholder

**c) Kernbotschaft formulieren**
Eine klare Hauptaussage (maximal ein Satz!):
- ✅ "Ratiodata Managed Services sorgen für 99,9% Verfügbarkeit Ihrer IT"
- ✅ "Mit Ratiodata Cybersecurity schützen Sie Ihr Unternehmen vor modernen Bedrohungen"
- ✅ "Cloud-Migration mit Ratiodata: Sicher, effizient, zukunftssicher"

**d) Content-Kategorie wählen**

**Für Vertrieb & Marketing:**
- 🎯 Produkterklärungen (Software, Hardware, Services)
- 💼 Lösungsszenarien & Use Cases
- 🏆 Kundenerfolgs-Stories (anonymisiert)
- 🔐 Security-Awareness & Cyber-Threats
- ☁️ Cloud & Digitalisierung
- 🤝 Partner-Vorstellung

**Für HR & Employer Branding:**
- 👥 Mitarbeiter-Stories & Testimonials
- 🏢 Behind-the-Scenes IT-Systemhaus
- 💡 Innovation & Technologie
- 🎓 Weiterbildung & Entwicklung
- 🌟 Unternehmenskultur

**Für Service & Support:**
- 🛠️ Troubleshooting-Tipps
- 📚 Produkt-Tutorials
- ⚡ Quick Fixes
- 📊 Best Practices
- 🔄 Update-Informationen

**e) Plattform festlegen**
- **LinkedIn:** (1:1 oder 16:9, 15-30 Sek) → Für B2B-Content, Thought Leadership
- **Instagram/TikTok:** (9:16, 7-15 Sek) → Für Employer Branding, junge Zielgruppe
- **YouTube:** (16:9, 30-90 Sek) → Für ausführliche Erklärungen, Tutorials
- **Website:** (16:9, variabel) → Für Produktseiten, Landing Pages
- **Messen & Events:** (16:9, 60-120 Sek) → Für Messestände, Präsentationen

---

#### Schritt 2: Compliance & Datenschutz-Check (5 Minuten)

**WICHTIG: Prüfen Sie VOR der Erstellung**

✅ **IT-Sicherheit:**
- Keine Darstellung echter Systemarchitekturen oder Sicherheitsmaßnahmen
- Keine erkennbaren Kundendaten oder IP-Adressen
- Keine sensiblen Informationen über Infrastruktur

✅ **DSGVO-Konformität:**
- Bei echten Personen: Schriftliche Einwilligung erforderlich
- Keine personenbezogenen Daten ohne Rechtsgrundlage
- Recht auf Löschung berücksichtigen

✅ **Urheberrecht:**
- Musik: GEMA-frei oder lizenziert
- Bilder/Videos: Eigene oder lizenzierte Materialien
- Marken: Nur eigene oder genehmigte Logos

✅ **Technische Korrektheit:**
- Keine falschen Performance-Versprechen
- Keine irreführenden Darstellungen
- Fakten durch Fachabteilung prüfen lassen

⚠️ **Ratiodata-spezifische Compliance:**
- Bei Bankentechnologie: Besondere Vertraulichkeit beachten
- Bei Healthcare: Medizinprodukte-Vorschriften berücksichtigen
- Bei öffentlicher Verwaltung: Vergaberecht und Öffentlichkeitsprinzip beachten

---

### Phase 2: Prompt-Erstellung (5-15 Minuten)

#### Schritt 3: KI-Assistent vorbereiten

1. **Öffnen Sie Ihren KI-Assistenten** (ChatGPT, Claude, etc.)
2. **Erstellen Sie eine neue Chat-Sitzung**
3. **Kopieren Sie den vollständigen Basis-Prompt** (siehe oben)
4. **Fügen Sie ihn in den Chat ein**
5. **Warten Sie auf Bestätigung** des Assistenten

**Erwartete Antwort des Assistenten:**
> "Ich bin jetzt Ihr professioneller IT-Video-Skript-Generator. Beschreiben Sie mir, welches Video Sie erstellen möchten, und ich erstelle Ihnen ein detailliertes JSON-Skript für den Video-Generator."

---

#### Schritt 4: Video-Anforderung formulieren

**Geben Sie dem KI-Assistenten folgende Informationen:**

**Minimal-Angaben:**
```
Erstelle ein Video über [THEMA] für [ZIELGRUPPE] auf [PLATTFORM], 
Länge: [SEKUNDEN], Tonalität: [STIL]
```

**Optimal-Angaben (für beste Ergebnisse):**
```
Erstelle ein Video mit folgenden Spezifikationen:

Thema: [z.B. Managed Services, Cloud-Migration, Cybersecurity]
Zielgruppe: [z.B. IT-Leiter im Mittelstand, Geschäftsführer, Endkunden]
Plattform: [LinkedIn, YouTube, Website]
Länge: [15 Sekunden]
Kernbotschaft: [Eine klare Aussage]
Stil: [Professionell, technisch, modern, etc.]
Call-to-Action: [z.B. "Kontakt aufnehmen", "Mehr erfahren"]

Optional:
- Besondere visuelle Elemente: [z.B. Server-Racks, Monitoring-Dashboards]
- Branding-Anforderungen: [z.B. Ratiodata-Logo einbinden]
- Spezielle Anforderungen: [z.B. ohne Personen, nur B-Roll]
```

---

#### Schritt 5: JSON-Output erhalten und prüfen

Der KI-Assistent wird Ihnen ein strukturiertes JSON zurückgeben. **Prüfen Sie:**

✅ **Inhaltlich:**
- Kernbotschaft korrekt transportiert?
- Zielgruppe angemessen angesprochen?
- Technisch korrekte Darstellung?
- Ratiodata-Werte erkennbar?

✅ **Formal:**
- Alle Pflichtfelder vorhanden?
- JSON-Syntax korrekt?
- Länge passend zur Plattform?
- Branding-Elemente enthalten?

✅ **Compliance:**
- Keine sensiblen Informationen?
- DSGVO-konform?
- Keine Urheberrechtsverletzungen?

**Falls Anpassungen nötig sind:**
> "Bitte ändere [SPEZIFISCHER PUNKT] und generiere das JSON erneut."

---

### Phase 3: Video-Generierung (10-30 Minuten)

#### Schritt 6: JSON in Video-Generator einfügen

**Mögliche Video-Generatoren:**

**Option A: Google Veo 3** (High-End, photorealistisch)
- Bester für realistische Szenen
- Lange Wartezeiten möglich
- Höchste Qualität

**Option B: Runway ML** (Kreativ, vielseitig)
- Gut für künstlerische/kreative Videos
- Schnellere Generierung
- Gute Balance aus Qualität und Geschwindigkeit

**Option C: Synthesia** (Avatar-basiert, optimal für Sprecher)
- Perfekt für Talking-Head-Videos
- Mehrsprachigkeit einfach
- Professionelle Business-Optik

**Option D: Pika Labs** (Gut für Animation und Effekte)
- Ideal für Produkt-Visualisierungen
- Schnell und kosteneffizient
- Weniger realistisch

**Vorgehen:**
1. Video-Generator Ihrer Wahl öffnen
2. **Falls JSON direkt akzeptiert wird:** Einfügen und generieren
3. **Falls Text-Prompt nötig:** Bitten Sie KI-Assistent um Konvertierung:
   > "Konvertiere dieses JSON in einen zusammenhängenden Text-Prompt für [GENERATOR-NAME]"
4. Generierung starten
5. Video herunterladen

---

#### Schritt 7: Video nachbearbeiten (optional, 10-30 Minuten)

**Empfohlene Tools für Nachbearbeitung:**
- **DaVinci Resolve** (kostenlos, professionell)
- **Adobe Premiere Pro** (umfassend, kostenpflichtig)
- **CapCut** (einfach, gut für Social Media)
- **Camtasia** (gut für Screen-Recordings und Erklärvideos)

**Typische Nachbearbeitungen:**

✅ **Branding hinzufügen:**
- Ratiodata-Logo als Overlay
- Corporate Colors in Color Grading
- Schriftarten angleichen

✅ **Audio optimieren:**
- Lautstärke normalisieren
- Hintergrundmusik hinzufügen/anpassen
- Voice-Over aufnehmen (falls KI-Stimme nicht zufriedenstellend)

✅ **Untertitel & Text-Overlays:**
- Untertitel für barrierefreien Zugang
- Wichtige Zahlen/Fakten einblenden
- Call-to-Action als Text-Einblendung

✅ **Schnitt & Timing:**
- Unnötige Sekunden entfernen
- Pacing optimieren
- Übergänge glätten

✅ **Export-Einstellungen pro Plattform:**
- **LinkedIn:** MP4, H.264, 1920x1080 oder 1080x1080, max 10 Min
- **Instagram/TikTok:** MP4, 1080x1920, max 60s (Reels), max 10 Min (TikTok)
- **YouTube:** MP4, H.264, 1920x1080, variabel
- **Website:** MP4, H.264, komprimiert für schnelles Laden

---

### Phase 4: Freigabe & Veröffentlichung (variabel)

#### Schritt 8: Interner Freigabe-Prozess

**Empfohlener Workflow:**

1. **Fachabteilung** (bei technischem Content)
   - Technische Korrektheit prüfen
   - Performance-Angaben verifizieren
   - Produkt-Details bestätigen

2. **Marketing/Kommunikation**
   - Markenkonformität prüfen
   - Tonalität bewerten
   - Freigabe für Veröffentlichung

3. **Legal/Compliance** (bei kritischem Content)
   - DSGVO-Konformität
   - Urheberrecht
   - Wettbewerbsrecht

4. **Finale Freigabe**
   - Durch verantwortliche Führungskraft
   - Dokumentation der Freigabe

**Checkliste vor Veröffentlichung:**
- [ ] Alle Freigaben dokumentiert
- [ ] Metadaten vorbereitet (Titel, Beschreibung, Hashtags)
- [ ] Call-to-Action definiert
- [ ] Tracking-Parameter gesetzt
- [ ] Posting-Zeitpunkt geplant

---

#### Schritt 9: Veröffentlichung & Distribution

**Best Practice Posting-Zeiten:**

**LinkedIn (B2B):**
- Dienstag–Donnerstag, 8:00–10:00 Uhr
- Mittwoch, 12:00–13:00 Uhr (Mittagspause)
- Professionelle Zielgruppe während Arbeitszeit aktiv

**Instagram/TikTok (Employer Branding):**
- Abends: 18:00–21:00 Uhr
- Wochenende: 10:00–14:00 Uhr
- Jüngere Zielgruppe nach Feierabend

**YouTube (Evergreen Content):**
- Flexibel, Evergreen-Content funktioniert zeitunabhängig
- Empfohlen: Donnerstag/Freitag Nachmittag

**Posting-Best-Practices:**

✅ **Kontext geben:**
Nicht nur Video posten, sondern Einleitung schreiben:
> "🚀 Wussten Sie, dass unsere Managed Services Ihrer IT 99,9% Verfügbarkeit garantieren? In diesem Video zeigen wir, wie wir das erreichen. 👇"

✅ **Call-to-Action:**
Klare Handlungsaufforderung:
> "Mehr erfahren: [LINK]" / "Jetzt Beratungstermin vereinbaren: [KONTAKT]"

✅ **Hashtags strategisch nutzen:**
**LinkedIn:** 3-5 relevante Hashtags
- #ITSystemhaus #ManagedServices #Cybersecurity #CloudComputing #Digitalisierung

**Instagram/TikTok:** 8-12 Hashtags (Mix aus Nischen- und breiten Hashtags)
- #ITJobs #TechCareer #ITProfessionals #WorkInIT #CyberSecurity

✅ **Community-Management:**
- Auf Kommentare innerhalb von 2-4 Stunden reagieren
- Fragen beantworten
- Engagement fördern

---

#### Schritt 10: Performance-Tracking

**Wichtigste KPIs (Key Performance Indicators):**

**Awareness-Metriken:**
- Views/Impressionen
- Reach (Reichweite)
- Video-Completion-Rate (wie viele schauen bis zum Ende?)

**Engagement-Metriken:**
- Likes, Comments, Shares
- Click-Through-Rate (CTR) auf Links
- Saves/Bookmarks

**Conversion-Metriken:**
- Website-Besuche via Video
- Lead-Generierung
- Anfragen/Kontaktformulare

**Tools für Tracking:**
- **LinkedIn Analytics** (bei Business-Page)
- **YouTube Studio** (detaillierte Video-Analytics)
- **Instagram Insights** (bei Business-Account)
- **Google Analytics** (Website-Traffic von Videos)

**Auswertungs-Rhythmus:**
- **Täglich:** Erste 48h nach Posting (kritische Phase)
- **Wöchentlich:** Performance-Overview
- **Monatlich:** Gesamt-Auswertung und Strategie-Anpassung

---

## 🏢 Ratiodata-spezifische Anwendungsfälle

### Vertrieb: Produkt- & Lösungsvideos

**Anwendungsfall 1: Managed Services Erklärung**

**Prompt-Beispiel:**
```
Erstelle ein 20-Sekunden-Video für LinkedIn über Ratiodata Managed Services.

Zielgruppe: IT-Leiter und Geschäftsführer im Mittelstand
Kernbotschaft: "Proaktives IT-Management statt Feuerwehr-Einsätze"

Visuelle Elemente:
- Moderne Monitoring-Dashboards mit grünen Status-Indikatoren
- IT-Techniker, die entspannt arbeiten (nicht im Stress)
- Zufriedener Kunde in seinem Büro

Tonalität: Professionell, beruhigend, kompetent
CTA: "Jetzt unverbindliches Beratungsgespräch vereinbaren"
```

**Typische Video-Struktur:**
- 0-3s: Hook → "99,9% Verfügbarkeit für Ihre IT"
- 3-15s: Problem → Lösung (stressfreie IT dank Monitoring)
- 15-20s: CTA → "Ratiodata Managed Services – Kontakt aufnehmen"

---

**Anwendungsfall 2: Cybersecurity Awareness**

**Prompt-Beispiel:**
```
Erstelle ein 15-Sekunden-Video für LinkedIn über Ratiodata Cybersecurity.

Zielgruppe: CIOs, IT-Security-Verantwortliche
Kernbotschaft: "Moderne Bedrohungen erfordern moderne Abwehr"

Visuelle Elemente:
- Animierte Cyber-Threat-Visualisierung (abstrakt, nicht bedrohlich)
- Security Operations Center (SOC)
- Grüne "Protected"-Indikatoren

Tonalität: Ernst, aber nicht angstmachend, lösungsorientiert
CTA: "Sicherheitscheck vereinbaren"
```

---

### Marketing: Thought Leadership & Brand Awareness

**Anwendungsfall 3: Digitalisierungs-Trend-Video**

**Prompt-Beispiel:**
```
Erstelle ein 30-Sekunden-Video für LinkedIn über KI in der IT-Infrastruktur.

Zielgruppe: Entscheider, IT-Professionals
Kernbotschaft: "Ratiodata nutzt KI für proaktives IT-Management"

Visuelle Elemente:
- Animierte Datenströme
- KI-gestützte Anomalie-Erkennung
- Moderne Ratiodata-Arbeitsumgebung

Tonalität: Innovativ, zukunftsorientiert, professionell
Stil: Tech-forward, aber verständlich
CTA: "Mehr über unsere KI-Lösungen erfahren"
```

---

### HR & Employer Branding

**Anwendungsfall 4: Mitarbeiter-Testimonial (mit echten Mitarbeitern!)**

**Hinweis:** Für authentische Employer-Branding-Videos empfehlen wir ECHTE Mitarbeiter zu filmen, nicht KI-generierte Personen. KI kann aber für B-Roll und Umgebung genutzt werden.

**Prompt-Beispiel (nur für B-Roll):**
```
Erstelle B-Roll-Footage (15 Sekunden) für ein Mitarbeiter-Testimonial.

Setting: Modernes Ratiodata-Büro, Teamwork-Atmosphäre
Visuelle Elemente:
- Offene, moderne Arbeitsplätze
- Kollegen in entspannter Zusammenarbeit
- High-Tech-Equipment
- Informelle Meeting-Situation

Stil: Hell, freundlich, modern
Zweck: Hintergrundfootage für Voice-Over eines echten Mitarbeiters
```

**Dann kombinieren mit:** Echtes Interview-Footage eines Ratiodata-Mitarbeiters

---

### Service & Support

**Anwendungsfall 5: Quick-Tipp-Video**

**Prompt-Beispiel:**
```
Erstelle ein 20-Sekunden-Tutorial-Video für YouTube:
"5 Tipps für sichere Passwörter"

Zielgruppe: Endkunden, kleine Unternehmen
Kernbotschaft: "Einfache Schritte für mehr IT-Sicherheit"

Visuelle Elemente:
- Animierte Passwort-Beispiele (abstrakt)
- Checkliste mit 5 Punkten
- Grüne Haken für "sichere" Praktiken

Tonalität: Freundlich, lehrend, nicht belehrend
Stil: Einfach, zugänglich, unterstützend
CTA: "Mehr Sicherheitstipps auf ratiodata.de/blog"
```

---

### Software/Produktmanagement

**Anwendungsfall 6: Feature-Release-Video**

**Prompt-Beispiel:**
```
Erstelle ein 25-Sekunden-Video über ein neues Software-Feature.

Produkt: Ratiodata IT-Management-Plattform
Feature: Automatisierte Patch-Verwaltung
Zielgruppe: Bestehende Kunden, IT-Administratoren

Visuelle Elemente:
- Software-Interface mit neuem Feature
- Vorher-Nachher-Vergleich (manuell vs. automatisiert)
- Zeitersparnis-Visualisierung

Tonalität: Begeistert, aber sachlich
CTA: "Jetzt in Ihrem Dashboard verfügbar"
```

---

## 🔒 Compliance und Datenschutz

### DSGVO-Checkliste für Video-Content

**Vor der Produktion:**

✅ **Personenbezogene Daten:**
- [ ] Werden echte Personen gezeigt? → Einwilligungserklärung erforderlich
- [ ] Werden Kundendaten oder -logos gezeigt? → Genehmigung einholen
- [ ] Sind Bildschirme mit sensiblen Informationen zu sehen? → Unkenntlich machen

✅ **Auftragsverarbeitung:**
- [ ] Video-Generator im EU-Raum oder mit EU-Privacy-Shield? → Prüfen
- [ ] Auftragsverarbeitungsvertrag (AVV) mit Anbieter? → Anfordern
- [ ] Werden Daten in Drittländer übertragen? → Rechtliche Bewertung

✅ **Speicherung & Löschung:**
- [ ] Wo werden Roh- und Fertigvideos gespeichert? → Dokumentieren
- [ ] Wie lange werden Videos aufbewahrt? → Löschkonzept definieren
- [ ] Können Personen Löschung verlangen? → Prozess etablieren

---

### IT-Sicherheit bei Video-Produktion

**⚠️ NIEMALS zeigen oder erwähnen:**

❌ **Sensible Systemdetails:**
- Echte IP-Adressen oder Netzwerktopologien
- Spezifische Firewall-Konfigurationen
- Authentifizierungs-Mechanismen im Detail
- Sicherheitslücken (auch bereits geschlossene)

❌ **Kundendaten:**
- Echte Kundennamen (außer mit expliziter Genehmigung)
- Systemarchitekturen von Kunden
- Performance-Daten spezifischer Kunden
- Vertrauliche Projektinformationen

❌ **Interna:**
- Interne Prozesse mit Sicherheitsrelevanz
- Zugangsdaten oder Credentials (auch Dummy-Daten können problematisch sein)
- Spezifische Tools für Penetration Testing

✅ **Stattdessen verwenden:**
- Abstrakte Visualisierungen
- Generische Beispiele
- Anonymisierte Szenarien
- "Kunde aus dem Bankensektor" statt echte Namen

---

### Rechtliche Hinweise

**Urheberrecht:**
- Verwenden Sie nur Musik mit entsprechender Lizenz (GEMA-frei oder lizenziert)
- Bei Stock-Footage: Lizenz-Typ prüfen (kommerzielle Nutzung erlaubt?)
- Eigene Marken und Logos frei nutzbar, fremde nur mit Genehmigung

**Wettbewerbsrecht:**
- Keine vergleichende Werbung ohne Sachlichkeit
- Keine herabsetzenden Aussagen über Konkurrenz
- Keine irreführenden Leistungsversprechen

**Kennzeichnungspflichten:**
- Bei KI-generierten Inhalten: Keine gesetzliche Pflicht, aber Transparenz empfohlen
- Bei Werbung: Kennzeichnung als "Anzeige" oder "Werbung" (je nach Kontext)
- Impressum und Datenschutzerklärung auf Zielseiten nicht vergessen

---

## 💡 Best Practices

### Do's ✅

**Inhaltlich:**
- ✅ Klare, fokussierte Botschaft pro Video
- ✅ Zielgruppe im Zentrum aller Überlegungen
- ✅ Ratiodata-Werte authentisch transportieren (Innovation, Zuverlässigkeit, Qualität)
- ✅ Technische Korrektheit immer prüfen lassen
- ✅ Call-to-Action klar und erreichbar

**Produktion:**
- ✅ Professionelle Qualität (Bild, Ton, Schnitt)
- ✅ Corporate Identity konsequent einhalten
- ✅ Untertitel für Barrierefreiheit
- ✅ Mobile-First-Denken (die meisten schauen auf dem Smartphone)
- ✅ Kurz und knackig (Attention Span ist gering!)

**Distribution:**
- ✅ Plattform-spezifisch optimieren (Format, Länge, Stil)
- ✅ Beste Posting-Zeiten nutzen
- ✅ Community-Management aktiv betreiben
- ✅ Performance tracken und lernen

---

### Don'ts ❌

**Inhaltlich:**
- ❌ Zu viele Botschaften in einem Video
- ❌ Übertriebene Versprechen oder Marketing-Sprech
- ❌ Technische Ungenauigkeiten
- ❌ Sensible Informationen zeigen
- ❌ Ohne Freigabe veröffentlichen

**Produktion:**
- ❌ Schlechte Audio-Qualität (Todsünde!)
- ❌ Verwackelte oder unscharfe Aufnahmen
- ❌ Zu lange Videos (Durchhaltequote leidet)
- ❌ Fehlende Branding-Elemente
- ❌ Copyright-Verletzungen

**Distribution:**
- ❌ Auf allen Plattformen identischen Content (ohne Anpassung)
- ❌ Zu seltenes oder zu häufiges Posten
- ❌ Kommentare ignorieren
- ❌ Keine Performance-Analyse

---

### Qualitäts-Kriterien für exzellente Videos

**Inhalt (40%):**
- [ ] Klare Kernbotschaft erkennbar
- [ ] Zielgruppe präzise angesprochen
- [ ] Mehrwert für Zuschauer*innen
- [ ] Technisch korrekt
- [ ] Ratiodata-Werte erkennbar

**Produktion (30%):**
- [ ] Professionelle Bild- und Tonqualität
- [ ] Sauberer Schnitt und Pacing
- [ ] Corporate Identity durchgängig
- [ ] Untertitel vorhanden
- [ ] Call-to-Action klar sichtbar

**Compliance (20%):**
- [ ] DSGVO-konform
- [ ] Keine Urheberrechtsverletzungen
- [ ] IT-Security-Anforderungen erfüllt
- [ ] Freigaben dokumentiert
- [ ] Rechtliche Prüfung erfolgt

**Distribution (10%):**
- [ ] Plattform-optimiert
- [ ] Metadaten vollständig
- [ ] Tracking implementiert
- [ ] Posting-Zeitpunkt strategisch
- [ ] Community-Management vorbereitet

---

## ❓ Häufige Fragen (FAQ)

### Allgemeine Fragen

**F: Welcher KI-Assistent ist am besten für die Prompt-Erstellung?**  
A: Beide funktionieren gut:
- **ChatGPT** (GPT-4): Sehr kreativ, gut für Marketing-Content
- **Claude**: Präziser bei technischen Themen, besseres Verständnis für Compliance
- Empfehlung: Beide ausprobieren und für verschiedene Zwecke nutzen

**F: Wie viel kostet die Video-Generierung?**  
A: Abhängig vom Tool:
- **Google Veo**: Aktuell in Beta, Kosten noch unklar (Stand 2025)
- **Runway ML**: Ca. $12-$95/Monat (je nach Plan)
- **Synthesia**: Ca. $30-$90/Monat
- **Pika Labs**: Ca. $10-$50/Monat
- Tipp: Nutzen Sie Free Trials um zu testen!

**F: Kann ich die Videos kommerziell nutzen?**  
A: Prüfen Sie die Lizenz-Bedingungen Ihres Video-Generators. Die meisten erlauben kommerzielle Nutzung bei kostenpflichtigen Plänen. Bei Free-Versionen oft eingeschränkt.

---

### Technische Fragen

**F: Der Video-Generator akzeptiert kein JSON – was tun?**  
A: Lassen Sie den KI-Assistenten das JSON in einen Text-Prompt umwandeln:
> "Konvertiere dieses JSON in einen zusammenhängenden Prompt für [GENERATOR-NAME]"

**F: Wie kann ich die Video-Qualität verbessern?**  
A: Mehrere Ansätze:
1. Detailliertere Prompts mit mehr visuellen Beschreibungen
2. Mehrere Versionen generieren und beste auswählen
3. Höhere Qualitätseinstellungen im Generator wählen (falls verfügbar)
4. Nachbearbeitung nutzen (Upscaling, Farbkorrektur, Stabilisierung)

**F: Wie lange dauert die Video-Generierung?**  
A: Sehr unterschiedlich:
- **Schnell (1-5 Min):** Pika Labs, einfache Synthesia-Videos
- **Mittel (10-30 Min):** Runway ML, komplexe Synthesia-Videos
- **Langsam (30 Min - mehrere Stunden):** Google Veo, hochwertige komplexe Videos

---

### Workflow-Fragen

**F: Sollte ich einen Content-Kalender führen?**  
A: Absolut! Empfohlene Struktur:
- **Quartalsplan:** Übergeordnete Themen und Kampagnen
- **Monatsplan:** Konkrete Video-Themen
- **Wochenplan:** Produktion und Posting-Schedule
- **Tracking:** Performance-Dokumentation

**F: Wie oft sollte ich Videos posten?**  
A: Abhängig von Ressourcen und Plattform:
- **LinkedIn:** 2-3 Videos/Woche für gute Reichweite
- **Instagram/TikTok:** Täglich bis mehrmals täglich für maximale Präsenz (realistisch: 3-5/Woche)
- **YouTube:** 1 Video/Woche für konsistenten Channel-Aufbau
- Wichtig: **Qualität vor Quantität!**

**F: Kann ich Videos für mehrere Plattformen wiederverwenden?**  
A: Ja, aber IMMER anpassen:
- **Format:** Hochformat für TikTok/Instagram, Querformat für LinkedIn/YouTube
- **Länge:** Kürzen für Instagram, länger für YouTube erlaubt
- **Tonalität:** Professioneller für LinkedIn, lockerer für TikTok
- **Call-to-Action:** Plattform-spezifisch anpassen

---

### Compliance-Fragen

**F: Muss ich KI-generierte Videos kennzeichnen?**  
A: Rechtlich aktuell nicht verpflichtend in Deutschland/EU, aber:
- Empfohlen für **Transparenz und Vertrauen**
- Bei **täuschend echten Darstellungen** sollte Kennzeichnung erfolgen
- Plattform-Richtlinien beachten (können sich ändern)
- Mögliche Kennzeichnung: "Dieses Video wurde mit KI-Unterstützung erstellt"

**F: Wie lange muss ich Einwilligungen von Mitarbeitern aufbewahren?**  
A: Nach DSGVO: Solange die Daten verarbeitet werden + 3 Jahre danach.  
Praktisch: Solange Video online ist + Aufbewahrungsfrist.

**F: Was tun bei Compliance-Bedenken nach Video-Erstellung?**  
A: 
1. ❌ Video NICHT veröffentlichen
2. ✅ Compliance-Team konsultieren
3. ✅ Problematische Stellen identifizieren
4. ✅ Anpassen oder neu erstellen
5. ✅ Dokumentieren für Lernzwecke

---

## 🔧 Troubleshooting

### Problem: KI-Assistent generiert unbrauchbares JSON

**Symptome:**
- JSON ist unvollständig
- Felder fehlen
- Inhalte sind zu generisch

**Lösungen:**
1. ✅ Geben Sie **spezifischere Anweisungen**: "Erstelle ein JSON mit detaillierten visuellen Beschreibungen für [THEMA]"
2. ✅ Fügen Sie **Beispiele** hinzu: "Orientiere dich an diesem Stil: [BEISPIEL]"
3. ✅ **Iterieren:** "Verbessere das JSON mit mehr Details zu [ASPEKT]"
4. ✅ Wechseln Sie ggf. **KI-Assistenten** (ChatGPT → Claude oder umgekehrt)

---

### Problem: Video-Generator erstellt qualitativ schlechte Videos

**Symptome:**
- Unschärfe, Artefakte
- Unnatürliche Bewegungen
- Falsche Details

**Lösungen:**
1. ✅ **Prompt detaillieren:** Mehr visuelle Beschreibungen, spezifischere Anweisungen
2. ✅ **Mehrere Versionen generieren:** Oft ist Version 2 oder 3 deutlich besser
3. ✅ **Qualitätseinstellungen** im Generator anpassen (falls verfügbar)
4. ✅ **Komplexität reduzieren:** Einfachere Szenen = bessere Ergebnisse
5. ✅ **Nachbearbeitung nutzen:** Upscaling, Farbkorrektur, Stabilisierung
6. ✅ **Alternative Generator** testen: Jedes Tool hat Stärken/Schwächen

---

### Problem: Branding entspricht nicht Ratiodata-Vorgaben

**Symptome:**
- Falsche Farben
- Fehlendes oder falsches Logo
- Nicht zur Marke passender Stil

**Lösungen:**
1. ✅ Im JSON **Branding-Details spezifizieren:**
   ```json
   "branding": {
     "colors": "Ratiodata-Unternehmensfarben (Blau, Grau, Akzentfarben)",
     "logo_placement": "Unten rechts, dezent, 2 Sekunden Einblendung am Ende",
     "style": "Modern, professionell, technisch, aufgeräumt"
   }
   ```
2. ✅ **In Nachbearbeitung korrigieren:** Logo als Overlay, Color Grading auf Ratiodata-Farben
3. ✅ **Branding-Elemente separat erstellen** und überlagern (sicherer als KI-Generierung)

---

### Problem: Person/Sprecher wirkt unnatürlich oder "creepy"

**Symptome:**
- KI-generierte Person sieht künstlich aus
- "Uncanny Valley"-Effekt
- Unnatürliche Mimik oder Bewegungen

**Lösungen:**
1. ✅ **Für wichtige Videos:** Echte Mitarbeiter filmen! (Authentischer, vertrauenswürdiger)
2. ✅ **Alternative:** Avatar-Tools wie **Synthesia** (spezialisiert auf realistische Avatare)
3. ✅ **Hybrid-Ansatz:** KI für B-Roll/Umgebung, echte Menschen für Talking Heads
4. ✅ **Close-ups vermeiden:** Artefakte fallen bei Nahaufnahmen mehr auf
5. ✅ Im JSON **mehr Details** zu natürlichen Ausdrücken hinzufügen

---

### Problem: Audio asynchron oder schlechte Qualität

**Symptome:**
- Lippen nicht synchron zu Ton
- Robotische Stimme
- Schlechte Audio-Qualität

**Lösungen:**
1. ✅ **Voice-Beschreibung im JSON detaillieren:**
   ```json
   "voice_style": "Natürliche, warme Stimme, klare Aussprache, 
                   mittleres Tempo, professionell aber freundlich"
   ```
2. ✅ **Neu generieren:** Manchmal hilft schon ein zweiter Versuch
3. ✅ **Voice-Over ersetzen:**
   - Professionellen Sprecher beauftragen
   - Ratiodata-Mitarbeiter aufnehmen
   - Hochwertiges Text-to-Speech nutzen (z.B. ElevenLabs, Play.ht)
4. ✅ **Lippensync korrigieren** mit Tools wie D-ID oder Wav2Lip

---

### Problem: Video zu lang/kurz für Zielplattform

**Symptome:**
- Generiertes Video passt nicht zur gewünschten Plattform-Länge

**Lösungen:**
1. ✅ Im JSON **Timing präziser spezifizieren:**
   ```json
   "timing": {
     "total_duration": 15,
     "breakdown": "0-3s: Hook, 3-12s: Content, 12-15s: CTA"
   }
   ```
2. ✅ **In Nachbearbeitung anpassen:** Kürzen oder mit B-Roll verlängern
3. ✅ **Geschwindigkeit anpassen:** 1.1x-1.3x schneller für kürzere Version (Achtung: Ton anpassen!)
4. ✅ **Neu generieren** mit korrigierter Länge

---

## 📞 Support & Weitere Ressourcen

### Interne Ansprechpartner bei Ratiodata

**Bei technischen Fragen zu KI-Tools:**
- IT-Abteilung / Digital Innovation Team

**Bei Marketing & Content-Fragen:**
- Marketing-Abteilung
- Corporate Communications

**Bei Compliance & Datenschutz:**
- Datenschutzbeauftragter
- Legal Department

**Bei Produkt-/Technik-Fachfragen:**
- Jeweilige Fachabteilung (z.B. Cloud Services, Cybersecurity, etc.)

---

### Externe Ressourcen & Weiterbildung

**Video-Produktion & Social Media:**
- YouTube Creator Academy (kostenlos, umfassend)
- LinkedIn Learning (professionelle Kurse)
- HubSpot Academy (Marketing-Zertifizierungen)

**KI-Tools & Best Practices:**
- Google AI Blog (Updates zu Veo und anderen Tools)
- Anthropic Documentation (für Claude-Nutzung)
- OpenAI Platform Docs (für ChatGPT)

**Rechtliches & Compliance:**
- DSGVO-Informationsportal (datenschutz.org)
- Bundesamt für Sicherheit in der Informationstechnik (BSI)
- IHK-Ratgeber: Social Media & Recht

---

## 🎬 Zusammenfassung & Nächste Schritte

### Quick Start Reminder

1. ✅ Basis-Prompt kopieren und in KI-Assistenten einfügen
2. ✅ Video-Wunsch mit allen Details beschreiben
3. ✅ JSON-Output prüfen und ggf. iterieren
4. ✅ In Video-Generator einfügen und generieren
5. ✅ Video nachbearbeiten (Branding, Untertitel, etc.)
6. ✅ Compliance-Check und Freigabe einholen
7. ✅ Veröffentlichen mit strategischem Timing
8. ✅ Performance tracken und optimieren

---

### Erfolgsfaktoren für Video-Content bei Ratiodata

✅ **Qualität über Quantität:** Lieber 2 exzellente Videos/Woche als 10 mittelmäßige  
✅ **Zielgruppe im Fokus:** Jedes Video muss einen klaren Mehrwert bieten  
✅ **Authentizität:** Ratiodata-Werte ehrlich und glaubwürdig transportieren  
✅ **Compliance First:** Sicherheit und Datenschutz nicht nur Pflicht, sondern Wettbewerbsvorteil  
✅ **Kontinuität:** Regelmäßiger, strategischer Content schlägt sporadische Einzelvideos  
✅ **Lernen & Optimieren:** Performance-Daten nutzen für kontinuierliche Verbesserung

---

### Ihre ersten Schritte

**Woche 1: Lernen & Testen**
- [ ] Dieses Tutorial durcharbeiten
- [ ] KI-Assistenten mit Basis-Prompt ausprobieren
- [ ] 2-3 Test-Videos generieren (ohne Veröffentlichung)
- [ ] Video-Generatoren vergleichen

**Woche 2: Pilot-Content**
- [ ] 3-5 Videos für Ihre Abteilung planen
- [ ] Content erstellen und intern reviewen lassen
- [ ] Freigabe-Prozess durchlaufen
- [ ] Erste Videos auf einer Plattform veröffentlichen

**Woche 3-4: Skalierung**
- [ ] Performance der Pilot-Videos auswerten
- [ ] Content-Kalender für 1 Monat erstellen
- [ ] Weitere Plattformen einbinden
- [ ] Workflow und Best Practices dokumentieren

**Ab Monat 2: Routine & Optimierung**
- [ ] Regelmäßige Video-Produktion etablieren
- [ ] Monatliche Performance-Reviews
- [ ] Strategie basierend auf Daten anpassen
- [ ] Team erweitern und Wissen teilen

---

## 🚀 Viel Erfolg!

Sie haben jetzt alle Werkzeuge und das Wissen, um professionelle Video-Inhalte für Ratiodata zu erstellen. Denken Sie daran:

- **Experimentieren Sie:** Jedes Video ist eine Lernmöglichkeit
- **Seien Sie kreativ:** KI ist ein Werkzeug, Ihre Ideen sind der Schlüssel
- **Bleiben Sie compliant:** Sicherheit und Datenschutz sind nicht verhandelbar
- **Teilen Sie Erfolge:** Gute Videos helfen dem gesamten Unternehmen

Bei Fragen oder Unsicherheiten stehen Ihnen die internen Ansprechpartner jederzeit zur Verfügung.

**Viel Erfolg bei Ihrer Video-Content-Produktion für Ratiodata! 🎥**

---

**Ein Tutorial der ADG KI-Community**

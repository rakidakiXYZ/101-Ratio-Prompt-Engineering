# 🎬 Leitfaden: Meta Prompts für KI-Videos

### (Cinematic Movies & Pixar-Style Movies)

---

## 🧭 1. Was ist ein Meta Prompt?

Ein **Meta Prompt** ist eine Art „Regieanleitung für die KI".
Er beschreibt **nicht direkt den Film**, sondern **führt den Nutzer Schritt für Schritt** zu einer strukturierten Video-Beschreibung im **JSON-Format**.
Dieses Format kann dann in **AI-Videogeneratoren** (z. B. Runway, Pika, Kaiber, Sora) verwendet werden, um **automatisch Filmszenen zu erzeugen**.

---

## 🎥 2. Warum ist das relevant?

Für Unternehmen wie **Ratiodata SE** bietet diese Technik:

* **Schnellere Content-Erstellung** (z. B. Employer-Branding-Videos, Produktvorstellungen, Kundenprojekt-Showcases, Social-Media-Beiträge)
* **Konsistente visuelle Qualität**, da das Sprachmodell klar strukturierte Informationen bekommt
* **Geringere Abhängigkeit von Agenturen** bei einfachen Video-Produktionen
* **Einfache Bedienung** auch ohne technisches Video-Vorwissen
* **Professionelle IT-Kommunikation** für komplexe Managed Services, Cloud-Lösungen und Cybersecurity-Themen

---

## ⚙️ 3. Wie funktioniert ein Meta Prompt?

1. Der Nutzer gibt eine **Idee oder ein Thema** ein (z. B. „Cloud-Migration Erfolgsprojekt bei Ratiodata").
2. Das Sprachmodell stellt gezielte **Fragen** zu Stil, Emotion, Kamera, Musik, Text usw.
3. Aus den Antworten entsteht automatisch eine **strukturierte JSON-Beschreibung**.
4. Diese Beschreibung kann anschließend in ein KI-Videotool eingefügt werden, um ein Video zu erzeugen.

---

## 🎬 4. Meta Prompt 1: **Cinematic Movie Builder**

### 🎯 Ziel

Erstellt realistische, filmreife Szenen – z. B. für Recruiting-Videos, Produktpräsentationen, Kundenprojekt-Showcases oder Managed-Services-Kampagnen.

### 🧩 Struktur (vereinfacht)

```json
{
  "description": "",
  "style": "",
  "camera": "",
  "lighting": "",
  "environment": "",
  "elements": [],
  "motion": "",
  "audio": "",
  "dialogue": [],
  "voice": "",
  "ending": "",
  "text": "",
  "keywords": []
}
```

### 🪄 Beispiel 1 – Deutsch

**Idee:** Eine emotionale Szene über IT-Sicherheit und Vertrauen bei Ratiodata.

```markdown
{
  "description": "Langsame Kamerafahrt durch ein modernes Ratiodata Security Operations Center. IT-Sicherheitsexperten überwachen mehrere Monitore mit Echtzeit-Analysen. Eine Hand zeigt auf einem Dashboard die erfolgreiche Abwehr eines Cyberangriffs. Die Szene endet mit einem zufriedenen Blick zwischen zwei Kollegen vor den Ratiodata-Markenfarben.",
  "style": "cinematic realism",
  "camera": "ruhige Steadicam, sanfte Bewegung durch das SOC",
  "lighting": "professionelles Bürolicht mit blauen Monitor-Reflexionen",
  "environment": "modernes Security Operations Center mit Monitoring-Walls und ergonomischen Arbeitsplätzen",
  "audio": "dezente elektronische Ambient-Musik, leises Tastatur-Klicken",
  "dialogue": [
    {"character": "Erzähler", "line": "IT-Sicherheit braucht Expertise und Vertrauen – seit über 50 Jahren.", "tone": "kompetent, vertrauensvoll"}
  ],
  "voice": "professionelle männliche Erzählerstimme",
  "ending": "Zoom auf das Ratiodata-Logo in Unternehmensfarben",
  "text": "Innovation. Sicherheit. Verlässlichkeit.",
  "keywords": ["Cybersecurity", "Managed Services", "Vertrauen", "4K"]
}
```

### 🪄 Example 1 – English

```markdown
{
  "description": "A slow camera glides through a modern Ratiodata Security Operations Center. IT security experts monitor multiple screens with real-time analytics. A hand points to a dashboard showing successful defense against a cyberattack. The scene ends with a satisfied look between two colleagues in front of Ratiodata's brand colors.",
  "style": "cinematic realism",
  "camera": "smooth steadycam moving through SOC",
  "lighting": "professional office light with blue monitor reflections",
  "environment": "modern Security Operations Center with monitoring walls and ergonomic workstations",
  "audio": "subtle electronic ambient music, quiet keyboard clicks",
  "dialogue": [
    {"character": "Narrator", "line": "IT security needs expertise and trust – for over 50 years.", "tone": "competent, trustworthy"}
  ],
  "voice": "professional male narrator",
  "ending": "zoom to Ratiodata logo in corporate colors",
  "text": "Innovation. Security. Reliability.",
  "keywords": ["cybersecurity", "managed services", "trust", "4K"]
}
```

---

### 🪄 Beispiel 2 – Cloud-Migration & Digitalisierung (Deutsch)

```markdown
{
  "description": "Drohnenaufnahme über das moderne Ratiodata-Rechenzentrum. Kameraschwenk ins Innere zeigt klimatisierte Server-Racks und effiziente Infrastruktur. Ein Cloud-Architect erklärt einem Kunden am Whiteboard die Migrations-Strategie. Nahaufnahme eines Dashboards mit erfolgreicher Cloud-Migration.",
  "style": "documentary cinematic",
  "lighting": "kühles, professionelles Rechenzentrum-Licht mit warmen Akzenten in Besprechungsbereichen",
  "audio": "moderne Tech-Musik, dezente Servergeräusche",
  "text": "Ihre IT. Unsere Cloud. Gemeinsam digital.",
  "keywords": ["Cloud-Services", "Digitalisierung", "IT-Infrastruktur", "Innovation"]
}
```

---

### 🪄 Beispiel 3 – Employer Branding (Englisch)

```markdown
{
  "description": "Close-up of diverse Ratiodata IT professionals collaborating in a modern office space. They work on a complex network architecture diagram. Camera pans to show team members testing new hardware solutions. Scene ends with the team celebrating a successful project deployment.",
  "style": "modern corporate storytelling",
  "camera": "dynamic handheld, authentic feel",
  "lighting": "natural office light with warm undertones",
  "audio": "uplifting indie-tech track",
  "text": "Shape IT. Join Ratiodata.",
  "keywords": ["employer branding", "IT experts", "innovation", "teamwork"]
}
```

---

### 🪄 Beispiel 4 – Bankentechnologie & Finanzsektor (Deutsch)

```markdown
{
  "description": "Elegante Kamerafahrt durch einen modernen Banking-Floor. Ratiodata-Techniker installieren hochsichere Terminal-Systeme. Nahaufnahme von Fingerabdruck-Scannern und verschlüsselten Transaktionen. Ein Bankberater lächelt zufrieden, während im Hintergrund das Ratiodata-Support-Team arbeitet.",
  "style": "sophisticated financial cinematography",
  "camera": "smooth gliding camera, professionelle Bewegungen",
  "lighting": "elegantes Bankenlicht mit Sicherheitsakzenten",
  "environment": "moderne Bankfiliale mit modernster IT-Ausstattung",
  "audio": "vertrauensvolle Klaviermusik, dezente Büroatmosphäre",
  "dialogue": [
    {"character": "Erzähler", "line": "Bankentechnologie, die Vertrauen schafft – mit höchsten Sicherheitsstandards.", "tone": "seriös, kompetent"}
  ],
  "text": "Sichere Lösungen für den Finanzsektor.",
  "keywords": ["Banking", "Fintech", "Sicherheit", "Compliance", "Genossenschaftsbanken"]
}
```

---

## 🧚‍♀️ 5. Meta Prompt 2: **Pixar-Style Movie Builder**

### 🎯 Ziel

Erzeugt animierte, emotionale Kurzfilme im Stil von Pixar – mit Charakteren, Stimmen, Musik und Moral.

### 🧩 Struktur (vereinfacht)

```json
{
  "description": "",
  "style": "Pixar-style emotional 3D animation",
  "characters": [],
  "emotion": "",
  "camera": "",
  "lighting": "",
  "color_palette": "",
  "environment": "",
  "motion": "",
  "dialogue": [],
  "voices": [],
  "audio": "",
  "ending": "",
  "text": "",
  "keywords": []
}
```

---

### 🪄 Beispiel 1 – Deutsch

**Idee:** Eine kleine Firewall lernt, dass IT-Sicherheit Teamwork bedeutet.

```markdown
{
  "description": "Eine winzige, mutige Firewall mit großen Augen bewacht einen Server. Sie beobachtet, wie verschiedene Sicherheitssysteme – Antivirus, Backup, Monitoring – zusammenarbeiten. Die Firewall lernt, dass Sicherheit nur im Team funktioniert. Am Ende tanzen alle Security-Tools gemeinsam um geschützte Daten.",
  "characters": [
    {"name": "Firey", "description": "kleine orangefarbene Firewall mit wachsamen Augen und entschlossenem Gesicht"}
  ],
  "emotion": "Zusammenhalt, Verantwortung, Teamwork",
  "lighting": "warmes digitales Licht in Blau- und Orangetönen",
  "color_palette": "Ratiodata-Blau, Orange für Firewall, grüne Sicherheitssignale",
  "audio": "verspielte elektronische Musik mit rhythmischen Sicherheitsalarm-Beats",
  "dialogue": [
    {"character": "Firey", "line": "Ich dachte, ich kann alles alleine schaffen... aber gemeinsam sind wir unschlagbar!", "tone": "stolz, teamorientiert"}
  ],
  "voices": [
    {"character": "Firey", "voice": "junge, entschlossene Stimme"}
  ],
  "ending": "Kamera zoomt heraus und zeigt perfekt geschütztes Rechenzentrum",
  "text": "IT-Sicherheit ist Teamarbeit. – Ratiodata SE",
  "keywords": ["Pixar-Stil", "Animation", "Cybersecurity", "Teamwork"]
}
```

### 🪄 Example 1 – English

```markdown
{
  "description": "A tiny, brave firewall with big eyes guards a server. It watches as different security systems – antivirus, backup, monitoring – work together. The firewall learns that security only works as a team. It ends with all security tools dancing together around protected data.",
  "characters": [
    {"name": "Firey", "description": "small orange firewall with vigilant eyes and determined face"}
  ],
  "emotion": "unity, responsibility, teamwork",
  "lighting": "warm digital light in blue and orange tones",
  "color_palette": "Ratiodata blue, orange for firewall, green security signals",
  "audio": "playful electronic music with rhythmic security alarm beats",
  "dialogue": [
    {"character": "Firey", "line": "I thought I could handle everything alone... but together we're unbeatable!", "tone": "proud, team-oriented"}
  ],
  "voices": [
    {"character": "Firey", "voice": "young, determined voice"}
  ],
  "ending": "camera zooms out showing perfectly protected data center",
  "text": "IT security is teamwork. – Ratiodata SE",
  "keywords": ["Pixar style", "animation", "cybersecurity", "teamwork"]
}
```

---

### 🪄 Beispiel 2 – Cloud-Migration & Veränderung

```markdown
{
  "description": "Ein nervöses Daten-Paket schwebt zwischen On-Premise-Servern und der Cloud. Es hat Angst vor der Migration. Andere Daten-Pakete zeigen ihm, wie sicher und flexibel die Cloud ist. Das Paket wagt den Sprung und entdeckt eine bunte, sichere neue Welt mit schnelleren Verbindungen.",
  "emotion": "Mut, Veränderung, Vertrauen",
  "audio": "hoffnungsvolle Orchestrierung mit digitalen Effekten",
  "dialogue": [
    {"character": "Daten-Paket", "line": "Veränderung macht Angst... aber manchmal führt sie zu etwas Besserem!", "tone": "zögernd, dann begeistert"}
  ],
  "voices": [
    {"character": "Daten-Paket", "voice": "sympathische, etwas ängstliche Stimme"}
  ],
  "text": "Digitale Transformation. Sicher begleitet. – Ratiodata SE",
  "keywords": ["Pixar", "Cloud-Migration", "Change Management", "Innovation"]
}
```

---

### 🪄 Beispiel 3 – Managed Services (Englisch)

```markdown
{
  "description": "In a busy IT landscape, tiny service robots monitor systems 24/7. One robot named 'Manny' ensures everything runs smoothly – patching systems, responding to alerts, optimizing performance. When a critical issue appears, Manny calls the expert team who resolve it instantly.",
  "emotion": "reliability, dedication, partnership",
  "lighting": "warm service-center glow with blue monitoring screens",
  "audio": "comforting electronic music with gentle alert sounds",
  "dialogue": [
    {"character": "Manny", "line": "I never sleep, so your business never stops!", "tone": "cheerful, reliable"}
  ],
  "voices": [
    {"character": "Manny", "voice": "friendly, energetic voice"}
  ],
  "ending": "camera shows happy business running smoothly",
  "text": "Always on. Always secure. – Ratiodata SE",
  "keywords": ["Pixar style", "managed services", "reliability", "24/7"]
}
```

---

### 🪄 Beispiel 4 – Hardware-Innovation & Produktentwicklung (Deutsch)

```markdown
{
  "description": "Ein kleiner Prozessor-Chip träumt davon, Teil einer großen Innovation zu werden. Er durchläuft verschiedene Entwicklungsphasen – Konzeption, Testing, Integration. Andere Hardware-Komponenten werden zu seinen Freunden. Am Ende ist er Teil einer leistungsstarken Ratiodata-Lösung, die Kunden begeistert.",
  "emotion": "Innovation, Entwicklung, Stolz",
  "lighting": "technisches Labor-Licht mit warmem Erfolgs-Glow",
  "color_palette": "Silber-Metallic, Ratiodata-Blau, innovative Leuchteffekte",
  "audio": "inspirierende Tech-Musik mit Entwicklungs-Progression",
  "dialogue": [
    {"character": "Chippy", "line": "Vom Prototyp zur Lösung – gemeinsam erschaffen wir Großes!", "tone": "begeistert, innovativ"}
  ],
  "voices": [
    {"character": "Chippy", "voice": "neugierige, technikbegeisterte Stimme"}
  ],
  "text": "Hardware mit Herz. Innovation mit System. – Ratiodata SE",
  "keywords": ["Pixar-Stil", "Hardware", "Innovation", "Produktentwicklung"]
}
```

---

## 💡 6. Fazit

| Aspekt      | Cinematic Prompt                                          | Pixar-Style Prompt                                         |
| ----------- | --------------------------------------------------------- | ---------------------------------------------------------- |
| **Ziel**    | Realistische, emotionale Filmszenen                       | Animierte, charakterbasierte Kurzfilme                     |
| **Einsatz** | Employer Branding, Produktvorstellungen, Kundenprojekte   | Storytelling, Wertekommunikation, Schulungsvideos          |
| **Tonfall** | Ruhig, filmisch, professionell                            | Verspielt, emotional, mit Moral                            |
| **Output**  | Kamera, Licht, Text, Musik                                | Charaktere, Stimmen, Emotionen, Musik                      |

---

### 🚀 Nutzen für Ratiodata SE

* **Cinematic Prompt:** Ideal für Recruiting-Videos, Produktpräsentationen, Kundenprojekt-Showcases oder Managed-Services-Kommunikation
* **Pixar Prompt:** Ideal für interne Schulungen, Wertevermittlung, Change-Management oder Awareness-Kampagnen (Cybersecurity, Cloud-Adoption)

Beide Ansätze ermöglichen es, **Videoideen in Minuten zu strukturieren** und direkt in moderne KI-Video-Generatoren zu übertragen.

---

### 🎯 Anwendungsszenarien bei Ratiodata

**Vertrieb:**
- Produktvorstellungen für Hardware- und Software-Lösungen
- Kundenprojekt-Success-Stories
- Lösungspräsentationen für Bankentechnologie

**Marketing:**
- Social-Media-Content für LinkedIn und YouTube
- Employer-Branding-Videos für IT-Fachkräfte
- Event-Trailer für Messen und Kundenveranstaltungen

**Service:**
- Erklärvideos für Managed Services
- Onboarding-Material für neue Service-Kunden
- FAQ-Videos zu häufigen Support-Themen

**Software/Produktmanagement:**
- Feature-Vorstellungen neuer Software-Produkte
- Release-Trailer für Updates
- User-Story-Visualisierungen

**Hardware-Entwicklung:**
- Produktentwicklungs-Dokumentation
- Technologie-Demonstrationen
- Innovationskommunikation

---

### 🔒 Wichtige Hinweise für Ratiodata

**Datenschutz & DSGVO:**
- Keine vertraulichen Kundendaten in Video-Prompts verwenden
- Bei Kundenprojekten: Anonymisierung oder explizite Freigabe einholen
- Keine personenbezogenen Daten von Mitarbeitern ohne Zustimmung

**IT-Sicherheit:**
- Keine sensiblen Systemarchitekturen detailliert darstellen
- Sicherheitskonzepte nur auf abstraktem Level kommunizieren
- Bei Banking-Projekten: Compliance-Richtlinien beachten

**Compliance:**
- Videos mit regulatorischer Relevanz durch Fachabteilung prüfen lassen
- Bei Finanzsektor-Projekten: Besondere Vorsicht bei Darstellungen
- Markenschutz: Ratiodata-Logo und CI-Richtlinien einhalten

---

**Ein Tutorial der ADG KI-Community**

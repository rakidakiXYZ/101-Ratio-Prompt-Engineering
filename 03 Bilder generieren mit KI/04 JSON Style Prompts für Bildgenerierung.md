# 🎯 **JSON Prompting Guide für KI-Bildgenerierung**
## IT-Systemhaus & Managed Services Kommunikation


## 📘 1. Grundprinzipien
### Warum JSON-Prompts?

JSON-Prompts strukturieren Ideen klar und nachvollziehbar.
Statt lange Sätze zu schreiben, werden Inhalte in logische Blöcke unterteilt.
Das führt zu konsistenteren, realistischeren und markenkonformen Bildern für die professionelle IT-Kommunikation.

**Vorteile:**

- Klare Trennung von Stil, Technik, Material und Komposition
- Leicht anpassbar für verschiedene Szenarien (Vertrieb, Service, Cybersecurity, Cloud-Services, Hardware-Entwicklung)
- Besser reproduzierbare Ergebnisse
- Kombinierbar mit internen Corporate Design Richtlinien der Ratiodata SE

💡 **Wichtig:** Verwenden Sie generische Begriffe wie "KI-Tool" oder "Bildgenerator" statt spezifischer Produktnamen. Beachten Sie bei der Bildgenerierung immer die DSGVO-Anforderungen und IT-Sicherheitsrichtlinien.


## ⚙️ 2. Grundstruktur eines JSON-Prompts

```json
{
  "meta": {},
  "subject": {},
  "style": {},
  "technical": {},
  "materials": {},
  "environment": {},
  "composition": {},
  "quality": {}
}
```

💡 **Denke an:**

- **meta:** Zweck, Prioritäten, Gewichtungen
- **subject:** Was wird gezeigt? Wer ist zu sehen?
- **style:** Licht, Stimmung, Farbwelt
- **technical:** Kameraeinstellungen, Fokus, Auflösung
- **materials:** Texturen und Oberflächen
- **environment:** Ort, Tageszeit, Atmosphäre
- **composition:** Bildaufbau, Perspektive, Fokuspunkt
- **quality:** Qualität, Referenzen, Dinge, die vermieden werden sollen


## 🎯 3. Template #1 – IT-Strategiemeeting & Managed Services

### 🇩🇪 Deutsche Version

```json
{
  "meta": {
    "prompt_purpose": "Bild für IT-Strategiekommunikation der Ratiodata SE",
    "priority": ["subject", "style", "composition", "lighting", "environment", "quality"],
    "weights": {
      "subject": 1.0,
      "style": 0.9,
      "composition": 0.85,
      "lighting": 0.8,
      "environment": 0.7,
      "quality": 0.7
    },
    "notes": "Professionelle, technisch versierte Darstellung nach Ratiodata Corporate Design."
  },

  "subject": {
    "what": "Meeting von Ratiodata-Mitarbeitenden, die an einer IT-Infrastruktur-Strategie arbeiten",
    "participants": ["5–6 Personen, gemischtes Geschlecht und Alter, IT-Profis"],
    "actions": ["Diskussion am Konferenztisch", "zeigen auf Cloud-Dashboards, Network-Diagramme und Tablets"],
    "expression_mood": "engagiert, kompetent, innovativ, fokussiert, lösungsorientiert",
    "dress_code": "Business-Casual in Ratiodata-Farben (Blau, Cyan, dezente Grautöne)"
  },

  "style": {
    "primary": "dokumentarisch-realistisch",
    "secondary": ["Tech Editorial", "authentische IT-Reportage"],
    "mood": ["innovativ", "vertrauenswürdig", "technisch versiert", "zukunftsorientiert"],
    "color_palette": ["Ratiodata-Blau (#0066CC)", "helles Cyan (#00A3E0)", "Akzent-Dunkelblau (#003D82)", "warme neutrale Töne"],
    "rendering_quality": ["8k Details", "natürliche Hauttöne", "realistische Kontraste", "professionelle IT-Atmosphäre"]
  },

  "technical": {
    "camera_settings": {
      "lens": "35mm",
      "aperture": "f/4",
      "iso": "200",
      "shutter": "1/125"
    },
    "focus": "Gesichter und Gesten scharf, technische Displays erkennbar, Hintergrund leicht weich",
    "lighting_setup": "weiches Tageslicht durch Fenster, dezente Aufhellung, moderne Bürobeleuchtung",
    "postprocessing": ["minimale Retusche", "echte Farben", "leichte Vignette", "tech-professionell"]
  },

  "materials": {
    "skin_and_faces": "authentische Texturen, natürliche Imperfektionen",
    "fabrics": "Baumwolle, Business-Casual-Stoffe – sichtbar realistische Stoffstruktur",
    "surfaces": "mattes Konferenztischholz, IT-Dokumentation sichtbar, moderne Displays",
    "special": "feine Papierstruktur auf Dokumenten, moderne Tablet- und Monitor-Displays, Netzwerk-Diagramme"
  },

  "environment": {
    "location": "moderner Konferenzraum der Ratiodata SE",
    "background_elements": ["Glaswände", "dezentes Ratiodata-Logo im Hintergrund", "moderne IT-Infrastruktur", "Server-Racks oder Cloud-Visualisierungen im Hintergrund"],
    "lighting_conditions": "Tageslicht mit professioneller, innovativer Grundstimmung",
    "decor": ["moderne Technik", "reduziertes, professionelles Design", "ergonomische Möbel", "dezente IT-Symbolik"],
    "time_of_day": "später Vormittag"
  },

  "composition": {
    "shot_type": "Halbtotale",
    "perspective": "Augenhöhe mit leichtem Winkel für Tiefe",
    "framing": ["Drittelregel", "harmonische Gruppierung"],
    "subject_placement": "Team in leichter Bogenform um den Tisch mit Sicht auf technische Displays",
    "leading_lines": "Tischkanten und Lichtlinien führen zu IT-Dashboards und technischen Visualisierungen",
    "avoid": ["unruhiger Hintergrund", "überbelichtete Fenster", "angeschnittene Köpfe", "stereotype Tech-Klischees"]
  },

  "quality": {
    "include": [
      "authentische IT-Teamarbeit",
      "natürliche Beleuchtung",
      "professioneller IT-Dienstleister-Stil",
      "kompetente technische Ausstrahlung",
      "moderne Arbeitsumgebung"
    ],
    "avoid": [
      "gestellte Posen",
      "überschärfte Haut",
      "künstliche HDR-Effekte",
      "sterile Rechenzentrumsatmosphäre",
      "Hacker-Klischees mit Hoodies"
    ],
    "reference": ["Ratiodata Geschäftsberichte", "moderne IT-Kommunikation", "Enterprise IT-Kampagnen"],
    "safety": "Markenrechte respektieren; keine sensiblen IT-Daten oder Credentials; DSGVO-konform; IT-Sicherheit beachten"
  }
}
```

### 🇬🇧 English Version

```json
{
  "meta": {
    "prompt_purpose": "Corporate image for Ratiodata SE IT strategy communication",
    "priority": ["subject", "style", "composition", "lighting", "environment", "quality"],
    "weights": {
      "subject": 1.0,
      "style": 0.9,
      "composition": 0.85,
      "lighting": 0.8,
      "environment": 0.7,
      "quality": 0.7
    },
    "notes": "Professional and technically proficient depiction in Ratiodata corporate design style."
  },

  "subject": {
    "what": "meeting of Ratiodata employees working on an IT infrastructure strategy",
    "participants": ["5–6 IT professionals of mixed gender and age"],
    "actions": ["discussing around a conference table", "pointing at cloud dashboards, network diagrams, and tablets"],
    "expression_mood": "engaged, competent, innovative, focused, solution-oriented",
    "dress_code": "business-casual in brand colors (blue, cyan, subtle greys)"
  },

  "style": {
    "primary": "documentary photorealism",
    "secondary": ["tech editorial", "authentic IT reportage"],
    "mood": ["innovative", "trustworthy", "technically proficient", "future-focused"],
    "color_palette": ["Ratiodata blue (#0066CC)", "bright cyan (#00A3E0)", "accent dark blue (#003D82)", "warm neutral tones"],
    "rendering_quality": ["8k detail", "natural skin tones", "realistic contrast", "professional IT atmosphere"]
  },

  "technical": {
    "camera_settings": {
      "lens": "35mm",
      "aperture": "f/4",
      "iso": "200",
      "shutter": "1/125"
    },
    "focus": "faces and gestures sharp, technical displays recognizable, background softly defocused",
    "lighting_setup": "soft daylight through windows, balanced fill, modern office lighting",
    "postprocessing": ["minimal retouching", "true color balance", "slight vignette", "tech-professional"]
  },

  "materials": {
    "skin_and_faces": "authentic textures, natural imperfections",
    "fabrics": "cotton, business-casual fabrics with visible structure",
    "surfaces": "matte wooden conference table, IT documentation visible, modern displays",
    "special": "fine paper texture visible on documents, modern tablet and monitor displays, network diagrams"
  },

  "environment": {
    "location": "modern Ratiodata SE conference room",
    "background_elements": ["glass walls", "subtle Ratiodata logo presence", "modern IT infrastructure", "server racks or cloud visualizations in background"],
    "lighting_conditions": "daylight with professional, innovative tone",
    "decor": ["modern technology", "minimalist professional design", "ergonomic furniture", "subtle IT symbolism"],
    "time_of_day": "late morning"
  },

  "composition": {
    "shot_type": "medium wide shot",
    "perspective": "eye-level with slight angle for depth",
    "framing": ["rule of thirds", "balanced team layout"],
    "subject_placement": "team arranged in gentle arc around table with view of technical displays",
    "leading_lines": "table edges guide viewer toward IT dashboards and technical visualizations",
    "avoid": ["cluttered background", "overexposed windows", "cropped heads", "stereotypical tech clichés"]
  },

  "quality": {
    "include": [
      "authentic IT teamwork",
      "natural lighting",
      "professional IT service provider style",
      "competent technical presence",
      "modern work environment"
    ],
    "avoid": [
      "staged poses",
      "over-sharpened skin",
      "artificial HDR effects",
      "sterile data center atmosphere",
      "hacker clichés with hoodies"
    ],
    "reference": ["Ratiodata annual reports", "modern IT communication", "enterprise IT campaigns"],
    "safety": "respect brand rights; no sensitive IT data or credentials; GDPR-compliant; observe IT security"
  }
}
```

---

## 💼 Template #2 – Kundenberatung & Solution Design (Vertrieb)

### 🇩🇪 Deutsch

```json
{
  "meta": {"prompt_purpose": "Vertriebsberatung und Lösungskonzeption bei Ratiodata"},
  "subject": {
    "what": "Ratiodata-Vertriebsmitarbeiter berät Kunden zu IT-Infrastrukturlösungen",
    "participants": ["2–3 Personen: Vertriebsberater und Kunde(n)", "gemischtes Geschlecht und Alter"],
    "actions": ["persönliches Beratungsgespräch", "zeigen auf Präsentation oder Lösungsarchitektur", "gemeinsames Betrachten von Produktübersichten"],
    "expression_mood": "vertrauensvoll, kompetent, kundenorientiert, lösungsfokussiert"
  },
  "style": {
    "primary": "professionelle Businessfotografie",
    "mood": ["vertrauensvoll", "kompetent", "menschlich", "lösungsorientiert"],
    "color_palette": ["Ratiodata-Blau", "warme neutrale Töne", "Weiß", "dezente Grautöne"]
  },
  "technical": {"camera_settings": {"lens": "50mm", "aperture": "f/2.8"}},
  "environment": {"location": "moderner Beratungsraum bei Ratiodata oder beim Kunden", "lighting_conditions": "natürliches Licht mit professioneller Atmosphäre"},
  "composition": {"framing": ["Halbnah", "Drittelregel"], "perspective": "Augenhöhe, gemeinsamer Fokus auf Lösungsdarstellung"},
  "quality": {"include": ["echte Beratungssituation", "professionelle IT-Expertise", "authentische Kundenkommunikation"], "avoid": ["übertriebene Verkaufsposen", "zu inszeniert", "stereotype Business-Klischees"]}
}
```

### 🇬🇧 English

```json
{
  "meta": {"prompt_purpose": "Sales consulting and solution design at Ratiodata"},
  "subject": {
    "what": "Ratiodata sales consultant advising clients on IT infrastructure solutions",
    "participants": ["2–3 people: sales consultant and client(s)", "mixed gender and age"],
    "actions": ["personal consultation meeting", "pointing at presentation or solution architecture", "jointly reviewing product overviews"],
    "expression_mood": "trustworthy, competent, customer-oriented, solution-focused"
  },
  "style": {
    "primary": "professional business photography",
    "mood": ["trustworthy", "competent", "human", "solution-oriented"],
    "color_palette": ["Ratiodata blue", "warm neutral tones", "white", "subtle greys"]
  },
  "technical": {"camera_settings": {"lens": "50mm", "aperture": "f/2.8"}},
  "environment": {"location": "modern consultation room at Ratiodata or client site", "lighting_conditions": "natural light with professional atmosphere"},
  "composition": {"framing": ["medium shot", "rule of thirds"], "perspective": "eye-level, shared focus on solution presentation"},
  "quality": {"include": ["genuine consulting situation", "professional IT expertise", "authentic client communication"], "avoid": ["exaggerated sales poses", "overly staged", "stereotypical business clichés"]}
}
```

---

## 🔐 Template #3 – Cybersecurity & IT-Sicherheit

### 🇩🇪 Deutsch

```json
{
  "meta": {"prompt_purpose": "Cybersecurity-Services und IT-Sicherheitslösungen der Ratiodata"},
  "subject": {
    "what": "Ratiodata Security-Experten analysieren Sicherheitsdashboards im Security Operations Center",
    "participants": ["2–4 IT-Sicherheitsexperten", "diverse Zusammensetzung"],
    "actions": ["Überwachung von Security-Dashboards", "Analyse von Bedrohungen", "Teamkommunikation"],
    "expression_mood": "fokussiert, wachsam, professionell, kompetent"
  },
  "style": {
    "primary": "moderner Tech-Dokumentarstil",
    "mood": ["sicher", "vertrauenswürdig", "vigilant", "technisch versiert"],
    "color_palette": ["Ratiodata-Blau", "dunkles Cyan", "dezente Blautöne", "moderne Monitor-Glows", "warme Akzente"]
  },
  "technical": {"camera_settings": {"lens": "35mm", "aperture": "f/2.8", "iso": "800"}},
  "environment": {
    "location": "modernes Security Operations Center oder IT-Kontrollraum",
    "lighting_conditions": "gedämpftes Raumlicht mit Monitor-Beleuchtung, professionelle Atmosphäre",
    "background_elements": ["mehrere Monitore mit Security-Dashboards", "dezente Ratiodata-Branding-Elemente"]
  },
  "composition": {"framing": ["Halbtotale bis Detail"], "perspective": "leicht erhöht oder seitlich für dynamische Darstellung"},
  "quality": {
    "include": ["authentische IT-Sicherheitsarbeit", "moderne Überwachungstechnologie", "professionelle Security-Atmosphäre"],
    "avoid": ["Hollywood-Hacker-Klischees", "übertriebene Matrix-Ästhetik", "stereotype 'böse Hacker'-Darstellung", "unrealistische Alarm-Szenarien"]
  }
}
```

### 🇬🇧 English

```json
{
  "meta": {"prompt_purpose": "Cybersecurity services and IT security solutions from Ratiodata"},
  "subject": {
    "what": "Ratiodata security experts analyzing security dashboards in Security Operations Center",
    "participants": ["2–4 IT security experts", "diverse composition"],
    "actions": ["monitoring security dashboards", "threat analysis", "team communication"],
    "expression_mood": "focused, vigilant, professional, competent"
  },
  "style": {
    "primary": "modern tech documentary style",
    "mood": ["secure", "trustworthy", "vigilant", "technically proficient"],
    "color_palette": ["Ratiodata blue", "dark cyan", "subtle blue tones", "modern monitor glows", "warm accents"]
  },
  "technical": {"camera_settings": {"lens": "35mm", "aperture": "f/2.8", "iso": "800"}},
  "environment": {
    "location": "modern Security Operations Center or IT control room",
    "lighting_conditions": "dimmed room light with monitor illumination, professional atmosphere",
    "background_elements": ["multiple monitors with security dashboards", "subtle Ratiodata branding elements"]
  },
  "composition": {"framing": ["medium-wide to detail shot"], "perspective": "slightly elevated or lateral for dynamic representation"},
  "quality": {
    "include": ["authentic IT security work", "modern monitoring technology", "professional security atmosphere"],
    "avoid": ["Hollywood hacker clichés", "exaggerated Matrix aesthetics", "stereotypical 'evil hacker' portrayal", "unrealistic alarm scenarios"]
  }
}
```

---

## ☁️ Template #4 – Cloud Services & Digitalisierung

### 🇩🇪 Deutsch

```json
{
  "meta": {"prompt_purpose": "Cloud-Services und digitale Transformation bei Ratiodata"},
  "subject": {
    "what": "Mitarbeitende arbeiten mit Cloud-Infrastruktur und digitalen Plattformen",
    "participants": ["3–5 Personen verschiedener Altersgruppen und Rollen"],
    "actions": ["Nutzung von Cloud-Dashboards", "Collaboration-Tools", "digitale Workspaces"],
    "expression_mood": "innovativ, flexibel, zukunftsorientiert, effizient"
  },
  "style": {
    "primary": "moderne Workplace-Fotografie",
    "mood": ["innovativ", "agil", "vernetzt", "zukunftsorientiert"],
    "color_palette": ["helles Blau", "Cyan", "Weiß", "frische helle Töne", "moderne Tech-Akzente"]
  },
  "technical": {"camera_settings": {"lens": "35mm", "aperture": "f/4"}},
  "environment": {
    "location": "modernes Büro oder flexible Arbeitsumgebung",
    "lighting_conditions": "helles natürliches Licht, moderne offene Atmosphäre",
    "decor": ["moderne Arbeitsplätze", "Cloud-Visualisierungen", "kollaborative Bereiche"]
  },
  "composition": {"framing": ["Halbtotale", "Drittelregel"], "perspective": "Augenhöhe, zeigt Zusammenarbeit und moderne Technologie"},
  "quality": {
    "include": ["moderne Arbeitswelt", "Cloud-Technologie", "flexible Arbeitsmodelle", "digitale Transformation"],
    "avoid": ["veraltete Bürodarstellung", "starre Hierarchien", "isolierte Einzelarbeitsplätze"]
  }
}
```

### 🇬🇧 English

```json
{
  "meta": {"prompt_purpose": "Cloud services and digital transformation at Ratiodata"},
  "subject": {
    "what": "employees working with cloud infrastructure and digital platforms",
    "participants": ["3–5 people of various age groups and roles"],
    "actions": ["using cloud dashboards", "collaboration tools", "digital workspaces"],
    "expression_mood": "innovative, flexible, future-oriented, efficient"
  },
  "style": {
    "primary": "modern workplace photography",
    "mood": ["innovative", "agile", "connected", "future-focused"],
    "color_palette": ["bright blue", "cyan", "white", "fresh light tones", "modern tech accents"]
  },
  "technical": {"camera_settings": {"lens": "35mm", "aperture": "f/4"}},
  "environment": {
    "location": "modern office or flexible work environment",
    "lighting_conditions": "bright natural light, modern open atmosphere",
    "decor": ["modern workstations", "cloud visualizations", "collaborative areas"]
  },
  "composition": {"framing": ["medium-wide", "rule of thirds"], "perspective": "eye-level, shows collaboration and modern technology"},
  "quality": {
    "include": ["modern work environment", "cloud technology", "flexible work models", "digital transformation"],
    "avoid": ["outdated office representation", "rigid hierarchies", "isolated individual workstations"]
  }
}
```

---

## 🛠️ Template #5 – IT-Service & Support

### 🇩🇪 Deutsch

```json
{
  "meta": {"prompt_purpose": "IT-Service und technischer Support der Ratiodata"},
  "subject": {
    "what": "Service-Techniker löst IT-Problem vor Ort oder im Remote-Support",
    "participants": ["1–2 Service-Mitarbeiter", "optional: Kunde"],
    "actions": ["Fehlerdiagnose", "Reparatur", "Systemkonfiguration", "Kundenkommunikation"],
    "expression_mood": "hilfsbereit, kompetent, lösungsorientiert, freundlich"
  },
  "style": {
    "primary": "dokumentarischer Servicebereich-Stil",
    "mood": ["hilfsbereit", "kompetent", "zuverlässig", "kundenorientiert"],
    "color_palette": ["Ratiodata-Blau", "warme neutrale Töne", "professionelle Arbeitskleidung"]
  },
  "technical": {"camera_settings": {"lens": "35mm", "aperture": "f/2.8"}},
  "environment": {
    "location": "Kundenstandort, Rechenzentrum oder Service-Werkstatt",
    "lighting_conditions": "natürliches oder professionelles Arbeitslicht"
  },
  "composition": {"framing": ["Halbnah bis Detail"], "perspective": "zeigt Arbeitshandlung und Interaktion"},
  "quality": {
    "include": ["authentische Service-Arbeit", "professionelle Problemlösung", "moderne IT-Infrastruktur"],
    "avoid": ["gestellt wirkende Reparatur-Szenen", "unrealistische Darstellung", "zu inszeniert"]
  }
}
```

### 🇬🇧 English

```json
{
  "meta": {"prompt_purpose": "IT service and technical support from Ratiodata"},
  "subject": {
    "what": "service technician solving IT problem on-site or in remote support",
    "participants": ["1–2 service employees", "optional: customer"],
    "actions": ["fault diagnosis", "repair", "system configuration", "customer communication"],
    "expression_mood": "helpful, competent, solution-oriented, friendly"
  },
  "style": {
    "primary": "documentary service area style",
    "mood": ["helpful", "competent", "reliable", "customer-oriented"],
    "color_palette": ["Ratiodata blue", "warm neutral tones", "professional work attire"]
  },
  "technical": {"camera_settings": {"lens": "35mm", "aperture": "f/2.8"}},
  "environment": {
    "location": "customer site, data center, or service workshop",
    "lighting_conditions": "natural or professional work lighting"
  },
  "composition": {"framing": ["medium to detail shot"], "perspective": "shows work action and interaction"},
  "quality": {
    "include": ["authentic service work", "professional problem-solving", "modern IT infrastructure"],
    "avoid": ["staged repair scenes", "unrealistic portrayal", "overly staged"]
  }
}
```

---

## 👔 Template #6 – Employer Branding / Mitarbeiterportrait

### 🇩🇪 Deutsch

```json
{
  "meta": {"prompt_purpose": "Portrait für Employer Branding Kampagne Ratiodata SE"},
  "subject": {
    "what": "Ratiodata-Mitarbeiter/in steht im modernen IT-Büro mit freundlichem, authentischem Ausdruck",
    "expression_mood": "selbstbewusst, sympathisch, authentisch, kompetent, zugewandt"
  },
  "style": {
    "primary": "editorial portrait photography",
    "mood": ["professionell", "menschlich", "modern", "vertrauensvoll", "technisch versiert"],
    "color_palette": ["Ratiodata-Blau (#0066CC)", "helles Cyan", "Weiß", "warme Grautöne"]
  },
  "technical": {"camera_settings": {"lens": "85mm", "aperture": "f/2.8"}},
  "environment": {"location": "Ratiodata-Büro mit natürlichem Licht und modernem IT-Design", "background_elements": ["dezente Technik-Elemente", "moderne Arbeitsumgebung"]},
  "composition": {"framing": ["Halbportrait", "Drittelregel"], "perspective": "Augenhöhe"},
  "quality": {
    "include": ["natürliche Haut", "Corporate-Look", "Persönlichkeit sichtbar", "IT-Kompetenz", "Diversität"],
    "avoid": ["übermäßige Retusche", "steife Business-Posen", "stereotype Tech-Darstellung"]
  }
}
```

### 🇬🇧 English

```json
{
  "meta": {"prompt_purpose": "Employee portrait for Ratiodata SE employer branding campaign"},
  "subject": {
    "what": "Ratiodata employee standing in modern IT office with friendly, authentic expression",
    "expression_mood": "confident, approachable, authentic, competent, attentive"
  },
  "style": {
    "primary": "editorial portrait photography",
    "mood": ["professional", "human", "modern", "trustworthy", "technically proficient"],
    "color_palette": ["Ratiodata blue (#0066CC)", "bright cyan", "white", "warm greys"]
  },
  "technical": {"camera_settings": {"lens": "85mm", "aperture": "f/2.8"}},
  "environment": {"location": "Ratiodata office with natural light and modern IT design", "background_elements": ["subtle tech elements", "modern work environment"]},
  "composition": {"framing": ["half-portrait", "rule of thirds"], "perspective": "eye-level"},
  "quality": {
    "include": ["natural skin texture", "corporate look", "visible personality", "IT competence", "diversity"],
    "avoid": ["over-retouching", "stiff business poses", "stereotypical tech portrayal"]
  }
}
```

---

## 🏦 Template #7 – Bankentechnologie & Finanzsektor

### 🇩🇪 Deutsch

```json
{
  "meta": {"prompt_purpose": "Bankentechnologie und IT-Lösungen für Finanzinstitute"},
  "subject": {
    "what": "Ratiodata-Experten präsentieren Banking-IT-Lösungen",
    "participants": ["2–4 Personen, Banking-IT-Spezialisten"],
    "actions": ["Präsentation von Core-Banking-Systemen", "Diskussion über Sicherheitsarchitektur", "Compliance-Dokumentation"],
    "expression_mood": "vertrauenswürdig, kompetent, seriös, innovativ"
  },
  "style": {
    "primary": "professionelle Finanzsektor-Fotografie",
    "mood": ["vertrauenswürdig", "seriös", "innovativ", "sicherheitsorientiert"],
    "color_palette": ["Ratiodata-Blau", "dunkles Blau (#003D82)", "Silber", "Weiß", "edle Grautöne"]
  },
  "technical": {"camera_settings": {"lens": "50mm", "aperture": "f/4"}},
  "environment": {
    "location": "repräsentative Räume, die Sicherheit und Professionalität ausstrahlen",
    "background_elements": ["diskrete Banking-Symbolik", "moderne Sicherheitstechnologie"],
    "lighting_conditions": "professionelles, dezentes Licht"
  },
  "composition": {"framing": ["klassisch-professionell"], "perspective": "Augenhöhe, vermittelt Vertrauen"},
  "quality": {
    "include": ["höchste Seriosität", "Compliance-Bewusstsein", "Banking-Grade-Sicherheit", "regulatorische Kompetenz"],
    "avoid": ["zu lockere Darstellung", "Gaming-PC-Ästhetik", "unsichere oder chaotische Darstellung"]
  }
}
```

### 🇬🇧 English

```json
{
  "meta": {"prompt_purpose": "Banking technology and IT solutions for financial institutions"},
  "subject": {
    "what": "Ratiodata experts presenting banking IT solutions",
    "participants": ["2–4 people, banking IT specialists"],
    "actions": ["presenting core banking systems", "discussing security architecture", "compliance documentation"],
    "expression_mood": "trustworthy, competent, serious, innovative"
  },
  "style": {
    "primary": "professional financial sector photography",
    "mood": ["trustworthy", "serious", "innovative", "security-focused"],
    "color_palette": ["Ratiodata blue", "dark blue (#003D82)", "silver", "white", "elegant greys"]
  },
  "technical": {"camera_settings": {"lens": "50mm", "aperture": "f/4"}},
  "environment": {
    "location": "representative spaces that convey security and professionalism",
    "background_elements": ["discreet banking symbolism", "modern security technology"],
    "lighting_conditions": "professional, subtle lighting"
  },
  "composition": {"framing": ["classic-professional"], "perspective": "eye-level, conveys trust"},
  "quality": {
    "include": ["highest seriousness", "compliance awareness", "banking-grade security", "regulatory competence"],
    "avoid": ["too casual portrayal", "gaming PC aesthetics", "insecure or chaotic representation"]
  }
}
```

---

## 📊 8. Interne Anwendungsempfehlung für Ratiodata

| Ziel                                    | Template    | Verwendung                                                    |
| --------------------------------------- | ----------- | ------------------------------------------------------------- |
| **IT-Strategie & Managed Services**      | Template #1 | Geschäftsberichte, Strategiepräsentationen, Unternehmensbroschüren |
| **Vertrieb & Kundenberatung**           | Template #2 | Website, Vertriebspräsentationen, Kundenkommunikation        |
| **Cybersecurity & IT-Sicherheit**       | Template #3 | Security-Kampagnen, Whitepapers, Fachkommunikation           |
| **Cloud Services & Digitalisierung**    | Template #4 | Social Media, Cloud-Marketing, Digitalisierungs-Kampagnen    |
| **IT-Service & Support**                | Template #5 | Service-Dokumentation, Kundenmagazine, Support-Portal        |
| **Employer Branding**                   | Template #6 | Karriereportal, Social Recruiting, Mitarbeiterstories         |
| **Bankentechnologie**                   | Template #7 | Finanzsektor-Marketing, Compliance-Dokumentation, Fachpublikationen |

---

## 🧠 9. Qualitäts-Checkliste vor jedem Render

✅ Motiv klar (wer/was/welches Ziel)
✅ Ratiodata-Markenfarben korrekt (Blau #0066CC, Cyan #00A3E0, Akzent-Dunkelblau #003D82)
✅ Natürliches Licht (kein Spot, kein übertriebenes HDR)
✅ Emotion authentisch und professionell
✅ Kleidung & Haltung glaubwürdig für IT-Kontext
✅ Diversität selbstverständlich dargestellt
✅ Keine IT-Klischees oder Übertreibungen (Hacker-Hoodie, Matrix-Ästhetik)
✅ Perspektive harmonisch (Augenhöhe, Drittelregel)
✅ DSGVO-konform (keine sensiblen Daten, Credentials oder personenbezogene Informationen sichtbar)
✅ IT-Sicherheit beachtet (keine vertraulichen System-Details)

---

## 🎨 10. Ratiodata-spezifische Stilrichtlinien

### Farbwelt
- **Primärfarbe:** Ratiodata-Blau (#0066CC) – Technologie, Innovation & Vertrauen
- **Sekundärfarbe:** Helles Cyan (#00A3E0) – Frische, Modernität & Digitalisierung
- **Akzentfarbe:** Dunkelblau (#003D82) – Stabilität, Sicherheit & Expertise
- **Ergänzungsfarben:** Erfolgs-Grün (#00AA4F), Warnorange (#FF8C00) für spezielle Kontexte
- **Neutrale Töne:** Warme Grautöne, Weiß für Klarheit

### Bildsprache
- **Technisch versiert:** IT-Kompetenz und Expertise zeigen, ohne zu technokratisch zu wirken
- **Innovativ:** Moderne Technologie und zukunftsorientierte Lösungen
- **Vertrauenswürdig:** Professionell, aber zugänglich und menschlich
- **Lösungsorientiert:** Fokus auf praktische IT-Lösungen für reale Geschäftsprobleme
- **Divers:** Selbstverständliche Abbildung verschiedener Menschen, Altersgruppen und Rollen

### Vermeiden
- ❌ Stereotype Tech-Klischees (Hoodie-Hacker, Matrix-Code-Regen)
- ❌ Übertriebene Sci-Fi-Ästhetik
- ❌ Gaming-PC-Optik in professionellem Business-Kontext
- ❌ Ausschließlich junge männliche IT-Nerds
- ❌ Sterile, unmenschliche Rechenzentrumsdarstellung
- ❌ Unsichere oder chaotische Arbeitsumgebungen
- ❌ Sichtbare Credentials, Passwörter oder sensible IT-Daten

---

## 💡 11. Praktische Tipps für den Arbeitsalltag

### Für Social Media (LinkedIn, Twitter/X, Facebook)
- Quadratisches Format (1:1) oder Hochformat (9:16) mitdenken
- Platz für Text-Overlays und Call-to-Actions einplanen
- Kompaktere Prompts für schnellere Iterationen
- Emotionale Momente betonen (Team-Erfolge, Innovation)
- LinkedIn-gerechte Professional-Ästhetik

### Für Print-Materialien (Broschüren, Flyer, Poster)
- Hochauflösende Qualität betonen (8k, 300dpi minimum)
- Querformat (16:9 oder 4:3) bevorzugen
- Ruhigere Kompositionen für bessere Lesbarkeit
- Ausreichend Weißraum für Text und Logos

### Für Präsentationen (PowerPoint, Keynote)
- Klare Fokuspunkte setzen
- Genug Weißraum für Texteinblendungen und Diagramme
- Professioneller IT-Look, aber nicht zu technokratisch
- Konsistente Farbpalette durch alle Slides

### Für Employer Branding & Recruiting
- Authentizität vor Perfektion
- Vielfalt der IT-Rollen zeigen (nicht nur Entwickler)
- Moderne Arbeitsumgebung realistisch darstellen
- Work-Life-Balance und Unternehmenskultur kommunizieren
- Persönlichkeiten der Mitarbeitenden durchscheinen lassen

### Für Fachkommunikation & Whitepapers
- Technische Expertise sichtbar machen
- Professionelle Seriosität für Finanz- und Healthcare-Kunden
- Compliance- und Security-Aspekte betonen
- Referenzen zu Zertifizierungen und Standards

---

## 🚀 12. Schnellstart-Guide

### In 5 Schritten zum perfekten Ratiodata-Bild:

1. **Ziel definieren:** Welche Botschaft? Welcher Kanal? Welche Zielgruppe?
2. **Template wählen:** Passendes Beispiel aus diesem Guide auswählen
3. **Anpassen:** Spezifische Details für Ihr Projekt ergänzen (Abteilung, Use Case, Kontext)
4. **Qualitätskontrolle:** Checkliste durchgehen (Farben, DSGVO, IT-Sicherheit)
5. **Generieren:** Prompt in KI-Bildgenerator eingeben und iterieren

### Beispiel-Workflow:

```
Aufgabe: LinkedIn-Post für neue Managed Services
↓
Template #1 (IT-Strategiemeeting) wählen
↓
Anpassen: Fokus auf Cloud-Infrastruktur, Quadratformat, jüngere Zielgruppe
↓
Checkliste: Ratiodata-Farben ✓, Authentisch ✓, Divers ✓, Keine sensiblen Daten ✓
↓
Generieren, iterieren und finalisieren
```

---

## 🔒 13. IT-Sicherheit & Compliance-Hinweise

### DSGVO-Konformität
- ❗ Keine personenbezogenen Daten in generierten Bildern
- ❗ Keine erkennbaren Gesichter realer Personen ohne Einwilligung
- ❗ Keine Kunden- oder Projektdaten sichtbar

### IT-Sicherheit
- 🔒 Keine Credentials, Passwörter oder API-Keys
- 🔒 Keine detaillierten Netzwerkdiagramme mit realen IPs
- 🔒 Keine sensiblen Systemarchitekturen oder Security-Konfigurationen
- 🔒 Keine Informationen über Sicherheitslücken oder Schwachstellen

### Branchenspezifische Anforderungen
- **Finanzsektor:** Besondere Vorsicht bei Banking-Daten, Transaktionen
- **Healthcare:** Patientendaten müssen vollständig anonymisiert sein
- **Öffentliche Verwaltung:** Behördendaten und Citizen-Informationen schützen

---

## 🏢 14. Abteilungsspezifische Anwendungsfälle

### Vertrieb
- Produktpräsentationen (Hardware, Software, Services)
- Kundenberatungs-Szenarien
- Solution-Design-Workshops
- Competitive Analysis Visualisierungen

### Marketing
- Social Media Content (LinkedIn, Twitter/X, Facebook)
- Website-Hero-Images und Landing Pages
- Kampagnen-Visuals (Cloud, Security, Managed Services)
- Event-Marketing (Messen, Webinare)
- Case Study Illustrationen

### Software / Produktmanagement
- Product Roadmap Visualisierungen
- Feature-Announcement-Grafiken
- User Story Workshops
- Agile Development Szenarien
- Developer-Collaboration-Bilder

### Service & Support
- Helpdesk und Support-Szenarien
- Remote Support Darstellungen
- On-Site-Service-Dokumentation
- Incident-Management-Visualisierungen
- Kundenzufriedenheits-Kommunikation

### Hardware-Entwicklung
- Produktentwicklungs-Prozesse
- Testing und Quality Assurance
- Hardware-Integration-Szenarien
- Technische Dokumentation
- Produktlaunch-Visuals

---

## 📌 15. Best Practices für verschiedene Branchen

### Finanzsektor (Banken, Versicherungen)
- **Stil:** Besonders seriös, vertrauenswürdig, compliance-orientiert
- **Farben:** Konservativere Palette, Dunkelblau, Silber, Weiß
- **Fokus:** Sicherheit, Regulierung, Stabilität
- **Vermeiden:** Zu moderne/hippe Ästhetik, lockere Darstellung

### Healthcare
- **Stil:** Professionell, aber menschlich und empathisch
- **Farben:** Frisches Grün zusätzlich zu Ratiodata-Blau
- **Fokus:** Datenschutz, Patientensicherheit, medizinische IT
- **Vermeiden:** Klinische Kälte, sensible Patientendaten

### Mittelstand & KMU
- **Stil:** Nahbar, lösungsorientiert, pragmatisch
- **Farben:** Volle Ratiodata-Palette
- **Fokus:** Praktische IT-Lösungen, Kosteneffizienz, Skalierbarkeit
- **Vermeiden:** Zu konzernlastig oder übertechnisch

### Öffentliche Verwaltung
- **Stil:** Vertrauenswürdig, bürgernah, modern
- **Farben:** Ratiodata-Farben mit bürgerfreundlicher Anmutung
- **Fokus:** Digitalisierung, Bürgerservice, Verwaltungsmodernisierung
- **Vermeiden:** Behördenmuff, veraltete IT-Darstellung

---

## 🎓 16. Weiterführende Tipps

### Iteration und Verfeinerung
- Generieren Sie mehrere Varianten mit leicht angepassten Prompts
- Testen Sie verschiedene Perspektiven und Kompositionen
- Passen Sie Gewichtungen in den `weights` an für unterschiedliche Schwerpunkte
- Dokumentieren Sie erfolgreiche Prompt-Formulierungen für zukünftige Verwendung

### Konsistenz wahren
- Speichern Sie bewährte Prompts in einer Prompt-Bibliothek
- Verwenden Sie einheitliche Farbwerte über alle Generierungen hinweg
- Achten Sie auf konsistente Bildsprache über Kampagnen hinweg
- Erstellen Sie Prompt-Templates für wiederkehrende Use Cases

### Qualitätssicherung
- Lassen Sie generierte Bilder von Kollegen gegenchecken
- Prüfen Sie auf unbeabsichtigte sensible Informationen
- Verifizieren Sie Markenkonformität (Farben, Stil, Tonalität)
- Testen Sie Bilder in verschiedenen Verwendungskontexten (Web, Print, Social Media)

---

## 📞 17. Support und Ressourcen

### Bei Fragen zu:
- **Corporate Design:** Ratiodata Marketing-Team
- **IT-Sicherheit:** Ratiodata Security-Team
- **DSGVO & Compliance:** Datenschutzbeauftragte
- **Markenrichtlinien:** Brand Management

### Nützliche interne Ressourcen:
- Ratiodata Corporate Design Manual
- IT-Sicherheitsrichtlinien
- DSGVO-Compliance-Leitfaden
- Social Media Guidelines

---

## 🎯 Zusammenfassung

Dieser JSON-Prompting-Guide hilft Ihnen, professionelle und markenkonforme Bilder für die IT-Kommunikation der Ratiodata SE zu generieren. 

**Wichtigste Prinzipien:**
1. ✅ Strukturierte JSON-Prompts für konsistente Ergebnisse
2. ✅ Ratiodata-Farbschema konsequent einsetzen
3. ✅ Authentische IT-Darstellung ohne Klischees
4. ✅ DSGVO und IT-Sicherheit immer beachten
5. ✅ Diversität und Professionalität kombinieren
6. ✅ Branchenspezifische Anforderungen berücksichtigen

**Denken Sie daran:**
- KI-generierte Bilder sind ein Werkzeug, kein Ersatz für menschliches Urteilsvermögen
- Lassen Sie wichtige Visuals von Fachexperten überprüfen
- Dokumentieren Sie erfolgreiche Prompts für die Wiederverwendung
- Bleiben Sie experimentierfreudig, aber markentreu

---

**Ein Tutorial der ADG KI-Community**

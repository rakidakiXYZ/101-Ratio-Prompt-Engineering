# PowerPoint-Skill für Ratiodata erstellen - Einfache Anleitung

## Was Sie erreichen

Mit dieser Anleitung erstellen Sie einen PowerPoint-Skill, der automatisch Präsentationen im Ratiodata Corporate Design erstellt.

**Ergebnis:** Sie sagen Claude "Erstelle eine Kundenpräsentation über Managed Services" und erhalten eine fertige PowerPoint im Ratiodata-CI.

---

## Was Sie brauchen

1. ✅ Zugriff auf Claude (claude.ai)
2. ✅ Eine Ratiodata PowerPoint-Vorlage (.pptx Datei mit Ihrem CI)
3. ✅ 10-15 Minuten Zeit

**Optional:** Ratiodata-Logo als separate Datei (falls nicht in der Vorlage)

---

## Schritt 1: Vorlage vorbereiten

### Was macht eine gute Vorlage aus?

Ihre PowerPoint-Vorlage sollte enthalten:
- ✅ Ratiodata-Logo (korrekt platziert)
- ✅ Ratiodata-Farben (#0066CC, #00A3E0, #003D82)
- ✅ Verschiedene Folienlayouts:
  - Titelfolie
  - Standard-Inhaltsfolie
  - Zwei-Spalten-Layout
  - Chart/Diagramm-Folie
- ✅ Master-Folien mit Ihrem Design
- ✅ Footer mit "© 2025 Ratiodata SE | Eine Tochtergesellschaft der Atruvia AG"

**Tipp:** Je besser Ihre Vorlage, desto besser das Ergebnis!

---

## Schritt 2: Skill erstellen mit Claude

### 2.1 Vorlage hochladen

1. Öffnen Sie Claude (claude.ai)
2. Stellen Sie sicher, dass **Skills aktiviert** sind:
   - Einstellungen → Features
   - "Skills" aktivieren
3. Laden Sie Ihre PowerPoint-Vorlage hoch (einfach per Drag & Drop)

### 2.2 Den Magic-Prompt verwenden

Kopieren Sie diesen Prompt und passen Sie ihn an:

```
Ich möchte einen PowerPoint-Skill für Ratiodata erstellen.

Bitte lies die offizielle pptx-Fähigkeit und die skill-creator-Fähigkeit.

Erstelle dann einen neuen Skill namens "ratiodata-powerpoint", der:

1. AUSLÖSER: Aktiviert wird, wenn ich folgendes sage:
   - "Erstelle eine Ratiodata-Präsentation"
   - "Mache eine PowerPoint im Ratiodata CI"
   - "Erstelle Folien für [Thema] im Firmen-Design"

2. DESIGN-SYSTEM: Extrahiere aus meiner hochgeladenen Vorlage:
   - Alle Farben (Hex-Codes) - besonders die Ratiodata-Blautöne
   - Schriftarten und Größen
   - Logo-Position
   - Folienlayouts und deren Verwendung
   
3. RATIODATA-SPEZIFISCH:
   - Firmenwerte integrieren: Innovation, Zuverlässigkeit, Qualität, Sicherheit
   - Immer Footer mit: "© 2025 Ratiodata SE | Eine Tochtergesellschaft der Atruvia AG"
   - Atruvia AG Logo im Footer (falls vorhanden)

4. COMPLIANCE:
   - DSGVO-Hinweis: Keine personenbezogenen Daten ohne Anonymisierung
   - IT-Sicherheit: Keine vertraulichen Systemdaten in Präsentationen
   - Hinweis auf branchenspezifische Anforderungen (Banking, Healthcare)

5. ANWENDUNGSFÄLLE:
   Optimiert für:
   - Vertrieb: Kundenpräsentationen, Pitch-Decks
   - Marketing: Event-Präsentationen, Produktmarketing
   - Service: SLA-Dokumentationen, Service-Berichte
   - Produktmanagement: Feature-Releases, Roadmaps
   - Hardware: Technische Spezifikationen

Erstelle den Skill und gib ihn als ZIP-Datei aus, die ich installieren kann.
```

### 2.3 Claude arbeitet

Claude wird jetzt:
1. ✅ Ihre Vorlage analysieren
2. ✅ Das Design-System extrahieren
3. ✅ Den Skill erstellen
4. ✅ Alles als .skill-Datei paketieren

**Das dauert ca. 2-3 Minuten.**

---

## Schritt 3: Skill installieren

### 3.1 Skill herunterladen

Claude gibt Ihnen einen Download-Link für die `.skill`-Datei.
- Dateiname: z.B. `ratiodata-powerpoint.skill`
- Speichern Sie die Datei auf Ihrem Computer

### 3.2 In Claude installieren

1. Gehen Sie zu **Einstellungen** (Zahnrad-Symbol)
2. Klicken Sie auf **Skills**
3. Klicken Sie **"Upload Skill"** oder **"Skill hochladen"**
4. Wählen Sie Ihre `ratiodata-powerpoint.skill` Datei
5. Bestätigen Sie mit **"Installieren"**

### 3.3 Skill aktivieren

1. In der Skills-Liste finden Sie "ratiodata-powerpoint"
2. Schieben Sie den Schalter auf **"Aktiv"** ✅
3. Fertig!

---

## Schritt 4: Skill testen

### Test 1: Einfache Präsentation

```
Erstelle eine Ratiodata-Präsentation über Managed Services:
- 5 Folien
- Zielgruppe: Mittelständisches Unternehmen
- Inhalt: Was sind Managed Services, Vorteile, unsere Lösung, Kontakt
```

**Was passiert:**
- Claude erstellt automatisch 5 Folien im Ratiodata-Design
- Alle Folien haben Ratiodata-Logo und CI-Farben
- Footer mit Atruvia AG ist automatisch drin
- Sie bekommen eine fertige .pptx zum Download

### Test 2: Kundenpräsentation

```
Erstelle eine Kundenpräsentation für einen Bankkunden:
Titel: "IT-Sicherheit für Sparkassen"
8 Folien
Branche: Banking
Compliance: BaFin-konform
```

**Erwartung:**
- Banking-spezifisches Design (konservativer)
- BaFin-Hinweise werden automatisch eingefügt
- Vertraulichkeits-Level wird beachtet

### Test 3: Interne Präsentation

```
Erstelle eine interne Service-Dokumentation:
"SLA-Übersicht Q1 2025"
5 Folien mit Service-Level-Matrix
```

---

## Tipps für beste Ergebnisse

### ✅ Gute Anfragen an Claude

```
✅ "Erstelle eine Ratiodata-Präsentation über Cybersecurity für einen Healthcare-Kunden, 10 Folien"

✅ "Mache PowerPoint-Folien im Ratiodata CI für einen Sales-Pitch zu Cloud-Services, 12 Folien"

✅ "Erstelle eine technische Spezifikation im Firmendesign für unser neues Hardware-Produkt"
```

### ❌ Vermeiden Sie

```
❌ "Mache eine Präsentation" 
   (zu unspezifisch, Skill wird nicht ausgelöst)

❌ "Erstelle Folien" 
   (kein Hinweis auf Ratiodata CI)
```

### 🎯 Je mehr Details, desto besser

Geben Sie Claude:
- **Thema**: Worum geht es?
- **Folienanzahl**: Wie viele Folien?
- **Zielgruppe**: Kunde oder intern? Welche Branche?
- **Besonderheiten**: Compliance, Vertraulichkeit, spezielle Anforderungen

---

## Häufige Probleme & Lösungen

### Problem 1: "Skill wird nicht aktiviert"

**Symptom:** Claude erstellt normale Folien ohne Ratiodata-Design

**Lösung:** Verwenden Sie explizite Trigger-Wörter:
```
"Erstelle eine RATIODATA-Präsentation..."
"Mache Folien im RATIODATA CI..."
```

### Problem 2: "Farben sind falsch"

**Symptom:** Präsentation hat nicht die Ratiodata-Farben

**Lösung:** Skill neu erstellen mit besserem Prompt:
```
Achte besonders auf die Ratiodata-Farben:
- Hauptblau: #0066CC
- Cyan: #00A3E0  
- Dunkelblau: #003D82
```

### Problem 3: "Logo fehlt"

**Symptom:** Ratiodata-Logo ist nicht auf den Folien

**Lösung:** 
1. Prüfen Sie, ob Logo in Ihrer Vorlage vorhanden ist
2. Falls nicht: Logo als separate Datei hochladen
3. Im Prompt explizit erwähnen:
```
Verwende das hochgeladene Ratiodata-Logo und platziere es oben rechts auf jeder Folie.
```

### Problem 4: "Atruvia AG fehlt im Footer"

**Symptom:** Footer hat nicht "Eine Tochtergesellschaft der Atruvia AG"

**Lösung:** Im Prompt explizit erwähnen:
```
Footer MUSS IMMER enthalten:
"© 2025 Ratiodata SE | Eine Tochtergesellschaft der Atruvia AG"
```

---

## Skill verbessern

### Wenn Sie mehr Vorlagen brauchen

Sie können den Skill jederzeit erweitern:

```
Erweitere meinen ratiodata-powerpoint Skill um:
- Eine Banking-spezifische Vorlage (konservativere Farben, BaFin-Disclaimer)
- Eine Healthcare-Vorlage (DSGVO-Hinweise, medizinische Icons)
- Eine Event-Vorlage (große Bilder, wenig Text)
```

### Wenn Sie andere Layouts brauchen

```
Füge eine neue Folie zum ratiodata-powerpoint Skill hinzu:
- "Service-Level-Vergleich" mit 3-Spalten-Tabelle
- Verwendung für: SLA-Dokumentationen
```

---

## Skill ans Team verteilen

### Option 1: Direkt teilen

1. Ihre `.skill`-Datei per E-Mail oder Intranet teilen
2. Kollegen installieren wie in Schritt 3 beschrieben
3. Fertig!

### Option 2: Quick-Start-Mail

Verschicken Sie diese Vorlage an Ihr Team:

```
Betreff: Neuer PowerPoint-Skill für Ratiodata-Präsentationen

Hallo Team,

ich habe einen Skill erstellt, der automatisch PowerPoint-Präsentationen 
im Ratiodata CI erstellt.

Installation:
1. Skill-Datei herunterladen: [Link zur .skill-Datei]
2. In Claude: Einstellungen → Skills → Upload
3. Skill aktivieren

Verwendung:
"Erstelle eine Ratiodata-Präsentation über [Thema], [X] Folien"

Beispiele:
- "Erstelle eine Kundenpräsentation über Managed Services, 8 Folien"
- "Mache Folien im Ratiodata CI für einen Banking-Pitch, 10 Folien"

Bei Fragen: [Ihr Name/Kontakt]

Viel Erfolg!
```

---

## Zusammenfassung

### Was Sie erreicht haben

✅ Einen PowerPoint-Skill für Ratiodata erstellt  
✅ Automatische CI-konforme Präsentationen auf Knopfdruck  
✅ Zeit gespart bei der Folienerstellung  
✅ Konsistentes Branding über alle Präsentationen  

### Nächste Schritte

1. **Testen Sie verschiedene Szenarien:**
   - Kundenpräsentationen
   - Interne Berichte
   - Technische Dokumentationen

2. **Sammeln Sie Feedback:**
   - Was funktioniert gut?
   - Was fehlt noch?
   - Welche Vorlagen werden gebraucht?

3. **Skill erweitern:**
   - Mehr Folienlayouts
   - Branchenspezifische Anpassungen
   - Abteilungs-spezifische Vorlagen

4. **Mit Team teilen:**
   - Kollegen einweisen
   - Best Practices dokumentieren
   - Support-Kanal einrichten

---

## Checkliste für perfekte Ratiodata-Präsentationen

Vor Finalisierung prüfen:

### Design
- [ ] Ratiodata-Logo auf allen Folien (außer Titelfolie)
- [ ] Farben: #0066CC, #00A3E0, #003D82 verwendet
- [ ] Schriftarten: Segoe UI oder Open Sans
- [ ] Footer vollständig: "© 2025 Ratiodata SE | Eine Tochtergesellschaft der Atruvia AG"

### Inhalt
- [ ] Keine Rechtschreibfehler
- [ ] Fachbegriffe korrekt
- [ ] Ratiodata-Werte kommuniziert (Innovation, Zuverlässigkeit, etc.)
- [ ] Zielgruppengerecht formuliert

### Compliance
- [ ] Keine personenbezogenen Daten (DSGVO)
- [ ] Keine vertraulichen Systemdaten
- [ ] Kunden-Referenzen genehmigt
- [ ] Branchenspezifische Anforderungen beachtet (BaFin, HIPAA, etc.)

---

## Weiterführende Ressourcen

- **Claude Dokumentation:** https://docs.claude.com
- **Ratiodata Intranet:** [Link zu internen CI-Guidelines]
- **ADG KI-Community:** [Link zum internen KI-Forum]
- **Support:** Bei Fragen wenden Sie sich an [Kontakt]

---

## Anhang: Der komplette Prompt nochmal

Für Ihre Unterlagen - der vollständige Prompt zum Kopieren:

```
Ich möchte einen PowerPoint-Skill für Ratiodata erstellen.

Bitte lies die offizielle pptx-Fähigkeit und die skill-creator-Fähigkeit.

Erstelle dann einen neuen Skill namens "ratiodata-powerpoint", der:

1. AUSLÖSER: Aktiviert wird, wenn ich folgendes sage:
   - "Erstelle eine Ratiodata-Präsentation"
   - "Mache eine PowerPoint im Ratiodata CI"
   - "Erstelle Folien für [Thema] im Firmen-Design"
   - "Ratiodata-Pitch-Deck"
   - "Kundenpräsentation im CI"

2. DESIGN-SYSTEM: Extrahiere aus meiner hochgeladenen Vorlage:
   - Alle Farben (Hex-Codes) - besonders Ratiodata-Blautöne
   - Schriftarten (Segoe UI, Open Sans) und Größen
   - Logo-Position und -Größe
   - Alle Folienlayouts und deren Verwendungszweck
   - Abstände und Whitespace-Regeln
   
3. RATIODATA-SPEZIFISCH:
   - Firmenwerte: Innovation, Zuverlässigkeit, Qualität, Sicherheit, Kundenorientierung
   - Immer Footer: "© 2025 Ratiodata SE | Eine Tochtergesellschaft der Atruvia AG"
   - Atruvia AG Logo im Footer (falls vorhanden)
   - Systemhauspartner der Genossenschaftlichen FinanzGruppe erwähnen
   - Branchen: IT-Systemhaus, Managed Services, Bankentechnologie, Cybersecurity, Cloud

4. COMPLIANCE & SICHERHEIT:
   - DSGVO: Keine personenbezogenen Daten ohne Anonymisierung
   - IT-Sicherheit: Keine vertraulichen Systemdaten, Credentials, IP-Adressen
   - Branchenspezifisch:
     * Banking: BaFin-konform, regulatorische Hinweise
     * Healthcare: HIPAA/GDPR, keine Patientendaten
     * Öffentliche Verwaltung: E-Government-Standards, Barrierefreiheit

5. ANWENDUNGSFÄLLE (Ratiodata-Abteilungen):
   
   VERTRIEB:
   - Kundenpräsentationen für Software/Hardware/Services
   - Pitch-Decks für IT-Lösungen
   - Angebotspräsentationen
   - Technical Solution Design
   
   MARKETING:
   - Event-Präsentationen (Messen, Konferenzen)
   - Produktmarketing-Decks
   - Social Media Kampagnen
   - Content-Präsentationen
   
   SERVICE:
   - SLA-Dokumentationen
   - Service-Level-Übersichten
   - Incident Reports
   - Wissensdatenbank-Content
   
   SOFTWARE/PRODUKTMANAGEMENT:
   - Feature-Release-Notes
   - Produkt-Roadmaps
   - Technische Spezifikationen
   - User Story Workshops
   
   HARDWARE-ENTWICKLUNG:
   - Produktspezifikationen
   - Competitive Intelligence
   - Marktanalysen
   - Testkonzepte

6. WORKFLOW:
   - Immer zuerst Design-System aus Vorlage laden
   - Vorlage-basiert arbeiten (Folien duplizieren, nicht neu erstellen)
   - Ratiodata-Logo automatisch platzieren
   - Footer automatisch generieren
   - Compliance-Check vor Finalisierung

Erstelle den Skill, validiere ihn und gib ihn als installationsfähige .skill-Datei aus.
```

---

**Viel Erfolg beim Erstellen Ihrer Ratiodata-Präsentationen!** 🚀

Bei Fragen oder Problemen wenden Sie sich an die ADG KI-Community.

---

**Ein Tutorial der ADG KI-Community**

# **Projektstrukturplan: VolksCar – Modulares Baukasten-Fahrzeug**

## **🔄 Angepasste Version mit präzisierten technischen Details**

---

### **📌 1. Projektübersicht**
**Arbeitstitel:** VolksCar  
**Ziel:** Entwicklung eines modular erweiterbaren, dreirädrigen Leichtfahrzeugs, das als Fahrrad beginnt und zum allradgetriebenen, wettergeschützten Multifunktionsfahrzeug mit Notstromfunktion skalierbar ist.  
**Schwerpunkt:** Baukastenplattform mit standardisierten Schnittstellen für maximale Individualisierung und Reparierbarkeit.  
**Leitbild:** *„Dein Fahrzeug – deine Konfiguration. Von der Stange war gestern.“*

---

### **🎯 2. Ziele & Nutzen**

| Ziel | Beschreibung | Konkreter Nutzen |
|------|-------------|------------------|
| **1. Modularität** | Baukastensystem mit 3 Hauptmodulen (Antrieb, Energie, Dach) und Server-Schacht-Prinzip | Lebenslange Upgrades, leichte Reparatur, individuelle Anpassung |
| **2. Multimodale Energie** | Integration von Akkus, Solar und standardisiertem Baumarkt-Generator (z.B. Einhell) | Reichweitenautonomie, Notstromversorgung (230V), reduzierte Ladeängste |
| **3. Rechtliche Flexibilität** | Konfigurierbare Geschwindigkeitsstufen: 20/25/45/50 km/h | Start als Pedelec, erweiterbar auf S-Pedelec/Kleinkraftrad nach Bedarf |
| **4. Allwettertauglichkeit** | PETG-Frontscheibe + Stoff-/Solardach | Ganzjahresnutzung, Wetterschutz für Oberkörper und Beine |
| **5. Standardkomponenten** | Nutzung verfügbarer E-Bike-Teile und Baumarktgeneratoren | Niedrige Kosten, einfache Ersatzteilbeschaffung, DIY-freundlich |
| **6. Transportkapazität** | 96-Liter-Einkaufskorb + modularer Stauraum | Praxistauglich für Einkauf, Gewerbe, Familien |

---

### **📐 3. Technisches Gesamtsystem**

#### **3.1 Rahmen & Fahrwerk**  
- **Bauform:** Delta-Dreirad (1×26" vorne, 2×21" hinten)  
- **Rahmen:** Doppelrohr-Stahlrahmen (Ø40mm), steigt 30cm hinter dem Sitz an und trägt Modulkasten  
- **Breite:** Maximal 100cm (straßentauglich)  
- **Bodenfreiheit:** 15cm für Stadtgebrauch  
- **Lenkung:** Direktlenkung mit Fahrradkomponenten  

#### **3.2 Zentraler Modulkasten**  
**Position:** Zwischen Hinterrädern, unter dem Einkaufskorb  
**Abmessungen:** 100×35×42 cm (3 nebeneinanderliegende Fächer)  

| Fach | Maße (B×H×T) | Inhalt | Standardkomponente |
|------|--------------|---------|-------------------|
| **Generator** | 40×35×42 cm | Benzingenerator, schallgedämmt | Einhell 2000W (40×35×42 cm) |
| **Elektronik** | 20×35×42 cm | Controller, Laderegler, Wechselrichter | Eigenentwicklung mit Standardsteckern |
| **Akkus** | 20×35×42 cm | 4× E-Bike-Akkus (500Wh each) | 48V/14Ah Standardakkus |

**Zugang:** Von hinten wie Server-Einschübe, auch bei beladenem Korb zugänglich

#### **3.3 Antriebskonfigurationen**

| Level | Setup | Leistung | Geschwindigkeit | Rechtlicher Status |
|-------|-------|----------|-----------------|-------------------|
| **A** | Nur Tretantrieb | 0W | 20-30 km/h | Fahrrad |
| **B** | Mittelmotor | 250-500W | 25 km/h (drosselbar) | Pedelec |
| **C** | Triple-Nabenmotor | 3×500W (1500W) | 45 km/h | S-Pedelec* |
| **D** | Triple-Motor + Generator | 1500W + Generator | 50 km/h (Offroad) | Kleinkraftrad* |

*Mit entsprechender Zulassung

**Triple-Motor Setup:**
- Vorne: 26-Zoll-Nabenmotor (500W)
- Hinten: 2× 21-Zoll-Nabenmotor (je 500W)
- Elektronische Traktionskontrolle für Allradbetrieb

#### **3.4 Energie-Management**
- **Primär:** 2-4 kWh Akkukapazität (4× Standard-E-Bike-Akkus)
- **Sekundär:** Flexible Solarpaneele auf Dach (bis 300W)
- **Tertiär:** Standard-Baumarktgenerator (800-2000W)
- **Steuerung:** Intelligentes Lastmanagement mit automatischer Umschaltung
- **Notstrom:** Generator liefert 230V bei Stillstand (bis 2000W Dauerleistung)

#### **3.5 Wetterschutzsystem**
- **Frontscheibe:** PETG, 3mm, gewölbt, Klemmsystem am Rahmen
- **Dach:** Wahlweise Stoffplane oder festes Solardach
- **Montage:** Ohne zusätzliche Stützen (trägt sich vom Rahmen/Kasten)

#### **3.6 Ladefläche**
- **Einkaufskorb:** 80×30×40 cm (96 Liter), verzinkter Stahl mit Kunststoffgeflecht
- **Zuladung:** Bis 50 kg im Korb + 100 kg Fahrer/Ladung gesamt

---

### **📊 4. Entwicklungsphasen (Roadmap)**

| Phase | Fokus | Hauptaufgaben | Dauer |
|-------|-------|---------------|--------|
| **1. Rahmen-Prototyp** | Mechanische Basis | Rahmenbau, Lenkung, Fahrwerktest | 3 Monate |
| **2. Elektro-Basis** | Mittelmotor-Integration | Antrieb, Akkueinbau, Bremsen | 2 Monate |
| **3. Modulkasten** | Server-Schacht-System | 3-Fach-Kasten, Zugangssystem | 2 Monate |
| **4. Wetterschutz** | Alltagstauglichkeit | PETG-Scheibe, Dach, Ergonomie | 2 Monate |
| **5. Multi-Energy** | Energieautarkie | Generator-Integration, Solar, Steuerung | 3 Monate |
| **6. Triple-Motor** | Hochleistungsversion | Allradantrieb, Traktionskontrolle | 3 Monate |
| **7. Serienvorbereitung** | Dokumentation | Bauanleitungen, Community-Aufbau | laufend |

**Gesamtdauer:** 15-18 Monate bis zur voll konfigurierbaren Plattform

---

### **💰 5. Wirtschaftlichkeit & Kosten**

#### **Basis-Stückliste (Prototyp Phase 1)**
| Komponente | Spezifikation | Kosten (ca.) | Notizen |
|------------|---------------|--------------|---------|
| Stahlrohr & Rahmenbau | Ø40mm, geschweißt | 300 € | Lokale Schweißerei |
| Räder & Reifen | 1×26", 2×21" | 180 € | Standard-Fahrradteile |
| Lenkung & Gabel | Fahrradkomponenten | 120 € | |
| PETG-Scheibe | 3mm, gewölbt | 80 € | Kunststoffhandel |
| Mittelmotor | Bafang M420 (500W) | 400 € | Drosselbar auf 250W |
| Akku | 48V/15Ah | 350 € | Standard-E-Bike |
| Modulkasten | Stahlblech, 3 Fächer | 200 € | Eigenfertigung |
| Korb & Halterungen | 80×30×40 cm | 60 € | |
| Elektronik | Controller, Display | 150 € | |
| **Gesamt (Basis)** | **-** | **~1.840 €** | **Selbstbau-Prototyp** |

#### **Vollausstattung (Phase 6)**
- + 2× Nabenmotoren: 600 €
- + Generator-Modul: 300 €
- + Solardach: 450 €
- + Zusätzliche Akkus: 700 €
- **Gesamt:** ~3.890 €

#### **Vergleich mit Markt**
- Standard-Lastenrad: 2.500-4.000 €
- S-Pedelec: 4.000-6.000 €
- **VolksCar-Vorteil:** Modularität, Notstromfunktion, individuelle Konfiguration

---

### **⚖️ 6. Rechtliche Einordnung**

| Konfiguration | Max. Geschw. | Motorleistung | Zulassung | Versicherung |
|---------------|---------------|---------------|-----------|--------------|
| **Basis (Tret)** | - | 0W | Keine | Keine |
| **Pedelec** | 25 km/h | 250W (gedrosselt) | Keine | Empfohlen |
| **S-Pedelec** | 45 km/h | 500-1000W | Mofa-Prüfbescheinigung | Pflicht (ca. 80€/Jahr) |
| **Kleinkraftrad** | 50 km/h | >1000W | Führerschein Klasse AM | Pflicht + TÜV |
| **Offroad/Privat** | >50 km/h | Bis 1500W | Nur Privatgelände | Eigene Verantwortung |

**Empfehlung:** Basis als 25-km/h-Pedelec vermarkten, mit Upgrade-Optionen

---

### **🛠️ 7. Prototyping-Strategie**

#### **Phase 1: Proof of Concept**
1. Rahmen aus Standardrohren bauen
2. Fahrwerksfunktion testen
3. Basis-Elektroantrieb integrieren

#### **Phase 2: Modularitätsnachweis**
1. Modulkasten mit 3 Fächern fertigen
2. Generator-Einschub testen (Baumarktgenerator)
3. Akku-Wechselsystem validieren

#### **Phase 3: Alltagstauglichkeit**
1. Wetterschutz installieren
2. Korb und Stauraum optimieren
3. Straßentests (500 km)

#### **Phase 4: Hochleistungsversion**
1. Triple-Motor-Integration
2. Allrad-Steuerung programmieren
3. Notstromfunktion testen

---

### **🌍 8. Zielgruppen & Anwendungen**

| Zielgruppe | Primärkonfiguration | Nutzen |
|------------|---------------------|--------|
| **Stadtpendler** | Mittelmotor + Dach | Wettergeschützt, günstig, parkplatzfreundlich |
| **Gewerbe (Lieferdienste)** | Großer Korb + Reichweite | Transport + Notstrom für Geräte |
| **Camper/Outdoor** | Solar + Generator | Energieautarkie, Geländetauglichkeit |
| **Technik-Enthusiasten** | Triple-Motor + Open-Source | Experimentierplattform, Modifikationen |
| **Kommunen/Shared Mobility** | Basis-Pedelec | Teilenutzung, niedrige Wartungskosten |

---

### **🤝 9. Partner & Kooperationen**

#### **Akut benötigt:**
1. **Schweißerei/Rahmenbau** – für Prototypenrahmen
2. **E-Bike-Spezialist** – für Antriebsintegration
3. **Elektronik-Entwickler** – für Steuerungssystem
4. **Kunststoffverarbeitung** – für PETG-Scheibe

#### **Langfristig:**
1. **Hochschulen** – für Forschungskooperationen
2. **Fördergeber** – BMUV, EFRE, Horizon Europe
3. **Community** – Open-Source-Entwicklung
4. **Kleinserienfertiger** – für Bausätze

---

### **📈 10. Nächste konkrete Schritte**

1. **Woche 1-4:** Detaillierte CAD-Zeichnungen des Rahmens
2. **Woche 5-8:** Materialbeschaffung für Prototyp 1
3. **Woche 9-12:** Rahmenbau und mechanischer Zusammenbau
4. **Woche 13-16:** Elektroinstallation und erste Testfahrten
5. **Woche 17-20:** Modulkasten-Entwicklung und -Fertigung
6. **Woche 21-24:** Gesamttest und Dokumentation

---

### **✅ 11. Risiken & Lösungen**

| Risiko | Wahrscheinlichkeit | Auswirkung | Gegenmaßnahme |
|--------|-------------------|------------|---------------|
| Rechtliche Hürden | Mittel | Hoch | Als Pedelec starten, Upgrades dokumentieren |
| Kostenüberschreitung | Hoch | Mittel | Modularer Ansatz, Standardteile, Community |
| Technische Komplexität | Hoch | Hoch | Schrittweise Entwicklung, Fokus auf Basisversion |
| Marktakzeptanz | Mittel | Mittel | Klare Zielgruppenansprache, Praxisvorteile zeigen |

---

### **🚀 12. Einzigartige Verkaufsargumente**

1. **Erster Baumarktgenerator-fähiger Fahrzeugbaukasten**
2. **Skalierbar von Fahrrad bis Leichtkraftrad**
3. **Notstromversorgung integriert**
4. **Open-Source & Community-getrieben**
5. **Wettergeschützt bei minimalem Gewicht**
6. **Reparierbar mit Standardteilen**

---

### **📊 13. Erfolgsmetriken (KPIs)**

| Metrik | Zielwert | Messpunkt |
|--------|----------|-----------|
| Prototyp-Fertigstellung | 6 Monate | Funktionierender Basisprototyp |
| Reichweite (elektrisch) | 80 km | Test unter realen Bedingungen |
| Modulwechselzeit | <5 Minuten | Praxis-Timing |
| Community-Beiträge | 50+ im ersten Jahr | GitHub, Foren |
| Kosten pro km | <0.05 € | Betriebskostenberechnung |
| Kundenzufriedenheit | 4/5 Sternen | Feedback von Testnutzern |

---

**🎯 Fazit:** Das VolksCar adressiert mit seinem modularen Baukastenansatz eine echte Marktlücke zwischen Standard-Fahrrädern und teuren Spezialfahrzeugen. Durch die Integration von Notstromfunktion, Allwettertauglichkeit und skalierbarer Leistung schafft es einen Mehrwert, der über reine Mobilität hinausgeht. Die schrittweise Entwicklungsroadmap ermöglicht realistische Meilensteine mit überschaubarem Risiko.

# **Projektstrukturplan: VolksCar – Modulares Baukasten-Fahrzeug**

---

## **📌 1. Projektübersicht**

**Arbeitstitel:** VolksCar  
**Ziel:** Entwicklung eines modular erweiterbaren, dreirädrigen Leichtfahrzeugs, das als Fahrrad beginnt und zum allradgetriebenen, wettergeschützten Multifunktionsfahrzeug mit Notstromfunktion skalierbar ist.  
**Schwerpunkt:** Baukastenplattform mit standardisierten Schnittstellen für maximale Individualisierung und Reparierbarkeit.  
**Leitbild:** *„Dein Fahrzeug – deine Konfiguration. Von der Stange war gestern."*
**Preisziel:** Basisversion unter 800€ Materialkosten, Bausatz unter 1.000€

---

## **🎯 2. Ziele & Nutzen**

| Ziel | Beschreibung | Konkreter Nutzen |
|------|-------------|------------------|
| **1. Bezahlbare Mobilität** | Gesamtkosten unter 800€ für Basismodell | Zugänglich für breite Bevölkerung |
| **2. Modularität** | Baukastensystem mit Server-Schacht-Prinzip | Lebenslange Upgrades, leichte Reparatur |
| **3. Multimodale Energie** | Akkus + Solar + Generator optional | Reichweitenautonomie, Notstrom möglich |
| **4. Allwettertauglichkeit** | PETG-Frontscheibe + einfaches Dach | Ganzjahresnutzung, praktischer Wetterschutz |
| **5. Standardkomponenten** | E-Bike-Teile + Baumarktgenerator | Einfache Ersatzteilbeschaffung, DIY-freundlich |
| **6. Skalierbare Leistung** | Von 250W bis 1500W konfigurierbar | Rechtliche Flexibilität, individuelle Anpassung |

---

## **📐 3. Technisches Gesamtsystem**

### **3.1 Rahmen & Fahrwerk**  

- **Bauform:** Delta-Dreirad (1×26" vorne, 2×21" hinten)  
- **Rahmen:** Fertigrahmen aus China, Doppelrohr-Stahl (Ø40mm), inkl. 3-fach Modulkasten  
- **Kosten Rahmen:** 250€ (China-Fertigung, versandoptimiert)  
- **Breite:** 100cm (straßentauglich)  
- **Radstand:** ~140cm  

### **3.2 Zentraler Modulkasten**  

**Position:** Zwischen Hinterrädern, unter dem Einkaufskorb  
**Abmessungen:** 100×35×42 cm (3 nebeneinanderliegende Fächer)  

| Fach | Maße (B×H×T) | Inhalt | Kostenrahmen |
|------|--------------|---------|--------------|
| **Generator** | 40×35×42 cm | Optionaler Baumarktgenerator | Generator extra |
| **Elektronik** | 20×35×42 cm | Controller, Laderegler, Verkabelung | Inkl. im Rahmen |
| **Akkus** | 20×35×42 cm | 4× E-Bike-Akkus (je 48V/7Ah) | 4× 60€ = 240€ |

**Zugang:** Von hinten wie Server-Einschübe

### **3.3 Antriebskonfigurationen**

| Level | Setup | Leistung | Geschwindigkeit | Rechtlicher Status | Kosten |
|-------|-------|----------|-----------------|-------------------|--------|
| **A** | Nur Tretantrieb | 0W | 20-30 km/h | Fahrrad | +0€ |
| **B** | Mittelmotor | 250W | 25 km/h | Pedelec | 120€ |
| **C** | Single-Nabenmotor | 500W | 25-45 km/h | S-Pedelec* | 120€ |
| **D** | Triple-Nabenmotor | 3×500W | 45+ km/h | S-Pedelec/Kleinkraftrad* | 360€ |

*Mit entsprechender Zulassung

### **3.4 Energie-Management**

- **Primär:** 336Wh - 1,3kWh (1-4× 48V/7Ah Akkus)
- **Sekundär:** Flexible Solarpaneele optional (150-300W)
- **Tertiär:** Standard-Baumarktgenerator optional (800-2000W)
- **Steuerung:** Einfaches Lastmanagement
- **Reichweite Basis:** 50-60km (1 Akku, 25km/h)

### **3.5 Wetterschutzsystem**

- **Frontscheibe:** PETG, 2mm, vorgeformt aus China: 20€
- **Dach:** PVC-Folie auf Alugestänge: 25€
- **Solar-Dach optional:** Flexibles Panel 150W: 120€

### **3.6 Ladefläche**

- **Einkaufskorb:** 80×30×40 cm (96 Liter): 25€
- **Zuladung:** 50kg im Korb + 100kg Fahrer gesamt

---

## **📊 4. Entwicklungsphasen (Roadmap)**

| Phase | Fokus | Hauptaufgaben | Dauer | Budget |
|-------|-------|---------------|--------|---------|
| **1. Prototyp DE** | Mechanische Basis | Eigenbau-Prototyp, Funktionstest | 3 Monate | 800€ |
| **2. China-Design** | Fertigungsoptimierung | CAD für Massenfertigung, Stanzwerkzeuge | 2 Monate | 1.500€ |
| **3. Testserie** | Alltagstauglichkeit | 10 Vorserien-Fahrzeuge, Straßentests | 3 Monate | 5.000€ |
| **4. Markteinführung** | Bausatz-Produktion | Erstcharge 100 Stück, Dokumentation | 2 Monate | 20.000€ |

---

## **💰 5. Wirtschaftlichkeit & Kosten (REALISTISCH)**

### **5.1 Materialkosten Basisversion**

| Komponente | Spezifikation | Kosten | Quelle |
|------------|---------------|--------|---------|
| Fertigrahmen China | Inkl. Modulkasten, Gabel | 250€ | Alibaba/Bulk |
| Räder & Reifen | 1×26", 2×21" komplett | 65€ | China-Bulk |
| Mittelmotor 250W | Bafang BBS01B | 110€ | China-Direkt |
| Akku 48V/7Ah | Standard-E-Bike | 55€ | China-Bulk |
| Bremsen | Mechanische Scheiben 3× | 45€ | China |
| Wetterschutz | PETG-Scheibe + Dach | 45€ | China |
| Lenkung & Sitz | Standardkomponenten | 35€ | China |
| Korb & Halterungen | 80×30×40cm | 25€ | China |
| Elektronik & Beleuchtung | Controller, Display, LED | 50€ | China-Set |
| **Gesamt Material** | **Basisversion** | **680€** | ✅ **Unter 700€** |

### **5.2 Preismodelle für Endkunden**

| Produkt | Inhalt | Materialkosten | Verkaufspreis |
|---------|--------|----------------|---------------|
| **BASIC-KIT** | Alles zum Selbstbau | 680€ | **799€** |
| **KOMPLETTBAUSATZ** | Teilmontiert | 750€ | **899€** |
| **FERTIGFAHRZEUG** | Komplett montiert | 900€ | **1.099€** |
| **ALLRAD-UPGRADE** | +2 Nabenmotoren | +240€ | +299€ |
| **ENERGIE-PAKET** | +3 Akkus + Solar | +300€ | +399€ |

### **5.3 Vergleich mit Markt**

- Standard-Lastenrad: 2.500-4.000€
- S-Pedelec: 4.000-6.000€
- **VolksCar BASIC:** **799€** (Bausatz)
- **VolksCar FERTIG:** **1.099€**
- **Einsparung:** 65-80% gegenüber Marktprodukten

---

## **⚖️ 6. Rechtliche Einordnung**

| Konfiguration | Motorleistung | Max. Geschw. | Zulassung | Versicherung |
|---------------|---------------|--------------|-----------|--------------|
| **Pedelec** | 250W (gedrosselt) | 25 km/h | Keine | Optional |
| **S-Pedelec** | 500-750W | 45 km/h | Mofa-Prüfbescheinigung | Pflicht (~80€/Jahr) |
| **Kleinkraftrad** | 1000-1500W | 50 km/h | Führerschein AM | Pflicht + TÜV |

**Empfehlung:** Als 25-km/h-Pedelec vermarkten, Upgrades als "Offroad-Kits"

---

## **🌍 7. Zielgruppen & Anwendungen**

| Zielgruppe | Empfohlene Konfiguration | Preis | Nutzen |
|------------|--------------------------|-------|--------|
| **Stadtpendler** | Mittelmotor + 1 Akku | 799€ | Wettergeschützt, günstig |
| **Gewerbe (Lieferdienste)** | Großer Korb + 2 Akkus | 999€ | Transport + Reichweite |
| **Camper/Outdoor** | Solar + Generatoroption | 1.299€ | Energieautarkie |
| **Technik-Enthusiasten** | Allrad + Open-Source | 1.199€ | Experimentierplattform |
| **Kommunen** | Basis-Pedelec | 699€ (Menge) | Teilenutzung, Inklusion |

---

## **📈 8. Nächste konkrete Schritte**

1. **Monat 1-2:** Detaillierte CAD-Zeichnungen für China-Fertigung
2. **Monat 3:** Prototyp aus Standardteilen bauen (800€ Budget)
3. **Monat 4:** Funktionstests und Optimierung
4. **Monat 5:** Kontakt mit chinesischen Fertigungspartnern
5. **Monat 6:** Kostenangebote einholen, Stückzahl kalkulieren
6. **Monat 7:** Crowdfunding/Vorbestellungen starten
7. **Monat 8:** Erstproduktion 100 Stück

---

## **✅ 9. Risiken & Lösungen**

| Risiko | Wahrscheinlichkeit | Lösung |
|--------|-------------------|---------|
| **Lieferketten-Probleme** | Mittel | Mehrere Lieferanten, lokale Alternativen |
| **Qualitätssicherung China** | Hoch | Strenge QC, Testmuster, Garantie |
| **Rechtliche Hürden** | Mittel | Als Pedelec zertifizieren lassen |
| **Akzeptanz Bausatz** | Mittel | Ausführliche Anleitung, Video-Tutorials |
| **Konkurrenz durch Billigprodukte** | Niedrig | Einzigartiges Modulkonzept schützt |

---

## **🚀 10. Einzigartige Verkaufsargumente**

1. **Unschlagbarer Preis:** 799€ für komplettes Bausatz-Fahrzeug
2. **Echte Modularität:** Server-Schacht-System für einfache Upgrades
3. **Notstrom-fähig:** Baumarktgenerator als Range-Extender
4. **Wettergeschützt:** PETG-Scheibe + Dach inklusive
5. **Reparierbar:** Standardteile aus Fahrrad- und Baumarkt
6. **Skalierbar:** Von 250W Fahrrad bis 1500W Allrad

---

## **📊 11. Erfolgsmetriken**

| Metrik | Ziel | Messung |
|--------|------|---------|
| **Materialkosten Basis** | <700€ | Stückliste |
| **Endkundenpreis Bausatz** | 799€ | Verkaufspreis |
| **Montagezeit** | <8 Stunden | Durchschnitt Kunde |
| **Reichweite Basis** | 50+ km | Praxistest |
| **Vorbestellungen** | 100+ Stück | Crowdfunding |
| **Community-Mitglieder** | 500+ | Forum/Gruppen |

---

## **🎯 FAZIT**

Das VolksCar ist mit **Materialkosten von 680€** für die Basisversion und einem **Verkaufspreis von 799€** für den Bausatz nicht nur ein theoretisches Konzept, sondern eine realisierbare, bezahlbare Mobilitätslösung.

**Die Kerninnovationen:**

1. **China-Fertigung** des Rahmens für 250€ statt lokaler Schweißerei
2. **Standardisierte E-Bike-Komponenten** mit bekannten Preisen
3. **Einfacher Selbstbau** durch durchdachtes Bausatzsystem
4. **Echte Upgrade-Fähigkeit** durch Server-Schacht-Prinzip

Das Projekt adressiert eine echte Marktlücke: Ein wettergeschütztes, elektrisches Transportfahrzeug zum Preis eines einfachen E-Bikes. Die modulare Bauweise ermöglicht es Nutzern, genau die Konfiguration zu wählen, die sie benötigen - und sie später zu erweitern, wenn sich die Anforderungen ändern.

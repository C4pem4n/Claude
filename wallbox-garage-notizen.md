# Wallbox und Werkstatt in der Garage: Notizen

Stand: 2026-10-06. Zusammenfassung unserer Diskussion. Alle technischen Angaben sind Praxis-Faustregeln, nicht aus Normen zitiert. Vor Umsetzung von einer Elektrofachkraft prüfen und beim Netzbetreiber anmelden lassen. Land: Deutschland (angenommen).

## Vorhaben
- Erdkabel Haus (Zählerschrank) zur Garage, geplant: 5x16 mm²
- 22-kW-Wallbox (3-phasig) plus DIY-Werkstatt (Kreissäge, Kompressor, Schweißgerät)
- Im Zählerschrank ist bereits ein Überspannungsschutz vorhanden (Typ unbekannt)

## Offene Daten (noch nicht bekannt)
1. Hauptsicherung (A) und Netzform (TN-C, TN-S, TT)
2. Länge der Strecke Haus-Garage
3. Typenschilddaten von Kreissäge, Kompressor, Schweißgerät
4. Wallbox-Modell (hat sie eine DC-Fehlerstromerkennung 6 mA?)
5. Typ des vorhandenen Überspannungsschutzes

## Erdkabel
- Tiefe: ca. 60 cm unter befahrenen Flächen, ca. 40 cm im Garten
- Sandbett, Warnband, ggf. Abdeckung und Leerrohr; Kabel NYY-J
- Querschnitt 5x16 mm²: Belastbarkeit im Erdreich ungefähr 80-100 A (zu prüfen), Vorsicherung ca. 63 A (zu prüfen)

## Wallbox 22 kW
- LS-Schalter 3-polig 32 A, B-Charakteristik: Hager MBN332
- FI Typ B 4-polig 40 A 30 mA: Hager CDB640E (Alternative CDB640D, Typ B+)
- Typ-A-FI nur, wenn die Wallbox integrierte DC-Fehlerstromerkennung (6 mA) hat und der Hersteller Typ A zulässt
- Eigene Zuleitung zur Wallbox, nicht über die Garagen-Unterverteilung (üblich, zu bestätigen)
- Netzbetreiber: bis 11 kW anmeldepflichtig, darüber genehmigungspflichtig (nachfragen); Hausanschluss prüfen, ggf. Lastmanagement

## Überspannungsschutz
- Faustregel: ca. 10 m Leitungslänge, danach zusätzlicher Schutz nahe den Verbrauchern (nicht verifiziert)
- Garage ist ein eigenes Gebäude, daher ggf. eigener Schutz am Eintritt; Hager SPN317 ist nur für TN-C, TN-S braucht 3+1 bzw. 4-polige Variante

## Unterverteilung Garage
- Sinnvoll wegen Werkstatt: eigene Stromkreise, 30-mA-FI für Steckdosen, Platz für Überspannungsschutz
- Zuleitung muss für die Summe der Lasten mit Gleichzeitigkeitsfaktor ausgelegt sein (Faktor vom Elektriker)
- Hausanschluss ist vermutlich der Engpass

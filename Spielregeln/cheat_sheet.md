# Cheat Sheet

# Proben

## Schwellwerte

* Leicht: 1
* Durchschnittlich: 2
* Schwierig: 4
* Sehr schwierig: 6
* Extrem schwierig: 8-10

## Limits

* **Körperlich**: ((Stärke * 2) + Konstitution + Reaktion) / 3 (aufgerundet)
* **Geistig**: ((Logik * 2) + Intuition + Willenskraft) / 3 (aufgerundet)
* **Sozial**: ((Charisma * 2) + Willenskraft + Essenz) / 3 (aufgerundet)

## Erfolgsprobe

    Probe auf (Fertigkeit für Probe) + (Attribut für Probe) [Limit] (Schwellwert)

## Vergleichende Probe

* Haben keinen Schwellwert, da der höhrere Wert gewinnt.
* Limit gilt trotzdem

    Vergleichende Probe auf (Fertigkeit für Probe) + (Attribut für Probe) [Limit] gegen (Fertigkeit für Probe) + (Attribut für Probe) [Limit]

## Ausgedehnte Proben

S. 50, Schwellwerte / Intervalle auf S. 51

## Zweiter Versuch

-2 W6 auf erneute Probe.

## Häufige Proben

* **Wahrnehmungsprobe**: Wahrnehmung + Intuition (Geistig)

### Schlösser knacken

S. 362

#### Standardschloss

* ausg. Probe: Schlosser + Geschick [Körperlich] (Schlossstufe, 1 Kampfrunde)
* mech. Dietrich kann Anzahl Würfel erhöhren oder Schlosser-Fertikeit ersetzen

#### Transponderschlüssel

* benötigt Elektronik-Kiste zur Feststellung der Charakteristik
* Kalibrierung: ausg. Probe: Hardware + Logik [Geistig] (Schlossstufe, 1 Minute)
* Char kalibriert Schloss und knackt gleichzeitig? Würfelpool -2W6

#### Magschloss

* physisch (Keypad, Karte, Stick etc.) oder biometrisch
* Zugriff per Netzwerk manchmal möglich
* Überwachung durch Sicherheitsrigger möglich

* Verkleidung entfernen / anbringen: ausg. Probe: Schlosser + Geschick [Körperlich] (Magschlossstufe * 2, 1 Kampfrunde)
* Verkleidung zerstören: Barrierestufe = Magschlossstufe

* Anti-Manipulationssysteme können Alarm auslösen

# Kampf

S. 158

* Pro Runde 1 Angriff (bei 2 einfachen Handlungen 1 "Luftschuss")

* Durschlagskraft (DK): negativ == mehr Panzerung beim Ziel, positiv == weniger

* Panzerung: Panzerungswert wird zum Schadenswiderstandsmonitor hinzugefügt, S.171

## Kampfrunde

* 1 Kampfrunde = 3 Sekunden

### 1. Initiative

* Höchster Wert fängt zuerst an
* Gleichstand: Vergleich von ERIM (Edge, Reaktion, Intuition, Münzwurf)

### 2. Handlungsphase

Werden nach vorher ermittelter Reihenfolge durchgeführt

* müssen vorher angesagt werden
* zwei Einfache Handlungen oder eine Komplexe Handlung
* eine Freie Handlung möglich

### 3. Initiative reduzieren

* Nach jedem Durchgang -10, bis < 10
* Alle unter 10: neue Kampfrunde

## Kampfsequenz

### Ansage

* Angreifer seinen Angriff
* Verteidiger seine Verteidigung

### Angriff

* Angreifer: Kampffertigkeit + Attribut +- Modifikatoren [Limit]
* Modifikatoren: S. 175

### Verteidigung

* Verteidiger: Reaktion + Intuition +- Modifikatoren

#### 1) Vergleichsprobe

  * Angreifer mehr Erfolge? Treffer!
  * Gleichstand? Streifschuss - kein Schaden, aber Kontaktwirkung (bspw. Gift, Strom etc.)
  * Verteidiger mehr Erfolge? Daneben.
  * **Nettoerfolge** merken: Erfolge Angreifer die der Angreifer mehr hat

#### 2) Schaden

* Modifizierter Schadenscode berechnen: Nettoerfolge + Schadenscode
* Modifzierter Panzerungswert: Panzerung - Durchschlagskraft

* Mod. Schadenscode >= mod. Panzerungswert: körperlicher Schaden, ansonsten geistig

* Verteidiger: Konstitution + mod. Panzerungswert W6 würfeln
  * Jeder Erfolg = -1 mod. Schadenscode
  * Dadurch mod. Schadenscode < 0? Panzerung schluckt Angriff

#### 3) Wirkung

* Verbleibenden Schaden auf Zustandsmonitor des Ziels eintragen
* Pro 3 Kästchen -1 W6
* Hier auch Nebenwirkung Schadensarten bestimmen

# Ausrüstung

S. 418 ff

## Verfügbarkeit

* kein V/E: legal, aber nicht unbedingt einfach zu bekommen
* **E**: eingeschränkt verfügbar, benötigt Lizenz
* **V**: verboten

* Verfügbarkeitsprobe: vergl. Probe auf Verhandlung + Charisma [Sozial] gegen Verfügbarkeitswert
* für 25% mehr Kaufpreis je 1 zusätzlicher Würfel, max 12
* Patzer sorgt für unerwünschte Aufmerksamkeit

* Kauf durch Connection möglich: S. 420

* Lieferzeiten: S. 420

## Verstecken

S. 421

# Spielleiter

## Barrieren

S. 196

* Zustandsmonitor = Strukturstufe * Quadratmeter

* Falls Ziel komplett verdeckt: -6 W6 für Angreifer (Blindes Feuern)
* Angriffe müssen Barriere durchschlagen. Struktur + Panzerung für Schadenswiderstand. Übriger Schaden weiter an Ziel, das diesem normal widerstehen kann.

* Zerstören: Erfolgsprobe gegen Barriere

* Durchschießen: S. 197, Penetrierende Waffen
* Barriere schlockt Schaden: 1 Kugel = 1 Schaden, 3 Kugeln = 2 Schaden, 6 Kugeln = 3 Schaden, 10 Kugeln = 4 Schaden
* Nur falls Schaden > Panzerungswert

### Sprengstoffe

* Fertigkeit: S. 145
* Anwendung, Produkte: 2. 438

* Radiale Ausbreitung, -2 pro Meter
* Gerichtete Ausbreitung, -1 pro Meter
* Am Ziel befestigt: halbiert Panzerung, ansonsten DK -2

* Probe: Sprengstoffe + Logik [Geistig], jeder Erfolg = +1 Sprengstoffstufe
* Schadenscode: Sprengstoffstufe (+ Erfolge Probe) * Quadratwurzel Kilogramm


## Bösewichte

S. 381 ff

## Belohnung

S. 376 / S.489

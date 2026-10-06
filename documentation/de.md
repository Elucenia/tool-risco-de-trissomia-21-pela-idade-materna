<!-- ELUCENIA technical documentation · risco-de-trissomia-21-pela-idade-materna · de · no clinical/professional/rights approval -->

# Down-Syndrom-Risiko nach mütterlichem Alter

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/risco-de-trissomia-21-pela-idade-materna)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Mütterliches Alter am errechneten Geburtstermin

`idade`

Jahre · Bereich: 15–50

## Fassung der Methode

Morris–Mutton–Alberman 2002: England/Wales-Lebendgeburtsmodell 1989–1998; kein universelles Gestationsrisiko

## Dokumentierte Formel

Morris, Mutton, Alberman (2002): Risiko = 1 ÷ \[1 + e(7,330 − 4,211 ÷ (1 + e−0,282 × (Alter − 37,23)))\]

Logistisches Modell des nationalen Down-Registers England/Wales (1989 bis 1998), für fehlendes Screening und Schwangerschaftsabbruch korrigiert.

## Grenzen und Population

Diese Formel beschreibt die Prävalenz des Down-Syndroms bei Lebendgeborenen nach mütterlichem Alter anhand von Daten aus England und Wales 1989–1998 unter Schätzung fehlenden Screenings und selektiver Schwangerschaftsunterbrechung. Sie liefert kein Risiko für jedes Gestationsalter und ersetzt weder Screening noch individuelle Diagnose.

## Referenzen

- [Morris JK, Mutton DE, Alberman E. Revised estimates of the maternal age specific live birth prevalence of Down's syndrome. J Med Screen, 2002.](https://doi.org/10.1136/jms.9.1.2)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Basisrisiko (a priori) im Alter von 35 Jahren: 0,28%

| Ergebnisdetails | |
| --- | --- |
| Wahrscheinlichkeit | 0,283% |

Dies ist das Ausgangsrisiko: Das kombinierte Screening oder der NIPT verändern es nach oben oder unten.


### 2

Basisrisiko (a priori) im Alter von 40 Jahren: 1,16%

| Ergebnisdetails | |
| --- | --- |
| Wahrscheinlichkeit | 1,164% |

Dies ist das Ausgangsrisiko: Das kombinierte Screening oder der NIPT verändern es nach oben oder unten.


### 3

Basisrisiko (a priori) im Alter von 25 Jahren: 0,07%

| Ergebnisdetails | |
| --- | --- |
| Wahrscheinlichkeit | 0,075% |

Dies ist das Ausgangsrisiko: Das kombinierte Screening oder der NIPT verändern es nach oben oder unten.


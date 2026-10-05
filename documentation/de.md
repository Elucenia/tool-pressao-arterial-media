<!-- ELUCENIA technical documentation · pressao-arterial-media · de · no clinical/professional/rights approval -->

# Mittlerer arterieller Druck und Pulsdruck

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/pressao-arterial-media)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Systolischer Blutdruck

`pas`

mmHg · Bereich: 50–300

### Diastolischer Druck

`pad`

mmHg · Bereich: 20–200

## Fassung der Methode

MAP=(systolisch+2 diastolisch)/3; Pulsdruck systolisch−diastolisch; Näherung bei Erwachsenen mit üblichem Rhythmus; brasilianische Leitlinie 2020

## Dokumentierte Formel

MAP = diastolischer Blutdruck + (systolischer Blutdruck − diastolischer Blutdruck) ÷ 3

Pulsdruck = systolischer Blutdruck − diastolischer Blutdruck

## Grenzen und Population

Die Näherung aus diastolischem Druck plus einem Drittel des Pulsdrucks setzt laut AHA-Stellungnahme 2019 eine normale Herzfrequenz voraus; sie ist keine direkte Integration der Druckkurve. Verwenden Sie systolische und diastolische Werte in mmHg, mit geeigneter Technik und geeignetem Gerät gemessen, und dokumentieren Sie die Messbedingungen. Systolisch minus diastolisch ist der Pulsdruck, nicht die Pulsfrequenz. Das Ergebnis allein stellt weder eine Hypertoniediagnose noch einen universellen Zielwert für kritisch kranke Patienten dar.

## Referenzen

- [Barroso WKS et al. Diretrizes Brasileiras de Hipertensão Arterial – 2020. Arq Bras Cardiol, 2021.](https://doi.org/10.36660/abc.20201238)

- [AHA scientific statement2019,Measurement of Blood Pressure in Humans](https://pmc.ncbi.nlm.nih.gov/articles/PMC11409525/)

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

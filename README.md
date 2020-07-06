---
title: Studienleistung 4
author: Martin Kocur
documentclass: scrartcl
classoption:
  - a4paper
header-includes: |
    \usepackage{german}
	\usepackage{xcolor} 
    \usepackage[a4paper,left=2.5cm, right=2.5cm,top=2.5cm, bottom=3cm]{geometry}
    \usepackage{fancyhdr}
    \pagestyle{fancy}
    \fancyhf{}
    \rhead{Webtechnologien}
    \lhead{SL4}
    \fancypagestyle{plain}{
      \fancyhf{}
      \rhead{Webtechnologien}
      \lhead{SL4}}


---



## Aufgabe 1: Normalisierung

Erstellen Sie eine Datenbank, die folgende Tabelle abbildet:

_DHMaster (LectureTitle, LectureCredits, LecturerFirstName, LecturerLastName, ModuleID, ModuleName)_

Überführen Sie die Tabelle in die dritte Normalform, indem Sie passende Relationen mit Primär-und Fremdschlüsseln erstellen. Sie können  [\textcolor{blue}{DB Browser für SQLite}](https://sqlitebrowser.org/) verwenden, um die Datenbank zu generieren. 



## Aufgabe 2: SQL-Abfragen

Verwenden Sie die zur Verfügung gestellte Datenbank [\textcolor{blue}{chinook}](https://www.sqlitetutorial.net/sqlite-sample-database/) um mit Hilfe von SQL-Queries die im Folgenden vorgegebenen Daten zu erhalten. Die Datenbank kann über GRIPS heruntergeladen werden. Alle Aufgaben dürfen nur mit **einer** SQL-Abfrage gelöst werden. Mehrere SQL-Abfragen hintereinander führen zu 0 Punkten bei der jeweiligen Teilaufgabe. Kennzeichnen Sie mit Hilfe von Kommentaren, welche Query welcher Teilaufgabe zuzuordnen ist.

- Geben Sie Namen aller in der Datenbank aufgeführten Künstler (artists) aus.
- Geben Sie alle Alben von AC/DC aus.
- Geben Sie alle Kunden aus, die in den USA wohnhaft sind.
- Geben Sie den Namen und die Gesamtsumme alle Rechungen von Leonie Köhler aus.
- Geben Sie die Namen aller Tracks aus, die in den Alben von Iron Maiden enthalten sind.
- Geben Sie die Anzahl aller Tracks von Aerosmith, in der Datenbank gespeichert sind.
- Geben Sie alle Tracks und die dazugehörigen Namen der Komponisten der Playlist "Brazilian Music" aus.
- Geben Sie alle Tracks aus, die dem Genre "Reggae" zugeordnet sind.

------

*Abgabekriterien:*

Laden Sie Ihre Lösung bis spätestens 19.7.2020 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch.  Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und verwenden Sie geeignete Formate:

- Aufgabe 1: Ihre Datenbank als .sqlite - Datei
- Aufgabe 2:  Ihre SQL-Queries in einer .sql - Datei

Der Name der Zip-Datei ergibt sich aus dem Präfix „SL_WT_SS20“, der Nr. der Studienleistung, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **SL_WT_SS20_4_Max_Mustermann.zip**


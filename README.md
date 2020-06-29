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

Überführen Sie die Tabelle in die dritte Normalform, indem Sie passende Relationen erstellen. Sie können  [\textcolor{blue}{DB Browser für SQLite}](https://sqlitebrowser.org/) verwenden, um die Datenbank zu erstellen.



## Aufgabe 2: SQL-Abfragen

Verwenden Sie die zur Verfügung gestellte, auf [\textcolor{blue}{IMDb}](https://www.imdb.com/) - basierende Datenbank _movies_, um mit Hilfe von SQL-Queries die im Folgenden vorgegebenen Daten zu erhalten. Alle Aufgaben dürfen nur mit **einer** SQL-Abfrage gelöst werden. Mehrere SQL-Abfragen hintereinander führen zu 0 Punkten bei der jeweiligen Teilaufgabe. Kennzeichnen Sie mit Hilfe von Kommentaren, welche Query welcher Teilaufgabe zuzuordnen ist.

- Geben Sie Namen und Geburtsjahr aller in der movies-Datenbank aufgeführten Personen aus.
- Geben Sie alle Filme aus, die zwischen 1990 und 2000 ausgestrahlt worden sind.
- Geben Sie alle Filme aus, in denen Sylvester Stallone mitspielt.
- Geben Sie die Anzahl aller Filme aus, in denen Sylvester Stallone zwischen 1990 und 2000 mitgespielt hat.
- Geben Sie die Namen aller "Stars" aus, die in dem Film "Interstellar" mitgewirkt haben.
- Geben Sie die Anzahl aller Filme aus, die in der Datenbank gespeichert sind.
- Geben Sie alle Filme (Titel, Jahr, Schauspieler) zwischen 1995 und 2010 aus, in denen entweder Vin Diesel oder Brad Pitt oder beide mitspielen.
- Geben Sie den Titel und die Bewertung der Filme aus, die mit mehr als 100.000 Bewertungen besser als 9.0 bewertet worden sind.
- Geben Sie den Titel, das Jahr und die Bewertung der Filme von Matthew McConaughey aus, die besser als 8.5 bewertet worden sind. Basierend auf der Bewertung, sollen die Filme in aufsteigender Reihenfolge dargestellt werden.
- Geben Sie die durchschnittliche Bewertung der Filme mit Leonardo DiCaprio aus.



------

*Abgabekriterien:*

Laden Sie Ihre Lösung bis spätestens 19.7.2020 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch.  Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und verwenden Sie geeignete Formate:

- Aufgabe 1: Ihre Datenbank als .sqlite - Datei
- Aufgabe 2:  Ihre SQL-Queries in einer .sql - Datei

Der Name der Zip-Datei ergibt sich aus dem Präfix „SL_WT_SS20“, der Nr. der Studienleistung, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **SL_WT_SS20_4_Max_Mustermann.zip**


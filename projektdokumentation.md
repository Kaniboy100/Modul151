# Projekt-Dokumentation

Elangeswaran

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | Ich habe mir erste Gedanken zum Projekt gemacht              |
|       | 0.0.2   |                                                              |
|       | 0.0.3   |                                                              |
|       | 0.0.4   |                                                              |
|       | 0.0.5   |                                                              |
|       | 0.0.6   |                                                              |
|       | 1.0.0   |                                                              |

# 0 Ihr Projekt

Es ist ein Glücksradspiel als Webapplikation. Hierbei kann der Spieler einen Einsatz an Geld hineintun und dann an einem Glücksrad drehen. Diese hat zwei Felder: ``Geldbetrag x`` und ``Bankrott``. 

Falls es auf ``Geldbetrag x`` landet darf der Spieler einen Konsonanten raten oder ein Vokal Kaufen, um das Ratewort oder Rätsel-Phrase herauszufinden. Bei erfolg, erhält der Spieler den eingesetzten Betrag, je nach wie oft dieser vorkommt, gutgeschrieben. Falls man nichts erratet verliert man einen Lebenspunkt, welcher am Anfang bei 3 liegt. 

Falls es auf ``Bankrott`` landet verliert der Spieler all sein Guthaben auf dem Konto und das Spiel wird neu gestartet. 

Man kann jedoch auch bei jedem seiner Züge versuchen das Wort zu erraten, jedoch verliert man auch hier einen Lebenspunkt, falls man es falsch errät. Sobald alle Konsonanten erraten worden sind, wird der Spieler gezwungen Vokale zu kaufen oder das Rätselwort herauszufinden. 

Als Motivation gibt es eine Highscore Liste mit den grössten Gewinnen.

# 1 Analyse

* Tier 1 (Presentation): Anzeigen des Highscores, Entgegennahme von Buchstaben
* Tier 2 (Webserver): Organisiert das Speichern von Gewinne
* Tier 3 (Application Server): Verbindung zur Datenbank, Prüfung auf fehleingaben
* Tier 4 (Dataserver): Gewinne

# 2 Technologie

* Tier 1 (Presentation): HTML/CSS
* Tier 2 (Webserver): HTML/CSS, JavaScript
* Tier 3 (Application Server): JavaScript
* Tier 4 (Dataserver): mySQL

# 3 Datenbank

Über eine Applikation der Datenbank

# 4.1 User Stories


| US-№ | Verbindlichkeit | Typ          | Beschreibung                       |
| ---- | --------------- | ----         | ---------------------------------- |
| 1    | Muss            | Funktional   | Als Spieler möchte ich am Glücksrad drehen können, damit ich spielen kann                   |
| 2    | Muss            | Funktional   | Als Spieler möchte ich Konsonanten auswählen können, damit ich die Lösung herausfinden kann |
| 3    | Muss            | Funktional   | Als Spieler möchte ich Wörter eingeben können, damit ich das Rätselwort herausfinden kann   |



# 4.2 Testfälle

| TC-№ | Vorbereitung         | Eingabe             | Erwartete Ausgabe                 |
| ---- | ------------         | -------             | -----------------                 |
| 1.1  | Programm läuft       | Drehen Knopf        | Glücksradausgabe                  |
| 2.1  | Programm läuft       | Konsonant           | Passt oder nicht                  |
| 3.1  | Programm läuft       | Wärter              | Passt oder nicht                  |


# 5 Prototyp

✍️ Erstellen Sie Prototypen für das GUI (Admin-Interface und Quiz-Seite).

# 6 Implementation

✍️ Halten Sie fest, wann Sie welche User Story bearbeitet haben

| User Story | Datum | Beschreibung |
| ---------- | ----- | ------------ |
| ...        |       |              |

# 7 Projektdokumentation

| US-№ | Erledigt? | Entsprechende Code-Dateien oder Erklärung |
| ---- | --------- | ----------------------------------------- |
| 1    | ja / nein |                                           |
| ...  |           |                                           |

# 8 Testprotokoll

✍️ Fügen Sie hier den Link zu dem Video ein, welches den Testdurchlauf dokumentiert.

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

# 9 `README.md`

✍️ Beschreiben Sie ausführlich in einer README.md, wie Ihre Applikation gestartet und ausgeführt wird. Legen Sie eine geeignete Möglichkeit (Skript, Export, …) bei, Ihre Datenbank wiederherzustellen.

# 10 Allgemeines

- [ ] Ich habe die Rechtschreibung überprüft
- [ ] Ich habe überprüft, dass die Nummerierung von Testfällen und User Stories übereinstimmen
- [ ] Ich habe alle mit ✍️ markierten Teile ersetzt

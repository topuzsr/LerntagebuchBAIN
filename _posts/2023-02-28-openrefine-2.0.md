---
title: "Lerneinheit 3: Metadaten modellieren und Schnittstellen nutzen 1/2 (OpenRefine)"
date: 2023-02-28
---

# Intro
Später Einstieg : Dozent hat sich bei den Uhrzeiten geiirt

Wir beginnen heute schon mit OpenRefine

Weiter warten wegen der Aufzeichnung der Vorlesung

Ausgefallene Lehrveranstaltung nachholen: 05. Mai? Diskussion unter den Studierenden und dem Dozent welcher Tag am Besten geht
Dozent wird sich jetzt mit den Kolleggen / Studienleitung in Kontakt setzen

# Literaturempfehlung

Erster Literaturtip: Library Carpentry
Speziell für Menschen die im Bibliothekswesen, wie sie möglichst schnellst IT-Fähigkeiten anzugeignen durch Kurse
Vorteil: Kurse sind PeerReviewed (auch vom Dozent zu empfehlen)
Keine Vorkenntnisse aus dem IT-Bereich nötig
Meinung Dozent: Lehreinheiten sind interessant
Nicht so wichtig für den Kurs, aber wer sich für solche Communities interessiert, dann sollte man diese mal anschauen

Lesson Index:
Einige für den Kurs interessant wie zum Beispiel: Fetching and Parsing Data from Web with OpenRefine
--> wenn man die heutige Lektion über OpenRefine vertiefen will

Neues Buch das in Entstehung ist: Handbuch IT in Bibliotheken
Leute vor Ort treffen und in zwei drei Tagen anfangen und dann online gemeinsam mit mehreren Personen ein Buch schreiben resp. weitere Enträge
--> Booksprint

# Fragen aus der Runde
Frage 1: Ist dem Dozent nicht bekannt, dass er was zu Archiv kennt
Weitere Fragen aus der Runde? Stille 'crickets'

# Timeout in Codespaces
Dozent informiert uns über den Timeout in Codespaces --> erhöhen
- Settings - Codespaces

Geändert auf 240 Minuten auf Empfehlung des Dozenten
- Codespace nach jeder Lerneinheit noch löschen
- Codespaces aufrufen (Settings) ... Delete Button

....Kurze Pause (9min)....
Persönliche Notiz:
Gefährlich, aber die Notizen direkt ins GitHub reinschreiben während der Vorlesung, mal schauen wie das funktioniert und diese Beiträge dann nach den Lerneinheiten korrigieren und auf Wunsch formatieren.
Wichtig ist es in gewissen Momenten diese Beiträge zwischenzeitlich zu speichern!

# Lerneinheit (Start OpenRefine)

## Einführung (kurze) in OpenRefine
Idee von OpenRefine: Rohdaten die zu einem Diamanten geschliffen werden
Claim: Powerful free....
Mächtig frei und OpenResource mit "schmutzigen" Daten = gut geeignet um Daten zu bereinigen und von einem Format in ein anderes Format zu konfigurieren

Reconicliation = Versöhnung; ein Datensatz mit einem anderen Datensatz verbinden = matchen (Gemeinsamkeiten über eine ID feststellen) und Daten zusammenführen (Verknüpfungen herstellne)

Hauptfunktion von OpenRefine: Facettieren von Daten
Von einer klassischen Tabellenfunktion wie Excel plus Suchmaschine (Webseite wie Amazon) wie man mit Filter sich durch Daten hindurcharbeiten kann

Clustering = Algorithmen anwenden wie z.B. Key Collission, z.B. unterschiedliche Schreibweisen von Namen herausfinden

Infinite undo/redo = Protokollierung und Einstieg in die Automatisierung; mit Daten die Historie erarbeitet kann man diese auch auf einen anderen Datensatz zu übertragen (wie zum Beispiel wenn man die neue Version einer Datenlieferung bekommt und vom Aufbau alles gleich bleibt, kann man das anwenden)

Privacy = Daten die man mit OpenRefine bearbeitet bleiben privat auf der lokalen Obefläche (kann man lokal installieren); JavaSoftware, wird bedent über einen Webbrowser, aber man hat eigentlich keine Internetverbindung und man sendet keine Daten

Das wären die Hauptfunktionen

## Praxisteil und Übungen in OpenRefine
Um diese auszuprobieren: Link aufrufen GitHub https://github.com/felixlohmeier/bain-lc-openrefine
Aufruren vom Container; Create Codespace on Main

Persönliche Arbeitsumgebung; Noch nicht eingerichtet (selber machen) OpenRefine starten (noch nicht im Skript und im ReadMe: kommt später vom Dozent)
Start von OpenRefine (Befehl): openrefine-3.6.2/refine

Was auch noch nicht automatisch funktioniert ist die Porteingabe (Dozent)

Neben Terminal hat es Ports (kenn mich nicht so sehr mit Ports aus, war mal Thema in früheren Vorlesungen; lokaler Rechner http://127.0.0.1:3333/)
für OpenRefine immer 3333 = das in Port eingebene + Return + Weltkugel anklicken und Fenster geöffnet (sieht aus wie eine Webseite ist aber nur für mich zugreifbar)

## Wieder ins Skript: Erzählt mehr über OpenRefine
Claim: Daten von anderen bekommt, statistisch überblicken kann (mit OpenRefine mit Filter analysieren)
Konvertieren: ein Format in ein anderes Format
Lokale Installation - Bedienung über Webbrowser

Nutzerbefragung OpenRefine:
Wichtig für Dozent bei einer OpenSource-Software - hängt sehr an Institutionen und Personen ab, man kann nicht durch Verkaufsprozesse erkennen wie gut diese laufen. Nicht einfach zu beurteilen und im Kurs haben wir das Ziel solche Softwares zu evaluieren.
Wenn man eine OpenSource-Software als Institution , lohnen 

OpenRefine = Breite Communities
- Bibliotheken haben den grössten Ausschlag
- Breite diverse Community, breite Community = höhere Stabilität und Input aus anderen Fachbereichen
-  Unterschiedliche Skills aus diversen Bereichen

Unterstützte Formate von OpenRefi

Einsatzmöglichkeiten
- In der Praxis für die wertvollen Daten (eher subjektiv) verwendet 

Historie:

(Pause = 20min)

## Übung LibraryCarpentry Lesson
URL aufrufen

Clipboard: Wenn ich einen Teilausschnitt aus einer Excel-Tabelle auswähle und auschneide, dann kann ich das auch in die Zwischenablage und dies funktioniert auch in Clipboard (Teilauszüge)

Database und Google Data: Datenbanken und Google Sheets (privat und öffentlich) aufrufbar

Eigentlich geht es hier mehr die Oberfläche von OpenRefine kennenzulernen und die Funktionen = Startbildschirm

Zurück zum Skript:
Übungen werden jetzt teils gemacht, er empfiehlt die weiteren in der privaten Zeit zu üben, aber ist nicht obligatorisch laut Dozent

Zu einem späteren Zeitpunkt wird OpenRefine aufgegriffe und MARCXML zu üben

Jetzt:
- Materialien aus der Library Carpentry Lesson
- (KJetzt mitmachen und nachher schreiben)



# Lerneinheit 2.0: OpenRefine

(3000 - 4000 Zeichen)


# Projekt-Dokumentation


| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 03.05.2024      | 0.0.1     | Kickoff-Meeting und Einführung in das Projekt. Ideen für Spielmenü gesammelt.|
| 17.05.2024      | 0.0.2     | Entscheidung für die Entwicklung von Tic Tac Toe und Hangman in C#. Beginn der Programmierung von Tic Tac Toe. Erste Tests der Benutzereingabe.                |
| 24.05.2024      | 0.0.3     | Entscheidung für die Entwicklung von Tic Tac Toe und Hangman in C#. Beginn der Programmierung von Tic Tac Toe. Erste Tests der Benutzereingabe.                |
| 07.06.2024      | 0.0.4     | Entscheidung für die Entwicklung von Tic Tac Toe und Hangman in C#. Beginn der Programmierung von Tic Tac Toe. Erste Tests der Benutzereingabe.                |
| 14.06.2024      | 0.0.5     | Entscheidung für die Entwicklung von Tic Tac Toe und Hangman in C#. Beginn der Programmierung von Tic Tac Toe. Erste Tests der Benutzereingabe.                |

## 1 Informieren

### 1.1 Ihr Projekt

Wir entwickeln eine interaktive Webseite, die ein spannendes Quiz-Spiel durch ein robustes Backend ermöglicht.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
|  1   |  Muss  | Funktional | Als ein User möchte ich, dass die Quiz Game Website in der Lage ist, Fragen anzuzeigen.   |
|  2   |  Muss  | Funktional | Als ein User möchte ich die Möglichkeit haben, zwischen vier verschiedenen Blöcken auszuwählen.   |
|  3   |  Muss  | Qualitativ | Als ein User möchte ich, dass der richtige Block grün markiert wird, wenn ich darauf klicke.  |
|  4   |  Muss  | Qualitativ | Als ein User möchte ich, dass ein falscher Block rot markiert wird, wenn ich darauf klicke.   |
|  5   |  Muss  | Qualitativ | Als ein User möchte ich, dass oben rechts auf der Website die Anzahl der richtigen Antworten angezeigt wird.   |
|  6   |  Muss  | Qualitativ | Als ein User möchte ich, dass das Projekt über VS-Code programmiert wird.  |
|  7   |  Muss  | Qualitativ | Als ein User möchte ich, dass das Projekt mit dem IPERKA-Verfahren durchgeführt wird.   |
|  8   |  Muss  | Qualitativ | Als ein User möchte ich, dass das Grundgerüst der Quiz Game Website mit Hilfe von HTML und der funktionale Teil mit JavaScript erstellt wird.  |
|  9   |  Muss  | Qualitativ | Als ein User möchte ich, dass das Design der Quiz Game Website mit Hilfe von CSS erstellt wird.   |
|  10  |  Muss  | Funktional | Als ein User möchte ich, dass das Backend das gesamte Programm unterstützt. |


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |              |         |                   |
| ...  |              |         |                   |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

✍️ Hier können Sie PAPs, Use Case- und Gantt-Diagramme oder Ähnliches einfügen.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |           |              |               |
| ...  |       |           |              |               |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

Für unseren Lernauftrag 1304 haben wir MongoDB als Datenbank ausgewählt und die Mongoose-Bibliothek zur Modellierung von Objektdaten verwendet. Verschiedene Beziehungen wurden damit verwaltet. Um sicherzustellen, dass Anmeldedaten nicht in einem öffentlich zugänglichen Online-Repository erscheinen, haben wir .env-Dateien genutzt.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.


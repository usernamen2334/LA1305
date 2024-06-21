# Projekt-Dokumentation


| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 03.05.2024  | 0.0.1 | Kickoff-Meeting und Einführung in das Projekt. Ideen für Spielmenü gesammelt.|
| 17.05.2024  | 0.0.2 | Entscheidung für die Entwicklung von Tic Tac Toe und Hangman in C#. Beginn der Programmierung von Tic Tac Toe. Erste Tests der Benutzereingabe.  |
| 24.05.2024  | 0.0.3 | Entscheidung für die Entwicklung von Tic Tac Toe und Hangman in C#. Beginn der Programmierung von Tic Tac Toe. Erste Tests der Benutzereingabe.  |
| 07.06.2024  | 0.0.4 | Entscheidung für die Entwicklung von Tic Tac Toe und Hangman in C#. Beginn der Programmierung von Tic Tac Toe. Erste Tests der Benutzereingabe.  |
| 14.06.2024  | 1.0.0 | Entscheidung für die Entwicklung von Tic Tac Toe und Hangman in C#. Beginn der Programmierung von Tic Tac Toe. Erste Tests der Benutzereingabe.  |

## 1 Informieren

### 1.1 Ihr Projekt

Choices of Life - Ein Spiel, bei dem man Lebensentscheidungen trifft und die Konsequenzen dieser Entscheidungen erlebt. Es wurde in C# unter Verwendung von objektorientierter Programmierung (OOP) entwickelt.


### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1 | Muss | Funktional | Als ein User möchte ich, dass ich spannende Fragen gestellt bekomme.|
| 2 | Muss | Funktional | Als ein User möchte ich, dass mir bei Entscheidungspunkten jeweils drei verschiedene Antwortmöglichkeiten zur Verfügung stehen. |
| 3 | Muss | Funktional | Als ein User möchte ich, dass mein Gesundheitszustand im Spiel durch eine Lebensanzeige dargestellt wird. |
| 4 | Muss | Funktional | Als ein User möchte ich, dass Entscheidungen direkte Auswirkungen auf meine Lebenspunkte haben. |
| 5 | Muss | Qualitativ | Als ein User möchte ich, dass der Lebensanzeiger im Spiel visuelles Feedback über meinen aktuellen Gesundheitszustand gibt, indem er seine Farbe basierend auf der verbleibenden Anzahl von Lebenspunkten ändert.|
| 6 | Muss | Qualitativ | Als ein User möchte ich meinen aktuellen Standort sehen. |
| 7 | Muss | Qualitativ | Als ein User möchte ich, dass mein aktueller Standort dsich dynamisch anpasst und aktualisiert, sobald ich im Spiel Entscheidungen treffe. |
| 8 | Muss | Qualitativ | Als ein User möchte ich, Im Spiel endet das Spielerlebnis, sobald der Lebenspunktestand des Spielers auf null fällt. |


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1 |              |   -      |                   |
| 2.1 |              |         |                   |
| 3.1 |              |         |                   |
| 4.1 |              |         |                   |
| 1.1 |              |         |                   |
| 1.1 |              |         |                   |
| 1.1 |              |         |                   |


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


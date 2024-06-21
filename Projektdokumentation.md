# Projekt-Dokumentation
Atputharasa, Angelov, Jashari, Marku

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 03.05.2024  | 0.0.1 | Kickoff-Meeting und Einführung in das Projekt. Ideen für das Spiel gesammelt.|
| 17.05.2024  | 0.0.2 | Entscheidung für die Entwicklung von Choices of Life in C#. Beginn der Programmierung. Erste Tests der Benutzeroberfläche.  |
| 24.05.2024  | 0.0.3 | Weiterentwicklung von Choices of Life. Fortsetzung der Programmierung und Durchführung weiterer Tests.  |
| 07.06.2024  | 0.0.4 | Fertigstellung der finalen Version von Choices of Life. |
| 14.06.2024  | 1.0.0 | Abschluss der Entwicklung, finale Tests durchgeführt. Projektdokumentation finalisiert.  |

## 1 Informieren

### 1.1 Ihr Projekt

Choices of Life - Ein Spiel, bei dem man Lebensentscheidungen trifft und die Konsequenzen dieser Entscheidungen erlebt. Es wurde in C# unter Verwendung von objektorientierter Programmierung (OOP) entwickelt.


### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1 | Muss | Funktional | Als ein User möchte ich, dass ich spannende Inputs zu meiner Situation erhallten. |
| 2 | Muss | Funktional | Als ein User möchte ich, dass mir bei Entscheidungspunkten jeweils drei verschiedene Antwortmöglichkeiten zur Verfügung stehen. |
| 3 | Muss | Funktional | Als ein User möchte ich, dass mein Gesundheitszustand im Spiel durch eine Lebensanzeige dargestellt wird. |
| 4 | Muss | Funktional | Als ein User möchte ich, dass Entscheidungen direkte Auswirkungen auf meine Lebenspunkte haben. |
| 5 | Muss | Qualitativ | Als ein User möchte ich, dass der Lebensanzeiger im Spiel visuelles Feedback über meinen aktuellen Gesundheitszustand gibt, indem er seine Farbe basierend auf der verbleibenden Anzahl von Lebenspunkten ändert. |
| 6 | Muss | Qualitativ | Als ein User möchte ich meinen aktuellen Standort sehen. |
| 7 | Muss | Qualitativ | Als ein User möchte ich, dass mein aktueller Standort sich dynamisch anpasst und aktualisiert, sobald ich im Spiel Entscheidungen treffe. |
| 8 | Muss | Qualitativ | Als ein User möchte ich, im Spiel endet das Spielerlebnis, sobald der Lebenspunktestand des Spielers auf null fällt. |


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1 | Im  Quiz-spiel |   -    |  "Du findest eine geheime Kammer mit Hinweisen auf den Verbleib des Gegenstands."|
| 2.1 | Im  Quiz-spiel Situation wird beschrieben. |  -   | "[1] Du betrittst die geheime Tür und erkundest das Innere. [2] Du ignorierst die Tür und setzt deine Suche draussen fort. [3] Du markierst die Tür und informierst deine Verbündeten."                 |
| 3.1 | Im  Quiz-spiel Situation wird beschrieben. |  -   |       Lebensanzeiger          |
| 4.1 | Im  Quiz-spiel Situation wird beschrieben. |  "1"   |    Lebensanzeiger -1               |
| 5.1 | Im  Quiz-spiel Situation wird beschrieben. |  "1"   |    Lebensanzeiger wird rot.        |
| 6.1 | Im  Quiz-spiel |  -       |     "Hamburg"              | 
| 7.1 | Im  Quiz-spiel Situation wird beschrieben. |  "1"   | "München"|
| 8.1 | Im  Quiz-spiel Situation wird beschrieben. |  "1"   | "Du hast das Spiel abgeschlossen, aber ohne Erfolg." |



### 1.4 Diagramme

✍️ Hier können Sie PAPs, Use Case- und Gantt-Diagramme oder Ähnliches einfügen.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 14.06.2024 |  Jashari, Marku         |  Entwicklung von spannenden Inputs für den User basierend auf seiner Situation.                                                  |  90' |
| 2.A  | 14.06.2024 |  Atputharasa, Angelov   |  Bereitstellung von drei verschiedenen Antwortmöglichkeiten bei Entscheidungspunkten.                                            |  90' |
| 3.A  | 14.06.2024 |  Jashari, Atputharasa   |  Darstellung des Gesundheitszustands des Spielers durch eine Lebensanzeige.                                                      |  90' |
| 4.A  | 14.06.2024 |  Marku, Angelov         |  Entscheidungen sollen direkte Auswirkungen auf die Lebenspunkte haben.                                                          |  90' |
| 5.A  | 14.06.2024 |  Atputharasa, Marku     |  Lebensanzeige gibt visuelles Feedback über den Gesundheitszustand, indem sie ihre Farbe basierend auf den Lebenspunkten ändert. |  90' |
| 6.A  | 14.06.2024 |  Jashari, Angelov       |  Anzeige des aktuellen Standorts des Spielers.                                                                                   |  90' |
| 7.A  | 14.06.2024 |  Jashari, Marku         |  Dynamische Anpassung und Aktualisierung des Standorts basierend auf Entscheidungen des Spielers.                                |  90' |
| 8.A  | 14.06.2024 |  Atputharasa, Angelov   |  Das Spiel endet, wenn der Lebenspunktestand des Spielers auf null fällt.                                                        |  90' |

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


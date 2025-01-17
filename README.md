# Projekt-Dokumentation

Gruppe:

- Cedric Tuma
- Liam Koch
- Robin Sacher
- Damian Müller
- Nikola Manojlovic

| Datum      | Version | Zusammenfassung                                                                                                                                 |
| ---------- | ------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| 10.01.2025 | 0.0.1   | Heute haben wir eine unsere Projektidee erarbeitet und den Projektantrag ausgefüllt, sowie abgeben und mit der Projektdokumentation angefangen. |
| 17.01.2025 | 0.2.0   |                                                                                                                                                 |
| 24.01.2025 | 0.3.0   |                                                                                                                                                 |
| 31.01.2025 | 0.4.0   |                                                                                                                                                 |
| 21.02.2025 | 0.5.0   |                                                                                                                                                 |
| 28.02.2025 | 0.6.0   |                                                                                                                                                 |
| 07.03.2025 | 1.0.0   |                                                                                                                                                 |

## 1 Informieren

### 1.1 Ihr Projekt

Wir entwickeln ein Mehrspieler-UNO-Spiel, das es Spielern ermöglicht, sich in einer Lobby zu verbinden und eine Runde UNO nach den klassischen Regeln zu spielen.

In diesem Projekt setzen wir die klassische UNO-Spielmechanik in einer Webanwendung um, bei der mehrere Spieler über eine Online-Verbindung in Echtzeit interagieren können. Unser Ziel ist es, eine benutzerfreundliche Plattform zu schaffen, die Echtzeit-Updates und eine korrekte Regelumsetzung ermöglicht. Dabei lernen wir, ein Backend mit sauberer Architektur zu entwerfen, REST-APIs zu entwickeln, MongoDB für Datenverwaltung einzusetzen und Frontend und Backend effizient zu verknüpfen. Zudem möchten wir unser Verständnis von Programmierprinzipien wie Modularität, Validierung und Fehlerbehandlung vertiefen.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ           | Beschreibung                                                                                                                                 |
| ---- | --------------- | ------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Muss            | Randbedingung | Als ein Entwickler möchte ich, dass mindestens .Net Version 7.0 oder höher verewendet wird, damit eine aktuelle Version vewendet wird.       |
| 2    | Muss            | Randbedingung | Als ein Enwickler möchte ich, dass das Frontend mit HTML, CSS und Java Script umgesetzt wird, damit das Endprofukt eine Webseite ist.        |
| 3    | Muss            | Randbedingung | Als ein Entwickler möchte ich, dass als zentrale Datenbank, MongoDB Atlas verwendet wird, damit alle Teammitglieder darauf zugreifen können. |
| 4    | Muss            | Qualität      | Als ein Benutzer möchte ich, dass die Webseite als Single Page Application umgesetzt wird, damit die Ladezeit gering ist.                    |
| 5    | Muss            | Funktional    | Als Benutzer möchte ich, dass ich eine Gruppe/Raum erstellen kann in dem ich mit anderen Spielern spielen kann, damit ich nicht alleine Spiele|
| 6    | Muss            | Funktional    | Als Benutzer möchte ich, dass ich mir einen Benutzername für das Spiel geben kann, damit ich weiss wer ich bin.                              |
| 7    | Muss            | Funktional    | Als Benutzer möchte ich, dass ich ein Kartenspiel in der Gruppe/Raum spielen kann, damit ich etwas spielen kann.                             |
| 8    | Muss            | Funktional    | Als Entwickler möchte ich, dass alle Daten in der MongoDB-Datenbank gespeichert werden.                                                      |
| 9    | Muss            | Funktional    | Als Entwickler möchte ich, dass das Frontend die Daten für ein Spiel über das Backend holt.                                                  |
| 10   | Muss            | Funktional    | Als Benutzer möchte ich, dass mir Karten ausgeteilt werden wenn das Spiel startet, damit ich ein Spiel spielen kann.                         |
| 11   | Muss            | Funktional    | Als Benutzer möchte ich, dass ich nur Karten legen kann die nach den Regeln gelegt werden können, damit ich ein Spiel spielen kann, dass nicht inkonsistent ist.|
| 12   | Muss            | Funktional    | Als Benutzer möchte ich, dass der erste Spieler welcher keine Karte mehr hat gewonnen hat, damit man ein Spiel gewinnen kann.                |
| 13   | Muss            | Funktional    | Als Benutzer möchte ich, dass die Webseite online zugänglich ist, damit ich es spielen kann.                                                 |

✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: _Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️_.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |              |         |                   |
| ...  |              |         |                   |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

✍️Fügen Sie hier ein Use Case-Diagramm mit mindestens 3 Anwendungsfällen ein; und eine Skizze davon, wie Ihre Netzseite aussehen sollte.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |           |              |               |
| ...  |       |           |              |               |

Total:

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.

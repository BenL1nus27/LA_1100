

Müller

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 28.08 | 0.0.1   | Heute habe ich das Projekt geplant.                          |
|   01.09    | 0.0.2      |  Heute habe ich den Code geschrieben und den Generator sommit in den Grunzügen fertig gecodet.|                                             | 08.09               | 0.0.3 | Heute habe ich den Code verfeinrt und grundlegende Fehler behoben. Danach habe ich das Layout verschönert und die Benutzerfreundlichkeit verbessert.
|       |   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Dieses Projekt beinhaltet einen RandomNumber Generator, bei dem der User die Zahl erraten muss, wärend das Projekt dir mithilfe von Tipps hilft.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |    Muss         |  FA  | Der Generator soll eine Zahl zwischen 1-100 generieren.  |
| 2  |       Muss          |  FA    | Der Generator soll nach US 6 einen Hinweis (> oder < als Zahl) geben.                                   |
| 3 | Kann| QA | Die Website bzw. Applikation soll ein anschauliches Design haben.
| 4| Kann| QA | Das Programm soll, nach erraten der RN, ausgeben wieviele Rateversuche gebraucht wurden.
|5| Kann| QA| Das Programm soll mit Fehleingaben umgehen können --> Hinweis auf Fehleingabe|
|6| Muss| FA| Der Generator erkennt eine Eingabe des Users.|
### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |   User drückt auf Start. | Befehl zu Ausführung   | Der RNGenerator speichert eine RN ohne sie auszugeben.|
| 2.1  | User versucht die RN zu erraten. |Eingabe einer Zahl| Der RNG vergeleicht die RN und die Eingabe miteinander und gibt aus ob <, > oder =.|
|4.1| User errät RN. | Eingabe von RN|  RNG gibt aus wieviele Rateversuche gebraucht wurden.|
|5.1| User gibt Zahl auserhalb 1-100 ein| Eingabe von -13| Der RNG gibt aus dass EIngabe ausserhalb des benutzbaren Zahlenraumes ist.|
|6.1| User versucht RN zu erraten.| Eingabe einer Zahl| Der Generator erkennt die Ausgabe und geht zu US 1 über.|
### 1.4 Diagramme
 
![PapDesigner - RandomNumber pap 25 08 2022 11_16_02](https://user-images.githubusercontent.com/111043950/186626368-ac4ae957-a94d-4f4c-b6b9-15a6d16ec5de.png)
![PapDesigner - RandomNumber pap 25 08 2022 11_16_10](https://user-images.githubusercontent.com/111043950/186626402-3f849ccb-eb00-42ae-ba1a-3963d6d5d6cd.png)

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1  |  1.9.22     |   Ben    |  Schreiben des Codes zur Generierung einer RandomNumber, Ausführen des Codes| 1 Arbeitspaket |
| 2 | 1.9.22   |  Ben   | Schreiben des Codes zu Erkennung einer Eingabe.  | 1 Arbeitspaket|
|3 | 08.9.22| Ben| Verbessung des Designes, Anpassungen der Buttons.| 2 Arbeitspakete|
|4| 1.9.22| Ben| Schreiben des Codes zur Zählung und Ausgabe der benötigten Versuche.| 1 Arbeitspaket|
|5| 

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |   01.09    |    Ben       |     1 AP          |    30 Min.               |
| 2.A  | 01.09      |  Ben         |    1 AP           |       1 AP            |
| 3.A| 01.09| Ben | 1 AP | 1.5 AP|
| 4.A| 08.09| Ben | 2 AP | 3 AP|



✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 01.09 |  Der RNG generiert und speichert eine Zahl.        | Ben       |
| 2.1  | 01.09    | Der RNG verarbeitet die Eingabe und gibt aus ob >, < oder =.           |    Ben    |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.

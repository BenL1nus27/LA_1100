

Müller, Ben 

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 28.08 | 0.0.1   | Heute habe ich das Projekt geplant.                          |
|   01.09    | 0.0.2      |  Heute habe ich den Code geschrieben und den Generator sommit in den Grunzügen fertig gecodet.|                                             | 08.09    | 0.0.3 | Heute habe ich den Code verfeinert und grundlegende Fehler behoben. Danach habe ich das Layout verschönert und die Benutzerfreundlichkeit verbessert. |
|   15.09    |     0.0.4    |   Heute habe ich kleine Änderungen vorgenommen, ich habe den Code etwas schöner geschrieben und die CW Commands ausgebessert.                                                           |



## 1 Informieren

### 1.1 Ihr Projekt

Dieses Projekt beinhaltet einen RandomNumber Generator, bei dem der User die Zahl erraten muss, wärend das Projekt dir mithilfe von Tipps hilft.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |    Muss         |  FA  | Der Generator soll eine Zahl zwischen 1-100 generieren.  |
| 2  |       Muss          |  FA    | Der Generator soll nach US 6 einen Hinweis (> oder < als Zahl) geben.|
| 3 | Kann| QA | Die Website bzw. Applikation soll ein anschauliches Design haben.|
| 4| Kann| QA | Das Programm soll, nach erraten der RN, ausgeben wieviele Rateversuche gebraucht wurden.|
|5| Kann| QA| Das Programm soll mit Fehleingaben umgehen können --> Hinweis auf Fehleingabe|
|6| Muss| FA| Der Generator erkennt eine Eingabe des Users.|
|7| Muss| FA | Der Gen fragt den User ob er Schwierigkeitsgrad 1 oder 2 will.|

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |   User drückt auf Start. | Befehl zu Ausführung   | Der RNGenerator speichert eine RN ohne sie auszugeben.|
| 2.1  | User versucht die RN zu erraten. |Eingabe einer Zahl| Der RNG vergeleicht die RN und die Eingabe miteinander und gibt aus ob <, > oder =.|
|4.1| User errät RN. | Eingabe von RN|  RNG gibt aus wieviele Rateversuche gebraucht wurden.|
|5.1| User gibt Zahl ausserhalb 1-100 ein| Eingabe von -13| Der RNG gibt aus dass Eingabe ausserhalb des benutzbaren Zahlenraumes ist.|
|6.1| User versucht RN zu erraten.| Eingabe einer Zahl| Der Generator erkennt die Ausgabe und geht zu US 1 über.|
### 1.4 Diagramme
 
![PapDesigner - RandomNumber pap 25 08 2022 11_16_02](https://user-images.githubusercontent.com/111043950/186626368-ac4ae957-a94d-4f4c-b6b9-15a6d16ec5de.png)
![PapDesigner - RandomNumber pap 25 08 2022 11_16_10](https://user-images.githubusercontent.com/111043950/186626402-3f849ccb-eb00-42ae-ba1a-3963d6d5d6cd.png)

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1  |  01.9.2022     |   Ben    |  Schreiben des Codes zur Generierung einer RandomNumber, Ausführen des Codes| 1 Arbeitspaket |
| 2 | 01.9.2022   |  Ben   | Schreiben des Codes zu Erkennung einer Eingabe.  | 1 Arbeitspaket|
|3 | 08.9.2022| Ben| Verbessung des Designes, Anpassungen der Buttons.| 2 Arbeitspakete|
|4| 01.9.2022| Ben| Schreiben des Codes zur Zählung und Ausgabe der benötigten Versuche.| 1 Arbeitspaket|
|5| 01.9.2022| Ben | Schreiben des Codes zu Erkennung einer Fehleingabe.| 30 Min.|
|6| 08.9.2022| Ben | Schreiben des Codes zur Erfragung des Schwierigkeitsgrades.| 1 Arbeitspaket|
|7| 15.09.2022| Ben | Verbesserungen sowie verschönerung des Codes.| 2-3 Arbeitspaket|
Total: 8-9 Arbeitspakete




## 3 Entscheiden


## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |   01.09    |    Ben       |     1 AP          |    30 Min.               |
| 2.A  | 01.09      |  Ben         |    1 AP           |       1 AP            |
| 3.A| 01.09| Ben | 1 AP | 1.5 AP|
| 4.A| 08.09| Ben | 2 AP | 2 AP|
|5.A| /| /| /| /|
|6.A| 15.09| Ben| 2-3 AP | ca. 3.5 AP|


## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 01.09 |  Der RNG generiert und speichert eine Zahl.        | Ben       |
| 2.1  | 01.09    | Der RNG verarbeitet die Eingabe und gibt aus ob >, < oder =.           |    Ben    |
|/|/|/|/|
|4.1|22.09.|Der RNG gibt nach erraten der Zahl durch User die Anzahl Verusche aus.|Ben|
|5.1|22.09|Der RNG erkennt eine Fehleingabe und wiederholt die gestellte Frage. |Ben|
|6.1|22.09|  Der Generator erkennt wenn und was für eine Eingabe gemacht wurde, und reagiert entsprechend darauf.  |Ben|
|7.1|22.09| Nicht 1 zu 1 so umgesetzt, aber nach Beendigung des ersten Schwierigkeitsgrades, fragt das Programm ob nochmals eine Runde, aber diesmal schwieriger, gespielt werden möchte. |Ben|



## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.

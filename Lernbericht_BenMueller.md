# Lern-Bericht
Ben Müller

## Einleitung

In diesem Projekt habe ich einen RandomNumberGuesser programmiert. Dieser generiert eine zufällige Zahl zwischen 1-100 beziehungsweise zwischen 1-1000, die dann von dem User erratet werden muss.

## Was habe ich gelernt?

In diesem Projekt habe ich gelernt wie und wo man eine Try/Catch Schleife verwendet.


## Beschreibung

In diesem Projekt haben wir einen RandomNumberGuesser programmiert. In diesem Rahmen mussten wir eine Try/Catch Schleife einbauen, um Fehleingaben zu verhindern.
Diese Schleife gibt einem die Möglichkeit, falls der User einen Fehler beziehungsweise eine Eingabe, welche nicht mit dem Code kompatibel ist, eingibt, einen Programmabsturz zu verhindern. 
So bekommt der User beispielsweise eine Information dass seine Eingabe nicht den Vorgaben entspricht. Wahlweise stoppt das Programm oder der User wird nach einer neuen Eingabe gefragt.

Zum Verständnis hier ein kleines Beispiel:
```csharp
         
            int Zahl;
            try
            {
                Console.WriteLine("Geben Sie eine Zahl ein:");
                Zahl = Convert.ToInt32(Console.ReadLine());
            }
            catch
            {
                Console.WriteLine("Ungültige Eingabe");
            }
```
Führt man das Programm aus, wird der User nach einer Zahl gefragt. Im Normalfall gibt der User dann eine gefragte Zahl ein (0,1,2,3,4,5,6,7,8,9). 
Falls die Eingabe falsch ist, wird der User in diesem Fall darüber informiert und das Programm gestoppt.


### Richtige Eingabe
![image](https://user-images.githubusercontent.com/111043950/191689682-7123b314-00c7-4138-a4e5-5025517af6d1.png)

### Falsche Eingabe

![image](https://user-images.githubusercontent.com/111043950/191689923-f6c90e93-b7f7-4b86-96bf-9aaeebd1e46a.png)



## Verifikation

In dem Codeausschnitt sieht man wie eine einfache Try/Catch Schleife aufgebaut ist. 
Die beiden Printscreens geben an, wie die möglichen Ausgaben aussehen beziehungsweise wie  das Programm ''aufgefangen'' wird

# Reflexion zum Arbeitsprozess

#### Was lief gut?

Ich fand, dass ich im Homeschooling viel konzentrierter gearbeitet habe. Die Arbeitsatmoshpäre war gelassener und ich war produktiver, da ich mich weniger 
durch andere Mitschüler ablenken lassen konnte. Mein Schlafrythmus wurde dadurch ebenfalls geschont, da ich 1.5 h mer Schlaf hatte. Einzig die Beschaffung von Hilfe zu Fehlern
war Zuhause schwieriger, da man keine direkte Ansprechperson hatte.

#### Was lief nicht gut?

In meinem Arbeitsprozess gab es zwischendurch Momente, in denen ich ein bisschen auf der Stelle lief. Mir war nicht immer klar was ich jetzt als nächstes machen sollte.
Die Planung meiner Projektdokumentation konnte mir da zum Glück etwas unter die Arme greifen, dennoch hatte ich hier und da mal Probleme beziehungsweise ''Leerläufe''.



**VBV**: 

Nächstes Mal, werde ich meine Projektplanung detaillierter gestalten, um Momente des Nichtstuns zu vermeiden und sommit auch etwas Zeit zu sparen.




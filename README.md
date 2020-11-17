# Übung 8
Quellcode der Vorlesung: https://github.com/fdiba-inf/vorlesung
## Repl.it öffnen
Bevor Sie die Taste _"Work in Repl.it"_ klicken, öffnen Sie https://repl.it/auth/github/get, um sicherzustellen, dass Sie in repl.it angemeldet sind.
## Aufgabe 0. Utils
Betrachten Sie die Klasse _Utils_ im Paket _exercise8_, die zwei static-Variablen und eine static-Methode _equals_ enthält.
Die Methode überprüft, ob zwei reale Werte gleich sind. 
Das ist notwendig, weil die realen Zahlen unendlich viel sind und mit einem Fehler im begrenzten Speicherplatz gespeichert werden.
Das Literal _1e-4_ ist gleich zum Literal _0.0001_.
## Aufgabe 1. Punkt
Ändern Sie die Klasse _Point_ im Paket _exercise8_. Jeder Punkt wird durch die 2D-Koordinaten _x, y_ dargestellt. Alle Werte sind in derselben Dimension z.B. _cm_.
* **Definition der Attribute** Definieren Sie zwei Attribute _x_ und _y_ vom Typ _double_. 
* **Definition vom Konstruktor ohne Parameter** Die Attribute werden mit dem Wert _0_ initialisiert.
* **Definition vom Konstruktor mit zwei Parametern** Die Attribute bekommen ihre Werte von den Parametern.
* **Definition vom Copy-Konstruktor** Die Attribute kopieren ihre Werte von einem anderen Punkt.
* **Definition einer Methode _initialize_ zur Eingabe** Sie soll die Eingabe der Attribute in der Konsole organisieren.
* **Definition einer Methode _translate_ zur Translation** Sie soll die Attribute des Punktes durch Translation ändern.
* **Definition einer Methode _createNewTranslatedPoint_ zur Erstellung eines Punktes durch Translation** Sie soll einen neuen Punkt durch Translation relativ zum Punkt erstellen.
* **Definition einer Methode _equals_ zum Vergleich zu einem anderen Punkt** Sie vergleicht, ob die Attribute des Punktes und die Attribute eines anderen Punktes gleich sind.
* **Definition einer Methode _toString_** Sie hat die Aufgabe der Punkt als String darzustellen z.B. _(2.6, 9.1)_.
## Aufgabe 2. Demo
Betrachten Sie die Klasse _PointDemo_ im Paket _exercise8_.
Sie enthalten eine main-Methode, die alle Konstruktoren und Methoden der _Point_ Klasse überprüft.
Das folgende wird in der Konsole ausgegeben, wenn für Punkt 3 die Werte _6_ und _9_ eingegeben werden:
``` 

``` 
## Aufgabe 3. Speicherplatz
Wie sieht der Speicherplatz nach der Ausführung der main-Methode aus? 
Nehmen Sie an, dass für Punkt 3 die Werte _6_ und _9_ in der Konsole eingegeben werden.
## Achtung! Achtung! Achtung!
Wenn Sie alle Aufgaben gemacht haben, sollen Sie die Lösungen in _GitHub_ hochladen. 
Wenn "Version Control" nicht verfügbar ist, geben Sie die folgenden Befehle in die Konsole ein:
``` 
git pull
git add .
git commit -m "Some message"
git push
``` 

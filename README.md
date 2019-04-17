# Challenge

**Es soll ein einfaches Spiel implementiert werden, das den folgenden Regeln folgt:**

*Jeder Spieler erhält fünf Karten, die er verdeckt vor sich auslegt. Jede Karte
hat dabei eine andere von sechs Farben. Der Würfel zeigt keine Zahlen, sondern
jeweils eine der sechs Farben. Es wird reihum gewürfelt. Würfelt ein Spieler
eine Farbe, zu der er eine Karte besitzt, die noch verdeckt ist, dann dreht er
diese Karte um. Hat ein Spieler alle Karten umgedreht, hat er gewonnen. 
Am Spiel sollen die drei Spieler Alice, Bob und Carol teilnehmen.*

Das Spiel soll dabei über eine minimalistische View verfügen, über welche mit einer Action das Spiel gestartet werden kann. Anschliessend sollte der Spielverlauf und der Gewinner minimalistisch angezeigt werden.

Achten Sie generell auf minimale Schnittstellen und auf die Einhaltung des
*Single-Responsibility-Prinzips.*
(https://en.wikipedia.org/wiki/Single_responsibility_principle)

Die Daten/Models müssen nicht persisistiert werden.

Gehen Sie in kleinen Schritten vor. Denken Sie zunächst an "Nouns and Verbs" 
und überlegen Sie sich, welche Klassen Sie implementieren möchten und welche
öffentlichen Schnittstellen diese brauchen. Achten Sie auch auf das Naming und 
befolgen Sie bestmöglich die Rails conventions. 

**Schritte:**
  1. Neues Git Repo erstellen und Rails Applikation erzeugen
  2. Erstellen eines UMLs (Skizze) und kurze Besprechung des Models
  3. Umsetzung des Spiels
  4. Repository auf Github veröffentlichen oder zippen und abgeben

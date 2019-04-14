# Eingesetzter Sensor: Pedometer

## Allgemeine Eigenschaften des Sensors
Der Pedometer verwendet die Bewegungssensoren des Telefons, um zu erkennen, wann die Person sich mit dem Handy fortbewegt. Dabei wird versucht die Anzal der Schritte zu messen. Wenn der Schrittzähler auf die Länge des Fußes abgestimmt ist, können die Werte besser geschätzt werden.

## Spezielle Schnittstelle des Sensors im AppInventor
????

## Mobile App: Appinventor

### Name
project_Pedometer

### Beschreibung
Ziel der App ist es, die Möglichkeiten des Sensors im Appinventor einzuschätzen und darzustellen.

### Zielgruppe
- Entwickler die sich mit dem Sensor "Pedometer" schnell vertraut machen wollen.
- Sportler die ihre Distanz dokumentiert haben wollen.

### technische Eigenschaften
Das Ziel der App ist es alle Eigenschaften zu präsentieren die der Sensor "Pedometer" im Appinventor anbieten kann. 
- StrideLength: Setzt die Beinlänge (in Meter)
- ElapsedTime: Zeit in Millisekunden seit der Pedometer gestartet wurde
- Distance: Zurückgelegte Strecke in Meter (wobei aber laut einer Internetquelle es "Fuß" sind, deswegen wurde die Zahl * 0.3048 gerechnet)
- SimpleStep/WalkStep: Der Unterschied besteht darin, dass das Ereignis WalkStep nur dann ausgelöst wird, wenn ein SimpleStep mit der Vorwärtsbewegung verbunden zu sein scheint. Für Activity Tracking Apps ist dies eine wichtige und vielleicht auch kritische Unterscheidung. Darüber hinaus liefern die Ereignisse nicht nur die Anzahl der seit dem Start der Schrittzähler-Komponente erfassten Schritte, sondern auch die vom Geher zurückgelegte Strecke, basierend auf der StrideLength-Eigenschaft, die für die Komponente eingestellt werden kann.
- StopDetectionTimeout: Dauer in der kein Schritt getätigt wurde. (Kein richtigen Wert gefunden)

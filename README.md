# Use-Case-Diagramm

## Titel: UC 1.03 - Alarm bei zu hoher Herzfrequenz
## Discription: 
Es wir dein Alarm ausgelöst sobald die Herzferquenz einen bestimmten Wert überschreitet .
## Actor:
### Sensor: 
Misst Herzfrequenz
### System:
Werten Daten des Sensors aus und löst wenn nötig Alarm aus. 
## Pre-condition:
es ist ein Grenzwert für den Alarm gegeben/ Leistungstest muss aktiv laufen und gemsssen werden
## Post-condition:
Alarm wird wenn nötig ausgelöst, je nach Herzfrequenz. alle weiteren Aktionen folge
## Basic path
1. Das System überwacht kontinuierlich die Herzfrequenz des Probanden während des Leistungstests.
2. Wenn die gemessene Herzfrequenz den vordefinierten Schwellenwert überschreitet, löst das System einen Alarm aus.
3. Der Alarm wird dem Trainer angezeigt und kann auch akustisch signalisiert werden.
4. Der Trainer/in erhält eine Benachrichtigung über den Alarm und reagiert dementsprechend
## Alternativ paths:
wenn Herzfrequenz den Grenzwert nicht übershcreitet wird kein Alarm ausgelöst.
## Exeption paths:
falls Sensor oder System nicht richtig läuft, wird der Alarm nicht oder zum falsch Ausgelöst

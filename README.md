# Use-Case-Diagramm

## Titel: UC 1.03 - Alarm bei zu hoher Herzfrequenz
## Discription: 
Es wir dein Alarm ausgelöst sobald die Herzfrequenz einen bestimmten Wert überschreitet .
## Actor:
### Sensor: 
Misst Herzfrequenz
### System:
Wertet Daten des Sensors aus und löst wenn nötig Alarm aus. 
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
# User Storys 
## Probanden 
1. Als Proband möchte ich während des Leistungstests kontinuierlich meine Herzfrequenz überwachen lassen.
2. Ich erwarte, dass das System einen Alarm auslöst, wenn meine Herzfrequenz den vordefinierten Schwellenwert überschreitet.
3. Der Alarm sollte klar und deutlich auf dem Bildschirm angezeigt werden und gegebenenfalls auch durch akustische Signale aufmerksam machen.
4. Die Benachrichtigung über den Alarm sollte zeitnah erfolgen, damit ich angemessen darauf reagieren kann.
5. Ich möchte die Möglichkeit haben, meine Anstrengung entsprechend anzupassen oder den Leistungstest abzubrechen, falls mein Herzfrequenzwert zu hoch ist.
6. Das System sollte sicherstellen, dass meine Gesundheit und Sicherheit während des gesamten Leistungstests gewährleistet ist.

## Diagnostiker
1. Als Diagnostiker möchte ich in Echtzeit über die Herzfrequenzwerte aller Probanden informiert werden, die an Leistungstests teilnehmen.
2.Ich erwarte, dass das System einen Alarm auslöst, wenn die Herzfrequenz eines Probanden den vordefinierten Schwellenwert überschreitet.
3. Der Alarm sollte deutlich und sofort auf meinem Überwachungsmonitor oder in der Anwendungssoftware angezeigt werden.
4. Die Benachrichtigung über den Alarm sollte präzise Informationen über den betroffenen Probanden und den aktuellen Zustand enthalten.
5. Das System sollte sicherstellen, dass die Integrität der Herzfrequenzdaten und die Genauigkeit des Alarms gewährleistet sind, um Fehlalarme zu minimieren und die Zuverlässigkeit der Diagnose zu verbessern.

## system
1. Als System möchte ich kontinuierlich die Herzfrequenzdaten der Probanden während des Leistungstests erfassen und überwachen.
2. Ich erwarte, dass das System einen Alarm auslöst, wenn die gemessene Herzfrequenz eines Probanden den vordefinierten Schwellenwert überschreitet.
3. Der Alarm sollte klar und deutlich auf dem Bildschirm des Diagnostikers angezeigt werden und gegebenenfalls auch durch akustische Signale aufmerksam machen.
4. Das System sollte sicherstellen, dass die Herzfrequenzdaten zuverlässig und genau sind, um Fehlalarme zu minimieren und die Genauigkeit der Diagnose zu verbessern.
5. Ich möchte die Möglichkeit haben, den betroffenen Probanden in Echtzeit zu identifizieren und relevante Informationen über den Zustand des Probanden bereitzustellen.
6. Das System sollte flexibel genug sein, um den Schwellenwert für die maximale Herzfrequenz an die spezifischen Anforderungen und Sicherheitsstandards anzupassen.

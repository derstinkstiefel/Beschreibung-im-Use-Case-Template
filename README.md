# Beschreibung-im-Use-Case-Template

## UC1.03 - Alarm bei zu hoher Herzfrequenz 
### Description
Es wird ein Alarm ausgelöst sobalt die Herzrewuenz
einen bestimmen wert überschreitet.
### Actor 
#### Sensor
Misst die Herzfrequenz.
#### System 
wertet die Daten aus und löst Alarm aus.
### Pre-condition
es ist ein Schwellenwert für den Alarm gegeben und
Der leistungstest muss aktiv laufen/ Gemesseb werden.
### Post-condition
alarm wird wenn nötig ausgelöst oder nicht ausgelöst, je nach Herzfrequenz. alle weiteren aktionen müssen folgen.
### Basic path
1. Das System überwacht kontinuierlich die Herzfrequenz des Probanden während des Leistungstests.
2. Wenn die gemessene Herzfrequenz den vordefinierten Schwellenwert überschreitet, löst das System einen Alarm aus.
3. Der Alarm wird dem Trainer angezeigt und kann auch akustisch signalisiert werden.
4. Der Trainer/in erhält eine Benachrichtigung über den Alarm und reagiert dementsprechend.
### Alternative paths 
wenn die Herzfrequenz unter dem Schwellwert bleibt wird kein alarm ausgelöst.
### Exeption paths 
falls der Sensor nicht rihtig funktioniert oder fehlerhaft misst kann kein wahrer Alarm ausgelöst werden.

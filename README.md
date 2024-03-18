# Beschreibung-im-Use-Case-Template

## UC1.03 - Alarm bei zu hoher Herzfrequenz 
### Description
Es wird ein Alarm ausgelöst sobalt die Herzfrequenz
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

# User Storys 
## Probanden 
1. Als Proband möchte ich während des Leistungstests kontinuierlich meine Herzfrequenz überwachen lassen.
2. Ich erwarte, dass das System einen Alarm auslöst, wenn meine Herzfrequenz den vordefinierten Schwellenwert überschreitet.
3. Der Alarm sollte klar und deutlich auf dem Bildschirm angezeigt werden und gegebenenfalls auch durch akustische Signale aufmerksam machen.
4. Die Benachrichtigung über den Alarm sollte zeitnah erfolgen, damit ich angemessen darauf reagieren kann.
5. Ich möchte die Möglichkeit haben, meine Anstrengung entsprechend anzupassen oder den Leistungstest abzubrechen, falls mein Herzfrequenzwert zu hoch ist.

## Diagnostiker
1. Als Diagnostiker möchte ich in Echtzeit über die Herzfrequenzwerte aller Probanden informiert werden, die an Leistungstests teilnehmen.
2.Ich erwarte, dass das System einen Alarm auslöst, wenn die Herzfrequenz eines Probanden den vordefinierten Schwellenwert überschreitet.
3. Der Alarm sollte deutlich und sofort auf meinem Überwachungsmonitor oder in der Anwendungssoftware angezeigt werden.
4. Die Benachrichtigung über den Alarm sollte präzise Informationen über den betroffenen Probanden und den aktuellen Zustand enthalten.
5. Ich möchte die Möglichkeit haben, den betroffenen Probanden unmittelbar zu kontaktieren oder den Leistungstest abzubrechen, um auf die erhöhte Herzfrequenz angemessen zu reagieren.

## system
1. Als System möchte ich kontinuierlich die Herzfrequenzdaten der Probanden während des Leistungstests erfassen und überwachen.
2. Ich erwarte, dass das System einen Alarm auslöst, wenn die gemessene Herzfrequenz eines Probanden den vordefinierten Schwellenwert überschreitet.
3. Der Alarm sollte klar und deutlich auf dem Bildschirm des Diagnostikers angezeigt werden und gegebenenfalls auch durch akustische Signale aufmerksam machen.
4. Das System sollte sicherstellen, dass die Herzfrequenzdaten zuverlässig und genau sind, um Fehlalarme zu minimieren und die Genauigkeit der Diagnose zu verbessern.
5. Das System sollte flexibel genug sein, um den Schwellenwert für die maximale Herzfrequenz an die spezifischen Anforderungen und Sicherheitsstandards anzupassen.
6. Nach Auslösung des Alarms sollte das System eine Protokollierung der Ereignisse durchführen, um eine Nachverfolgung und Analyse zu ermöglichen.

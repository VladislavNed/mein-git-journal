# Mein Git Lernjournal
## Grundlagen

Für jeden Commit speichert das System drei Dinge.

1. **was** wurde geändert (z.B. Zeile 5 im Dokument wurde gelöscht, und eine andere hinzugefügt).
2. **wer** hat es geändert(Benutzername der Person).
3. **warum** wurde es geändert (Der Entwickler schreibt eine kurze Nachricht, z.B. "Rechtschreibfehler im Vorwort korrigiert).<br>

Dadurch entszteht eine lückenlose, nachvollziehbare Geschichte des gesamten Projekts. Du kannst jederzeit Zurückblicken und jede einzellne Änderung seit Projektbeginn sehen. <br>

In der Versionskontrolle ist der "Stamm" (oder Trunk/Main Branch) die Hauptentwicklungsleitung eines Projekts, die den stabilsten und aktuellsten Hauptcode enthält, von dem aus neue Funktionen (in Branches) entwickelt werden, bevor sie wieder zusammengeführt (merged) werden – quasi das Rückgrat des Projekts, das alle offiziellen Versionen repräsentiert.
## Architektur ##
Der Single Point of Failure ist die zentrale Komponente (z. B. der Hauptserver), deren Ausfall das gesamte System lahmlegt, da es keine redundanten Ausweichmöglichkeiten gibt.
<br>
In einem verteilten System wie Git wird die vollständige Projekthistorie lokal auf dem Rechner jedes einzelnen Entwicklers gespeichert.<br>

## Der Workflow ##

Einkaufswagen: git add

Schnappschuß: git commit

## Den Verlauf überprüfen ##

git log --oneline
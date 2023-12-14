# PVL Moderne Softwaretechnik

## Zeitreise 1

Sprung um ein Commit zurück. Bei dem die Datei game-start.html noch nicht gelöscht war.

Mit dem Command "git checkout (commit-hash)" konnte ich zu einem früheren Commit springen.
Mit dem Command "git reset --soft (commit-hash)" habe ich versucht Main auf diesen alten Stand zurück zu setzen.
Das hat aber leider nicht funktioniert. Als Ausgabe bekam ich immer "Head detached at (commit-hash)", aber Main war immer noch auf dem aktuellsten Stand.
Da der working-tree leer war, konnte ich auch kein Commit durchführen.
Ich habe es noch versucht zu mergen, aber das hat keine Änderung ergeben. Main war immer noch auf dem neusten Stand.
Also die Datei game-start.html war immer noch gelöscht.


## Zeitreise 2

Bei diesem Versuch habe ich zuerst eine test-zeitreise.html angelegt und commited.
Danach habe ich den Command "git revert --no-commit (commit-hash) angewendet, um zum vorherigen Commit zu springen.
Das hat funktioniert.




# Diffgeo

## Generelles

Cheatsheet vom letzten Semester

Bitte folgende Aufteilung berücksichtigen:
- Fach (Folder)
  - Übungsnummer (Folder)
    - headerfile.tex
    - beispiel##.tex (für jedes Beispiel ein .tex, das mit \input ins headerfile eingebunden wird)

## Commits
Bei Commits bitte immer das jeweilige Fachkürzel vorstellen, d.h. bei einem Commit zu einer PDG Übung als Commit-Text
```
	PDG: bliblablub
```
verwenden

## Git Cheatsheet

Git repository clonen:

```
    git clone https://<username>@github.com/wiedeflo/Mathe-Public
```

Neue Datein hinzufügen (bzw. nach Dateien umbenennen ausführen!):

```
    git add DATEI
```

Änderungen ansehen (bevor man etwas commited sinnvoll):
```
    git diff
```

Änderungen verwerfen:
```
    git checkout -- .
```

Änderungen commiten (kurze Beschreibung der Änderung nicht vergessen!)

```
    git commit -am "Kurze Beschreibung"
```

Commits hochladen auf Github:

```
    git push
```

Neue Änderungen von Github herunterladen:

```
    git fetch
```

Die heruntergeladenen Änderungen ansehen:

```
    git diff ...remote/branch
```

Die heruntergeladen Änderungen mergen:

```
    git merge
```

oder die letzten beiden Schritte in einem (mühsamer bei merge conflicts!):

```
    git pull --rebase
```

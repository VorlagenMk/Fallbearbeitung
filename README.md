# Fallbearbeitung

Dieses Repo soll als Vorlage für Fallbearbeitungen verwendet werden
können.

Damit die PDF Datei erzeugt werden kann muss im Terminal noch die entsprechende Software nachinstalliert werden:

```bash
$ sudo apt update
$ sudo apt install pandoc pandoc-citeproc texlive texlive-xetex
```

Der Befehl für die Erzeugung eines PDF lautet:

```bash
$ pandoc --filter pandoc-citeproc fallbearbeitung.md -o fallbearbeitung.pdf
```



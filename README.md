# Statistik-I-II
Zusatzmaterial zu Statistik I und II - HU-Berlin Wirtschaftswissenschaften

## Sind diese Skripte etwas für mich?

Kommt darauf an. Wenn Du bereits verstanden hast, worum es in den Aufgaben geht und sehen willst, wie man sie mithilfe eines Computers löst, bist Du hier genau richtig. Das heißt aber auch, dass Du interessiert daran bist, Dich mit der Programmiersprache Python auseinander zu setzen und idealerweise schon über erste Kenntnisse darin verfügst.

Wenn das alles nicht so Dein Ding ist, ist das auch kein Problem, denn:

```diff
- All diese Codes sind **nicht** für die Klausur relevant, genau genommen haben
- sie mit dem Lehrstuhl für Statistik **rein gar nichts** zu tun.
```

## Wo kann ich Python lernen?

Zugegeben, *hier* wäre es eine eher schlechte Idee Python lernen zu wollen. Viel Wissen, z.B. über die nativen Datenstrukturen in Python (`Listen`, `Tupel`, `Dictionaries`, etc.), wird vorausgesetzt. Wenn Du aber nach einem guten Start suchst, kann ich Dir zwei Quellen empfehlen:

1. [Learn Python3 the hard way](https://learnpythonthehardway.org/python3/) ist eine hervorragende Einführung. Auch wenn der Titel nicht besonders vertrauenerweckend klingt...
2. [DataCamp](https://www.datacamp.com/) bietet eine mittlerweile recht ansehliche Sammlung an Python-Material speziell für Datenanalysen.

## Und warum sollte ich mir das antun?

Ganz einfach: wegen den Grafiken! Oft haben die Methoden, die wir in der Vorlesung kennen lernen, eine geometrische Interpretation (die mir zum Beispiel geholfen hat, den Sinn hinter manchen Definitionen zu verstehen).

Die gewonnene Funktionalität, hat aber einen Haken: Wir müssen zuerst `JupyterLab` installieren. Das ist eine Entwicklungsumgebung, die es einfacher macht den Python-Code mit erklärendem Text zu erweitern und es Dir daheim ermöglicht, an den Grafiken herum zu spielen. Es ist aber auch möglich, die Notebooks in diesem repository auch ohne `JupyterLab` zu betrachten, denn normalerweise verfügt Github bereits über eine ausreichende Darstellung von Python-Notebooks.

### Wie installiere ich `Python` und `JupyterLab`?

Am einfachsten ist es, wenn man die Python Version nimmt, die von [Anaconda](https://www.anaconda.com/) bereitgestellt wird. Diese enthält bereits alle Kernels und alle Module, die wir voraussichtlich benutzen werden. Um Anaconda auf Euren Rechnern zu installieren, folgt den Anweisungen für Euer Betriebssystem [hier](https://conda.io/docs/user-guide/install/index.html).

Um dreidimensionale Grafiken in einem Browser drehen zu können, müsst Ihr unter Umständen folgende Befehle in einer Konsole ausführen:

```bash
conda install -c conda-forge ipympl
conda install nodejs
jupyter labextension install @jupyter-widgets/jupyterlab-manager
jupyter labextension install jupyter-matplotlib
```

### Wie öffne ich eine Konsole?

**Unter Windows** öffnet man eine Konsole, indem man die Windows-Taste drückt und anfängt, `Eingabeaufforderung` einzugeben. Es öffnet sich ein schwarzes Fenster, in das Ihr die oben genannten Befehle eingebt. Alternativ, kann man auch die `Windows-Taste + R` drücken.

**Unter MacOS** kann man das Kürzel `Cmd + Leertaste` verwenden, um eine Suchleiste zu öffnen. Hier könnt Ihr nach `terminal` suchen und `Enter` drücken. Es öffnet sich ein schwarzes Fenster, in das Ihr die oben genannten Befehle eingebt.

**Unter Linux** öffnet man ein Terminal mit der Tastenkombination `Str+Alt+T`. Es öffnet sich ein schwarzes Fenster, in das Ihr die oben genannten Befehle eingebt.

### Wie komme ich an die Skripte?

Ganz einfach: oben rechts gibt es ein grünes Feld mit der Aufschrift: `clone or download`

Click es an und lade Dir die `.zip`-Datei herunter. Öffne das Notebook Deiner Wahl in `JupyterLab` und das wars schon :)

# LIT 2023: Datenanalyse mit Python
Vortrag beim Linux-Infotag 2023 am 29.4.2023 in Augsburg.

Beim Umstieg zu Linux bietet sich zur Datenanalyse und -manipulation zunächst die Tabellenkalkulationskomponente Calc aus dem Office-Paket LibreOffice an.  Für diejenigen mit etwas Python-Programmiererfahrung lohnt es sich jedoch, die Verwendung des [pandas](https://pandas.pydata.org)-Pakets in Betracht zu ziehen. Hiermit lassen sich Daten, die in den verschiedensten Formaten vorliegen können, in ein Python-Programm importieren und verarbeiten sowie graphisch darstellen. Damit stehen alle Möglichkeiten des Python-Universums offen, unter anderem die Datenanalyse in [Jupyter](https://jupyter.org)-Notebooks. Der Vortrag wird am Beispiel der Analyse von Daten aus dem [Open-Data-Portal der Deutschen Bahn AG](https://data.deutschebahn.com/) eine Einführung in die Benutzung des pandas-Pakets geben und die explorative Analyse von Daten in einem Jupyter-Notebook demonstrieren.

### Installation der Pythonumgebung

Die Vortragspräsentation liegt in Form des Jupyter-Notebooks `lit2023.ipynb` vor. Um das Notebook zu präsentieren, kann die RISE-Erweiterung verwendt werden. Eine passende Pythonumgebung lässt sich folgendermaßen erzeugen:
```
conda env create -f environment.yml
```

### Verwendete Datensätze

Die beiden Datensätze und eine Abbildung sind nicht in diesem Repository vorhanden, sondern können mit Hilfe von `get_resources` heruntergeladen werden.

Der Vortrag basiert auf Datensätzen, die über das Open-Data-Portal der Deutschen Bahn AG zur Verfügung gestellt werden:
* [Passagierzählung S-Bahn Hamburg](https://data.deutschebahn.com/dataset/passagierzahlung-s-bahn-hamburg.html)
* [Haltestellendaten](https://data.deutschebahn.com/dataset/data-haltestellen.html)


# Ausgewählte Kapitel sozial Webtechnologien - Neuronale Netze
## Trainieren eines Word2Vec Modells und Darstellung von Wort- und Dokumentenvektoren anhand von Anfragetexten des FragDenStaat-Projektes

Bearbeiten von:
* Sebastian Jüngling (558556)
* Konstantin Bruckert (558290)

Prüfer:
* Benjamin Voigt

Projektbeschreibung, Code und Dokumentation siehe Exposé und Jupyter Notebook.

# Installation
## Datendownload:
Die Datei 'fds_requests_preprocessed.json' muss leider manuell eingeladen werden, da diese für die Versionsverwaltung zu groß ist.  
Downloadlink: https://webdrive.htw-berlin.de/public/file/M6jwaKmqPEGUFOR8bKMYYw/fds_requests_preprocessed.json
Lade die Datei herunter und speichere sie auf gleicher Ebene wie das Jupyter Notebook.
Das Passwort erhalten Sie auf Anfrage bzw. in der Mail zur Abgabe.

## Dependencies:
Verwendete Python-Version: 3.6.5

### Falls Pipenv verwendet wird:
cd in Projektverzeichnis:
```
$ pipenv install
$ pipenv shell
$ python -m ipykernel install --user --name=`basename $VIRTUAL_ENV`
```

Start Jupyter Notebook und darauf achten den richtigen (oben erstellten) virtuellen ipykernel zu wählen:
```
$ jupyter notebook
```

### Alternativ:
Installiere Dependencies via requirements.txt

oder

zu installierende Dependencies:
* numpy
* pandas
* tensorflow
* sklearn
* plotly

## Licenses

Notebook License (CC-BY-SA 4.0)
The following license applies to the complete notebook, including code cells. It does however not apply to any referenced external media (e.g., images), namely "Trainieren eines Word2Vec Modells und Darstellung von Wort- und Dokumentenvektoren anhand von Anfragetexten des FragDenStaat-Projektes" <br/>
by Sebastian Jüngling, Konstantin Bruckert <br/>
is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.<br/>
Based on a work at HTW Berlin.

The following license only applies to code cells of the notebook.Copyright 2019 Sebastian Jüngling, Konstantin Bruckert <br> Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
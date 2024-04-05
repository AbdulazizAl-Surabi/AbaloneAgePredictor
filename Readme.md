# Abalone Age Prediction Project

## Einleitung

Dieses Projekt verwendet Machine Learning-Modelle, um das Alter von Abalones (Meeresschnecken) basierend auf physischen Messungen zu schätzen. Das Alter wird durch die Anzahl der Wachstumsringe auf der Schale der Abalones bestimmt. Der beiliegende Jupyter Notebook im `src`-Verzeichnis beinhaltet die komplette Analyse und die Modellierung.

## Umgebung einrichten

Es wird empfohlen, eine virtuelle Umgebung zu verwenden, um die Abhängigkeiten zu verwalten. Führen Sie die folgenden Schritte aus, um die Umgebung einzurichten und zu aktivieren.

### Voraussetzungen

Stellen Sie sicher, dass Sie Python 3.8 oder höher installiert haben, sowie `pip` und `virtualenv`.

### Virtuelle Umgebung erstellen

Öffnen Sie ein Terminal oder eine Eingabeaufforderung und navigieren Sie zum Projektverzeichnis.
Erstellen Sie dann eine virtuelle Umgebung namens `abalones_age_env`:

```
python -m venv abalones_age_env
```

### Aktivieren der virtuellen Umgebung

Um die virtuelle Umgebung zu aktivieren, führen Sie den entsprechenden Befehl für Ihr Betriebssystem aus:

**Windows:**

```
abalones_age_env\Scripts\activate
```

**macOS/Linux:**

```
source abalones_age_env/bin/activate
```

### Abhängigkeiten installieren

Installieren Sie alle erforderlichen Pakete über `pip` mit der `requirements.txt`-Datei:

```
pip install -r src/requirements.txt
```

## Notebook starten

Stellen Sie sicher, dass Ihre virtuelle Umgebung aktiviert ist. Navigieren Sie zum `src`-Ordner und starten Sie Jupyter Notebook. Öffnen Sie das `*.ipynb`-Notebook im Jupyter Notebook-Dashboard, um mit der Ausführung der Analyse zu beginnen.

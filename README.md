# Carbon.CH - Mobilitäts-Tracker & Vergleich

Ein interaktives Tool zur Berechnung und zum Vergleich von CO2-Emissionen verschiedener Verkehrsmittel (Auto, Zug, Flug, Velo). Entwickelt mit Python, Jupyter Notebooks und ipywidgets im modernen "Swiss Design".

## Funktionen

*   **Interaktive Berechnung:** Geben Sie Distanz und Personenanzahl ein und sehen Sie das Ergebnis in Echtzeit.
*   **Vergleichsmodus:** Vergleicht Ihre Wahl automatisch mit anderen Verkehrsmitteln.
*   **Pro-Kopf-Berechnung:** Berücksichtigt, dass sich Emissionen beim Auto auf die Mitfahrer aufteilen, während sie bei Zug/Flug pro Person konstant bleiben.
*   **Swiss Design UI:** Klares, minimalistisches Layout ohne störende Scrollbars.

## Installation

Stellen Sie sicher, dass Python installiert ist. Installieren Sie die notwendigen Bibliotheken:

```bash
pip install ipywidgets voila
```

## Nutzung

### 1. Als Jupyter Notebook
Öffnen Sie die Datei `carbon_interactive.ipynb` in Jupyter Lab oder Notebook:

```bash
jupyter notebook carbon_interactive.ipynb
```
Führen Sie alle Zellen aus (`Cell` -> `Run All`), um das Interface anzuzeigen.

### 2. Als Web-App (Browser-Ansicht)
Für die beste Nutzererfahrung können Sie das Notebook als eigenständige Webanwendung starten. Dabei werden der Code ausgeblendet und nur die interaktiven Elemente angezeigt. Wir nutzen dafür **Voila**.

Führen Sie folgenden Befehl im Terminal aus:

```bash
voila carbon_interactive.ipynb
```

Dies startet einen lokalen Server und öffnet automatisch Ihren Standard-Browser mit dem Carbon Tracker.

---

## Projektstruktur
*   `carbon_interactive.ipynb`: Das aktuelle, interaktive Notebook (GUI).
*   `carbon_analysis.ipynb`: Die ursprüngliche Basis-Version (Text-basiert).
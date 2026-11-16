# Agenda: Start in JupyterHub.nrw

Lebendes Dokument für die Session. 90 Minuten, etwa zehn Personen, überwiegend Multiplikatoren.
Leitfrage des Publikums: "Was kann ich damit meinen Forschenden und Lehrenden anbieten?"

## Ablauf

| Zeit | Block | Inhalt | Material |
|---|---|---|---|
| 0–10 | Begrüßung | Vorstellungsrunde, ein Satz zum eigenen Anwendungsfall | |
| 10–20 | Teaser | Live-Demo: Login, Notebook öffnen, Plot, Slider. Zeigt, wo die Reise hingeht | `02_daten.ipynb` |
| 20–35 | Login | Token eingeben, Login über eigenen IDP, Server starten. Erst vorführen, dann alle | Login-Handzettel |
| 35–50 | Erste Schritte | Gemeinsam durch das Notebook: Zellen, Markdown, Kernel, Dateibrowser, Reihenfolge-Falle | `01_erste_schritte.ipynb` |
| 50–70 | Daten | Datensatz einlesen, filtern, plotten, Slider. Wer fertig ist, nimmt sich eine Zugabe | `02_daten.ipynb`, `zugaben/` (R, Textanalyse, SymPy) |
| 70–90 | Ausblick | nbgitpuller als "so geht es heute", e2xgrader-Exchange als Zukunft (Screenshots). Gespräch: Was braucht ihr? | Folien |

## Roter Faden

Reproduzierbarkeit: Code, Daten, Text und Ergebnis in einem Dokument, gleiche Umgebung für alle, "Restart & Run All".

Aha-Momente, die ich setzen will:

- Keine Installation nötig.
- Gerätewechsel: gleiche Arbeit auf einem anderen Gerät weiterführen.
- Auflösung am Ende: alle Materialien kamen über einen einzigen Link.

## Login als Hauptrisiko

- Vorab-Mail: IDP-Login einige Tage vorher testen lassen.
- Schritt-für-Schritt-Folie mit Screenshots, zusätzlich als Handzettel mit QR-Code.
- Ablauf einmal vorführen, bevor alle loslegen.
- Plan B: zu zweit an einem Laptop.
- Wer schon drin ist, bekommt eine Miniaufgabe im ersten Notebook.

## Technik

- Hub der Uni Münster. Image enthält pandas, matplotlib, ipywidgets und einen R-Kernel. `wordcloud` fehlt und wird im Textanalyse-Notebook per `%pip install` nachinstalliert.
- Datensatz: Gapminder (`daten/gapminder.csv`). Texte: zehn Grimm-Märchen aus dem TextGrid-Repository (`daten/maerchen/`, Lizenz in `QUELLE.md`).

## Offene Fragen

- Funktionieren die IDPs von HHU, Westfälischer Hochschule, Wuppertal, Hochschule Bochum und FernUniversität in Hagen? Was tun Gäste ohne passenden IDP?
- Gibt es eine zweite Person, die beim Login hilft?
- Die Gesamtagenda des Tages liegt noch nicht vor.

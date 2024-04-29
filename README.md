# DNA Sequencing Classification

Dieses Repository enthält ein Machine-Learning-Modell, das DNA-Sequenzen anhand ihres Ursprungs klassifiziert. Das Modell verwendet einen Bag-of-Words-Ansatz, um k-Mer-Wörter (in diesem Fall Hexamer-Wörter) aus den Sequenzen zu extrahieren und ein Multinomial-Naive-Bayes-Klassifikator zur Klassifizierung zu verwenden.

## Hintergrund

Die Analyse von DNA-Sequenzen ist ein wichtiger Bestandteil der Bioinformatik und Genomik. Klassifizierung von DNA-Sequenzen ermöglicht es, genetische Informationen zu interpretieren, evolutionäre Beziehungen zwischen Arten zu untersuchen und genetische Ursachen von Krankheiten zu identifizieren.

## Daten

Die Daten für dieses Projekt sind in drei Dateien enthalten: `human_data.txt`, `chimp_data.txt` und `dog_data.txt`. Jede Datei enthält DNA-Sequenzen und ihre Klassenzuordnungen (0 für menschliche DNA, 1 für Schimpansen-DNA und 2 für Hunde-DNA).


# Verwendung
Führe das dna_classification.ipynb Jupyter Notebook aus, um das Modell zu trainieren und zu evaluieren. Das Notebook führt die folgenden Schritte aus:

# Daten laden und vorverarbeiten.
Bag-of-Words-Modell erstellen.
Daten in Trainings- und Testsets aufteilen.
Multinomial-Naive-Bayes-Klassifikator trainieren.
Vorhersagen auf Testdaten machen und Metriken auswerten.

# Ergebnisse:
Das trainierte Modell erreicht eine Genauigkeit von 98.4% und kann menschliche, Schimpansen- und Hunde-DNA mit hoher Genauigkeit klassifizieren.

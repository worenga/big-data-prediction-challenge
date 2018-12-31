# Big Data Predictions Challenge
Einreichung für die it-talents.de / Materna IT Code-Competition Dezember 2018 ("[Bit Data Predictions](https://www.it-talents.de/foerderung/code-competition/code-competition-12-2018)"). 

# Kurzbeschreibung
In unserer Lösung wird versucht zunaechst die bereitgestellten Daten aufzubereiten.
Anschliessend, explorieren und visualisieren wir die Daten.
Zu guter letzt trainieren wir zwei Feed-Forward neuronalen Netze zu um folgende Modelle bereitzustellen:

- Ein Modell zur Berechnung des Gewinners bei gegebener Strecke, Herausforderer und Opponent, sowie Datum und Wettervorhersage In unserer Loesung benutzen wir ein Feed-Forward deep neuronales Netz mit Embeddings fuer kategorische Variablen, sowie Dropouts. Wir erreichen eine Genauigkeit von 74% bei der Vorhersage des Gewinners nur anhand von Datum, Strecke und Wettervorhersage. 
- Ein Modell zur Schaetzung des Spritverbrauchs (fuel_consumption). Wir modifizieren dazu unser vorheriges Modell zur Schaetzung einer kontinuierlichen Variable. 



# Abgabeartefakte 
Die Lösung ist als Jupyter Notebook verfasst (Python3 Kernel).

-  [Daten Aufbereitung](./00-cleaning/Cleaning.ipynb)
-  [Daten Analyse](./01-analysis/Exploration-Analysis.ipynb)
-  [FNN Model Gewinnerberechnung](./02-prediction/FuelConsumptionPrediction.ipynb)
-  [FNN Model Spritverbrauch](./02-prediction/FuelConsumptionPrediction.ipynb)


# Installationsvorraussetzungen

Falls das Jupyter Notebook local ausgeführt werden soll müssen die folgenden Softwarepakete und python pakete installiert sein.

 * jupyter notebook
 * pytorch
 * pandas
 * matplotlib
 * numpy
 * scikit-learn
 * [sklearn-pandas](https://github.com/scikit-learn-contrib/sklearn-pandas)
 * [pandas-summary](https://github.com/mouradmourafiq/pandas-summary)

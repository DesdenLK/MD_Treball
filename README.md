# MDSegonTreball

## Installation

Si no teniu instalat les llibreries necessàries. Ho podeu fer amb anaconda o creant un virtual environment. Per la segona opcio cal seguir els seguents passos:

`python3 -m venv .env`

`source .env/bin/activate`

`pip install -r requirements.txt`

## Estructura de directoris

En el directori base es troben les notebooks utilitzades per al treball:

- `Preprocessing-Adapted.ipynb`: Passes de preprocessing, genera els datasets preprocessats a partir de l'original.
- `KNN_Final.ipynb`: Tests amb k-NN
- `NaiveBayes.ipynb`: Tests amb Naive Bayes
- `DecisionTrees.ipynb`: Tests amb decision trees
- `SVMs.ipynb`: Tests amb SVMs
- `Meta-learning.ipynb`: Tests amb meta learning methods
- `McNemarTest.ipynb`: Notebook amb els McNemar tests

En el directori `Dataset` es troba:

- `smoking.csv`: les dades del dataset original
- `Smoking_preprocessed.csv`: dades preprocessades sense estandardització ni normalització.
- `Standardized_Smoking.csv`: dades preprocessades estandarditzades.
- `Normalized_Smoking.csv`: dades preprocessades normalitzades.
- `metadata.json`: Arxiu de metadades que venia amb el dataset original.
- `Methodology_(en|kr).pdf`: Pdf descriptor de la metodologia trobat a la web oficial de l'organització responsable del dataset. L'original en koreà i una traducció automàtica a l'anglès estan disponibles (en|kr).

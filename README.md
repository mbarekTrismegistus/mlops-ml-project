# mlops-ml-project — baseline ML reproductible

## Installation

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Entraînement

```bash
python scripts/train.py
```

## Évaluation

```bash
python scripts/evaluate.py
```

## Tests

```bash
python -m pytest -q
```

## Artefacts

Les artefacts sont générés dans `artifacts/` et ne sont pas versionnés.

- `model.joblib` : pipeline entraîné
- `metrics.json` : accuracy et f1_macro
- `confusion_matrix.png` : matrice de confusion
- `report.json` : rapport de classification

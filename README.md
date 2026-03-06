# Progetto Kaggle - Enzyme Substrate (S3E18)

## Struttura del Team
- **Davide:** Feature Engineering (vedi `src/preprocessing.py`)
- **Elisabetta:** Modelli GBDT (XGBoost/LightGBM)
- **Gabrielle:** Modelli Deep Learning (MLP)
- **Giovanni:** Lead Integration & Validation (`utils.py`)

## Regole d'oro
1. **Non modificare mai `utils.py`** senza aver avvisato Giovanni.
2. **Usa sempre la funzione di caricamento** in `utils.py` per leggere i dati.
3. **Pull prima di Push:** Prima di iniziare a lavorare ogni giorno, fai `git pull origin main`.

## Istruzioni
1. Installa le dipendenze: `pip install -r requirements.txt`
2. Esegui il preprocessing: `python src/preprocessing.py`
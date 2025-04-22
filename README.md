# CHIP-Risk Predictor

Una demo interattiva sviluppata in Streamlit per la predizione del rischio cardiovascolare basata su variabili cliniche e genetiche, inclusa la presenza di mutazioni CHIP (DNMT3A, TET2, ASXL1).

## 🧠 Modello

Il modello è un classificatore Gradient Boosting allenato su dati sintetici ma realistici, che tiene conto di:

- Età
- CRP, BMI, Colesterolo, NLR, PLR
- Mutazioni CHIP e rispettivo VAF
- CHIP burden calcolato

## 🚀 Come eseguirlo in locale

### 1. Crea ambiente virtuale (opzionale ma consigliato)

```bash
python3 -m venv venv
source venv/bin/activate
```

### 2. Installa dipendenze

```bash
pip install -r requirements.txt
```

### 3. Avvia Streamlit

```bash
streamlit run streamlit_app.py
```

## 🌐 Come pubblicarlo online (Streamlit Cloud)

1. Crea un repository pubblico su GitHub
2. Carica:
   - `streamlit_app.py`
   - `modello_finale.pkl`
   - `requirements.txt`
   - `LICENSE`
   - `README.md`
3. Vai su [https://streamlit.io/cloud](https://streamlit.io/cloud)
4. Collegati con GitHub e seleziona il repository
5. Clicca “Deploy”

## 📄 Licenza

Distribuito con licenza MIT (vedi file `LICENSE`).

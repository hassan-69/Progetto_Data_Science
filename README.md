# 📊 Progettino – Generazioni Social

## 🎯 Obiettivo del progetto
Analizzare l'utilizzo dei social media (Instagram, TikTok, Facebook e LinkedIn) tra diverse generazioni (Gen Z, Millennials, Gen X) e identificare pattern comuni tramite tecniche di clustering.  
Il progetto è stato realizzato nell’ambito del corso **“Fondamenti di Scienza dei Dati e Laboratorio” – A.A. 2024/25**.

---

## 🧵 Domande di ricerca
- Quale generazione utilizza di più TikTok e quale Instagram?
- Esistono differenze significative tra le abitudini delle generazioni?
- È possibile identificare gruppi di utenti simili nel comportamento digitale?

---

## 📁 Contenuto della repository

| File/Cartella                    | Descrizione                                                  |
|----------------------------------|--------------------------------------------------------------|
| `Progettino_Generazioni_Social.ipynb` | Notebook Jupyter completo con analisi e clustering          |
| `social_media_generations.csv`  | Dataset realistico ispirato a dati pubblici                 |
| `requirements.txt`              | Librerie Python necessarie per eseguire il notebook         |
| `README.md`                     | Questo file                                                  |

---

## 📊 Dataset
Dataset simulato ispirato a survey pubblici, contenente:
- `Age`, `Gender`
- Ore settimanali di utilizzo per: Instagram, TikTok, Facebook, LinkedIn
- Classificazione generazionale (`Gen Z`, `Millennials`, `Gen X`)

---

## 🧪 Tecniche utilizzate
- Pulizia e categorizzazione dei dati
- Statistiche descrittive e visualizzazione (Seaborn, Matplotlib)
- Clustering non supervisionato (PCA + KMeans)

---

## 📈 Risultati principali
- Gen Z è il gruppo più attivo su TikTok
- Millennials bilanciano Instagram e LinkedIn
- Gen X è più attiva su Facebook
- Tre cluster principali emergono dai dati:
  - Social addicted (TikTok/Instagram)
  - Equilibrati
  - Tradizionali (Facebook/LinkedIn)

---

## 📌 Requisiti
Vedi `requirements.txt` oppure installa con:

```
pip install pandas matplotlib seaborn scikit-learn
```

---

## 📬 Consegna
- Repository pubblica GitHub
- Link inviato tramite modulo ufficiale (o mail solo se necessario)

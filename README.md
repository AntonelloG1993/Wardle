# 🎮 Wordle Game in Python | Wardle

> Repository by [AntonelloG1993](https://github.com/AntonelloG1993)

---
Un semplice **clone del gioco Wordle**, interamente realizzato in **Python**, con integrazione API per generare parole casuali, salvataggio e aggiornamento delle **statistiche di gioco**, e visualizzazione grafica dei risultati tramite **Matplotlib**.

---
## 🚀 Funzionalità principali

- 🎮 Gioco interattivo da terminale (CLI)
- 🧠 Generazione di parole casuali tramite **WordsAPI**
- 📊 Salvataggio automatico delle statistiche in un file `.json`
- 📈 Visualizzazione delle prestazioni con grafico a barre (Matplotlib)
- ✅ Controllo e colorazione dinamica delle lettere (verde, giallo, grigio)
- 💾 Sistema di caricamento e aggiornamento continuo delle statistiche

---
### 🧰 Librerie utilizzate

- **Python 3.x**
- **Requests**
- **Colorama**
- **Matplotlib**
- **JSON**
- **WordsAPI**

---
Durante la partita, il programma fornisce feedback colorato:
- 🟩 **Verde** → lettera nella posizione corretta  
- 🟨 **Giallo** → lettera presente ma in posizione errata  
- ⬜ **Grigio** → lettera non presente nella parola  

---
### 📊 Statistiche di gioco

Ogni partita aggiorna automaticamente il file `wordle.stats`, contenente il numero di tentativi impiegati per indovinare la parola.  
Le statistiche possono essere visualizzate in due modalità:
- In console (con caratteri `X`)
- Con grafico a barre tramite **matplotlib**

---
## 🧩 Struttura del progetto

📁 Wordle-Python
│
├── main.py # File principale del gioco
├── wordle.stats # File generato automaticamente con le statistiche
├── requirements.txt # Librerie necessarie (vedi sezione installazione)
└── README.md # Documentazione del progetto


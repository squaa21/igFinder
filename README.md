# igFinder 🔍

> Scopri chi non ti segue su Instagram — senza login, senza app di terze parti, senza dare la tua password a nessuno.

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-squaa21.github.io/igFinder-E1306C?style=for-the-badge)](https://squaa21.github.io/igFinder)
[![Licenza](https://img.shields.io/badge/Licenza-MIT-blue?style=for-the-badge)](LICENSE)
[![HTML](https://img.shields.io/badge/HTML-puro-orange?style=for-the-badge&logo=html5&logoColor=white)](index.html)
[![Privacy](https://img.shields.io/badge/Privacy-100%25_locale-green?style=for-the-badge)](#privacy)

---

## ✨ Funzionalità

- **Carica i file JSON** esportati direttamente da Instagram (nessun login richiesto)
- **Incolla manualmente** le liste di followers e following
- **Scopri chi non ti segue** back in un click
- **Cerca username specifici** e vedi subito il loro stato
- **Statistiche** su followers, following e account mutui
- **100% privato** — tutto elaborato nel browser, zero dati inviati a server

---

## 🚀 Come si usa

### Metodo 1 — File JSON (consigliato)

Instagram ti permette di scaricare i tuoi dati senza usare app esterne:

1. Apri Instagram → **Impostazioni e privacy** → **Attività** → **Scarica le tue informazioni**
2. Seleziona **Alcuni tuoi dati** e spunta solo **Followers** e **Following**
3. Scegli il formato **JSON** e premi **Crea file**
4. Scarica il file `.zip` quando arriva la notifica (può volerci fino a 48h)
5. Estrai lo zip e trascina `followers_1.json` e `following.json` su igFinder

### Metodo 2 — Incolla testo

Copia e incolla manualmente la lista degli username direttamente nella webapp.

---

## 🛡️ Privacy

igFinder è una **single-page app statica**. Non ha backend, non ha database, non manda nessun dato in rete. Tutto avviene nel tuo browser — puoi anche usarla offline dopo averla caricata una volta.

---

## 🗂️ Struttura del progetto

```
igFinder/
├── index.html       # L'intera applicazione (HTML + CSS + JS)
└── README.md        # Questo file
```

---

## 🛠️ Sviluppo locale

Non serve nessun tool. Clona il repo e apri il file:

```bash
git clone https://github.com/squaa21/igFinder.git
cd igFinder
open index.html   # oppure trascina il file nel browser
```

---

## 🤝 Contribuire

Pull request benvenute! Se hai idee per nuove funzionalità o trovi un bug, apri una [Issue](https://github.com/squaa21/igFinder/issues).

1. Fai un fork del progetto
2. Crea un branch (`git checkout -b feature/nuova-funzione`)
3. Commit delle modifiche (`git commit -m 'Aggiunge nuova funzione'`)
4. Push al branch (`git push origin feature/nuova-funzione`)
5. Apri una Pull Request

---

## 📋 Roadmap

- [ ] Esporta lista in CSV
- [ ] Storico — vedi chi ti ha tolto il follow nel tempo
- [ ] Supporto multilingua (EN, ES, FR)
- [ ] Statistiche avanzate
- [ ] Dark / light mode toggle

---

## 📄 Licenza

Distribuito sotto licenza MIT. Vedi [`LICENSE`](LICENSE) per i dettagli.

---

<p align="center">Fatto con ❤️ — nessun dato raccolto, mai.</p>

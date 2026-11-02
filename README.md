# BrainBox — Progetto di Interazione Uomo-Macchina

Questo repository contiene la relazione e i sorgenti LaTeX del progetto per il corso di **Interazione Uomo-Macchina** (Prof.ssa Daniela Fogli, Università degli Studi di Brescia — A.A. 2025/2026).

---

### In breve 🎯

Abbiamo preso in esame **BrainBox**, una piattaforma web pensata per aiutare gli studenti universitari a organizzare lo studio (appunti, trascrizioni audio delle lezioni con AI, sintesi vocale e gestione degli esami). 

L'obiettivo del progetto è stato analizzarne l'usabilità da cima a fondo, riprogettarne l'interfaccia e l'esperienza utente seguendo i principi dello **Human-Centred Design**, e infine verificare sul campo l'efficacia delle modifiche attraverso test con utenti reali.

Il risultato più significativo? Nei test con 15 studenti universitari, il punteggio di usabilità percepita (**SUS - System Usability Scale**) è passato da **47.7** (*insufficiente*) a **81.3** (*eccellente*).

---

### Cosa abbiamo fatto 🛠️

1. **Capire chi usa il sistema**: abbiamo delineato il profilo dello studente universitario medio e creato 5 *Personas* con abitudini, ritmi e bisogni differenti.
2. **Trovare i problemi (Valutazione Euristica)**: con 3 valutatori indipendenti e le 10 euristiche di Nielsen, abbiamo individuato e catalogato **93 problemi di usabilità** nell'interfaccia originale.
3. **Riprogettare l'esperienza**: 
   - Abbiamo ridefinito i flussi con *Task Analysis* e scenari d'uso.
   - Abbiamo applicato i design pattern di Jennifer Tidwell e i principi della Gestalt.
   - Abbiamo introdotto prototipi su Figma e riorganizzato la web app: navigazione più chiara, strumenti AI integrati direttamente negli appunti, calendario e notifiche accessibili ovunque, e form guidati passo-passo.
4. **Mettere alla prova il redesign (Test con Utenti)**: abbiamo condotto un esperimento controllato *within-subjects* su 15 partecipanti, misurando tempi, errori, commenti qualitativi e punteggi SUS a confronto tra la vecchia e la nuova versione.

---

### Il Report 📄

Se vuoi leggere direttamente l'elaborato completo con tutti i dettagli, le tabelle dei problemi e i grafici:
* Il PDF già compilato si trova in **[`out/main.pdf`](file:///tmp/elaborato-HCI/out/main.pdf)**.

#### Vuoi compilarlo dai sorgenti?
Basta avere una distribuzione TeX (TeX Live o MacTeX) e lanciare da terminale:

```bash
latexmk -pdf -outdir=out main.tex
```

oppure con `pdflatex`:

```bash
mkdir -p out && pdflatex -output-directory=out main.tex
```

---

### Struttura della repository 📂

* `main.tex` & `premable.tex` — documento principale e pacchetti.
* `01-introduzione.tex` — presentazione di BrainBox e dell'architettura del sito.
* `02-profilo-utente.tex` — caratteristiche degli utenti e schede delle Personas.
* `03-valutazione-euristica.tex` e `valutazione-euristica/` — problemi catalogati, curva di Nielsen e statistiche.
* `04-riprogettazione.tex` e `riprogettazione/` — scelte di design, pattern applicati e screenshot del nuovo sito.
* `05-esperimento-utenti.tex` e `esperimento-utenti/` — metodologia del test, compiti e protocollo.
* `06-analisi-dati.tex` e `analisi-dati/` — tempi, errori, questionario SUS e analisi statistica.
* `07-sviluppi-futuri.tex` — idee e prossimi passi per la piattaforma.
* `figures/` e `Screenshots/` — immagini, grafici vettoriali TikZ e mockup.

---

### Autori 🎓

Studenti del corso di Laurea in Ingegneria Informatica — **Università degli Studi di Brescia**:
* **Okba Kharef**
* **Matteo Legati**
* **Simone Rinaldi**

Docente: **Prof.ssa Daniela Fogli**

# Elaborato di Sicurezza del Software — UniVr

Report scritto in LaTeX per il corso di Sicurezza del Software (Magistrale, Università di Verona).

**Titolo:** La sicurezza nelle console di gioco  
**Autori:** Marica Bottega, Enrico Cicciarella

## Struttura

```
report latex/   # Sorgenti LaTeX del report
  main.tex      # File principale
  *.tex         # Capitoli (introduzione, memory corruption, crittografia white-box, fault injection, architetture moderne, conclusione)
  img/          # Immagini
fonti/          # PDF delle fonti bibliografiche
```

## Argomenti trattati

- Memory corruption (buffer overflow, vulnerabilità classiche)
- Crittografia white-box
- Fault injection
- Architetture di sicurezza moderne nelle console

## Compilazione

Compilare con `pdflatex` o `latexmk` dalla cartella `report latex/`:

```bash
latexmk -pdf main.tex
```

Il PDF compilato è disponibile in `report latex/main.pdf`.

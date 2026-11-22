# Intelligenza Artificiale

Appunti del corso di **Intelligenza Artificiale**, basati sul libro *Artificial Intelligence: A Modern Approach* (Russell & Norvig).

📄 **[Apri gli appunti in PDF](notes_from_slides/notes_from_slides.pdf)**

## Contenuto

| Percorso | Descrizione |
| --- | --- |
| `notes_from_slides/` | Appunti in LaTeX ricavati dalle slide del corso, con il PDF compilato |
| `hand_notes.xopp` | Appunti scritti a mano (Xournal++) |
| `local_search.xopp` | Appunti a mano sulla ricerca locale (Xournal++) |

## Argomenti trattati

**Agenti logici** (AIMA cap. 7)
- Knowledge base, entailment e inferenza
- Logica proposizionale: sintassi, semantica, equivalenze
- Validità, soddisfacibilità, teorema di deduzione e refutazione
- Risoluzione e forma normale congiuntiva
- Forward e backward chaining con clausole di Horn

**Rappresentare l'incertezza** (AIMA cap. 12)
- Probabilità come grado di credenza e teoria delle decisioni (MEU)
- Variabili aleatorie, eventi atomici, distribuzione congiunta
- Probabilità condizionata, regola del prodotto e della catena
- Inferenza per enumerazione e normalizzazione
- Indipendenza, indipendenza condizionata e regola di Bayes
- Il mondo del Wumpus in condizioni di incertezza

## Compilare gli appunti

Serve una distribuzione LaTeX completa (ad esempio TeX Live).

```bash
cd notes_from_slides
latexmk -pdf notes_from_slides.tex
```

## Laboratorio

Il materiale del laboratorio si trova nel repository [Isla-lab/AI_Lab](https://github.com/Isla-lab/AI_Lab). La copia locale (`AI_Lab/`) è esclusa da questo repository tramite `.gitignore`.

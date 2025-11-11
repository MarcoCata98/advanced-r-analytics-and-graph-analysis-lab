# Advanced R Analytics & Graphs

Benvenuto nel mio laboratorio personale di **analisi avanzata dei dati e network science** sviluppato interamente in **R**.  
Qui raccolgo, organizzo e perfeziono tutte le mie analisi – dai grafi complessi ai dataset reali – mettendo insieme:

- competenze di **statistica**,  
- tecniche di **analisi delle reti** (sociali, infrastrutturali, gerarchiche),  
- metodi di **data visualization** professionale,  
- e un workflow pulito e riproducibile basato su *tidyverse*.

L’obiettivo è costruire nel tempo una **collezione crescente e strutturata** di progetti che mostrano:
- come approccio un problema di analisi,
- come organizzo i dati,
- come valuto metriche diverse (power, centralità, distribuzioni…),
- e come presento risultati chiari e leggibili tramite R Markdown.

È un repository pensato per crescere con me: ogni nuova analisi, dataset o grafo complesso avrà qui il suo spazio.

---

## 📌 Contenuti principali del repository

### 👉 Analisi su grafi complessi (Network Science)
- **Rete sociale dei delfini** (dati reali su un gruppo animale → centralità, comunità, ruoli, hub)
- **Gasdotti europei** (rete infrastrutturale → hub, misure di potere, percorsi minimi, distanze)
- Tecniche usate:
  - PageRank, Eigenvector, Katz
  - Bonacich Power e β-power
  - Community detection (Louvain / Walktrap)
  - Layout ggraph + estetiche multilivello

### 👉 Analisi statistiche ed EDA
- ELO ranking e metodi correlati
- Confronto distribuzioni (ECDF, istogrammi, densità)
- Normalizzazioni, ranking, scaling

### 👉 Report Markdown
Ogni progetto contiene codice **riproducibile**, grafici, tabelle e spiegazioni discorsive.

## Requisiti
- R >= 4.2
- RStudio (consigliato)
- Pacchetti principali: `tidyverse`, `readr`, `janitor`, `glue`,
  `igraph`, `tidygraph`, `ggraph`, `gridExtra`, `knitr`, `rmarkdown`,
  `patchwork`, `scales`, `here`, `arrow`, `vroom`, `renv`

> Tutto è gestito con `renv` per garantire versioni coerenti.


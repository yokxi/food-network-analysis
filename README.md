# 🥘 Computational Gastronomy: Network Analysis of Catalan Cuisine

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![NetworkX](https://img.shields.io/badge/Library-NetworkX-green?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-success)

Questo progetto applica tecniche di **Network Science** e **Computational Gastronomy** per analizzare l'evoluzione della cucina catalana. L'obiettivo è confrontare la struttura topologica delle ricette tradizionali con quella dell'Alta Cucina moderna (rappresentata dal ristorante *El Celler de Can Roca*), modellando le ricette come una rete complessa basata sulla condivisione degli ingredienti.

---

## 🎯 Obiettivi

Lo studio risponde alla domanda: *L'innovazione culinaria radicale frammenta la tradizione o ne rappresenta un'evoluzione coesa?*

Attraverso l'analisi dei grafi, il progetto esplora:
* **Topologia della rete:** Densità, grado medio, clustering coefficient.
* **Backbone Extraction:** Identificazione dello "scheletro" essenziale dei sapori tramite *Maximum Spanning Tree (MST)*.
* **Community Detection:** Analisi della modularità per individuare cluster di ricette.
* **Robustezza:** Simulazione di attacchi alla rete rimuovendo gli ingredienti principali (Hub).

---

## 📂 Struttura del Repository

```text
├── 📓 main.ipynb             # Notebook Jupyter principale con tutto il codice di analisi
├── 📂 db/                    # Dataset (Matrici di adiacenza e liste nomi)
│   ├── 101_mat_ricette_output.txt
│   ├── Roca_mat_ricette_output.txt
│   ├── Ctrad_mat_ricette_substitution_output.txt
│   └── RecipeID_name_list_Ctrad.txt
├── 📂 assets/
│   └── 📂 images/            # Grafici generati (Backbone, Robustezza, ecc.)
└── 📄 README.md              # Documentazione del progetto
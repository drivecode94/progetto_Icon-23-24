# Progetto Ingegneria della conoscenza A.A. 2023-2024 

**Gruppo di lavoro**

-	Nicola Guida, 745142, n.guida2@studenti.uniba.it 

# FASE INIZIALE

**Installare SWIProlog** (installare la versione a 64 bit) 

https://www.swi-prolog.org/download/stable/bin/swipl-8.2.4-1.x64.exe.envelope 

**Clonare il repository dal prompt dei comandi:**


**Creare l'ambiente virtuale:** 

 cd progetto-icon23-24 

 python -m venv progetto-icon23-24 

**Installare le dipendenze:** 

 pip install -r requirements.txt 

# Esecuzione del codice 
**Preprocessing:** 

 python preprocessing\cleaning_datasets.py datasets\film.csv 

**Creazione dei cluster:**

 python clustering\clustering.py datasets\dataset_clustering.csv [n_cluster] [n_iter]

**Creazione Knowledge Base:**

 python kb\kb.py datasets\dataset_prolog.csv
 
**Creazione Bayesian Network:**

 python bn/ui.py 

 


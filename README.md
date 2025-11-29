# Knowledge Graph Completion — MS Research Lab

This repository template organizes datasets, notebooks, code, literature and experiments for Master-level projects on Knowledge Graph Completion (KGC).

## Repository structure

```plaintext
knowledge-graph-completion/
│
├── README.md
│
├── data/
│   ├── raw/                 # Raw datasets (FB15k, WN18, custom KG)
│   ├── processed/           # Cleaned & preprocessed triples
│   └── description.txt      # Explain data sources
│
├── notebooks/
│   ├── 01_Data_Preprocessing.ipynb
│   ├── 02_Embedding_Models.ipynb
│   ├── 03_Model_Training.ipynb
│   ├── 04_Evaluation.ipynb
│   └── 05_Visualization.ipynb
│
├── src/
│   ├── models/              # TransE, DistMult, ComplEx, RotatE implementations
│   ├── utils/               # Helper functions
│   ├── data_loader.py
│   ├── trainer.py
│   └── evaluate.py
│
├── literature/
│   ├── papers/              # PDF research papers
│   └── summaries/           # Student’s weekly summaries (in markdown)
│
├── experiments/
│   ├── exp1_transe/
│   ├── exp2_distmult/
│   └── exp3_rgcn/
│
├── results/
│   ├── metrics/             # MRR, Hits@10, etc.
│   └── plots/               # Loss curves, embeddings visualization
│
└── requirements.txt         # Python libraries

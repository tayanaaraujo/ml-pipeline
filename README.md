# ml-pipeline

Este repositório contém uma pipeline automatizada de ML usando GitHub Actions. A cada push, o workflow executa o script `train.py`, que treina um modelo de classificação e gera um relatório com acurácia, precisão, recall e F1-score, salvo como `report.txt`.

Criamos a seguinte estrutura:
├── data/sample.csv
├── train.py
├── requirements.txt
└── .github/workflows/ml.yml

## Workflow
- **Etapas principais:**
  1. Configuração do Python
  2. Instalação das dependências
  3. Treinamento do modelo (`train.py`)
  4. Upload do relatório (`report.txt`) como artefato

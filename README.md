# FIAP Postech — IA para Devs

Repositório com notebooks e códigos desenvolvidos durante a pós-graduação **IA para Devs** da FIAP Postech (FIAP + Alura).

## Sobre o curso

O programa tem carga horária total de **360h** e cobre desde os fundamentos de Machine Learning até tópicos avançados como LLMs, IA Generativa e deploy em nuvem (AWS/Azure).

**Avaliação:** Tech Challenge (60pts) + Hackathon (30pts) + Atividade Presencial (10pts) — aprovação com nota ≥ 70.

## Notebooks

| # | Notebook | Tópicos |
|---|----------|---------|
| 01 | [breast_cancer_ml.ipynb](breast_cancer_ml.ipynb) | Classificação, KNN/SVM, métricas (Recall, AUC, ROC), SHAP |
| 02 | [02_regressao_linear.ipynb](02_regressao_linear.ipynb) | Regressão Linear/Múltipla, Feature Scaling, Ridge/Lasso, MAE/MSE/R² |
| 03 | [03_clustering_kmeans_pca.ipynb](03_clustering_kmeans_pca.ipynb) | K-Means, Elbow Method, Silhouette Score, PCA |
| 04 | [04_huggingface_publicar_modelo.ipynb](04_huggingface_publicar_modelo.ipynb) | Hugging Face Hub, publicação de modelos sklearn, model card |
| 05 | [05_computer_vision_cnn_ocr.ipynb](05_computer_vision_cnn_ocr.ipynb) | CNN, Transfer Learning (ResNet/MobileNet), OCR, YOLO, GANs |

## Matriz Curricular

| Disciplina | Carga Horária |
|------------|--------------|
| Fundamentos de Inteligência Artificial | 20h |
| Machine Learning | 21h |
| Machine Learning Avançado | 32h |
| Processamento de Linguagem Natural | 21h |
| Introdução ao Algoritmo Genético | 22h |
| Desenvolvimento de ML na Cloud | 28h |
| Desvendando o Poder dos LLMs | 28h |
| IAs Generativas | 21h |
| O Chat-GPT: como extrair o máximo | 28h |
| Fine-Tuning para Documentos | 18h |
| Análise de Vídeo, Áudio e Texto | 23h |
| TextStract + Comprehender (AWS) | 23h |
| Open API | 12h |
| Privacidade e Proteção de Dados | 20h |
| Análise de Documentos com Serviços do Azure | 43h |

## Stack

- Python 3.11+
- scikit-learn, pandas, numpy, matplotlib, seaborn
- TensorFlow / PyTorch
- Hugging Face Transformers
- OpenCV, Tesseract (OCR)
- AWS (Textract, Comprehend), Azure Cognitive Services

## Setup

```bash
pip install scikit-learn pandas numpy matplotlib seaborn
```

Dependências específicas de cada notebook estão na célula de instalação no topo do arquivo.

# ❤️ Predição de Óbito em Pacientes com Insuficiência Cardíaca utilizando KNN e Random Forest

## 📖 Sobre o projeto

Este repositório contém a implementação desenvolvida para a disciplina de **Sistemas Inteligentes**, com o objetivo de comparar o desempenho dos algoritmos **K-Nearest Neighbors (KNN)** e **Random Forest** na predição de óbito em pacientes com insuficiência cardíaca.

Os modelos foram treinados utilizando dados clínicos e avaliados por diferentes métricas de classificação, permitindo analisar sua capacidade de identificar pacientes com maior risco de óbito.

---

## 📊 Base de dados

O estudo utiliza a base **Heart Failure Clinical Records Dataset**, composta por registros clínicos de pacientes com insuficiência cardíaca.

### Variáveis utilizadas

| Variável | Descrição |
|----------|-----------|
| Age | Idade do paciente |
| Ejection Fraction | Fração de ejeção |
| Serum Creatinine | Creatinina sérica |
| Serum Sodium | Sódio sérico |
| Creatinine Phosphokinase | Creatina fosfoquinase (CPK) |

### Variável alvo

| Classe | Significado |
|--------|-------------|
| **0** | Paciente sobreviveu |
| **1** | Paciente foi a óbito |

---

## ⚙️ Pré-processamento

Antes do treinamento dos modelos, foram realizadas as seguintes etapas:

- Seleção das variáveis utilizadas no estudo;
- Divisão da base em conjuntos de treinamento e teste;
- Padronização dos atributos utilizando **StandardScaler (Z-score Standardization)** para o algoritmo KNN.

---

## 🤖 Algoritmos

- K-Nearest Neighbors (KNN)
- Random Forest

---

## 📈 Métricas de avaliação

Os algoritmos foram comparados utilizando as seguintes métricas:

- ✅ Acurácia
- ✅ Precisão (Precision)
- ✅ Revocação (Recall)
- ✅ F1-score
- ✅ Matriz de Confusão
- ✅ Curva ROC
- ✅ Área sob a Curva (AUC)

---

## 🛠️ Tecnologias utilizadas

- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Estrutura do projeto

```text
📦 heart-failure-knn-random-forest
├── 📄 heart_failure_clinical_records_dataset.csv
├── 📓 insuficiencia_cardiaca.ipynb
└── 📄 README.md
```

## 🚀 Como executar

### Requisitos

- Python 3.10 ou superior
- Jupyter Notebook ou JupyterLab

### Instalação das bibliotecas

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### Execução

Inicie o Jupyter Notebook:

```bash
jupyter notebook
```

Em seguida, abra o notebook:

```text
notebooks/insuficiencia_cardiaca.ipynb
```

---

## 🎯 Objetivo

Comparar o desempenho dos algoritmos **KNN** e **Random Forest** na classificação de pacientes quanto ao risco de óbito por insuficiência cardíaca, utilizando dados clínicos e métricas de avaliação para analisar a qualidade dos modelos.

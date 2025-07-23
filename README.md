# 🐶🐱 Transfer Learning - Classificação de Gatos e Cachorros

Este projeto demonstra como utilizar **Transfer Learning** com o modelo pré-treinado **MobileNetV2** para classificar imagens em duas categorias: **gatos** e **cachorros**. O modelo é treinado e testado usando o dataset `cats_vs_dogs` do TensorFlow Datasets.

classificador-caes-gatos-transfer-learning
---

## 📌 Objetivos

- Usar Transfer Learning com MobileNetV2.
- Classificar imagens de gatos e cachorros.
- Treinar um modelo com baixo custo computacional.
- Publicar o código no GitHub de forma organizada.

---

## 🧠 Tecnologias Utilizadas

- Python 🐍
- TensorFlow 2.x
- TensorFlow Datasets
- Google Colab
- Git & GitHub

---

## 📁 Estrutura do Projeto
transfer-learning-dogs-vs-cats/
├── main.py # Código principal com o pipeline completo
├── README.md # Documentação do projeto
---

## 🚀 Como Executar

### ▶️ No Google Colab
Você pode executar este projeto diretamente no (https://colab.research.google.com/drive/1vf3g3LreXRS-S9AU5ypo1MhOj17kJzvy?authuser=0#scrollTo=l2KCUzEyiJEf):

1. Copie o conteúdo de `main.py` para um novo notebook.
2. Execute célula por célula.

### 💻 Localmente (requer GPU)

```bash
# Clonar o repositório
git clone https://github.com/wricardo81/transfer-learning-dogs-vs-cats.git
cd transfer-learning-dogs-vs-cats

# Criar ambiente virtual (opcional)
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows

# Instalar dependências
pip install tensorflow matplotlib tensorflow-datasets

# Executar
python main.py

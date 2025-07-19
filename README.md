House Pricing Project / Projeto de Previsão de Preço de Casas
📌 Description 
EN:
This project aims to build a simple regression model to predict house prices based on the dataset from Kaggle's House Prices competition. I used both manual gradient descent (with custom functions for cost, gradients, and updates) and the LinearRegression model from scikit-learn for comparison purposes.
The project focuses on using only one feature (OverallQual) to predict SalePrice, helping me understand the core concepts of linear regression and gradient descent from scratch.

Descrição(PT-BR):
Este projeto tem como objetivo construir um modelo de regressão simples para prever preços de casas utilizando o dataset da competição House Prices do Kaggle. Eu utilizei tanto o gradient descent manual (com funções customizadas para custo, gradientes e atualizações), quanto o modelo LinearRegression da biblioteca scikit-learn para fins de comparação.
O foco foi utilizar apenas uma variável (OverallQual) para prever o SalePrice, ajudando no entendimento prático dos conceitos de regressão linear e gradiente descendente do zero.

🧰 Tools and Libraries | Ferramentas e Bibliotecas
Python 3.x
Pandas
Numpy
Matplotlib
Seaborn
Scikit-Learn

📁 Project Structure | Estrutura do Projeto
bash
Copiar
Editar
📂 house_pricing/
│
├── 📄 Notebook.ipynb          # Main notebook with all experiments
├── 📄 README.md               # Project description
└── 📁 data/                   # Dataset (train.csv)
🎯 Goals | Objetivos
✅ Implement linear regression using Gradient Descent manually
✅ Compare results with Scikit-Learn LinearRegression
✅ Visualize convergence of cost function
✅ Evaluate model performance using MSE and R² metrics

✅ Implementar regressão linear com Gradiente Descendente manual
✅ Comparar resultados com o LinearRegression do Scikit-Learn
✅ Visualizar a convergência da função de custo
✅ Avaliar desempenho do modelo usando MSE e R²

🚀 How to Run | Como Rodar
bash
Copiar
Editar
# Clone the repository
git clone https://github.com/albertmarques7/TecnicasMachineLearning.git

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook Notebook.ipynb
📊 Results | Resultados
EN:

Gradient Descent reached a cost minimization comparable to Scikit-Learn.
Model performance with just one feature achieved around 65%-80% R².

PT-BR:

O Gradiente Descendente atingiu uma minimização de custo similar ao Scikit-Learn.
Com apenas uma feature, o modelo alcançou cerca de 65%-80% de R².

✍️ Author | Autor
👤 Alberto Marques
Project for learning Machine Learning fundamentals and improving regression understanding.
Projeto focado em aprender os fundamentos de Machine Learning e aprimorar o entendimento de regressão.








Perguntar ao ChatGPT



Ferramentas



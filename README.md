🏥 Medical Charges ML

Este projeto visa automatizar o processo de precificação de planos de saúde com base em dados demográficos e comportamentais de pacientes. Utilizando técnicas de Machine Learning, buscamos estimar os custos médicos individuais para auxiliar na definição de preços mais justos e personalizados.

📁 Estrutura do Repositório

medical-charges-ml/

├── datasets/

│   └── insurance.csv           # Dados de entrada

├── medical-cost.ipynb          # Notebook com análise e modelagem

└── README.md                   # Este arquivo

📊 Descrição do Dataset

O dataset utilizado contém as seguintes colunas:

age: Idade do paciente

sex: Sexo do paciente (male/female)

bmi: Índice de Massa Corporal

children: Número de filhos dependentes

smoker: Se o paciente é fumante (yes/no)

region: Região geográfica

charges: Custo médico anual (variável alvo)

⚙️ Tecnologias Utilizadas

Python 3.x

Pandas: Manipulação e limpeza de dados

NumPy: Operações matemáticas

Matplotlib & Seaborn: Visualizações gráficas

Scikit-learn: Modelagem preditiva (Random Forest Regressor)

Jupyter Notebook: Ambiente interativo para desenvolvimento

🚀 Como Executar

Clone o repositório:

git clone https://github.com/guilhermeej/medical-charges-ml.git
cd medical-charges-ml

Instale as bibliotecas necessárias (se ainda não tiver):

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

Abra o notebook:

jupyter notebook medical-cost.ipynb

Execute as células para realizar a análise e modelagem.

📈 Resultados Esperados

Análise exploratória dos dados (EDA)

Visualizações das distribuições e correlações

Construção e avaliação de um modelo preditivo para estimar os custos médicos

🔄 Próximos Passos

Implementar validação cruzada para avaliar a robustez do modelo

Explorar outros algoritmos de regressão (ex: Linear Regression, SVR)

Integrar o modelo em uma aplicação web para uso interativo

📄 Licença

Este projeto está licenciado sob a MIT License

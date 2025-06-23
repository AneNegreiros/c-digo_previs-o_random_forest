# código_previsão_random_forest
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AneNegreiros/c-digo_previs-o_random_forest/tree/main/HEAD)

# 🧠 Previsão de Comportamento de Usuários no Chatbot com NLP & Random Forest

Este repositório acompanha o artigo publicado no Medium sobre **“10 passos para utilizar Machine Learning para prever comportamentos do usuário no chatbot”**. O objetivo é prever a próxima jornada do usuário após uma falha de entendimento do chatbot, utilizando técnicas de Processamento de Linguagem Natural (NLP) e o algoritmo Random Forest.

🔗 **Leia o artigo completo:**  
[👉 10 passos para utilizar Machine Learning para prever comportamentos do usuário no chatbot](https://medium.com/@contatoanefreitas/10-passos-para-utilizar-machine-learning-para-prever-comportamentos-do-usu%C3%A1rio-no-chatbot-013e75c8fc77)

**🎯 Objetivo**
- Automatizar a análise de grandes volumes de interações em chatbots
- Prever a próxima jornada do usuário após uma falha (“Não Entendeu”)
- Identificar padrões comportamentais sem viés e com escalabilidade

🚀 Como Usar
Siga os passos abaixo para executar o projeto localmente:

**Clone este repositório:**
git clone https://github.com/AneNegreiros/c-digo_previs-o_random_forest.git
cd c-digo_previs-o_random_forest

**Instale as dependências:**
pip install -r requirements.txt

**Execute o notebook:**
Abra o arquivo codigo_para_previsao.ipynb no Jupyter Notebook, JupyterLab ou Google Colab e siga os passos conforme descrito.

**🔍 O que o projeto faz:**
- Carrega e limpa dados de interações de chatbot
- Cria uma coluna texto_completo com contexto de cada interação
- Realiza rotulagem manual parcial para treinar o modelo
- Vetoriza os textos com CountVectorizer e remove stopwords
- Treina o modelo RandomForestClassifier para prever jornadas
- Aplica previsões a registros não rotulados
- Exporta os resultados em formato .xlsx para validação posterior
  
**🛠️ Tecnologias Utilizadas**
- Python 3.x
- Pandas
- Scikit-learn
- NLTK
- Jupyter Notebook

📬 Contato
Este projeto foi desenvolvido por Ane Isabel N. Freitas
📨 @contatoanefreitas
⭐ Se este projeto te ajudou, não esqueça de deixar uma estrela no repositório!

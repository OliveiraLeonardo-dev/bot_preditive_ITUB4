📈 Modelo de Predição de Movimentação de Ações (ITUB4)

🎯 Objetivo

Notebook de predição D+1 para a ação ITUB4 (Itaú Unibanco), utilizando dados históricos da Yahoo Finance.

1 → previsão de alta (possível venda)

0 → previsão de baixa (manter ou comprar)

O modelo utiliza uma janela de 5 anos de dados históricos, mas pode ser adaptado para outras ações.

💻 O que contém o notebook

Extração de dados via Yahoo Finance API

Limpeza e tratamento de dados com Pandas

Feature engineering e criação de indicadores financeiros

Treinamento de modelo de classificação com Scikit-learn

Avaliação de performance e análise de predições

📂 Arquivo disponível

Modelo_FIAP.ipynb → notebook principal, pronto para execução e reprodução dos resultados.

⚡ Como usar

Abra o notebook no Jupyter Notebook ou Jupyter Lab.

Instale as dependências:

pip install pandas scikit-learn yfinance matplotlib


Execute as células do notebook na ordem para reproduzir a extração, treinamento e predições.

🚀 Possíveis melhorias

Tornar o notebook multi-ativo, replicando o modelo para outras ações.

Testar modelos avançados como XGBoost ou LightGBM.

Criar dashboards de visualização para acompanhamento das predições.

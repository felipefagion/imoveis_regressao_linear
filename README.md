# Análise de Aluguéis de Imóveis no Brasil 🏘️

Este projeto tem como objetivo analisar dados de imóveis para aluguel no Brasil, com foco em variáveis como cidade, área, número de quartos, banheiros, vagas de garagem, e mais. A análise busca entender quais fatores influenciam no preço total do aluguel e aplicar um modelo de machine learning para prever esse valor.

## 📂 Fonte dos Dados
- **Brazilian Houses to Rent Dataset**:  
  Disponível no Kaggle: [Brazilian Houses to Rent](https://www.kaggle.com/datasets/rubenssjr/brasilian-houses-to-rent)

## 📊 Variáveis Analisadas
- **city**: Cidade onde o imóvel está localizado.
- **area**: Área do imóvel em metros quadrados (m²).
- **rooms**: Número de quartos no imóvel.
- **bathroom**: Número de banheiros.
- **parking spaces**: Número de vagas de garagem.
- **floor**: Número do andar do imóvel.
- **animal**: Permissão para animais domésticos (Sim/Não).
- **furniture**: Imóvel mobiliado ou não (Sim/Não).
- **hoa (R$)**: Valor da taxa de condomínio.
- **rent amount (R$)**: Valor do aluguel mensal.
- **property tax (R$)**: Valor do IPTU.
- **fire insurance (R$)**: Valor do seguro contra incêndio.
- **total (R$)**: **Variável Alvo**, representando o valor total do aluguel (inclui condomínio, aluguel e taxas).

## 💻 Linguagem Utilizada

- **Python**

## 📚 Bibliotecas Utilizadas

- **Pandas**: Para tratamento de dados.
- **Numpy**: Para operações matemáticas e numéricas.
- **Sklearn (StandardScaler, LinearRegression, mean_squared_error, train_test_split)**: Para pré-processamento e modelagem.
- **Matplotlib**: Para visualização de dados.
- **Seaborn**: Para criação de gráficos avançados.
- **Plotly Express**: Para visualizações interativas.

## 🎯 Objetivos do Projeto

1. **Análise Exploratória de Dados (EDA)**: Explorar tendências, distribuições e outliers no conjunto de dados.
2. **Engenharia de Recursos**: Preparar e limpar os dados para uso em modelos.
3. **Visualização**: Gerar gráficos e visualizações que ajudem a entender as correlações entre as variáveis e o preço de aluguel.
4. **Modelagem**: Usar Regressão Linear para prever o preço total de aluguel com base nas características do imóvel.
5. **Avaliação**: Avaliar o modelo utilizando o Erro Quadrático Médio (MSE).

## 🔍 Conclusão
A análise permite entender os fatores que impactam o valor de aluguel em diferentes cidades brasileiras, oferecendo insights sobre o mercado imobiliário e ajudando a prever o preço de aluguel com base nas características do imóvel.

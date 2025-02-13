# Análise de Dados sobre Diabetes

## Descrição do Projeto
Este projeto realiza uma análise exploratória e estatística de um conjunto de dados sobre diabetes, buscando identificar padrões e relações entre diferentes variáveis de saúde. A análise inclui limpeza e tratamento de dados, visualização de informações relevantes, testes estatísticos e extração de insights.

## Tecnologias Utilizadas
- Python
- Pandas
- Matplotlib
- Seaborn
- Scipy
- Jupyter Notebook

## Conjunto de Dados
O conjunto de dados utilizado contém informações sobre a saúde de indivíduos, incluindo fatores como:
- Diagnóstico de diabetes
- Pressão alta
- Colesterol alto
- IMC (Índice de Massa Corporal)
- Consumo de frutas e vegetais
- Atividade física
- Avaliação geral da saúde
- Idade e nível de educação

## Principais Etapas
### 1. Leitura e Tratamento de Dados
- Remoção de duplicatas
- Identificação e remoção de outliers (IQR)
- Conversão de variáveis categóricas

### 2. Estatísticas Descritivas
- Cálculo de médias, medianas e distribuições
- Análise de dispersão dos dados

### 3. Visualização de Dados
- Histogramas e gráficos de densidade
- Boxplots para distribuição de variáveis
- Gráficos de dispersão para correlações
- Heatmap para matriz de correlação

### 4. Testes de Hipótese
- Teste qui-quadrado para verificar associações entre diabetes e outras variáveis
- Principais resultados:
  - Existe uma associação significativa entre diabetes e pressão alta
  - Há correlação entre diabetes e avaliação geral da saúde

## Resultados e Conclusões
Os resultados da análise indicam relações estatisticamente significativas entre a presença de diabetes e fatores como pressão alta e avaliação geral da saúde. Esses insights podem ser utilizados para direcionar estratégias de prevenção e tratamento.

## Como Executar o Projeto
1. Instale as bibliotecas necessárias:
   ```bash
   pip install pandas matplotlib seaborn scipy jupyter
   ```
2. Abra o Jupyter Notebook e execute as células sequencialmente.
3. Certifique-se de que o arquivo `Diabetes.csv` esteja no mesmo diretório do notebook.


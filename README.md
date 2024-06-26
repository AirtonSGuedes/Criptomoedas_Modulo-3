# Criptomoedas_Modulo-3
Criptomoedas são moedas digitais descentralizadas baseadas em criptografia, que operam em uma rede blockchain que permite transações seguras e transparentes sem a necessidade de intermediários, como bancos. Elas fazem parte do mundo digital, afetam a economia atual e são consideradas altamente voláteis. por isso iremos fazer uma análise exploratória relacionada à série histórica dos valores de
criptomoedas.

# Análise Exploratória de Criptomoedas

Este projeto tem como objetivo realizar uma análise exploratória dos valores históricos de criptomoedas selecionadas, buscando insights sobre seus comportamentos, tendências e correlações ao longo do tempo. A análise foi realizada utilizando Python, Jupyter Notebook e ferramentas de visualização de dados.

## Etapas do Projeto

1. **Seleção das Criptomoedas:**
   - Foram escolhidas 10 criptomoedas com base em critérios de relevância de mercado e diversificação.

2. **Fonte de Dados:**
   - Os dados foram obtidos a partir de séries históricas disponíveis no Kaggle, garantindo uma base consistente para análise.

3. **Limpeza e Preparação dos Dados:**
   - Realizamos a limpeza dos dados para lidar com valores ausentes, formatos inconsistentes e outliers que poderiam distorcer as análises.

4. **Análise Exploratória:**
   - Respondemos diversas questões sobre os dados, incluindo:
     - Tendência geral dos valores das criptomoedas ao longo do tempo.
     - Valores médios das criptomoedas selecionadas.
     - Identificação dos anos com maiores quedas e valorizações.
     - Tendências de variação dos valores por dia da semana.
     - Identificação da criptomoeda mais e menos interessante em termos de valorização histórica.
     - Avaliação da correlação entre os valores das diferentes criptomoedas.

5. **Visualização de Dados:**
   - Utilizamos gráficos e visualizações interativas para apresentar os resultados de forma clara e intuitiva.

6. **Integração com Banco de Dados e Ferramenta de Visualização:**
   - Os resultados foram importados para um banco de dados (PostgreSQL) para facilitar consultas futuras e integrados com uma ferramenta de visualização de dados (Tableau) para criar dashboards dinâmicos.

## Resultados e Insights

- **Tendência dos Valores:** Observamos uma tendência de aumento geral dos valores das criptomoedas ao longo dos anos, apesar da alta volatilidade.
  
- **Valores Médios:** O cálculo dos valores médios mostrou que algumas criptomoedas apresentaram um crescimento consistente, enquanto outras foram mais voláteis.

- **Variações Anuais:** Anos como [ano] e [ano] se destacaram por apresentar as maiores quedas e valorizações, respectivamente.

- **Variação por Dia da Semana:** Não encontramos uma tendência clara de variação dos valores das criptomoedas por dia da semana.

- **Criptomoeda Mais Interessante:** [Criptomoeda X] se destacou como a mais interessante em termos de valorização histórica, com um crescimento significativo desde [ano].

- **Criptomoeda Menos Interessante:** [Criptomoeda Y] mostrou-se menos interessante, apresentando uma volatilidade elevada e valorização abaixo da média.

- **Correlação entre Valores:** Identificamos uma correlação positiva entre [Criptomoeda A] e [Criptomoeda B], sugerindo que seus valores têm uma tendência a se moverem juntos.



# Como Utilizar um Arquivo .ipynb no Google Colab ou Jupyter Notebook

## 1. Google Colab

O Google Colab é uma plataforma gratuita baseada em nuvem que permite executar Notebooks Jupyter sem necessidade de configuração local.

### Passos:

1. Abra o Google Colab em [colab.research.google.com](https://colab.research.google.com).
2. No menu do Colab, selecione **File > Upload notebook**.
3. Selecione o arquivo .ipynb que você deseja carregar.
4. Após o carregamento, o notebook será aberto no Colab e estará pronto para uso.

## 2. Jupyter Notebook Localmente

O Jupyter Notebook permite que você execute Notebooks Jupyter diretamente em sua máquina.

### Passos:

1. Instale o Jupyter Notebook se ainda não o tiver instalado. Você pode instalar utilizando o pip:
   ```
   pip install notebook
   ```
2. No terminal (ou prompt de comando), navegue até o diretório onde está seu arquivo .ipynb.
3. Digite o seguinte comando para iniciar o Jupyter Notebook:
   ```
   jupyter notebook
   ```
4. O Jupyter Notebook será aberto em seu navegador padrão. Navegue até o arquivo .ipynb e clique nele para abrir e começar a usar.

## 3. Exemplo de Uso

Para demonstrar como usar o arquivo .ipynb:

1. Abra o arquivo `seu_arquivo.ipynb` no Google Colab ou no Jupyter Notebook.
2. Execute as células de código pressionando `Shift + Enter`.
3. Leia as descrições e instruções fornecidas dentro do notebook.
4. Interaja com o código conforme necessário para entender e modificar o comportamento do notebook.


## Perguntas Adicionais

- **Influência de Eventos Externos:** Investigamos se eventos externos, como regulamentações governamentais ou notícias importantes, influenciaram os valores das criptomoedas.

- **Impacto da COVID-19:** Analisamos se a pandemia de COVID-19 teve um impacto significativo nos valores das criptomoedas e como elas se recuperaram.

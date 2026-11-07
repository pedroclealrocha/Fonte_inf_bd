# Fonte_inf_bd
Atividades Da Fatec Disciplina, Fonte de informações e Banco de Dados.
-


ATIVIDADE - análise de dados abertos por meio de dashboards


<img width="632" height="419" alt="image" src="https://github.com/user-attachments/assets/ee3fb129-8968-421c-a797-353000872fbf"/>



ATIVIDADE - análise de dados abertos por meio de fórmulas


<img width="406" height="423" alt="image" src="https://github.com/user-attachments/assets/a3be3086-93d5-4283-b20d-743123de3699" />

INTRODUÇÃO AO POWER BI - Atividade análise de dados abertos
-

FERRAMENTAS USADAS

- USO DE FÓRMULA DAX
- VISUALIZAÇÕES
- TRANSFORMAÇÃO DE DADOS


<img width="674" height="451" alt="image" src="https://github.com/user-attachments/assets/f54fc27b-e7dc-43cf-ad98-acd7ad2f06ad" />

ATIVIDADE - ANÁLISE DE DADOS ABERTOS POWER BI.
- 
CENSO FAVELAS 2022


<img width="619" height="529" alt="image" src="https://github.com/user-attachments/assets/48c8d5d3-9a35-4437-8ef3-193a433a50df" />

Preços de combustíveis no Brasil: análise no Power BI
-
Relatório interativo em Power BI feito a partir de dados abertos do governo federal. O projeto cruza uma tabela fato de preços com uma tabela dimensão de produtos que traz uma figura para cada combustível, e mostra como o filtro de uma tabela se propaga para a outra.

Técnicas utilizadas.:

**DAX:**
Medidas com AVERAGE, MIN, MAX e COUNTROWS (preço médio, mínimo, máximo e quantidade de coletas).<br>
Coluna calculada com SWITCH para associar uma cor a cada produto.<br>
Medida com SELECTEDVALUE para devolver a cor do produto selecionado.

**Visualização e interatividade:**
Segmentação de botão com imagens, em grade de 6 colunas e 1 linha.<br>
Cartões, gráfico de colunas (preço médio por região), gráfico de linhas (preço médio por mês, com hierarquia de data reduzida a mês) e tabela com figura.<br>
Formatação condicional por valor do campo (fx), para as cores dos visuais acompanharem a cor da figura.<br>
Editar interações, para a segmentação não filtrar a tabela de produtos.

<img width="890" height="535" alt="image" src="https://github.com/user-attachments/assets/ea0f468a-494f-4490-a409-bf478bb97607" />

# Regressão Linear: Temperatura vs. Faturamento

## Passo a passo

1. **Carregamento dos dados**
   - Importação dos dados para um dataframe com as colunas `Temperature` e `Revenue`.
2. **Treinamento do modelo**
   - Criação de um modelo `LinearRegression`.
   - Temperatura como variável explicativa (X) e faturamento como variável alvo (y).
3. **Geração da linha de regressão**
   - Criação de 100 pontos entre a menor e a maior temperatura com `np.linspace`.
   - Previsão do faturamento para cada ponto com `modelo.predict`.
4. **Criação do gráfico**
   - Gráfico de dispersão dos dados reais com `sns.scatterplot`.
   - Linha de regressão sobreposta com `plt.plot`.
   - Título, rótulos dos eixos e legenda.
  
 ## 🛠️ Ferramentas utilizadas

- **Python**
- **Google Colab**
- **pandas**: manipulação dos dados
- **NumPy**: geração dos pontos da linha de regressão
- **scikit-learn**: treino do modelo (`LinearRegression`)
  
<img width="1096" height="653" alt="image" src="https://github.com/user-attachments/assets/b20e013e-29ca-40fe-b7d1-793bf0c1662e" />



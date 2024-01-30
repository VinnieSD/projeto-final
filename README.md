# projeto-final-ebac
Projeto desenvolvido no último módulo do curso Cientista de Dados da Ebac.


## Cienstista de Dados 


Aplicação web feita com Streamlit,Python e Pycaret.

https://github.com/VinnieSD/projeto-final/assets/150684999/ac0817cc-e93a-4420-b01f-b8f977a60e82





### Proposta do Projeto 
Neste projeto, estamos construindo um credit scoring para cartão de crédito, em um desenho amostral com 15 safras, e utilizando 12 meses de performance.
Carregue a base de dados credit_scoring.ftr.


###  Amostragem
Variáveis:
Considere que a variável data_ref não é uma variável explicativa, é somente uma variável indicadora da safra, e não deve ser utilizada na modelagem. A variávei index é um identificador do cliente, e também não deve ser utilizada como covariável (variável explicativa). As restantes podem ser utilizadas para prever a inadimplência, incluindo a renda.


### Descritiva Basica 
Descreva a base quanto ao número de linhas, número de linhas para cada mês em data_ref.
Faça uma descritiva básica univariada de cada variável. Considere as naturezas diferentes: qualitativas e quantitativas.

### Descritiva Bivariada 
Uma análise descritiva bivariada é uma técnica estatística usada para analisar a relação entre duas variáveis. Ela busca fornecer uma descrição detalhada das características conjuntas de duas variáveis ​​e identificar possíveis padrões ou associações entre elas.

### Desenvolvimento de Modelo 
Trate valores missings e outliers
Trate 'zeros estruturais'
Faça agrupamentos de categorias conforme vimos em aula
Proponha uma equação preditiva para 'mau'
Caso hajam categorias não significantes, justifique

### Avalicao de Modelo 
Avalie estas métricas nas bases de desenvolvimento e out of time.

### Criando uma pipeline 
 e  o aprendizado de máquina, é um conjunto de etapas sequenciais que são realizadas em um fluxo contínuo para processar dados e construir um modelo preditivo.
 
### Treinar um modelo de regressão logistica com o resultado
Para treinar um modelo de regressão logística, é necessário ter um conjunto de dados rotulados, onde as variáveis independentes (ou características) estão relacionadas ao resultado binário (0 ou 1) que você deseja prever.

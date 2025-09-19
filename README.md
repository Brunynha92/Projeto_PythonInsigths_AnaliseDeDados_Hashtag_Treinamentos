# Projeto Python Insights - Analisando Dados com Python - Hashtag Treinamentos - Jornada Python (Set/25)

Projeto básico de analise, tratamento e visualização de dados.

## Bibliotecas utilizadas:
* **Pandas**: para leitura e manuseio da base de dados;
* **Plotly**: para criação e visualização de graficos

### Comandos Utilizados:


* **Pandas.read_csv:** para ler a tabela (_para que possamos utilizar a tabela o mesmo deve ser inserida dentro de uma váriavel, caso contrario sistema apenas irá ler a tabela e descarta-la_)

* **For:** utilizado para acessar cada coluna da tabela.

* **.drop:** para remover colunas ou linhas da tabela

* **.info** para visuzaliar as principais informações da tabela como colunas, quantidade de linhas não vazias e tipo de dados.

* **.values_counts** para contar o valores de determinada coluna (_usando value_counts(normalize=True) o retorno vem em percentual_)

* **.histogram** para criar um grafico de acordo com os parametros estabelecidos

* **.show** para exibir um grafico


## Resolução
    O projeto identificou que 56,7% dos clientes cancelaram os serviços com motivos principais sendo:
    * Atraso mais de 20 dias
    * Assinatura do tipo Mensal
    * Mais de 4 ligações para os clientes

## Analises Adicionais

Considerando apenas os clientes ativos na base, incluso uma coluna condicional de risco baseado na variação de ligagoes para o callcenter, separando em **"Alto Risco"**, **"Médico Risco"** e **"BAixo Risco"**, incluso também em grafico identificando os risco como um farol.

### Comando adicionais utilizados:

* **color_discrete_sequence:** para incluir a lis de cores do farol

* **textposition:** para incluir o rotulo de dados acizma da barra do grafico

* **title:** para inserir um tirulo no grafico
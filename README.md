# ETL-Receita-Federal
Extrair informações da base de dados pública da Receita Federal, fazer as transformações necessárias e entregar um output das 1000 primeiras linhas da base final em Excel.

Fato 1: O time de negócios gostaria de enriquecer seus dados de cadastro com as informações públicas disponibilizadas pela RFB (Receita Federal Brasileira) [1].

 

Fato 2: O PO da área solicitou ao time de Data Engineering, que fosse feito o enriquecimento da base de cadastros.

 

Fato 3: Na reunião de alinhamento entre o PO e o Tech Lead do time, foi acordado que, antes enriquecer a base, o time de Engenharia faria o ETL dos dados da RFB. E, só iriam para a próxima etapa de desenvolvimento quando o time de negócios aprovarem a amostra do output.

 

Fato 4: O output acordado é uma amostra dos dados, das 1000 primeiras linhas da base final, entregues em excel.

 

Fato 5: A demanda do Tech Lead chega para o engenheiro de dados:

 

Olá Engenheiro, preciso que você faça o pipeline de ETL em python dos dados da RFB para o time cadastro.

Para ser mais rápido nessa atividade faça o download de apenas uma amostra dos dados e depois faça as transformações necessárias e me envie o output. Também me envie o jupyter notebook que você usou para operar os dados em questão.

               

	Em resumo:

               

	- Baixe uma Amostra de cada base no site da receita[1]:   EMPRESA 01, ESTABELECIMENTO 01, SÓCIO 1 .

               
	- Baixe as tabelas auxiliares também disponível no site (NÃO baixar/usar a tabela de  "Informações sobre o Simples Nacional/MEI").

               

	- Faça os joins necessários.

               

	- Faça o sort da base pelo número do CNPJ de forma decrescente e me envie as primeiras 1000 linhas em excel.


 

 

REF:

[1] https://www.gov.br/receitafederal/pt-br/assuntos/orientacao-tributaria/cadastros/consultas/dados-publicos-cnpj

 

DICAS:

    Leia atentamente a página da receita federal – lá você encontrará detalhes de como as tabelas são relacionadas e, também, o dicionário de dados de cada tabela.
    Use a lib pandas.

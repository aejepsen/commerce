> # Projeto de Commerce MongoBD
>> ## O projeto está desenvolvido em varios arquivos dentro da pasta challenges.
>> ### Querys dos respectivos desafios:
1. > Retorne a quantidade de documentos inseridos na coleção produtos:
   >> **desafio1.js**
2. > Ordene a coleção produtos pela quantidade de lanches vendidos em ordem crescente, mostrando apenas o nome e a quantidade de lanches vendidos:
   >> **desafio2.js**
3. > Retorne o lanche mais vendido, mostrando apenas o nome e a quantidade do lanche mais vendido:
   >> **desafio3.js**
4. > Retorne os lanches que tiveram vendas maiores que 50 e menores que 100, mostrando apenas o nome e a quantidade de lanches vendidos em ordem crescente:
   >> **desafio4.js**
5. > Retorne o nome, as curtidas e vendidos dos lanches que tiveram quantidade de curtidas igual a 36 ou tenham a quantidade de vendas igual a 85:
   >> **desafio5.js**
6. > Retorne o nome e as curtidas dos lanches que tiveram curtidas maiores que 10 e menores que 100:
   >> desafio6.js
7. > Retorne o nome e vendidos dos lanches que tenham sido vendidos com uma quantidade diferente de 50 e em que o campo tags não exista:
   >> desafio7.js
8. > Delete os lanches com menos de 50 curtidas e retorne o nome dos lanches que restaram no banco
   >> desafio8.js
9. > Retorne o nome de todos os lanches que possuam calorias abaixo de 500
   >> desafio9.js.
10. > Retorne o nome de todos os lanches que tenham o percentual de proteínas maior ou igual a 30 e menor ou igual a 40
    >> desafio10.js
11. > Retorne o nome do produto, a quantidade de curtidas e quantos itens foram vendidos dos produtos que não sejam iguais a Big Mac e McChicken
    >> desafio11.js
12. > Adicione ketchup aos ingredientes para todos os sanduíches menos o McChicken, garantindo que não haja duplicidade nos ingredientes
    >> desafio12
13. > Inclua o campo criadoPor em todos os documentos, colocando Ronald McDonald no valor desse campo
    >> desafio13.js
14. > Crie uma query que retorne todos os lanches que possuem picles em seus ingredientes e mostre apenas os 3 primeiros itens contidos no array valoresNutricionais. Sua query deve retornar apenas os campos nome, ingredientes e valoresNutricionais.
   >> desafio14.js
15. > Adicione o campo avaliacao em todos os documentos da coleção e efetue alterações nesse campo
Crie uma query que inclua o campo avaliacao do tipo NumberInt, com o valor 0 em todos os documentos da coleção.Crie uma query que incremente o valor do campo avaliacao em 5 em todos os sanduíches de carne do tipo bovino. eyesDe olho na dica: utilize como filtro o campo tags.Crie uma query que incremente o valor do campo avaliacao em 3 em todos os sanduíches de ave.Crie uma query que retorne o nome e avaliacao de todos os sanduíches.
    >> desafio15.js
16. > Adicione o campo ultimaModificacao com a data corrente somente no sanduíche Big Mac. Crie uma query que inclua somente ao sanduíche Big Mac o campo ultimaModificacao com a data corrente. Para a data corrente faça uso do tipo date ou timestamp. Crie uma query que retorne o nome de todos os documentos em que o campo ultimaModificacao existe. 
    >> desafio16.js
17. > Retorne a quantidade total de produtos em uma nova coleção chamada resumoProdutos. Crie uma query que insira na coleção resumoProdutos um documento com os campos: franquia com o valor McDonalds e totalProdutos com o valor sendo a quantidade total de produtos registrados na coleção produtos.Crie uma query que retorne os campos franquia e o totalProdutos da coleção resumoProdutos, resultantes da primeira query.
    >> desafio17.js 
18. > Inclua bacon no final da lista de ingredientes dos sanduíches Big Mac e Quarteirão com Queijo. Crie uma query que faça a inclusão de bacon no final da lista de ingredientes dos sanduíches Big Mac e Quarteirão com Queijo.Crie uma query que retorne o nome e ingredientes de todos os documentos.
    >> desafio18.js
19. > Remova o item cebola de todos os sanduíches. Crie uma query que faça a remoção do item cebola em todos os sanduíches. Crie uma query que retorne o nome e ingredientes de todos os documentos.
    >> desafio19.js
20. > Remova o primeiro ingrediente do sanduíche Quarteirão com Queijo. Crie uma query que faça a remoção do primeiro ingrediente no sanduíche Quarteirão com Queijo.
    >> desafio20.js
21. > Remova o último ingrediente do sanduíche Cheddar McMelt. Crie uma query que faça a remoção do último ingrediente no sanduíche Cheddar McMelt.
    >> desafio21.js
22. > Adicione a quantidade de vendas dos sanduíches por dia da semana. Crie uma query que inclua um campo vendasPorDia em todos os sanduíches. O valor deste campo deverá ser um array com sete posições. Cada uma delas representará um dia da semana, e cada posição iniciará em 0. O array deve seguir a estrutura do exemplo abaixo: "vendasPorDia": [0, 0, 0, 0, 0, 0, 0] O primeiro item desse array representa as vendas no domingo, o segundo item representa as vendas na segunda-feira, e assim sucessivamente até chegar ao último item, que representa as vendas no sábado.Crie uma query que incremente as vendas de Big Mac às quartas-feiras em 60.Crie uma query que incremente as vendas de todos os sanduíches de carne do tipo bovino aos sábados em 120.Crie uma query que retorne o nome e vendasPorDia de todos os documentos.
    >> desafio22.js
23. > Insira os valores combo e tasty no array tags de todos os sanduíches e aproveite para deixar os valores em ordem alfabética ascendente (A a Z). Crie uma query que faça tanto a inserção dos valores combo e tasty no array tags de todos os sanduíches. Ordene os valores de tags em ordem alfabética ascendente. Crie uma query que retorne o nome e tags de todos os documentos.
    >> desafio23.js
24. > Ordene em todos os documentos os valores do array valoresNutricionais pelo campo percentual de forma decrescente. Crie uma query que faça em todos os documentos a ordenação dos valores do array valoresNutricionais pelo campo percentual de forma decrescente. eyesDe olho na dica: mesmo sem adicionar nenhum novo valor, para essa operação é necessário utilizar também o modificador $each. Crie uma query que retorne o nome e valoresNutricionais de todos os documentos.
    >> desafio24.j
25. > Adicione o valor muito sódio ao final do array tags nos produtos em que o percentual de sódio seja maior ou igual a 40. 
Crie uma query que faça a adição do valor muito sódio ao final do array tags nos produtos em que o percentual de sódio seja maior ou igual a 40. Crie uma query que retorne o nome e tags de todos os documentos.
    >> desafio25.js
26. > Adicione o valor contém sódio ao final do array tags nos produtos em que o percentual de sódio seja maior do que 20 e menor do que 40. Crie uma query que faça a adição do valor contém sódio ao final do array tags nos produtos em que o percentual de sódio seja maior do que 20 e menor do que 40.
Crie uma query que retorne o nome e tags de todos os documentos.
    >> desafio26.js
27. > Conte quantos produtos contém Mc no nome, sem considerar letras maiúsculas ou minúsculas
    >> desafio27.js
28. > Conte quantos produtos têm 4 ingredientes
    >> desafio28.js
29. > Renomeie o campo descricao para descricaoSite em todos os documentos. Crie uma query que faça a renomeação do campo descricao para descricaoSite em todos os documentos.Crie uma query que retorne o nome e descricaoSite de todos os documentos.
    >> desafio29.js
30. > Remova o campo curtidas do item Big Mac. Crie uma query que faça a remoção do campo curtidas do item Big Mac.Crie uma query que retorne o nome para todos os documentos e curtidas (exceto para Big Mac).
    >> desafio30.js
31. > Retorne o nome dos sanduíches em que o número de curtidas é maior que o número de sanduíches vendidos
    >> desafio31.js
32. > Retorne o nome e a quantidade de vendas (vendidos) dos sanduíches em que o número de vendas é múltiplo de 5
    >> desafio32.js

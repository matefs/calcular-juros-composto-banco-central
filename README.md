#  Calcular juros composto com a taxa SELIC

Projeto para calcular o juro composto com base na taxa SELIC consultada na API do banco central do Brasil, trazendo a taxa definida nos últimos 45 dias.
Projeto utilizando Javascript, Bootstrape Chart.js  



### Imagens do projeto: 
![projeto taxa selic grafico](https://user-images.githubusercontent.com/30128774/203454361-98af184d-5391-4898-a2aa-ef3b5c079733.gif)



## Api Utilizada

Segue a url do banco central utilizada para consultar a taxa selic do último mês:
`` https://api.bcb.gov.br/dados/serie/bcdata.sgs.11/dados?formato=json&dataInicial=01/01/2022&dataFinal=31/12/2022 ``

Parametros:
1. ``sgs.{código}`` retorna qual a informação que a api vai consultar
2. ``?formato=json ``retorna a estrutura do resposta da api (pode ser em json,csv)
3. ``?dataInicial`` e ``?dataFinal ``  define a data da taxa selic a ser consultada


### Acesse o projeto online:
https://t3pr0j.csb.app/

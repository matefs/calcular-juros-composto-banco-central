#  Calcular juros composto com a taxa SELIC

Projeto para calcular o juro composto com base na taxa SELIC consultada na API do banco central do Brasil, trazendo a taxa definida nos últimos 45 dias.
Projeto utilizando Javascript, Bootstrape Chart.js.

### Imagens do projeto: 
![projeto taxa selic grafico](https://user-images.githubusercontent.com/30128774/203454361-98af184d-5391-4898-a2aa-ef3b5c079733.gif)
![image](https://user-images.githubusercontent.com/30128774/204943503-0b7be46e-87e9-410c-be51-89615349cbf5.png)


# Acesse o projeto online: 👇
https://lbfih9.csb.app/

## Api Utilizada

Segue a url do banco central utilizada para consultar a taxa selic do último mês:
`` https://api.bcb.gov.br/dados/serie/bcdata.sgs.11/dados?formato=json&dataInicial=01/01/2022&dataFinal=31/12/2022 ``

Parametros:
1. ``sgs.{código}`` retorna qual a informação que a api vai consultar
2. ``?formato=json ``retorna a estrutura do resposta da api (pode ser em json,csv)
3. ``?dataInicial`` e ``?dataFinal ``  define a data da taxa selic a ser consultada

## Links importantes 
1. Procurar por mais códigos para consultar da api: https://www3.bcb.gov.br/sgspub/localizarseries/localizarSeries.do?method=prepararTelaLocalizarSeries

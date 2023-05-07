#  Calcular juros composto com a taxa SELIC

Este repositório contém uma aplicação web que permite calcular o valor final de um investimento com base na taxa de juros compostos fornecida pelo Banco Central do Brasil. O aplicativo utiliza a API do Banco Central para obter a taxa de juros compostos atualizada. 

### Imagens do projeto: 
![projeto taxa selic grafico](https://user-images.githubusercontent.com/30128774/203454361-98af184d-5391-4898-a2aa-ef3b5c079733.gif)
 

# Acesse o projeto online: 👇
https://TAXA-SELIC.mateusschverz.repl.co


## Api Utilizada
Segue a url do banco central utilizada para consultar a taxa selic do último mês:
`` https://api.bcb.gov.br/dados/serie/bcdata.sgs.11/dados?formato=json&dataInicial=01/01/2022&dataFinal=31/12/2022 ``

Parametros:
1. ``sgs.{código}`` retorna qual a informação que a api vai consultar
2. ``?formato=json ``retorna a estrutura do resposta da api (pode ser em json,csv)
3. ``?dataInicial`` e ``?dataFinal ``  define a data da taxa selic a ser consultada

## Links importantes 
1. Procurar por mais códigos para consultar da api: https://www3.bcb.gov.br/sgspub/localizarseries/localizarSeries.do?method=prepararTelaLocalizarSeries

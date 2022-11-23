#  Calcular juros composto com a taxa SELIC

Projeto para calcular o juro composto com base na taxa SELIC consultada na API do banco central do Brasil, trazendo a taxa definida nos últimos 45 dias.
Projeto utilizando Javascript, Bootstrap (https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css) e Chart.js (https://cdn.jsdelivr.net/npm/chart.js)


## Api Utilizada

Segue a url do banco central utilizada para consultar a taxa selic do último mês:
`` https://api.bcb.gov.br/dados/serie/bcdata.sgs.11/dados?formato=json&dataInicial=01/01/2022&dataFinal=31/12/2022 ``

Parametros:
1. ``sgs.{código}`` retorna qual a informação que a api vai consultar
2. ``?formato=json ``retorna a estrutura do resposta da api (pode ser em json,csv)
3. ``?dataInicial`` e ``?dataFinal ``  define a data da taxa selic a ser consultada


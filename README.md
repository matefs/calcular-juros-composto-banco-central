#  Calcular juros composto com a taxa SELIC

Este repositório contém uma aplicação web que permite calcular o valor final de um investimento com base na taxa de juros compostos fornecida pelo Banco Central do Brasil. O aplicativo utiliza a API do Banco Central para obter a taxa de juros compostos atualizada. 
 
![projeto taxa selic grafico](https://user-images.githubusercontent.com/30128774/203454361-98af184d-5391-4898-a2aa-ef3b5c079733.gif)
 

# Acesse o projeto online: 👇
https://TAXA-SELIC.mateusschverz.repl.co
## **Tecnologias utilizadas**

- **[JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)**
- **[Bootstrap](https://getbootstrap.com/)**
- **[Chart.js](https://www.chartjs.org/)**

## **Como usar**

1. Clone este repositório para sua máquina local.
```
git clone https://github.com/matefs/calcular-juros-composto-banco-central.git
```
2. Na pasta do arquivo, rode o comando `npx live-server`
3. Abra o arquivo **`index.html`** em seu navegador.
4. Preencha os campos com os dados do seu investimento, incluindo o valor inicial, a taxa de juros e o prazo de investimento.
5. Clique no botão `Calculate` para obter o valor final do investimento.
6. A taxa SELIC definida nos últimos 45 dias será exibida em um gráfico abaixo da calculadora de juros compostos.

## Sobre a API utilizada
Segue a url do banco central utilizada para consultar a taxa selic do último mês:
`` https://api.bcb.gov.br/dados/serie/bcdata.sgs.11/dados?formato=json&dataInicial=01/01/2022&dataFinal=31/12/2022 ``

Parametros:
1. ``sgs.{código}`` retorna qual a informação que a api vai consultar
2. ``?formato=json ``retorna a estrutura do resposta da api (pode ser em json,csv)
3. ``?dataInicial`` e ``?dataFinal ``  define a data da taxa selic a ser consultada

## Links importantes 
1. Procurar por mais códigos para consultar da api: https://www3.bcb.gov.br/sgspub/localizarseries/localizarSeries.do?method=prepararTelaLocalizarSeries

## **Contribuições**

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver alguma ideia de como melhorar a aplicação, sinta-se à vontade para criar uma issue ou enviar um pull request.


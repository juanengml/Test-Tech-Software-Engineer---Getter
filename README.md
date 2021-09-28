# Test Tech Software Engineer
----

## Desafio

Neste desafio teremos 2 etapas fundamentais para concluir esste test.
Duração: até 6 dias
PS: Ambas as etapas devem ser seguidas, mas tambem existe margem para alterações, caso o candidato queira trocar a arqutietura, fica aberto para a mesma. De qualquer forma e indispensavel o uso das técnologias como Docker, Python e MongoDB

### 1 Etapa  (API REST) 🔌

Nessa desafio você precisa desenvolver uma api rest seja a porta de entrada para um grande volume de dados, tendo como ENDPOINT e rota abaixo 
Essa api precisa ser em formato CRUD, cadastrar dados, buscar, atualizar e deletar informações 

exemplo: ->  seuapp.heroku.com    

URL   | ENDPOINT | TIPO 
--------- | ------ | ----- 
seuapp.heroku.com | /api/v1/crud | [post, put,get, delete]


PARAMETRO   | TIPO 
--------- | ------ 
nome_componente | STRING
datetime | STRING 
descritivo | STRING 

EXEMPLO: 

PARAMETROS DE ENTRADA {'nome_componente':'resistor', 'datetime': '2018-05-01', 'descritivo':'resitor de 120 ohms'}

Essa aplicação precisa ter os seguintes requisitos minimos de arquivos(dockerfile, app.py e requirements.txt, README.md)


### 2 Etapa  (deploy-heroku) 🛠
Com base na imagem abaixo use seus conhecimentos em deploy para provisionar essa estrutura para comportar seus codigos da proxima etapa

- > heroku - https://www.heroku.com/

- > Banco de Dados - https://www.mongodb.com/pt-br

## Arquitetura PROPOSTA 🖥
 
 ![](https://raw.githubusercontent.com/juanengml/Test-Tech-Software-Engineer---Getter/main/arquitetura_getter_-_dev_api_-_test_tech.png)

## OBJETO DE AVALIAÇÃO ✅

ETAPA   | OBJETIVO 
--------- | ------ 
1 | QUALIDADE DO CODIGO 
1 | ARQUITETURA LIMPA E DOCUMENTAÇÃO CLARA 
2 | QUALIDADE DE CODIGO
2 | DOCUMENTAÇÃO CLARA  

---- 

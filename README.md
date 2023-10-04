# dio-explorando-ia-generativa-em-um-pipeline-de-etl-com-python
![Badge](https://img.shields.io/static/v1?label=python&message=v3.11.1&color=blue&logo=PYTHON)
<br><br>
Pipeline ETL (Extração, Transformação e Carregamento), demonstrando a relação entre dados, Inteligência Artificial (IA) e APIs - Digital Innovation One

## Contexto
Usar o poder da IA Generativa para criar mensagens de condições climáticas personalizadas, de forma humorística, para 5 cidades listadas.

## Cronograma
1. Consumir o endpoint GET https://api.hgbrasil.com/weather?woeid={woeid} (API HGBRAZIL WEATHER) para obter os dados climáticos das cidades.
<br><br>
2. usar a API do ChatGPT (OpenAI) para gerar uma mensagem de condições climáticas personalizada para cada cidade. Essa mensagem deve ter um tom humorísitico de dar notícia.
<br><br>
3. Gravar informações obtidas em um arquivo csv.

## Execução do projeto

1 - Faça o clone ou download do projeto.\
2 - Instale as bibliotecas necessárias no ``requirements.txt``\
3 - Configure em seu arquivo ``.env`` o valor da variável `OPENAI_API_KEY`\
4 - Execute a aplicação através do comando:\
```$ python app.py``` ou ```$ python3 app.py```\



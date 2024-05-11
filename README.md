# passando-recibo

Projeto da Imersão de AI da Alura - explorando o Google Gemini

## Objetivo

O objetivo deste projeto é explorar o Google Gemini para extrair informações de recibos
de maneira bem simples. O usuário passa recibos em formato de imagem e o sistema retorna
um resumo das informações extraídas e responde a perguntas.

## Exemplo

Execute o notebook. Na etapa de upload dos recibos você pode passar a imagem do recibo
abaixo:

![Exemplo de recibo](https://2.bp.blogspot.com/_LqCB_lgYPw0/TOpg2M5arSI/AAAAAAAAADg/oHsIX1_QeUs/s1600/lidl.jpg)

É esperada uma interação como essa:

```
    Você comprou 6 itens na loja Lidl e o total da sua compra foi de 10,62 euros. Os itens mais comprados foram:

    Bananas: 1,17 euros Cenouras: 0,90 euros Pimentões: 1,79 euros Alho francês: 0,89 euros 2 kebabs: 1,99 euro Iogurte grego: 1,99 euro
```

Você pode fazer perguntas. Por exemplo:

```
    Quanto gastamos no mês de maio?

    Resposta:  17,47 euros.
```

Digite "FIM" para encerrar a conversa.

Há um tempo eu e minha namorada queríamos fazer algo assim. Estávamos guardando recibos
para fazer esse processo manualmente. Que bom que agora temos um chatbot pra isso. ;)

## Datasets

Você pode encontrar datasets de recibos em:

* https://www.kaggle.com/datasets/trainingdatapro/ocr-receipts-text-detection
* https://www.kaggle.com/datasets/jenswalter/receipts
* https://www.kaggle.com/datasets/urbikn/sroie-datasetv2

## Ambiente de desenvolvimento

### Configurando as dependências

Instale o Poetry, ative o ambiente virtual e instale as dependências:

```bash
poetry shell
poetry install
```

### Executando o Jupyter Notebook

```bash
poetry run jupyter notebook
```

## Referências

* https://ai.google.dev/gemini-api/docs/get-started/python?hl=pt-br#generate_text_from_image_and_text_inputs
* https://ai.google.dev/api/python/google/generativeai/GenerativeModel#streaming
* Créditos da imagem: https://2.bp.blogspot.com/_LqCB_lgYPw0/TOpg2M5arSI/AAAAAAAAADg/oHsIX1_QeUs/s1600/lidl.jpg

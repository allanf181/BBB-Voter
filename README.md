# BBB-Voter

## Requerimentos
* Python
* Chrome

## Uso
Baixe o zip no botão Clone or download > Download ZIP e extraia onde quiser.
Com o python já instalando abra o cmd na pasta que você extraiu o projeto e digite:
```
pip install -U selenium
```

Após terminar de instalar o selenium, abra o arquivo ``config.json`` e preencha os campos **DENTRO DAS ASPAS**:
```js
{
    "pollURL": "COLOQUE AQUI A URL DA VOTAÇÃO", 
    "targetPosition": 1, //ESSE NUMERO É A POSIÇÃO DE QUEM VOCÊ QUER ELIMINAR, PRIMEIRO, SEGUNDO OU TERCEIRO
    "credentials": {
        "username": "COLOQUE AQUI SEU EMAIL", 
        "password": "COLOQUE AQUI SUA SENHA"
    },
    "webDriverPath": ""
}
```
Após preencher o arquivo corretamente, vá no mesmo cmd e digite ``py voter.py``

Mantenha o chrome aberto para ele ficar votando, pode minimizar sem problemas.

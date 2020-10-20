# API de Games
### Esta API é utilizada como estudo do curso

## Endpoints
### GET /games
Esse endpoint é responsável por retornar a listagem de todos games cadastrados no banco de dados.
#### Parâmetros
Nenhum
#### Respostas
##### OK! 200
Caso essa resposta aconteça você irá receber a listagem de todos os games
Exemplo de resposta:
```
aksjdalkjsd

adlkalskda


asdlka;sd

```
##### Falha na autenticação! 401
Caso essa resposta aconteça, isso significa que aconteceu alguma falha


### POST /auth
Esse enpoint é responsável por fazer o processo de login
#### Parâmetros
```
email: E-Mail do usuário cadastrado no sistema.
senha: Senha para o e-mail enviado
```


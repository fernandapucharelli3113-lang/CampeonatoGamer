# Campeonato de Gamer

## Situação-problema 

Nossa turma vai organizar partidas de jogos. Queremos registrar **jogo**, **time A**, **time B**, **placar** e **status**. Uma partida começa `agendada` com placar `0 X 0`. Depois podemos atualizar o resultado para `finalizada`.

Ao final. a API terá estas rotas:

|Método | Rota | O que faz|
|---    |---   | ---|
|Get    |`/`   | Confirma que a Api está funcionando|
|Get    |`\partidas` | Lista e filtra partidas|
|Get    |`\partidas:id` | Buscar uma partida|
|Post   |`\partidas` | Cadastrar uma partida|
|Put    |`\partidas` | Alterar uma partida e o placar |
|Delete |`\partidas` | Exclui uma partida|


## Etapa 1 - Criar o projeto

No terminal, digite **uma linha por vez**;

```bash
    mkdir CampeonatoGamer
    cd CampeonatoGamer
    npm init -y
    npm install express cors
    code .
```"# CampeonatoGamer" 
"# CampeonatoGamer" 
"# CampeonatoGamer" 

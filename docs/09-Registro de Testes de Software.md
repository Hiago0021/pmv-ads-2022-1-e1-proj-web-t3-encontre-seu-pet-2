# Registro de Testes de Software

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>, <a href="8-Plano de Testes de Software.md"> Plano de Testes de Software</a>

Relatório com as evidências dos testes de software realizados no sistema pela equipe, baseado em um plano de testes pré-definido.

## Página de Cadastro de Animais

Aqui consta um erro de "required" , não seria necessário pois acaba selecionado ambos e não dando andamento a próxima página.

![Falha em botões de Genêro](https://user-images.githubusercontent.com/79429140/173264476-8d498fd4-20a6-44a0-9986-eba886a87236.png)

Erro também localizado nos botões de escola de porte do animal, nos próximos testes iremos corrigir tendo obrigatoriedade em selecionar apenas um botão.

![Falha em botões de porte do animal](https://user-images.githubusercontent.com/79429140/173265429-a10e4e21-d5cb-4c53-98de-8d918551f552.png)




Discorra sobre os resultados do teste. Ressaltando pontos fortes e fracos identificados na solução. Comente como o grupo pretende atacar esses pontos nas próximas iterações. Apresente as falhas detectadas e as melhorias geradas a partir dos resultados obtidos nos testes.

> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)

## HomePage

![home22](https://user-images.githubusercontent.com/103226164/173270203-36f7ecdb-e947-45e8-b4b2-3eec0d861111.png)


Durante os testes com o Javascript da Homepage. O campo de busca não comportou corretamente com o banco de dados que existia, portanto foi decidido por hora, retirar a searchbar até solucionar o campo de busca, isto é, inserir um banco de dados via arquivo ou pela função *get*, por meio de uma API.

## Página de Cadastro de Usuário

![cadastro21](https://user-images.githubusercontent.com/103226164/173269735-cd1b09fb-e961-470a-a6dd-e530f4a70797.png)

No cadastro de usuários, houve um erro no Javascript que não retornava o usuário cadastrado. Felizmente, foi contornado o erro.

# Como ter um bom work flow com git
O git é essencial para o trabalho em equipe, porém se não for utilizado da forma ideal, pode ser um pesadelo. É interessante seguir boas práticas e padrões, para ter um bom fluxo de trabalho com o git. Imagina que você está entrando em um novo projeto, não tem documentação e quando você vai ver o histórico de commits e pull requests, as mensagens de commit não estão auto explicativas, e as pull requests não possuem um comentário se quer?

Com certeza todos já passaram ou ainda passarão por isso, mas não se preocupe, pois você agora vai ter uma base do que fazer, abaixo vou deixar dicas e boas práticas (lembrando que isso é o que eu utilizo e deu muito certo comigo, caso queira mudar algo, basta usar isso aqui como base).

# Padrões de commit
O commit ideal (minha opinião) possui os seguintes requisitos:
* Poucas alterações
* Cada commit referente a uma tarefa
* A mensagem do commit deve ser curta, porém auto explicativa (nada de "nova feature")
* É interessante seguir esse padrão:

  tipo de alteração: mensagem auto explicativa
  
  Exemplo:
  ```
  feat: adicionando atualização de tarefas
  ```
  Caso queira dar uma olhada nos demais tipos de alterações, basta acessar esse link: [https://github.com/iuricode/padroes-de-commits](https://github.com/iuricode/padroes-de-commits)

# Padrões de pull requests
É muito importante documentar as alterações, deixando tudo o mais claro possível, do que foi feito, como foi feito, etc. Isso ajuda quem está fazendo a revisão da pull request e também será útil, para em caso de problemas futuros, seja mais fácil identificar onde ocorreu um possível erro ou bug.

**Por exemplo**: Vamos supor que você está trabalhando em um projeto que é um sistema de pedidos, só que por algum motivo, os clientes reportam um problema na consulta de um pedido específico, sendo que a útlima tarefa referente a esse recurso, foi há 1 dia atrás (juntamente com mais 4 outras tarefas de outros recursos), sendo que até essa última alteração ser realizada, a consulta de pedidos estava funcionando. Concorda comigo que é muito mais fácil ir no histórico de pull requests e como já se tem um padrão de commits, você consegue pesquisar por palavras chave, como `feat` ou `consulta de pedido`. Dessa forma você vai localizar a pull request referente a útlima tarefa em consulta de pedidos, vai entender **O QUE** foi feito, **ONDE** foi feito e **PORQUE** foi feito, assim aumentando suas chances de corrigir o problema de uma forma eficiente e rápida. 

Mas agora a pergunta que fica, qual seria um exemplo de documentação de pull request? vamos lá, vou deixar abaixo o que eu utilizo como padrão e você também pode usar e fazer as devidas alterações, entenda esse padrão como um norte, um ponto de partida, não uma regra.

O padrão que utilizo é dividido em 3 partes:

* Informações sobre a alteração (título, descrição)
* O que foi feito
* Conclusão ou resultado

Na prática, fica assim:

![Screenshot 2024-10-16 234726](https://github.com/user-attachments/assets/79f96dce-89e1-49a3-878f-20d27576a2bb)

Dessa forma, buscando por uma pull request X, logo de cara eu já sei do que se trata, o que foi feito e o resultado de tudo.

# Conclusão
Pronto, agora você já tem um git-flow padronizado, usando boas práticas para o trabalho em equipe. É importante lembrar que nada aqui é uma regra, você só vai utilizar tudo isso como exemplo e adaptar para o seu contexto e do seu time.

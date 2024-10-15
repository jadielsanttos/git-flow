# Como ter um bom work flow com git
O git é essencial para o trabalho em equipe, porém se não for utilizado da forma ideal, pode ser um pesadelo. É interessante seguir boas práticas e padrões, para ter um bom fluxo de trabalho com o git. Imagina que você está entrando em um novo projeto, não tem documentação e quando você vai ver o histórico de commits e pull requests, as mensagens de commit não estão auto explicativas, e as pull requests não possuem um comentário se quer?

Com certeza todos já passaram ou ainda passarão por isso, mas não se preocupe, pois você agora vai ter uma base do que fazer, abaixo vou deixar dicas e boas práticas (lembrando que isso é o que eu utilizo e deu muito certo comigo, caso queira mudar algo, basta usar isso aqui como base).

# Padrões de commit
O commit ideal (minha opinião) possui os seguintes requisitos:
* Poucas alterações
* Cada commit referente a uma tarefa
* A mensagem do commit deve ser curta, porém auto explicativa (nada de "nova feature")
* É interessante utilizar seguir esse padrão:

  tipo de alteração: mensagem auto explicativa
  
  Exemplo:
  ```
  feat: adicionando atualização de tarefas
  ```
  Caso queira dar uma olhada nos demais tipos de alterações, basta acessar esse link: [https://github.com/iuricode/padroes-de-commits](https://github.com/iuricode/padroes-de-commits)

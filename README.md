Spy Board Game
==============

####Tema
Boardgame, espionagem, coop, geraçao aleatória do terreno

###Design
Todo jogador é um espiao.

O terreno é formados por dois tipos de peças distintas: Corredor e Sala.
Todas as peças de terreno tem tamanho de 5x5 casas.

O objetivo do jogo é adquirido escolhendo uma carta de um baralho de objetivos.
Cada carta de objetivo explica açoes que devem ser feitas em salas específicas
para que o objetivo seja válido.
Concluido os objetivos, os espioes devem voltar à sala inicial para que obtenha
a vitória.

O jogo se divide em dois turnos: o turno dos espioes e o turno dos guardas.
No turno dos espioes, todos os jogadores agem. A ordem com que os espioes agem
é definida pelos jogadores.
No turno dos guardas, todos os guardas agem.

####Corredor
Cada corredor tem no mínimo duas saidas.
Os corredores podem dar acesso a salas.

####Sala


####Espiao
Cada espiao pode usar, inicialmente, 5 custos de açao por turno.
Cada vez que um espiao receber um ataque de um guarda, ele perde 1 (um) no seu custo total de açoes.

#####Açoes
Cada açao possui um _Custo de Açao_.
Toda vez que uma açao é efetuada, o _Custo de Açao_ daquela açao é reduzida da quantidade
de açoes do espiao que a efetuou.

- [1] Andar
- [2] Andar furtivo
- [2] Correr (o espiao anda três casas e gera um marcador de ruído em cada casa)
- [3] Nocautear
- [2] Arrombar (lockpick)
- [1] Fazer ruído

####Guarda
Os guardas sao unidades geradas dentro do terreno (podendo ser gerados tanto nos corredores quanto nas salas).

#####Alerta
O guarda entra em alerta se um espiao estiver passado na sua visao no turno dos espioes (salvo o caso de o
espiao estar andando furtivamente) ou se durante uma movimentaçao do guarda, um espiao entrar em sua visao.

![Alert table](/SpyBoardGame/img/alert.png?raw=true)

#####Suspeita/Ruído
O guarda gera um marcador de suspeita no terreno na casa seguinte a última casa na sua visao que um espiao passou.

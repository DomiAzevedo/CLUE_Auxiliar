# Jogo CLUE

Clue é um jogo de tabuleiro de detetive, o seu objetivo é descobrir quem matou, onde matou, e com o que matou. Cada jogador possui uma certa quantidade de cartas, que são 
distribuídas em ordem (alguns jogadores podem ficar com cartas a mais que outros). As cartas podem ser de três tipos: armas, lugares ou pessoas.

No início, uma carta de cada tipo é retirada e não são reveladas a ninguém. Então um crime ocorreu na mansão, agora os jogadores precisam descobrir quem matou, onde matou, 
e como matou, ou seja, cada uma das cartas não reveladas. Os jogadores fazem isso dando palpites, e, caso tenham certeza, fazer uma acusação. Um palpite funciona da seguinte 
forma: o jogador diz uma carta de cada tipo, que acredite ser as cartas não reveladas, e, em ordem, os outros jogadores dizem se possuem ou não alguma daquelas cartas. 
Em caso negativo a pergunta é repassada para outro jogador na ordem até que a resposta seja positiva ou ninguém tiver alguma das cartas. Em caso afirmativo, o jogador 
deve motrar sua carta apenas para quem fez o palpite, e o jogo continua. Caso o jogador queira fazer uma acusação, ele olha as cartas não reveladas, se estiver correto ele
as mostra, e se estiver errado ele é eliminado e o jogo continua com os jogadores restantes.

Há um exemplo de jogo real, este jogo foi feito para 7 jogadores, cada um tendo 3 cartas, não necessariamente uma de cada tipo, haviam 7 armas, 7 pessoas e 10 lugares. 
No exemplo eu sou um jogador e preciso edivinhar as cartas não reveladas com base nos palpites de outros jogadores, as respostas e informações que me são dadas.

O código atualmente não ensina ninguém a jogar, ele auxilia em um jogo real, você precisa ter o tabuleiro e coisas como dar um palpite apenas no lugar em que você 
entrou movimentando a peça pelo número que saiu nos dados, oi mover a peça até tal lugar por um palpite não são levados em consideração, para saber mais sobre o jogo 
você pode ver esse vídeo: [Como Jogar Clue](https://www.youtube.com/watch?v=HNo9GTLPIiQ).

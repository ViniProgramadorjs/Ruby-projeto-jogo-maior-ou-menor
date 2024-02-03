# Ruby-projeto-jogo-maior-ou-menor

Esse código Ruby representa um jogo simples de adivinhação. Aqui está uma explicação resumida de cada função e do fluxo principal do programa:

"da_boas_vindas": Exibe uma mensagem de boas-vindas e solicita o nome do jogador.

"pede_dificuldade": Pergunta ao jogador sobre o nível de dificuldade desejado e retorna a escolha do jogador.

"sorteia_numero_secreto"(dificuldade): Com base no nível de dificuldade escolhido, gera e retorna um número secreto.

"pede_um_numero"(chutes, tentativa, limite_de_tentativas): Solicita um palpite ao jogador, exibindo informações sobre as tentativas anteriores e retorna o número inserido pelo jogador.

"verifica_se_acertou"(numero_secreto, chute): Compara o palpite do jogador com o número secreto e fornece feedback sobre se o palpite está correto, maior ou menor. Retorna true se o jogador acertou.

"ganhou": Exibe uma mensagem de vitória animada quando o jogador acerta o número secreto.

"joga"(nome, dificuldade): Inicia o jogo, sorteia um número secreto com base na dificuldade e permite ao jogador fazer palpites até acertar ou atingir o limite de tentativas.

"nao_quer_jogar"?: Pergunta ao jogador se deseja jogar novamente e retorna true se a resposta for "N" (não).

No final do código, o programa principal inicia saudando o jogador, pedindo o nível de dificuldade e, em seguida, entra em um loop onde o jogo é jogado repetidamente até que o jogador decida não jogar novamente.

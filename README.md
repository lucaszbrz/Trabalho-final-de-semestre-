RPG de Aventura – Restaure o Tempo
Descrição do Jogo

"RPG de Aventura – Restaure o Tempo" é um jogo de RPG em Python, onde o jogador embarca em uma jornada para restaurar o fluxo do tempo.
Você deve explorar áreas, coletar itens, completar quests, enfrentar inimigos e derrotar bosses, em três níveis desafiadores:

Lagoa dos Dragões

Berço de Kharzuth

Castelo de Drenvaar

Ao final da aventura, você encontrará desafios finais que testarão seu conhecimento e suas habilidades.

Estrutura do Projeto

O projeto é composto por dois arquivos principais:

1. rpg_main.py

Contém a lógica principal do jogo:

Exploração de áreas e eventos aleatórios.

Sistema de batalha contra inimigos e bosses.

Sistema de inventário e atributos do jogador.

Interação com NPCs e vendedores.

Quests de coleta de baús.

Desafio final do goblin.

Comandos durante o jogo:

Comando	Função
/inventario ou /inventário	Mostra o inventário do jogador
/atributos	Mostra atributos do jogador e permite upar
/ajuda ou /help	Mostra lista de comandos
/sair	Sai do jogo
2. classes_do_rpg.py

Define classes e funções auxiliares usadas no jogo principal:

Classes:

Personagem: jogador com atributos, inventário e habilidades.

Inimigo: inimigos e bosses.

NPC: personagens que oferecem quests.

Quest: sistema de quests e recompensas.

Funções auxiliares:

escolher_classe(): escolha da classe do jogador.

narrativa_inicio(): introdução à história.

Itens de cada fase:

itens_1, itens_2, itens_3.

Deve estar no mesmo diretório que rpg_main.py.

Como Jogar

Certifique-se de que ambos os arquivos (rpg_main.py e classes_do_rpg.py) estão no mesmo diretório.

Execute o jogo pelo terminal:

python rpg_main.py


Escolha sua classe e siga as instruções.

Explore, colete itens, enfrente inimigos e complete quests.

Resolva o desafio final do goblin para completar a aventura.

Mecânicas do Jogo

Exploração: Encontros aleatórios com inimigos, baús, NPCs e vendedores.

Batalha: Sistema de turnos com ataques, esquivas e habilidades especiais.

Inventário: Armas, escudos e poções de cura com durabilidade e efeitos.

Quests: Missões de coleta de baús com recompensas em moedas.

Bosses: Chefes com habilidades especiais de cada fase.

Desafio Final: Enigma do goblin que recompensa moedas ou causa dano.

Itens por Fase
Fase	Item	Tipo	Ataque/Defesa	Durabilidade	Cura
1	Espada quebrada	Arma	5	10	-
1	Escudo de madeira	Defesa	-	15	-
1	Poção de cura pequena	Cura	-	-	10
1	Katana enferrujada	Arma	7	8	-
2	Espada longa	Arma	10	20	-
2	Escudo de ferro	Defesa	-	20	-
2	Poção de cura média	Cura	-	-	20
2	Katana afiada	Arma	12	15	-
3	Espada Sagrada	Arma	15	30	-
3	Escudo Forjado	Defesa	-	35	-
3	Poção de cura grande	Cura	-	-	30
3	Katana lendária	Arma	20	25	-
3	Cajado do Mago Supremo	Arma	15	28	-
Inimigos Aleatórios
Nome	Nível	Vida	Ataque	Defesa	Habilidade
Goblin	2	12	6	1	veneno
Esqueleto	3	14	8	1	fúria
Orc	4	16	10	2	fúria
Slime	1	10	4	2	cura
Lobo Sangrento	3	15	6	1	fúria
Espectro	2	12	5	3	veneno
Morto-vivo	3	14	7	2	cura
Minotauro	5	18	9	1	fúria
Bosses
Nome	Nível	Vida	Ataque	Defesa	Habilidade
Dragão Ancião	8	30	12	4	fúria
Kharzuth - Criador dos Dragões	12	35	15	5	cura
Drenvaar - Senhor do Tempo	18	40	18	6	veneno
Requisitos

Python 3.x

Bibliotecas padrão: random, time

Possíveis Melhorias

Adição de novas classes, habilidades e magias.

Novos inimigos e bosses.

Novos itens e armas especiais.

Eventos aleatórios adicionais.

Sistema de habilidades especiais ou magias complexas.

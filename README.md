# CaiPalavra

**Desenvolvido para a disciplina de Prática de Programação usando JavaFX**

# Menu do Game

![Menu do Game](https://i.imgur.com/LtxwoLT.png)

### In-Game

![Game](https://i.imgur.com/zo6sXIr.png)

#

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal.
- **JavaFX**: Framework para construção da interface gráfica do usuário.
- **FXML**: Linguagem para a definição da interface gráfica em arquivos XML.
- **CSS**: Para estilização dos componentes visuais.
- **Áudio**: Sons e músicas em formato `.mp3` para eventos no jogo.
- **Imagens e Sprites**: Elementos gráficos utilizados para ícones, animações e plano de fundo.

## Regras do Jogo

1. O jogador deve digitar as palavras que aparecem caindo na tela.
2. Cada palavra digitada corretamente concede uma pontuação baseada na sua complexidade.
3. Se a palavra chegar ao fundo da tela sem ser digitada, o jogador perde uma das três vidas.
4. O objetivo é manter o maior número de vidas e acumular a maior pontuação possível.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **src**: Contém o código-fonte do jogo, incluindo controladores, lógica de pontuação e utilitários.
- **resources**: Inclui os recursos utilizados no jogo, como sons, imagens e sprites.
- **build**: Contém os arquivos compilados do projeto.
- **scoresArchive.dat**: Arquivo que armazena os recordes de pontuação.

## Funcionalidades

- **Menu Principal**: Interface inicial do jogo onde o jogador pode iniciar uma nova partida.
- **Jogo**: Durante a partida, o jogador precisa digitar rapidamente as palavras que caem da tela para evitar perder vidas.
- **Game Over**: Quando o jogador perde todas as vidas, o jogo exibe uma tela de fim de jogo com a opção de reiniciar ou voltar ao menu principal.

## Como Jogar

1. Execute o arquivo principal do jogo.
2. No menu inicial, clique em "Iniciar Jogo" para começar.
3. Durante o jogo, digite as palavras que aparecem antes que cheguem ao fundo da tela.
4. Tente bater o seu recorde de pontuação!

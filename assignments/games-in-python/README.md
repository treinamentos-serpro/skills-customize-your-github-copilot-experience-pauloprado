
# 📘 Assignment: Hangman Game

## 🎯 Objective

Crie uma versão jogável do jogo da Forca em Python. A atividade pratica manipulação de strings, seleção aleatória, condicionais, loops e entrada de dados.

## 📝 Tasks

### 🛠️ Set up the game

#### Description
Selecione uma palavra aleatória da lista fornecida e inicialize as variáveis necessárias para acompanhar os palpites e as tentativas incorretas.

#### Requirements
O programa concluído deve:

- Escolher aleatoriamente uma palavra da lista `words`.
- Manter o registro das letras já adivinhadas.
- Definir e acompanhar o limite de tentativas incorretas.

### 🛠️ Implement the guessing loop

#### Description
Implemente o loop principal para receber palpites, atualizar o progresso da palavra e encerrar o jogo quando o jogador vencer ou ficar sem tentativas.

#### Requirements
O programa concluído deve:

- Mostrar as letras adivinhadas nas posições corretas e `_` nas posições ainda não reveladas.
- Solicitar uma letra ao jogador e atualizar o estado do jogo conforme o palpite.
- Reduzir as tentativas restantes quando o palpite não estiver na palavra.
- Encerrar quando a palavra for revelada ou não houver mais tentativas incorretas.
- Exibir uma mensagem indicando vitória ou derrota; em caso de derrota, revelar a palavra escolhida.
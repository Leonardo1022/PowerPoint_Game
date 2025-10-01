# PowerPoint_Game

  Este é um jogo estilo _bullet hell_ feito inteiramente em Power Point.

# Como jogar

- Instale o arquivo .pptx e execute ele no Power Point (É de extrema importância que seja no App e não na versão web)
    - [Link para o arquivo](https://github.com/Leonardo1022/PowerPoint_Game/blob/main/jogoEmPP.pptx)
- Para jogar selecione a opção de apresentar slide e siga as instruções pelo próprio slide

# Processo de criação

  Ele funciona primariamente pela capacidade do Power Point de adicionar eventos a formas quando se ela é clicada ou quando o cursor passa por cima, esses eventos podem ser para mudar de slide, parar a apresentação etc, o que juntamente com a animação de formas possibilita a criação de diversos tipos de jogos baseadas nessa interação do cursor.
  A ideia de utilizar o Power Point desse jeito veio devido a esse vídeo no youtube: https://youtu.be/Ha6j3NxEPZI?si=DHQ3QHT6TxYC_o3V

# Problemas
- A tela de edição fica muito poluída após certo progresso, o que dificulta em alterações, além de que pela programação dos itens ser definida de forma que dependa do tempo decorrido pode ser muito demorado fazer alguma alteração num evento antigo.
- Por fim, o maior problema encontrado é uma falha na ativação de evento, em que é realizada uma ação (como ir para o próximo slide) apenas quando o mouse passa por cima do objeto, e não o contrário, o que resulta numa invensibilidade do jogador quando ele deixa o cursor em repouso.

README - Software Educacional de Memorização de Formas
Descrição
Este é um jogo educacional simples que ajuda a melhorar a memória visual dos alunos, com foco no reconhecimento e memorização de formas geométricas. O jogo envolve a apresentação de uma forma aleatória que o jogador precisa memorizar. Após um tempo, o jogador deve identificar a forma correta entre várias opções apresentadas.

Funcionalidade
O objetivo do jogo é desafiar o jogador a lembrar-se de uma forma específica e identificar essa forma entre várias opções. O jogo segue os seguintes passos:

Tela de Jogo Inicial: O jogador clica no botão "Jogar", e o jogo começa, exibindo uma forma para o jogador memorizar por um tempo.

Exibição da Forma Aleatória: Uma imagem aleatória é exibida ao jogador por 5 segundos.

Seleção da Forma Correta: Após 5 segundos, três opções de formas aparecem, e o jogador deve selecionar a forma correta.

Pontuação: O jogador ganha um ponto cada vez que escolhe a forma correta. A pontuação é exibida na tela.

Repetição do Jogo: O jogo continua, gerando novas imagens aleatórias para o jogador memorizar e escolher.

Estrutura do Código
O código está dividido em funções e eventos que controlam o fluxo do jogo. As principais funcionalidades são:

Variáveis Globais
imagens: Uma lista de strings representando o nome das imagens que são exibidas no jogo.

imagem_aleatoria: A imagem que o jogador deve memorizar.

placar: A pontuação do jogador, que aumenta cada vez que a forma correta é selecionada.

indiceAleatorio: Um índice aleatório utilizado para selecionar a imagem a ser exibida.

Funções Principais
onEvent("jogar", "click"): Ao clicar no botão "Jogar", a tela é alterada para a tela de memorização. Uma imagem aleatória é gerada e mostrada por 5 segundos antes de o jogador ter que identificar a forma.

onEvent("opcao1", "click"): Quando o jogador clica na primeira opção, verifica-se se a imagem associada à opção é igual à imagem que o jogador deve memorizar. Se for correta, a pontuação é aumentada em 1.

onEvent("opcao2", "click"): O comportamento é o mesmo do evento "opcao1", mas para a segunda opção.

onEvent("opcao3", "click"): O comportamento é o mesmo do evento "opcao1", mas para a terceira opção.

gerador_imagem_aleatoria(): Gera uma imagem aleatória da lista imagens e a exibe na tela para que o jogador memorize.

mostrar_imagem_lugar_aleatorio(): Exibe a imagem aleatória em uma das três opções, enquanto as outras opções mostram imagens aleatórias diferentes.

Fluxo do Jogo
Tela de Memorização: Uma imagem aleatória é mostrada.

Tela de Seleção: O jogador deve escolher qual das opções corresponde à imagem mostrada na tela de memorização.

O jogo segue com a alternância entre as telas até que o jogador decida parar.

Tecnologias Utilizadas
HTML: Para estruturar o layout da página.

JavaScript: Para controlar a lógica do jogo e a interação com o usuário.

Eventos: São usados para detectar as interações do usuário com os botões.

Como Jogar
Clique no botão "Jogar" para começar.

Memorize a forma exibida na tela.

Quando a tela mudar, selecione a forma que você memorizou entre as opções.

Se você acertar, seu placar aumentará. O jogo continuará até que você decida parar.

Melhorias Futuras
Adicionar níveis de dificuldade (formas mais complexas ou mais opções de escolha).

Adicionar um contador de tempo para aumentar a pressão e melhorar a experiência.

Incluir mais tipos de formas e personalizações no design das imagens.

Contribuições
Contribuições são bem-vindas! Se você tiver sugestões ou melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

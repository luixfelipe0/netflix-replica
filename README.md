# netflix-replica
Réplica da página inicial da Netflix usando HTML, CSS e um pouco de JavaScript

Fiz esse projeto com base no desafio #7DaysofCode, da Alura. A ideia inicial era usar apenas HTMl e CSS mas com o decorrer da produção, percebi que utilizar o JavaScript para o slide de filmes e séries seria mais fácil e me pouparia umas boas linhas de código.

<h1>Descrição do projeto</h1>

Começamos pelo header da página, onde temos a logo da Netflix, e uma lista de menu de navegação, quando passado o mouse por cima da lista de links, sua cor é alterada para vermelho, afim de orientar o usuário, no canto direito temos os ícones de pesquisa, notificações e user. Esses ícones não são funcionais, estão ali apenas para ilustrar.
Logo após temos o banner principal da página, onde temos o pôster do filme, o título, sua descrição e dois botões que simulam os botões de assistir o filme em questão, e mais informações sobre o mesmo, detalhe que eles também fazem o uso da pseudo-classe :hover, quando passado o mouse por cima eles alteram suas cores para vermelho.

![Captura de tela do cabeçalho e header da página](https://user-images.githubusercontent.com/119303049/218470927-1a402407-e9bc-4cc5-a3f2-60cbde1fc6b8.png)

Logo abaixo temos uma lista de pôsteres com filmes e séries, separadas por sessão, Minha lista, Em alta e Séries estrangeiras. Passando o mouse por cima o pôster diminui levemente o tamanho e ganha uma borda vermelha, para orientar melhor o usuário.

![Captura de tela da sessão de catálogo da página](https://user-images.githubusercontent.com/119303049/218471527-cec023b9-dbf8-4ec8-aba5-540aa8586f96.png)

Há mais um trilho de séries e filmes nessa sessão, porém esse poossui um diferencial que é o carrossel implementado para que o usuário possua mais opções, essa carrossel possui dois botões para navegação na cor vermelha, que quando passado o mouse por cima, fica na cor branca, e quando pressionado, retorna a cor vermhelha padrão, para orientar o usuário se o botão está sendo clicado ou não.

![Captura de tela do carrossel na sessão de catálogo da página](https://user-images.githubusercontent.com/119303049/218472112-a16349d5-a515-42de-bed4-e79a9c21e260.png)

Por último mas não menos importante, o rodapé. Contendo os ícones das redes sociais mais utilizadas atualmente, Facebook, Instagram, Twitter e YouTube, com a pseudo-classe :hover eles ficam levemente maiores com a passada do mouse por cima. O rodapé também possui informações cruciais sobre a página, como os termos de uso, informações corporativas, idiomas e legendas etc. Todos utilizando da mesma pseudo-classe :hover, ficando com um aspecto de link, com sublinhado porém com a cor vermelha
Logo abaixo um botão com o código de serviço (também não funcional, apenas ilustrativo) ficando branco com a passada do mouse, e um texto de copyright.

<h1>Tecnologias usadas no Projeto</h1>

No começo o intuito era apenas utilizar o HTML e CSS para a construção do projeto, porém, com o o decorrer da construção, senti que seria mais vantajoso colocar uma pitada de JavaScript para construir o carrossel da sessão de catálogos, então eu importei um plug-in, o SwiperJS, para ser mais fácil.

<h1>Como acessar a página</h1>

Você pode acessar a página do projeto através do link: https://luixx0.github.io/netflix-replica/

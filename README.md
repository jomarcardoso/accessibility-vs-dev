# Acessibilidade: O desenvolvedor não faz tudo
> mas boa parte é ele que faz.

Um dos maiores equívocos de uma empresa, em relação a acessibilidade, é esperar da equipe de desenvolvimento a iniciativa de tornar seu seus sites ou aplicativos acessíveis. A participação do dev é essencial, mas a organização de um projeto acessível deve envolver todos profissionais responsáveis, desde o conteudista, designer, até os profissionais envolvidos da qualidade.

O desenvolvedor é capaz de usar texto alternativo para imagens, cuidar a ordem e a semântica dos elementos que estão em tela ou fazer os saltos de conteúdos muito úteis para com deficiência chegar antes ao que lhe interessa. Já questões como contraste mínimo, texto de fácil interpretação e espaçamentos do mínimos do layout são questões que fogem da sua responsabilidade e precisam da cooperação de todos.

Mas então quais são tarefas do desenvolvedor? Vou listar algumas delas.

## Elementos semânticos

Independente da interface que está sendo usada, seja Web, aplicativo ou desktop, os elementos que irão compor essas aplicações devem ser semânticos (que sejam entendidos além do seu visual), como também organizados em ordem, para que possam ser entendidos. Um botão, uma lista, um título ou qualquer elemento, deve ter seu significado além do que está sendo visto em tela.

## Sequência lógica

O desenvolvedor pode se deparar com a situação em que a versão desktop está com uma sequência correta e ao adaptar para o mobile o conteúdo perdeu a ordem que ele queria (mais um motivo para pensar no mobile primeiro), aí para corrigir isso ele aplica um estilo que ajuste a ordem do conteúdo... Errado visualmente mudou alguma coisa, mas para a navegação com teclado e para leitores de tela aquele conteúdo continua na mesma sequência.

Os títulos também devem seguir uma hierarquia para que o usuário que usar um leitor de telas possa compreender e encontrar o conteúdo que ele deseja (falar sobre os atalhos para headings https://medium.com/@jovoloski/39f13a325366). Os títulos formam uma hierarquia igual aquela utilizada em TCCs, por isso não devemos pular algum deles devido ao seu estilo e muito menos deixar de usar.

![demonstração do aninhamento dos títulos de uma página web](https://user-images.githubusercontent.com/27368585/112071593-ddcf6a80-8b4e-11eb-94d2-0ca137c24522.png)

## Usar alternativa textual

O mais famoso trabalho do desenvovedor em relação a acessibilidade, e talvez o único que eu conhecia antes de estudar sobre o assunto. Um texto alternativo nada mais é que um texto para explicar qualquer coisa que não seja de estrutural que esteja em tela. Engana-se em pensar que isso benefinicia apenas pessoas cegas, o texto alternativo é muito empregado em imagens, mas também pode ser usado em vídeos e áudios, as legendas.

Mas assim como quase tudo na acessibilidade, o texto alternativo também não é apenas para pessoas com deficiência, a prova disso é quando você vê aquele ícone e não sabe o que aquilo faz e coloca o mouse sobre ele na esperança de que apareça um texto explicando o que aquele símbolo significa. Este é um bom exemplo para quem não tem uma grande limição sensorial entender que se para ela um texto auxiliar é útil, imagina para uma pessoa que não enxerga ou alguma que te deficiência de raciocínio.

## Área de toque mínima

Elementos pequenos na tela que são clicáveis ou tocáveis são podem ser desagradáveis para qualquer, mas a situação da pessoa pode piorar se ela tem alguma limitação motora como navegar com por mouse de botões, usando os pés ou até alguma doença que comprometa a precisão de seus movimentos ou de sua visão.

## Navegação com teclado

Não todas as pessoas em um computador são capazes de usar mouse, seja por limitações de visão ou movimento, então é importante que o desenvolvedor tenha feito uma navegação por teclado que esteja na ordem e com um foco visível para aqueles que têm visão porém não navegam usando mouse.

![amostra do site Terra de como ele mostra o foco visível](https://user-images.githubusercontent.com/27368585/112067430-cc826000-8b46-11eb-8361-0793bced04be.png)

## Saltos de conteúdos

Dar a possibilidade de saltar aquelas parte repetidas de página a página como o cabeçalho e a navegação. Inclusive ao fim do conteúdo principal disponibilizar uma forma de voltar ao início.

![amostra de como o Youtube mostra o salto de conteúdo](https://user-images.githubusercontent.com/27368585/112067736-54686a00-8b47-11eb-8e13-55356c3a60e0.png)

## Teclas de atalho

...

## Idioma

...



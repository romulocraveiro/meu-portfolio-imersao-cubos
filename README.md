# Meu Portfolio

## Objetivos / Aims

* Fazer meu portfólio a partir do modelo apresentado nas aulas da "Imersão Programação do Zero" da Cubos Academy.
* Make my portfolio from the model presented during the "Imersão Programação do Zero" classes at Cubos Academy.<i> </i>

## Problemas que consegui resolver / Problems I was able to solve

* Minha foto de perfil estava distorcendo (encurtando na horizontal) quando eu a estilizava no CSS com border-radius 50%. Para resolver o problema, editei-a com o aplicativo Fotos do Windows, tornando-a quadrada.
* _My profile picture was distorted (shrinking horizontally) when I styled it on CSS with border-radius 50%. To solve the problem, I edited it with the app "Fotos" on Windows, making it square._
* Eu não estava conseguindo colocar ícones de algumas instituições. Para resolver o problema, é possível ancorar a logomarca de uma empresa quando ela aparece nos resultados de pesquisa do Google, bastando para isso clicar com o botão direito do mouse, copiar o endereço da imagem e colar no atributo href.
* _I wasn't getting icons from some institutions. To resolve the issue, one can anchor a company's logo when it appears in Google search results by simply right-clicking, copying the image address, and pasting it in the href attribute._


* Quando abria a página no local host, título, profissão e coluna maior ficavam alinhadas. Porém, na página criada pelo GitHub, o header ganhava proporção maior e desalinhava tudo. Aprendi que a página do GitHub pode levar algum tempo para ficar totalmente pronta. Quando a visitei depois, estava tudo certo. Exceto por uma coisa que explicarei adiante.

* _When I opened the page on local host, the title, occupation and greater column in the main were aligned. However, on the GitHub page, the header was would grow and misaligned everything. I learned that the GitHub page can take a while to get ready. When I visited it again, everything was fine. Except for one thing that I will explain in the next item._

* Ao variar o tamanho da tela, a coluna maior ("Habilidades") se movia. Resolvi o problema com a propriedade `flex: 0 0 auto` que quer dizer flex grow = 0, flex shrink = 0, e flex basis = 0. Sem isso, a coluna menor à esquerda crescia e "empurrava" a coluna maior à direita.

*_When I changed the screen size, the greater column ("Habilidades") would move. I solved the problem with the property `flex: 0 0 auto`, which means flex gro = 0, flex shrink = 0, and flex=basis = 0. Without that, the minor column on the left would grow and "push" the greater column to the right._


## Algumas lições que aprendi / Some lessons I learned

* Em CSS, quando vamos estilizar a borda de alguma div, temos que informar 3 coisas: quantos pixels, o tipo, e a cor.
* Existem elementos que reservam, ocupam uma linha inteira, outras ficam no meio do texto mesmo.
* O elemento `<span><span/>` é um dos que ficam no meio do texto(Ele pode ser usado para agrupar elementos para fins de estilo (usando os atributos `class` ou `id)`
* A div, a h1, etc.,  por padrão, reservam uma linha inteira.
* Chamamos a essa característica "display".
* Para agrupar o conteúdo ao lado da imagem estilizamos "display: inline-block;" no css
* Classe é um atributo, assim com src, id, etc.
* O que listamos em css, dentro das chaves, são "propriedades".
* Via de regra, é melhor formatar um mesmo seletor que se repete no site e depois criar novas classes ou ids para características específicas.
* Por padrão, listas são recuadas (indented) e com bullet points. Para retirar tais características, é necessário estilizar no css com "list-style-type: none; e "padding: 0;
* O peso padrão de uma fonte (font-weight) é de 400px. Negrito: 700px.

## Tecnologias / Technologies

* CSS
* HTML

## Links 

* [Cubos Academy](https://cubos.academy/)

## Autor / Author

| Foto                                                   | Nome                               | GitHub                                               | Likedin                                                 | E-mail                   |
| ------------------------------------------------------ | ---------------------------------- | ---------------------------------------------------- | ------------------------------------------------------- | ------------------------ |
| <img src="./img/fotogit.jpeg" width="100px"> | Romulo Craveiro de Sousa Tartaruga | [Romulo Craveiro](https://github.com/romulocraveiro) | [Linkedin](https://www.linkedin.com/in/romulocraveiro/) | romulocraveiro@gmail.com |
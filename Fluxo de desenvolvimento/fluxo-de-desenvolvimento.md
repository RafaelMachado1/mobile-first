# Fluxo de desenvolvimento
## Base do projeto
* Link para acessar o
[ Figma do projeto Alura Books](https://www.figma.com/file/sSMbIqKaGBd66Y8roxTk2p/AluraBooks?node-id=37-94&t=Z8etnyZgy9C8Rfiu-0)

* Estruturando o HTML
Quando começamos qualquer projeto HTML, construímos uma estrutura básica de tags. Você pode consultar sobre estas tags e sua importância no artigo [“O que é o HTML e suas tags? Parte 1: estrutura básica”](https://www.alura.com.br/artigos/o-que-e-html-suas-tags-parte-1-estrutura-basica).

* Variáveis CSS
permitem armazenar e atualizar valores, que podem ser utilizados em vários lugares diferentes.
```CSS
:root {
    --cor-de-fundo: #EBECEE;
}
```

## O reset.css
Para evitar inconsistências, foi criado o reset.css, que faz uma limpeza nas estilizações do navegador. Você pode descobrir mais sobre ele no artigo [“Reset CSS: O que é, Exemplos, Como Criar e Utilizar”](https://www.alura.com.br/artigos/o-que-e-reset-css) 


## header_Flexbox_@import
display:flex em um elemento de bloco, transformando ele em um flex-container e os seus filhos em flex-itens. Caso você queira saber mais sobre flexbox, nós temos o artigo [“Flexbox CSS: Guia Completo, Elementos e Exemplos”](https://www.alura.com.br/artigos/css-guia-do-flexbox) e o Alura+ [“CSS FlexBox: Dicas para começar”.](https://cursos.alura.com.br/extra/alura-mais/css-flexbox-dicas-para-comecar-c301)

## menu-hamburguer
* Interação com clique?<br>
Ao construir a interação do usuário com o ícone do menu hambúrguer, aplicamos uma label associada ao id de um input checkbox. Esse tipo de interação sem o uso de Javascript também pode ser usado para outros casos, como é feito no Alura+ [“Animação de coração: um projeto em HTML/CSS”](https://cursos.alura.com.br/extra/alura-mais/animacao-de-coracao-um-projeto-em-html-css-c1360), em que simulamos uma animação de preenchimento quando o ícone de coração é clicado.

* Positions<br>
Ainda no menu hambúrguer, tivemos que usar as positions para posicionar a lista de links no lugar certo: abaixo do header. No header, colocamos a position relative, que permite aplicar propriedades como top, bottom, left e right. Já na lista, colocamos o absolute, que posiciona o elemento de acordo com outro que esteja em posição diferente de static (nesse caso, o elemento do menu). Para entender melhor sobre positions para usar em outros projetos, temos o artigo [“Entenda a propriedade position CSS”](https://www.alura.com.br/artigos/entenda-a-propriedade-position-css) feito pelo instrutor Luan Alves.
<br>
Por fim,  é importante saber sobre as diferentes unidades responsivas para utilizar em futuros prjetos. E pra isso também temos o artigo [“Guia de unidades no CSS”](https://www.alura.com.br/artigos/guia-de-unidades-no-css), feito pelo Paulo Scalercio.


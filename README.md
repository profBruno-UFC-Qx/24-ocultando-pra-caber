# Descrição

Neste exercício, você irá criar um layout de 3 colunas que oculta conteúdo não essencial em telas menores usando media queries. 

O objetivo é garantir que o conteúdo principal seja exibido de maneira clara e eficaz em dispositivos com tamanhos de tela reduzidos.

O objetivo deste exercício é praticar o uso de seletores CSS pseudo-classes.

**Todas as alterações devem ser feitas nos arquivos já existentes**

* src/index.html -> quando for necessário alterar HTML
* src/css/estilo.css -> quando for necessário alterar CSS
* src/js/script.js -> quando for necessário alterar JavaScript

## Instruções:

1. Altere o arquivo **src/index.html** e crie as seguintes seções:
    - Cabeçalho usando a tag `header`
    - Menu de navegação usando a tag `nav` 
    - Conteúdo principal usando a tag `main`
    - Anúncios usando a tag `aside`
    - Rodapé usando a tag `footer`
1. Adicione um parágrafo de texto fictício em cada seção.
2. No arquivo **src/css/estilos.css**, aplique estilos para as seções que definem as cores de fundo, larguras, alturas e margens.
3. Em telas maiores que 600 pixels, faça com que:
    - O menu de navegação deve ocupar 25% da largura disponível
    - O conteúdo principal ocupe 60% da largura disponível
    - A seção de anúncios ocupe a largura restante
    - Além disso, deve haver uma margem entre conteúdo da página e a janela do navegador.
4. Usando media queries, ajuste os estilos para que, quando a largura da tela for menor que 600 pixels com o seguinte objetivo:
    - As seções devem se reorganizar em uma única coluna. 
    - A seção anúncio deve ser ocultada.
    - Ajuste a largura e margem das seções para ocuparem a largura total da tela.
5.  Abra o arquivo **index.html** em um navegador para verificar o layout responsivo que você criou. Ajuste a largura da janela do navegador para ver a reorganização das seções.

Dicas:

* Use a propriedade `flexbox` para criar o layout de duas colunas.
* Use a media query `@media screen and (min-width: 600px)`.
* Ajuste as larguras e margens das seções para ocuparem a largura total da tela em uma única coluna.

Ao final do exercício a página deverá ter duas possíveias aparências como mostra a figura abaixo:

![Layout de tres colunas responsivo](src/img/laytou-tres-colunas-responsivo.png)


## Recomendações

**Certifique-se de validar seu código HTML usando um validador como o [W3C Markup Validation Service](https://validator.w3.org/), para garantir que seu código esteja sem erros e bem formado**.

**Experimente validar o seu código CSS em sites como:**

- <a href="https://jigsaw.w3.org/css-validator/" target="_blank">W3C CSS validation Service</a>
- <a href="https://beautifytools.com/css-validator.php" hreflang="en" target="_blank">Beatifytools CSS validator</a>

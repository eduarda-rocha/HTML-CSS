# O que foi aprendido

## Aula 1 - Adaptando a página inicial

* A ajustar a página principal para utilizar os mesmos padrões da página de produtos

* Medidas proporcionais com CSS (`em`)

* Como funciona a flutuação dos elementos e como modificá-la, com a propriedade `float` do CSS

* Como limpar o `float`, com a propriedade `clear` do CSS

## Aula 2 - Conteúdo externo

* A utilizar fontes externas nas nossas páginas

* Como incorporar um mapa à nossa página

* Como incorporar um vídeo à nossa página

## Aula 3 - Melhorando o CSS

* A melhorar mais ainda a semântica da página principal, com novas divisões, classes, etc

* Novas pseudo-classes 

* Como aplicar um background gradiente na página `background: linear-gradient`por exemplo

* Pseudo-elementos `before` `after`

## Aula 4 - Selecionando qualquer coisa

* Seletores avançados CSS

    * Seletor `>`, para acessar os filhos de determinado elemento. Por exemplo, para acessar todos os `p` dentro de `main`:

    ``` 
    main > p{

    }
    ``` 
    * Seletor `+`, para acessar o primeiro irmão de determinado elemento. Por exemplo, para acessar o primeiro `p` após um `img`:
    ```
    img + p{

    }
    ```
    * Seletor `~`, para acessar todos os irmãos de determinado elemento. Por exemplo, para acessar todos os `p` após um `img`:
    ```
    img ~ p{

    }
    ```
    * Seletor `not`, para acessar os elementos, exceto algum. Por exemplo, para acessar todos os `p` dentro de main, exceto o `p` que tem `id missao`:
    ```
    main p:not(#missao){

    }
    ```
* Como fazer contas com CSS, com a propriedade `calc`

## Aula 5 - Opacidade e sombra

* Como manipular a opacidade dos elementos, com a propriedade CSS `opacity` (varia de 0 a 1)

* Como manipular a opacidade das cores `rgba()`

* Como adicionar um sombreamento em volta dos elementos, com a propriedade CSS `box-shadow`(X Y O Cor)

* Como adicionar um sombreamento em textos, com a propriedade CSS `text-shadow`

## Aula 6 - Design responsivo

* Design responsivo: como ajustar o estilo da nossa página de acordo com o tamanho da tela do dispositivo que a acesse

    * `Meta` tag de `Viewport` `<meta name="viewport" content="width=device-width">`
    
    * Media Queries `@media (max-width:)`por exemplo
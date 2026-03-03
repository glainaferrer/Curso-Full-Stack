# INTRODUÇÃO AO CSS
O CSS é uma linguagem de estilo. Ele não cria conteúdo, mas define como o conteúdo HTML deve ser apresentado ao usuário. Com ele, você controla cores, fontes, tamanhos, espaçamentos e até animações.

## Por que usar CSS ?

O CSS é usado para separar o conteúdo do design, permitindo que você controle a aparência de várias páginas simultaneamente em um único arquivo. Isso garante que o site seja organizado, carregue mais rápido e, principalmente, seja responsivo, adaptando o layout para funcionar perfeitamente tanto em computadores quanto em celulares.

## Formas de aplicar CSS:
Inline: Direto na tag HTML (não recomendado para projetos grandes).

<p style="color: blue;">Texto</p>

Internal: Dentro da tag <style> no <head> do próprio HTML.

External (O Padrão): Você cria um arquivo separado (ex: style.css) e o linka no HTML. É a melhor forma de manter o código organizado.


### contextos:
background - cor do fundo
color - cor do texto
font-family - tipo de fontes
font-size - Tamanho da fote
margin - margem (espacamento externo)

CSS{
    background-color: red ;/ cor do fundo
    color: white ; / cor do texto
    font-family: tipo de fonte
    font-size: Tamanho da fonte
    margin: em todas as bordas
    margin: 20px 50 px / 20 px top e bottom, 50px left e right
    margin: 29px 50px 30px 34px / top right bottom left

}

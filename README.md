# Dicas de HTML.
1. **Para criar uma página básica digite ! e tecle enter.**

2. O que é **Colorization**?
O que é: É a técnica de destacar elementos do código com diferentes cores, de acordo com seu significado. Por exemplo, palavras-chave podem ser destacadas em azul, strings em vermelho e números em verde.
Por que é útil: A colorização torna o código mais fácil de ler e entender, ajudando a identificar rapidamente diferentes tipos de elementos e possíveis erros.

3. O que são **Snippets**?
O que são: São pequenos fragmentos de código pré-definidos que podem ser inseridos rapidamente em um documento. Eles podem conter funções, estruturas de controle, templates ou qualquer outro tipo de código reutilizável.
Por que são úteis: Os snippets ajudam a economizar tempo e reduzir a possibilidade de erros de digitação, especialmente para códigos que são frequentemente repetidos. Muitos editores e IDEs permitem criar e personalizar seus próprios snippets.

*Exemplo de um snippet:*
```JavaScript
// Snippet para criar uma função
function ${1:functionName}(${2:parameters}) {
    ${3:body}
}
> Ao digitar func e pressionar Tab, esse snippet será inserido, e você poderá preencher os placeholders (${1}, ${2}, etc.) com os valores desejados.
```

4. **Escapar o Código**
Para exibir o código HTML como texto na página, você precisa "escapar" os caracteres especiais do HTML, como <, >, e &. Isso pode ser feito usando as entidades HTML correspondentes:
    
>    < se torna &lt;
    > se torna &gt;
   & se torna &amp;

*Exemplo*
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mostrar Código HTML</title>
</head>
<body>
    <p>Este é um exemplo de código HTML escapado:</p>
    <pre>&lt;div&gt;Texto&lt;/div&gt;</pre>
</body>
</html>

```

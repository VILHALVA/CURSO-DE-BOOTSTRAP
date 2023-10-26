# DISPLAY FLEX [D-FLEX] EM [BOOTSTRAP] 
A classe `d-flex` em Bootstrap é usada para definir um elemento como um contêiner flexível (flex container). Isso permite que você aproveite as capacidades de layout flexível do CSS para criar layouts responsivos e controlar a posição e a ordenação de elementos filhos dentro desse contêiner. A classe `d-flex` é uma parte fundamental do sistema de layout flexível do Bootstrap.

Aqui está um exemplo de como usar a classe `d-flex` em Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Classe d-flex em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <div class="container mt-4">
        <div class="d-flex">
            <div class="p-2 bg-primary text-white">Item 1</div>
            <div class="p-2 bg-success text-white">Item 2</div>
            <div class="p-2 bg-info text-white">Item 3</div>
        </div>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, aplicamos a classe `d-flex` a um `<div>` para criar um contêiner flexível. Dentro desse contêiner, temos três elementos `<div>` (itens) com classes de cores diferentes. Graças à classe `d-flex`, esses itens são dispostos em linha horizontalmente, aproveitando o layout flexível do Bootstrap.

Você pode usar classes adicionais, como `flex-row`, `flex-column`, `justify-content`, e `align-items`, para controlar ainda mais o layout flexível e a posição dos elementos dentro do contêiner flexível. A classe `d-flex` é uma das muitas classes de layout flexível que o Bootstrap oferece para criar layouts responsivos e dinâmicos. Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap em seu projeto para usar essas classes com eficácia.
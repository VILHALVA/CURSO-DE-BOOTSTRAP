# MARGENS AUTOMÁTICAS CLASSES M-AUTO - DISPLAY FLEX #P4 EM [BOOTSTRAP] 
As classes `m-auto` em Bootstrap são usadas para aplicar margens automáticas a um elemento dentro de um contêiner flexível (criado com a classe `d-flex`). Essas margens automáticas centralizam o elemento horizontalmente em relação ao contêiner pai, o que é especialmente útil para alinhar elementos no centro de uma área de conteúdo.

Aqui está um exemplo de como usar a classe `m-auto` em Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Margens automáticas (m-auto) em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <div class="container mt-4">
        <h4 class="text-center">Margens automáticas (m-auto) em Bootstrap</h4>

        <div class="d-flex">
            <div class="p-2 bg-primary text-white m-auto">Elemento Central</div>
        </div>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, aplicamos a classe `m-auto` a um elemento dentro de um contêiner flexível. Como resultado, o elemento é centralizado horizontalmente dentro do contêiner. Isso é útil para criar layouts responsivos e alinhar elementos no centro, independentemente do tamanho da tela.

Você pode usar a classe `m-auto` em elementos individuais para centralizá-los horizontalmente. Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap em seu projeto para que a classe `m-auto` funcione corretamente.
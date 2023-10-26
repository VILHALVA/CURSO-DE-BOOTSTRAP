# CLASSE BORDER E SUAS VARIAÇÕES EM BOOTSTRAP
O Bootstrap fornece várias classes relacionadas a bordas (border) que permitem estilizar elementos HTML com bordas de diferentes estilos, tamanhos e cores. Vou listar algumas das classes de borda mais comuns em Bootstrap e explicar suas variações:

1. `border`: Esta é a classe base para adicionar uma borda simples a um elemento. Por padrão, ele cria uma borda sólida cinza.

2. `border-0`: Esta classe remove a borda de um elemento. É útil quando você deseja remover uma borda de um elemento que, por padrão, teria uma.

3. `border-top`, `border-end`, `border-bottom`, `border-start`: Essas classes aplicam bordas apenas em um dos quatro lados do elemento, respectivamente: superior, direito, inferior e esquerdo.

4. `border-primary`, `border-secondary`, `border-success`, `border-danger`, `border-warning`, `border-info`, `border-light`, `border-dark`, `border-white`: Essas classes permitem adicionar uma borda colorida ao elemento, usando as cores do esquema de cores do Bootstrap.

5. `border-rounded`: Esta classe arredonda as bordas do elemento, criando cantos arredondados.

6. `border-1`, `border-2`, `border-3`, `border-4`, `border-5`: Essas classes definem o tamanho da borda, onde o número representa a espessura em pixels. Por exemplo, `border-2` cria uma borda de 2 pixels de espessura.

7. `border-solid`, `border-dashed`, `border-dotted`, `border-double`: Essas classes definem o estilo da borda, onde `border-solid` cria uma borda sólida, `border-dashed` cria uma borda tracejada, `border-dotted` cria uma borda pontilhada e `border-double` cria uma borda dupla.

Aqui está um exemplo de como usar algumas dessas classes de borda:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Classes de Bordas em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <div class="container mt-4">
        <div class="border border-primary p-3">
            Esta é uma div com uma borda primária.
        </div>

        <div class="border border-success border-3 rounded p-3 mt-3">
            Esta é uma div com uma borda verde, espessura de 3 pixels e cantos arredondados.
        </div>

        <div class="border border-dark border-dotted p-3 mt-3">
            Esta é uma div com uma borda escura e estilo de borda pontilhada.
        </div>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, aplicamos várias classes de borda a elementos `<div>` para demonstrar como você pode personalizar as bordas dos elementos usando as classes de borda Bootstrap. Você pode experimentar diferentes combinações de classes para atender às suas necessidades de design. Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap em seu projeto para que as classes de borda funcionem corretamente.
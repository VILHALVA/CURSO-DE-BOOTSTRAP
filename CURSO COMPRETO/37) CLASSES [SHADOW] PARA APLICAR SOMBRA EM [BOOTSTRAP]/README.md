# CLASSES [SHADOW] PARA APLICAR SOMBRA EM [BOOTSTRAP]
O Bootstrap fornece classes de sombra que permitem adicionar efeitos de sombra a elementos HTML, criando uma sensação de profundidade e destaque. Abaixo estão algumas das classes de sombra disponíveis no Bootstrap:

## Classes de Sombra:
1. `shadow-sm`: Adiciona uma sombra suave ao elemento. É a sombra mais leve disponível.

2. `shadow`: Esta é a classe padrão para adicionar uma sombra moderada a um elemento.

3. `shadow-lg`: Adiciona uma sombra mais pronunciada e intensa ao elemento.

4. `shadow-none`: Remove qualquer sombra existente do elemento.

5. `shadow-inner`: Esta classe é usada para criar uma sombra interna, dando a impressão de que o elemento está afundado na superfície.

Aqui está um exemplo de como usar essas classes de sombra em Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Classes de Sombra em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <div class="container mt-4">
        <div class="bg-primary text-white p-3 shadow-sm">
            Esta div tem uma sombra suave.
        </div>

        <div class="bg-success text-white p-3 shadow">
            Esta div tem uma sombra padrão.
        </div>

        <div class="bg-info text-white p-3 shadow-lg">
            Esta div tem uma sombra intensa.
        </div>

        <div class="bg-warning text-dark p-3 shadow-inner">
            Esta div tem uma sombra interna.
        </div>

        <div class="bg-danger text-white p-3 shadow-none">
            Esta div não tem sombra.
        </div>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, aplicamos diferentes classes de sombra a elementos para demonstrar como essas classes funcionam. Você pode escolher a classe de sombra que melhor se adapta ao seu design e personalizar de acordo com suas necessidades. Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap em seu projeto para que as classes de sombra funcionem corretamente.
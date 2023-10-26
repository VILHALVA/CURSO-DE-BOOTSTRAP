# ALIGN-CONTENT VS JUSTIFY-CONTENT - DISPLAY FLEX #P3 EM [BOOTSTRAP]
No contexto do layout flexível do Bootstrap (usando as classes `d-flex`), as propriedades `align-content` e `justify-content` são usadas para controlar o alinhamento dos elementos dentro de um contêiner flexível. No entanto, é importante notar que essas propriedades têm diferentes funções e afetam o alinhamento em direções diferentes.

1. `align-content`:
   - A propriedade `align-content` é usada para controlar o alinhamento vertical dos elementos dentro de um contêiner flexível (ao longo do eixo transversal).
   - É aplicada ao contêiner flexível (pai) e controla o espaçamento entre as linhas de elementos flexíveis.
   - Pode ter valores como `start`, `end`, `center`, `space-between`, `space-around`, `stretch`, etc., que afetam o alinhamento vertical dos elementos.
   - Útil quando você deseja controlar o espaçamento entre as linhas de elementos flexíveis.

2. `justify-content`:
   - A propriedade `justify-content` é usada para controlar o alinhamento horizontal dos elementos dentro de um contêiner flexível (ao longo do eixo principal).
   - Também é aplicada ao contêiner flexível (pai) e controla o espaçamento entre os elementos flexíveis ao longo do eixo principal.
   - Pode ter valores como `start`, `end`, `center`, `space-between`, `space-around`, etc., que afetam o alinhamento horizontal dos elementos.
   - Útil quando você deseja controlar o espaçamento entre os elementos flexíveis ao longo do eixo principal.

Aqui está um exemplo que demonstra a diferença entre `align-content` e `justify-content` em um contêiner flexível em Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>align-content vs justify-content em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <div class="container mt-4">
        <h4 class="text-center">align-content vs justify-content em Bootstrap</h4>

        <!-- Exemplo com align-content -->
        <div class="d-flex flex-wrap align-content-center" style="height: 200px;">
            <div class="p-2 bg-primary text-white">Item 1</div>
            <div class="p-2 bg-success text-white">Item 2</div>
            <div class="p-2 bg-info text-white">Item 3</div>
        </div>

        <!-- Exemplo com justify-content -->
        <div class="d-flex justify-content-between mt-3" style="height: 200px;">
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

Neste exemplo, aplicamos `align-content-center` ao primeiro contêiner flexível e `justify-content-between` ao segundo contêiner flexível. O primeiro afeta o alinhamento vertical dos elementos, enquanto o segundo afeta o alinhamento horizontal dos elementos.

Certifique-se de ajustar as classes e propriedades de acordo com suas necessidades de layout e design. Ambas as propriedades são poderosas ferramentas para controlar o alinhamento de elementos em layouts flexíveis em Bootstrap.
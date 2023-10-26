# AUTO ALINHAMENTO DOS ELEMENTOS, ALIGN-SELF - FLEX #P5
A classe `align-self` em Bootstrap é usada para controlar o alinhamento vertical de um elemento individual dentro de um contêiner flexível criado com a classe `d-flex`. Ela permite que você ajuste o alinhamento vertical de elementos específicos em relação aos demais elementos dentro do contêiner. A classe `align-self` pode ser aplicada em elementos filhos, permitindo o alinhamento personalizado de cada elemento.

Aqui estão alguns dos valores possíveis para a classe `align-self` em Bootstrap:

- `align-self-start`: Alinha o elemento ao início do contêiner flexível, o que corresponde ao alinhamento vertical superior.
- `align-self-center`: Centraliza verticalmente o elemento dentro do contêiner flexível.
- `align-self-end`: Alinha o elemento ao final do contêiner flexível, o que corresponde ao alinhamento vertical inferior.
- `align-self-baseline`: Alinha o elemento à linha de base, que é a linha em que os caracteres descansam.
- `align-self-stretch` (padrão): Estica o elemento verticalmente para preencher o espaço disponível.

Aqui está um exemplo de como usar a classe `align-self` em Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Classe align-self em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <div class="container mt-4">
        <h4 class="text-center">Classe align-self em Bootstrap</h4>

        <div class="d-flex">
            <div class="p-2 bg-primary text-white align-self-start">Início</div>
            <div class="p-2 bg-success text-white align-self-center">Centro</div>
            <div class="p-2 bg-info text-white align-self-end">Fim</div>
        </div>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, aplicamos diferentes classes de `align-self` a elementos dentro de um contêiner flexível. Cada elemento é alinhado verticalmente de acordo com a classe aplicada. Isso permite controlar o alinhamento vertical individual de cada elemento dentro do contêiner flexível.

Lembre-se de que a classe `align-self` deve ser aplicada a elementos individuais dentro do contêiner flexível para personalizar seu alinhamento vertical. Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap em seu projeto para que a classe `align-self` funcione corretamente.
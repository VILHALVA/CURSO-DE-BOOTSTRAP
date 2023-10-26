# SPINNER DE LOAD EM BOOTSTRAP
O Bootstrap fornece classes para criar spinners de carregamento (loading spinners) que podem ser usados para indicar que uma tarefa está em andamento. Os spinners são animações que podem ser usadas em botões, caixas de diálogo, ou qualquer lugar onde você deseja mostrar que algo está acontecendo.

Aqui estão algumas classes de spinner no Bootstrap:

- `.spinner-border`: Cria um spinner circular.
- `.spinner-grow`: Cria um spinner em crescimento.
- `.text-*`: Use estas classes para definir a cor do spinner. Por exemplo, `.text-primary` define a cor do texto para "primary."

**Exemplo de uso de um Spinner de Carregamento:**

Aqui está um exemplo de como usar um spinner de carregamento no Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Spinner de Carregamento em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <div class="container mt-4">
        <h2>Exemplo de Spinner de Carregamento em Bootstrap</h2>

        <!-- Spinner circular padrão -->
        <div class="spinner-border text-primary" role="status">
            <span class="visually-hidden">Carregando...</span>
        </div>

        <!-- Spinner em crescimento -->
        <div class="spinner-grow text-danger" role="status">
            <span class="visually-hidden">Carregando...</span>
        </div>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, usamos as classes `.spinner-border` e `.spinner-grow` para criar dois tipos de spinners de carregamento, um circular e outro em crescimento. As classes `.text-*` definem a cor do spinner. Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap no seu projeto para que as classes de spinner funcionem corretamente.

Você pode incorporar esses spinners em botões, caixas de diálogo ou outros elementos para indicar que uma ação está em andamento.
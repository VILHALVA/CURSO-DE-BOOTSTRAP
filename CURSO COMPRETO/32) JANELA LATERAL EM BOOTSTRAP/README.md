# OFFCANVAS EM BOOTSTRAP [JANELA LATERAL EM BOOTSTRAP]
O componente Offcanvas em Bootstrap permite criar janelas laterais que podem ser abertas e fechadas para mostrar conteúdo adicional, menus, ou informações. Vou fornecer um exemplo de código e explicar como criar uma janela lateral (Offcanvas) em Bootstrap.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Janela Lateral em Bootstrap (Offcanvas)</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <!-- Botão para Abrir a Janela Lateral (Offcanvas) -->
    <button class="btn btn-primary" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasExample" aria-controls="offcanvasExample">
        Abrir Janela Lateral
    </button>

    <!-- Janela Lateral (Offcanvas) -->
    <div class="offcanvas offcanvas-start" tabindex="-1" id="offcanvasExample" aria-labelledby="offcanvasExampleLabel">
        <div class="offcanvas-header">
            <h5 class="offcanvas-title" id="offcanvasExampleLabel">Título da Janela Lateral</h5>
            <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Fechar"></button>
        </div>
        <div class="offcanvas-body">
            <p>Este é o conteúdo da janela lateral.</p>
        </div>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, criamos uma janela lateral (Offcanvas) em Bootstrap. Aqui está uma explicação do código:

- O botão com a classe `btn btn-primary` e os atributos `data-bs-toggle="offcanvas"` e `data-bs-target="#offcanvasExample"` é usado para abrir a janela lateral. O atributo `data-bs-target` faz referência ao ID da janela lateral que queremos abrir.

- A janela lateral é criada com um elemento `<div>` com a classe `offcanvas offcanvas-start`. O atributo `id="offcanvasExample"` é usado para identificar a janela lateral. O atributo `aria-labelledby` é usado para associar um título à janela lateral para fins de acessibilidade.

- A seção `offcanvas-header` contém o título da janela lateral e um botão de fechamento.

- A seção `offcanvas-body` é onde você coloca o conteúdo principal da janela lateral. Neste exemplo, é um parágrafo de texto.

- O botão de fechamento é definido com a classe `btn-close` e o atributo `data-bs-dismiss="offcanvas"` para fechar a janela lateral.

Certifique-se de personalizar o título e o conteúdo da janela lateral conforme suas necessidades. Além disso, inclua os arquivos CSS e JavaScript do Bootstrap na ordem correta em seu projeto para que a janela lateral funcione corretamente.
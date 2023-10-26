# COLLAPSE EM BOOTSTRAP
Os colapsos (ou "accordions") no Bootstrap são componentes interativos que permitem ocultar ou exibir conteúdo em uma área expansível quando um título ou botão é clicado. Isso é útil para criar seções expansíveis de conteúdo, como perguntas frequentes, listas de categorias ou painéis de configuração. Aqui estão os principais elementos envolvidos na criação de um colapso no Bootstrap:

- `.collapse`: A classe que deve ser aplicada ao elemento que deseja tornar expansível ou recolhível.
- `.collapse.show`: A classe que indica que o conteúdo está expandido (visível).
- `data-toggle="collapse"`: A atributo usado para ativar o colapso quando um elemento de acionamento (geralmente um botão ou link) é clicado.
- `data-target="#ID"`: O atributo que especifica qual elemento de colapso deve ser afetado pelo clique do elemento de acionamento.

**Exemplo de uso:**

Aqui está um exemplo de como criar um colapso simples no Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Colapso em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <div class="container mt-4">
        <h2>Exemplo de Colapso em Bootstrap</h2>

        <button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#conteudo" aria-expanded="false" aria-controls="conteudo">
            Clique para Expandir
        </button>

        <div class="collapse" id="conteudo">
            <div class="card card-body">
                Este é um exemplo de colapso em Bootstrap. O conteúdo pode ser oculto ou expandido quando o botão é clicado.
            </div>
        </div>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, usamos a classe `.collapse` para criar o conteúdo que pode ser oculto ou expandido. O botão com o atributo `data-toggle` e `data-target` é usado para acionar o colapso. O `data-target` é definido com o ID do elemento que será afetado.

Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap no seu projeto para que as classes de colapso funcionem corretamente. O conteúdo pode ser personalizado e expandido de acordo com suas necessidades.
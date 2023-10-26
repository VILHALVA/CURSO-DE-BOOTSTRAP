# LISTGROUP EM BOOTSTRAP
No Bootstrap, um `ListGroup` é um componente que permite criar uma lista de itens em forma de grupo, como uma lista de elementos relacionados. Esses elementos podem conter texto, links, botões ou qualquer outro conteúdo HTML. Aqui estão algumas das classes e componentes principais relacionados ao `ListGroup` no Bootstrap:

- `.list-group`: A classe base que cria o contêiner do `ListGroup`.
- `.list-group-item`: Cria um item na lista.
- `.active`: Marca um item como ativo.
- `.disabled`: Marca um item como desativado.
- `.list-group-item-action`: Torna o item clicável, ativando a transição de estado quando clicado.

**Exemplo de uso:**

Aqui está um exemplo de como criar um `ListGroup` no Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de ListGroup em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <div class="container mt-4">
        <h2>Exemplo de ListGroup em Bootstrap</h2>

        <ul class="list-group">
            <li class="list-group-item">Item 1</li>
            <li class="list-group-item">Item 2</li>
            <li class="list-group-item">Item 3</li>
            <li class="list-group-item">Item 4</li>
        </ul>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, utilizamos a classe `.list-group` para criar o contêiner do `ListGroup` e a classe `.list-group-item` para criar os itens da lista. Você pode personalizar o `ListGroup` adicionando classes adicionais para ativar a transição de estado quando um item é clicado, ou marcando um item como ativo ou desativado.

O Bootstrap oferece muitas opções de personalização para `ListGroup`, permitindo que você crie listas de elementos atraentes e interativas em seu site ou aplicativo. Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap no seu projeto para que as classes de `ListGroup` funcionem corretamente.
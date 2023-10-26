# CRIANDO O JUMBOTRON NO BOOTSTRATP 3 NO 5
O Bootstrap 5 introduziu algumas mudanças na forma como os elementos como Jumbotron são criados em comparação com o Bootstrap 3. A classe jumbotron ainda está disponível no Bootstrap 5 para criar Jumbotrons, mas você notará algumas diferenças sutis. Aqui está como você pode criar um Jumbotron no Bootstrap 5.

O Jumbotron é frequentemente usado para destacar informações importantes em uma seção do site. Aqui está como criar um Jumbotron:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Jumbotron Bootstrap 5</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">

</head>
<body>

    <div class="container mt-4">
        <div class="jumbotron">
            <h1 class="display-4">Bem-vindo ao Meu Site</h1>
            <p class="lead">Este é um exemplo de Jumbotron no Bootstrap 5.</p>
            <hr class="my-4">
            <p>Ele é usado para destacar informações importantes.</p>
            <a class="btn btn-primary" href="#" role="button">Saiba mais</a>
        </div>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo:

1. Incluímos o Bootstrap 5 no cabeçalho do documento com os arquivos CSS e JavaScript.

2. Usamos uma `<div>` com a classe `container` para criar um contêiner que limita o conteúdo da página.

3. Dentro desse contêiner, criamos um Jumbotron usando a classe `jumbotron`. O Jumbotron é uma caixa que ocupa toda a largura da tela e possui um fundo cinza claro por padrão.

4. Dentro do Jumbotron, usamos uma série de elementos HTML para construir a seção destacada:
   - `<h1 class="display-4">`: Cabeçalho principal com estilo grande.
   - `<p class="lead">`: Um parágrafo de introdução com estilo.
   - `<hr class="my-4">`: Uma linha horizontal para separar o conteúdo.
   - `<p>`: Outro parágrafo com informações adicionais.
   - `<a class="btn btn-primary" href="#" role="button">`: Um botão que pode ser personalizado com as classes de cores do Bootstrap.

Você pode personalizar o conteúdo e o estilo do Jumbotron de acordo com suas necessidades específicas. É uma maneira eficaz de destacar informações importantes em seu site. Certifique-se de que os arquivos CSS e JavaScript do Bootstrap estejam corretamente incluídos em seu projeto para que as classes funcionem conforme demonstrado.
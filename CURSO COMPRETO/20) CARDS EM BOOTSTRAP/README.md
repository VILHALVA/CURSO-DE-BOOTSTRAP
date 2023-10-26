# CARDS EM BOOTSTRAP
Os "cards" são componentes flexíveis e versáteis no Bootstrap que podem ser usados para exibir informações em uma variedade de maneiras. Eles são frequentemente usados para mostrar conteúdo, como artigos, produtos, perfis de usuário e muito mais. Aqui estão algumas das classes e componentes principais relacionados aos "cards" no Bootstrap:

- `.card`: A classe base que cria o contêiner de um card.
- `.card-header`: Usada para criar um cabeçalho para o card.
- `.card-body`: Usada para criar o corpo do card.
- `.card-title`: Usada para adicionar um título ao card.
- `.card-text`: Usada para adicionar texto ao card.
- `.card-footer`: Usada para criar um rodapé para o card.
- `.card-img-top`: Usada para adicionar uma imagem ao topo do card.

**Exemplo de uso:**

Aqui está um exemplo de como criar um card simples no Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Card em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <div class="container mt-4">
        <h2>Exemplo de Card em Bootstrap</h2>

        <div class="card" style="width: 18rem;">
            <img src="https://via.placeholder.com/150" class="card-img-top" alt="Imagem de Exemplo">
            <div class="card-body">
                <h5 class="card-title">Título do Card</h5>
                <p class="card-text">Este é um exemplo de card no Bootstrap. Você pode adicionar texto e conteúdo a ele.</p>
            </div>
        </div>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, usamos a classe `.card` para criar o contêiner do card e adicionamos uma imagem, um título e texto ao card. Você pode personalizar o card conforme necessário, adicionando cabeçalhos, rodapés, botões e outros elementos para exibir o conteúdo da maneira desejada.

Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap no seu projeto para que as classes de card funcionem corretamente.
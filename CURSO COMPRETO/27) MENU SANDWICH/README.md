# MENU SANDWICH 
O "menu sanduíche" em Bootstrap é uma técnica usada para criar um menu de navegação responsivo que é exibido como um ícone de três barras empilhadas (geralmente chamado de ícone "hamburguer") em telas menores, como smartphones e tablets. Quando o usuário clica no ícone, o menu de navegação é exibido. Vou mostrar como criar um exemplo de menu sanduíche em Bootstrap.

**1. Estrutura HTML básica:**

Aqui está o código HTML básico para criar um menu sanduíche em Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu Sanduíche em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <!-- Barra de Navegação com Menu Sanduíche -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Meu Site</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Página Inicial</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Sobre Nós</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Serviços</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contato</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Conteúdo do Site -->
    <div class="container mt-4">
        <h2>Conteúdo do Site</h2>
        <p>Este é o conteúdo do site.</p>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, usamos o mesmo código que expliquei anteriormente para criar uma barra de navegação Bootstrap com o menu sanduíche. O botão do menu sanduíche é representado pelo elemento `<button>` com a classe `navbar-toggler` e um ícone de três barras empilhadas fornecido pelo elemento `<span>` com a classe `navbar-toggler-icon`. Quando a tela é redimensionada para um tamanho menor, o menu de navegação é recolhido automaticamente e o botão do menu sanduíche aparece. Ao clicar no botão, o menu de navegação é exibido.

Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap na ordem correta em seu projeto para que o menu sanduíche funcione corretamente em telas menores.
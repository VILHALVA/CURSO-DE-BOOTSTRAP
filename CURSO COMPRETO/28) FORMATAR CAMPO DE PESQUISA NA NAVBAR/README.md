# FORMATAR CAMPO DE PESQUISA NA NAVBAR
Para formatar um campo de pesquisa (barra de pesquisa) na barra de navegação (navbar) do Bootstrap, você pode usar as classes do Bootstrap para estilizar o elemento de input de forma que fique alinhado com a barra de navegação. Vou fornecer um exemplo de código e explicar como fazer isso:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barra de Navegação com Campo de Pesquisa</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <!-- Barra de Navegação Bootstrap com Campo de Pesquisa -->
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
            
            <!-- Campo de Pesquisa na Barra de Navegação -->
            <form class="form-inline my-2 my-lg-0">
                <input class="form-control mr-sm-2" type="search" placeholder="Pesquisar" aria-label="Pesquisar">
                <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Pesquisar</button>
            </form>
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

Neste exemplo, adicionamos um campo de pesquisa à barra de navegação usando o elemento `<form>` com a classe `form-inline`. O campo de pesquisa em si é um elemento de input com a classe `form-control`. Você pode personalizar o placeholder e o rótulo ARIA conforme necessário.

Além disso, incluímos um botão de pesquisa na barra de navegação para que os usuários possam realizar a pesquisa. O botão é estilizado com a classe `btn` e a classe `btn-outline-success`, mas você pode alterar a classe para se adequar ao seu estilo.

Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap na ordem correta em seu projeto para que o campo de pesquisa e a barra de navegação funcionem corretamente.
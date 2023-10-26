# NAV EM BOOTSTRAP, CRIANDO ELEMENTOS DE NAVEGAÇÃO
No Bootstrap, você pode criar uma barra de navegação (navbar) e adicionar elementos de navegação, como links para diferentes páginas ou seções do seu site. A barra de navegação é uma parte fundamental de muitos sites, permitindo aos usuários navegar facilmente pelo conteúdo. Vou mostrar como criar uma barra de navegação simples com elementos de navegação usando Bootstrap.

**Exemplo de uso:**

Aqui está um exemplo de como criar uma barra de navegação com elementos de navegação em Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Barra de Navegação em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Meu Site</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
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
        </div>
    </nav>

    <div class="container mt-4">
        <h2>Conteúdo do Site</h2>
        <!-- Seu conteúdo aqui -->
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, criamos uma barra de navegação Bootstrap com a classe `.navbar`. Os elementos de navegação estão contidos em uma lista não ordenada (`ul`) com a classe `.navbar-nav`. Os links de navegação são representados por elementos `li` com a classe `.nav-item` e links com a classe `.nav-link`.

Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap no seu projeto para que a barra de navegação e os elementos de navegação funcionem corretamente. Você pode personalizar a barra de navegação de acordo com as necessidades do seu site.
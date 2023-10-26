# CLASSE NAVBAR EM BOOTSTRAP
A classe `navbar` em Bootstrap é usada para criar uma barra de navegação responsiva em seu site ou aplicação web. A barra de navegação é um componente fundamental para a navegação do usuário e pode ser personalizada de várias maneiras.

Aqui está um exemplo de como criar uma barra de navegação simples usando a classe `navbar` em Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barra de Navegação em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <!-- Barra de Navegação Bootstrap -->
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

Neste exemplo:

- Utilizamos a classe `navbar` para criar a barra de navegação.
- Adicionamos um logotipo (ou texto de marca) com a classe `navbar-brand`.
- Incluímos um botão de alternância para dispositivos móveis usando a classe `navbar-toggler`.
- Adicionamos itens de menu com a classe `navbar-nav` em uma lista não ordenada (`ul`).
- Personalizamos os links do menu com a classe `nav-link`.
- Usamos a classe `navbar-expand-lg` para controlar o comportamento responsivo da barra de navegação. Neste exemplo, a barra de navegação se expandirá em dispositivos de largura média ou maior (lg).

Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap em seu projeto para que a barra de navegação funcione corretamente. Você pode personalizar ainda mais a barra de navegação de acordo com suas necessidades, adicionando itens de menu adicionais ou outros elementos.
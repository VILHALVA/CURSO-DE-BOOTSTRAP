# MENU DROPDOWN EM BOOTSTRAP
Os menus dropdown (ou menus suspensos) são uma parte comum da interface de usuário em muitos sites e aplicativos. No Bootstrap, você pode criar menus dropdown facilmente usando as classes e componentes disponíveis. Aqui estão os principais elementos envolvidos na criação de um menu dropdown no Bootstrap:

- `.dropdown`: A classe que deve ser aplicada a um elemento pai para criar um menu dropdown.
- `.dropdown-toggle`: Aplicada a um elemento (geralmente um botão ou link) que aciona o menu dropdown quando clicado.
- `.dropdown-menu`: A classe que cria o menu suspenso real, que é oculto por padrão e é exibido quando o botão de acionamento é clicado.

**Exemplo de uso:**

Aqui está um exemplo de como criar um menu dropdown simples no Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Menu Dropdown em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <div class="container mt-4">
        <h2>Exemplo de Menu Dropdown em Bootstrap</h2>

        <div class="dropdown">
            <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                Opções
            </button>
            <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                <a class="dropdown-item" href="#">Opção 1</a>
                <a class="dropdown-item" href="#">Opção 2</a>
                <a class="dropdown-item" href="#">Opção 3</a>
            </div>
        </div>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, usamos a classe `.dropdown` para criar o contêiner do menu dropdown. O botão com a classe `.dropdown-toggle` ativa o menu quando é clicado. O menu suspenso real é criado usando a classe `.dropdown-menu`.

Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap no seu projeto para que as classes de menu dropdown funcionem corretamente. Você pode personalizar o conteúdo do menu dropdown de acordo com as suas necessidades.
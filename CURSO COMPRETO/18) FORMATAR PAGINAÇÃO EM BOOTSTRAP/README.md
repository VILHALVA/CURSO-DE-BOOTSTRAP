# FORMATAR PAGINAÇÃO EM BOOTSTRAP
O Bootstrap oferece classes para criar elementos de paginação que são úteis quando você tem uma lista longa de itens e deseja dividi-la em várias páginas. As classes de paginação permitem a criação de controles de navegação para avançar ou retroceder nas páginas. Aqui estão algumas das classes relacionadas à paginação no Bootstrap:

1. `.pagination`: Cria o contêiner para a paginação.
2. `.page-item`: Cria um item individual na paginação (normalmente usado para criar botões).
3. `.page-link`: Cria um link dentro de um item de página.
4. `.disabled`: Marca um item de página como desativado (não clicável).

**Exemplo de uso:**

Aqui está um exemplo de como criar uma paginação simples no Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paginação em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <div class="container mt-4">
        <h2>Exemplo de Paginação em Bootstrap</h2>

        <ul class="pagination">
            <li class="page-item">
                <a class="page-link" href="#" aria-label="Página anterior">
                    <span aria-hidden="true">&laquo;</span>
                </a>
            </li>
            <li class="page-item"><a class="page-link" href="#">1</a></li>
            <li class="page-item"><a class="page-link" href="#">2</a></li>
            <li class="page-item disabled">
                <span class="page-link">...</span>
            </li>
            <li class="page-item"><a class="page-link" href="#">5</a></li>
            <li class="page-item">
                <a class="page-link" href="#" aria-label="Próxima página">
                    <span aria-hidden="true">&raquo;</span>
                </a>
            </li>
        </ul>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, usamos classes de paginação para criar uma lista de páginas numeradas com botões "Página anterior" e "Próxima página". O Bootstrap lida automaticamente com a estilização e a funcionalidade desses botões. Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap no seu projeto para que as classes de paginação funcionem corretamente.

Você pode personalizar a paginação de acordo com suas necessidades específicas e o número de páginas em seu aplicativo.
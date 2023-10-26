# CLASSES PARA FORMULÁRIO EM BOOTSTRAP #P2
Continuando com as classes para formatação de formulários em Bootstrap, aqui estão algumas classes adicionais que você pode usar para personalizar e estilizar seus formulários:

10. `.form-control-lg` e `.form-control-sm`:
    - Essas classes permitem definir o tamanho dos elementos de entrada em um formulário. `.form-control-lg` é usado para elementos de entrada de tamanho grande, enquanto `.form-control-sm` é usado para elementos de entrada de tamanho pequeno.

11. `.form-select`:
    - Esta classe é usada para estilizar elementos `<select>` e criar seletores personalizados.

12. `.form-range`:
    - Aplicada a elementos `<input type="range>`, esta classe estiliza barras de rolagem deslizantes.

13. `.form-switch`:
    - Usada para criar chaves de alternância personalizadas (toggle switches) com elementos `<input type="checkbox>`.

14. `.form-check-input` e `.form-check-label`:
    - Estas classes são usadas em conjunto para criar caixas de seleção personalizadas ou botões de opção.

15. `.form-control-plaintext`:
    - Esta classe é usada para tornar um campo de texto de formulário não editável, exibindo-o como texto simples.

16. `.form-control-plaintext`:
    - Usada para desabilitar a entrada do usuário em um campo de texto de formulário, impedindo que o usuário o edite.

17. `.form-floating`:
    - Esta classe é usada para criar campos de entrada flutuantes, onde o rótulo se move para cima quando o usuário começa a digitar no campo de entrada.

18. `.is-invalid` e `.is-valid`:
    - Essas classes são usadas em elementos de formulário para fornecer feedback de validação personalizado. `.is-invalid` é usado para destacar campos inválidos com estilos de erro, enquanto `.is-valid` é usado para destacar campos válidos com estilos de sucesso.

Aqui está um exemplo atualizado de como usar algumas das classes de formatação de formulários em Bootstrap:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Classes para Formatação de Formulário em Bootstrap (Parte 2)</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <div class="container mt-4">
        <h4 class="text-center">Exemplo de Formulário em Bootstrap (Parte 2)</h4>

        <form>
            <div class="form-group">
                <label for="nome" class="form-label">Nome:</label>
                <input type="text" class="form-control form-control-lg" id="nome">
            </div>

            <div class="form-group">
                <label for="email" class="form-label">Email:</label>
                <input type="email" class="form-control form-control-sm" id="email">
            </div>

            <div class="form-group">
                <label for="idade" class="form-label">Idade:</label>
                <input type="number" class="form-control" id="idade">
            </div>

            <div class="form-group">
                <label for="selecao" class="form-label">Escolha uma opção:</label>
                <select class="form-select" id="selecao">
                    <option value="opcao1">Opção 1</option>
                    <option value="opcao2">Opção 2</option>
                    <option value="opcao3">Opção 3</option>
                </select>
            </div>

            <div class="form-group">
                <label class="form-check-label">Gênero:</label>
                <div class="form-check">
                    <input type="radio" class="form-check-input" id="genero1" name="genero" value="masculino">
                    <label for="genero1" class="form-check-label">Masculino</label>
                </div>
                <div class="form-check">
                    <input type="radio" class="form-check-input" id="genero2" name="genero" value="feminino">
                    <label for="genero2" class="form-check-label">Feminino</label>
                </div>
            </div>

            <div class="form-group">
                <label for="toggle" class="form-check-label">Ativar/Daativar:</label>
                <div class="form-check form-switch">
                    <input type="checkbox" class="form-check-input" id="toggle">
                    <label for="toggle" class="form-check-label"></label>
                </div>
            </div>

            <div class="form-group">
                <label for="textArea" class="form-label">Comentários:</label>
                <textarea class="form-control" id="textArea" rows="4"></textarea>
            </div>

            <div class="form-group">
                <label class="form-check-label">Aceito os termos e condições:</label>
                <div class="form-check">
                    <input type="checkbox" class="form-check-input" id="aceitoTermos">
                    <label for="aceitoTermos" class="form-check-label">Sim</label>
                </div>
            </div>

            <button type="submit" class="btn btn-primary">Enviar</button>
        </form>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, aplicamos algumas das classes adicionais para personalizar ainda mais o formulário. Você pode ajustar essas classes de acordo com suas necessidades de design e layout. Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap em seu projeto para que as classes de formatação de formulários funcionem corretamente.
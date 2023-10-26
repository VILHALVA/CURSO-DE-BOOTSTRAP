# CLASSES PARA ALERTAS NO BOOTSTRATP
O Bootstrap fornece classes para criar alertas que informam os usuários sobre ações, estados ou informações importantes. Os alertas podem ser usados para exibir mensagens de sucesso, erros, avisos, informações etc. Aqui estão algumas das classes de alerta mais comuns no Bootstrap:

1. **Alerta de Sucesso (Success)** - Classe `.alert-success`:
   - Use esta classe para indicar que uma ação foi realizada com sucesso.

2. **Alerta de Informação (Info)** - Classe `.alert-info`:
   - Use esta classe para fornecer informações gerais.

3. **Alerta de Aviso (Warning)** - Classe `.alert-warning`:
   - Use esta classe para alertar o usuário sobre algo que requer atenção, mas não é necessariamente um erro.

4. **Alerta de Erro (Danger)** - Classe `.alert-danger`:
   - Use esta classe para informar o usuário sobre erros ou problemas críticos.

5. **Alerta Padrão (Default)** - Classe `.alert-primary`:
   - Essa classe é usada para um estilo de alerta padrão.

Além dessas classes de contexto, existem algumas classes adicionais que podem ser usadas para adicionar mais informações aos alertas:

- `.alert-dismissible`: Esta classe adiciona um botão "X" que permite ao usuário fechar o alerta.

**Exemplo de Uso:**

Aqui está um exemplo de como criar alertas usando classes no Bootstrap:

```html
<div class="alert alert-success" role="alert">
  Esta é uma mensagem de sucesso.
</div>

<div class="alert alert-info" role="alert">
  Esta é uma mensagem de informação.
</div>

<div class="alert alert-warning" role="alert">
  Esta é uma mensagem de aviso.
</div>

<div class="alert alert-danger" role="alert">
  Esta é uma mensagem de erro.
</div>
```

Também é possível criar alertas com a opção de serem fechados pelo usuário. Nesse caso, você pode adicionar a classe `.alert-dismissible` e incluir o botão "X" para fechar o alerta:

```html
<div class="alert alert-warning alert-dismissible fade show" role="alert">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close">
    <span aria-hidden="true">&times;</span>
  </button>
  Este é um alerta fechável.
</div>
```

Neste exemplo, a classe `.alert-dismissible` é usada para criar um alerta que pode ser fechado pelo usuário, e um botão "X" é adicionado para permitir o fechamento.

Esses são exemplos simples de como usar classes de alerta do Bootstrap. Você pode personalizar ainda mais o conteúdo e o estilo dos alertas de acordo com suas necessidades específicas. Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap em seu projeto para que as classes de alerta funcionem corretamente.
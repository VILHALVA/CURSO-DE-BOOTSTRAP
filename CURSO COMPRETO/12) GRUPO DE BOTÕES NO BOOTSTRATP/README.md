# GRUPO DE BOTÕES NO BOOTSTRATP
No Bootstrap, você pode criar grupos de botões para agrupar vários botões relacionados, como botões de opções, botões de seleção múltipla, ou botões de ação relacionados. Para criar um grupo de botões, você pode usar a classe `.btn-group` e suas variantes. Existem dois tipos principais de grupos de botões no Bootstrap: grupos de botões regulares e grupos de botões de ação (dropdown).

Aqui estão exemplos de ambos os tipos:

**Grupo de Botões Regulares:**

```html
<div class="btn-group" role="group" aria-label="Exemplo de grupo de botões regulares">
  <button type="button" class="btn btn-primary">Botão 1</button>
  <button type="button" class="btn btn-success">Botão 2</button>
  <button type="button" class="btn btn-warning">Botão 3</button>
</div>
```

Neste exemplo, usamos a classe `.btn-group` para criar um grupo de botões regulares. Os botões são exibidos lado a lado.

**Grupo de Botões de Ação (Dropdown):**

```html
<div class="btn-group">
  <button type="button" class="btn btn-primary">Ação</button>
  <button type="button" class="btn btn-primary dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    <span class="visually-hidden">Alternar navegação</span>
  </button>
  <ul class="dropdown-menu">
    <li><a class="dropdown-item" href="#">Item 1</a></li>
    <li><a class="dropdown-item" href="#">Item 2</a></li>
    <li><a class="dropdown-item" href="#">Item 3</a></li>
  </ul>
</div>
```

Neste exemplo, criamos um grupo de botões de ação que inclui um botão principal e um menu suspenso. O botão principal tem a classe `.dropdown-toggle`, e o menu suspenso é definido com a classe `.dropdown-menu`.

Lembre-se de que você precisará incluir os arquivos CSS e JavaScript do Bootstrap no seu projeto para que esses grupos de botões funcionem corretamente. Certifique-se de verificar a documentação do Bootstrap para obter mais informações sobre como estilizar e personalizar grupos de botões de acordo com suas necessidades específicas.
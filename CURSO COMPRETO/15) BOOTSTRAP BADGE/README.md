# BOOTSTRAP BADGE 
Os "badges" no Bootstrap são elementos que permitem destacar informações numéricas ou de status em seu site. Eles são frequentemente usados para mostrar notificações, contagens ou rótulos. Você pode criar badges facilmente com classes Bootstrap predefinidas.

Aqui estão algumas classes de badge comuns no Bootstrap:

- `.badge`: A classe base para criar um badge padrão.
- `.badge-primary`, `.badge-secondary`, `.badge-success`, `.badge-warning`, `.badge-danger`, `.badge-info`, `.badge-light`, `.badge-dark`: Classes de cor que você pode aplicar aos badges para correspondê-los ao estilo do seu site.

**Exemplo de uso:**

Aqui está um exemplo de como criar e estilizar badges no Bootstrap:

```html
<span class="badge badge-primary">Badge Primário</span>
<span class="badge badge-success">Badge de Sucesso</span>
<span class="badge badge-warning">Badge de Aviso</span>
<span class="badge badge-danger">Badge de Perigo</span>
```

Você pode incorporar badges em botões, cabeçalhos, ou qualquer lugar que queira destacar informações específicas.

**Exemplo de uso em botões:**

```html
<button type="button" class="btn btn-primary">
  Notificações <span class="badge badge-light">5</span>
</button>
```

Neste exemplo, um badge é incorporado em um botão para indicar o número de notificações.

Lembre-se de que você pode personalizar ainda mais os badges e seu estilo com CSS personalizado, se necessário. Certifique-se de incluir os arquivos CSS e JavaScript do Bootstrap em seu projeto para que as classes de badge funcionem corretamente.
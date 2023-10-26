# CLASSES PARA PROGRESSBAR EM BOOTSTRAP
O Bootstrap oferece classes para criar barras de progresso (progress bars) que são úteis para mostrar o progresso de uma tarefa ou a conclusão de uma etapa em seu site ou aplicativo web. Aqui estão algumas das classes e componentes principais relacionados a barras de progresso no Bootstrap:

1. **Classe `.progress`**: Esta classe é usada para criar o contêiner da barra de progresso.

2. **Classe `.progress-bar`**: Essa classe é usada para criar a barra de progresso propriamente dita. Você pode definir a largura da barra de progresso e o valor do progresso usando a largura (width) ou a classe `.w-*`. Por exemplo, `.w-25` define a barra de progresso em 25%.

3. **Atributo `aria-valuemin`**: Use este atributo para definir o valor mínimo da barra de progresso.

4. **Atributo `aria-valuenow`**: Use este atributo para definir o valor atual da barra de progresso.

5. **Atributo `aria-valuemax`**: Use este atributo para definir o valor máximo da barra de progresso.

**Exemplo de uso:**

Aqui está um exemplo de como criar uma barra de progresso no Bootstrap:

```html
<div class="progress">
  <div class="progress-bar" role="progressbar" style="width: 25%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
</div>
```

Neste exemplo, estamos criando uma barra de progresso que está 25% completa. Você pode personalizar a largura da barra de progresso definindo a propriedade `style` com o valor de largura desejado.

Além disso, você pode adicionar classes de cor ao `progress-bar` para indicar o status, como `bg-success` para sucesso, `bg-warning` para aviso e `bg-danger` para perigo, entre outras.

Aqui está um exemplo com uma barra de progresso de sucesso:

```html
<div class="progress">
  <div class="progress-bar bg-success" role="progressbar" style="width: 75%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
</div>
```

Certifique-se de personalizar a barra de progresso de acordo com as necessidades do seu projeto. O Bootstrap oferece flexibilidade para estilizar e adaptar as barras de progresso ao seu design.
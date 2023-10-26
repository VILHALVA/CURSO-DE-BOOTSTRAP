# TRABALHANDO COM GRIDS BOOTSTRAP, CLASSES COL E ROW 
Trabalhar com o sistema de grade (grid system) do Bootstrap é uma parte fundamental para criar layouts responsivos e organizados em suas páginas da web. O Bootstrap usa as classes `col` e `row` para isso. Aqui estão algumas informações sobre como usar essas classes no Bootstrap:

**1. Classe `.row`**

A classe `.row` é usada para criar linhas (rows) que contêm as colunas do seu layout. Cada linha pode conter uma ou mais colunas e ajuda a organizar o conteúdo na horizontal. Uma linha geralmente é envolvida por uma `<div>` com a classe `.container` ou `.container-fluid` para definir seus limites. Aqui está um exemplo:

```html
<div class="container">
    <div class="row">
        <!-- Suas colunas vão aqui -->
    </div>
</div>
```

**2. Classe `.col`**

A classe `.col` é usada para criar colunas em uma linha (row). Você pode especificar o tamanho das colunas usando as classes `.col-*`, onde o `*` é substituído pelo tamanho desejado. Os tamanhos variam de `col-1` (a menor) a `col-12` (a maior). Além disso, você pode especificar o tamanho das colunas para diferentes tamanhos de tela, como `col-md-*` (médio), `col-lg-*` (grande), etc. Por exemplo:

```html
<div class="row">
    <div class="col-12">Coluna 1</div>
    <div class="col-6">Coluna 2</div>
    <div class="col-6">Coluna 3</div>
</div>
```

Neste exemplo, temos uma linha com três colunas, onde a primeira coluna ocupa toda a largura da linha, e as outras duas ocupam metade da largura cada. As classes `.col-*` garantem que as colunas se ajustem automaticamente com base no tamanho da tela.

Lembre-se de que a soma dos tamanhos das colunas em uma linha deve ser igual a 12 ou menos para garantir que elas se ajustem corretamente em todos os dispositivos.


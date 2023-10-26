# TIPOGRAFIA EM BOOTSTRAP
O Bootstrap oferece classes e estilos para formatação de fonte e tipografia para facilitar o design e a legibilidade de seu conteúdo. Aqui estão algumas classes e estilos comumente usados para formatar a tipografia em Bootstrap:

1. **Tamanhos de Texto**:
   - `.h1` a `.h6`: Essas classes definem tamanhos de cabeçalhos, onde `.h1` é o maior e `.h6` o menor.
   - `.lead`: Esta classe é usada para destacar um parágrafo como introdução.

Exemplo:
```html
<h1 class="h1">Título de nível 1</h1>
<h2 class="h2">Título de nível 2</h2>
<p class="lead">Este é um parágrafo de introdução.</p>
```

2. **Estilos de Texto**:
   - `.text-muted`, `.text-primary`, `.text-secondary`, `.text-success`, `.text-danger`, `.text-warning`, `.text-info`, `.text-light`, `.text-dark`: Essas classes são usadas para definir as cores do texto.
   - `.font-weight-bold`: Essa classe define o texto em negrito.
   - `.font-italic`: Essa classe define o texto em itálico.

Exemplo:
```html
<p class="text-muted">Este é um texto em cinza.</p>
<p class="text-primary">Este é um texto em azul.</p>
<p class="font-weight-bold">Este é um texto em negrito.</p>
<p class="font-italic">Este é um texto em itálico.</p>
```

3. **Alinhamento de Texto**:
   - `.text-left`, `.text-center`, `.text-right`, `.text-justify`: Essas classes são usadas para alinhar o texto.
   
Exemplo:
```html
<p class="text-left">Texto alinhado à esquerda.</p>
<p class="text-center">Texto centralizado.</p>
<p class="text-right">Texto alinhado à direita.</p>
<p class="text-justify">Este é um exemplo de texto justificado, que preenche a largura da caixa.</p>
```

4. **Espaçamento e Margens**:
   - `.m-1` a `.m-5`: Essas classes definem margens para todos os lados de um elemento.
   - `.mt-1` a `.mt-5`: Essas classes definem margens superiores.
   - `.mb-1` a `.mb-5`: Essas classes definem margens inferiores.
   - `.ml-1` a `.ml-5`: Essas classes definem margens à esquerda.
   - `.mr-1` a `.mr-5`: Essas classes definem margens à direita.
   
Exemplo:
```html
<p class="mt-3">Este parágrafo tem uma margem superior de 3 unidades.</p>
<p class="mb-4">Este parágrafo tem uma margem inferior de 4 unidades.</p>
<p class="ml-2">Este parágrafo tem uma margem à esquerda de 2 unidades.</p>
<p class="mr-5">Este parágrafo tem uma margem à direita de 5 unidades.</p>
```

Essas são apenas algumas das classes de tipografia que o Bootstrap oferece. Você pode personalizar ainda mais a aparência da tipografia em seu projeto usando variáveis CSS ou sobrescrevendo os estilos padrão do Bootstrap para atender às suas necessidades específicas. Certifique-se de consultar a documentação do Bootstrap para obter informações detalhadas sobre as classes de tipografia e seus estilos.
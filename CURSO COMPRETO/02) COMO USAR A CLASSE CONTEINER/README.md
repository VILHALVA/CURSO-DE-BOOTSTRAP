# COMO USAR A CLASSE CONTEINER?
A classe `.container` é uma parte fundamental do sistema de grid do Bootstrap e é usada para envolver o conteúdo da página em um contêiner responsivo. Ela é projetada para criar uma área limitada no layout da página, garantindo que o conteúdo seja adequadamente centralizado e ajustado em telas de diferentes tamanhos. Aqui está como usar a classe `.container`:

1. **Incluir a classe `.container`**: Para usar a classe `.container`, basta adicionar essa classe a um elemento HTML que envolve o conteúdo que você deseja que seja responsivo. Geralmente, esse elemento é um `<div>`.

   ```html
   <div class="container">
       <!-- Conteúdo da página -->
   </div>
   ```

2. **Hierarquia do Contêiner**: O Bootstrap oferece três tipos de contêineres: `.container`, `.container-fluid`, e `.container-sm`, cada um com comportamentos ligeiramente diferentes.

   - `.container`: Este é o contêiner padrão. Ele tem uma largura máxima responsiva, o que significa que ele não ficará muito largo em telas grandes.

   - `.container-fluid`: Este contêiner ocupa a largura total da tela, independentemente do tamanho do dispositivo. É útil para criar layouts de largura total.

   - `.container-sm`: Este contêiner é restrito a dispositivos de tamanho pequeno. É útil quando você deseja que o conteúdo seja responsivo apenas em telas menores.

3. **Exemplo de Uso**:

   ```html
   <div class="container">
       <h1>Título da Página</h1>
       <p>Este é um exemplo de uso da classe .container do Bootstrap.</p>
   </div>
   ```

A classe `.container` é uma parte fundamental para garantir que o conteúdo do seu site seja formatado de maneira responsiva e atraente em diferentes dispositivos. Ela ajuda a evitar que o conteúdo se estenda demais em telas largas e mantém o alinhamento centralizado, o que é comum em muitos designs de sites.

Lembre-se de que você pode usar a classe `.container` em várias partes do seu site, não apenas no início da página. É comum usá-la para agrupar seções de conteúdo que devem ser responsivas, como cabeçalhos, seções de texto e imagens.
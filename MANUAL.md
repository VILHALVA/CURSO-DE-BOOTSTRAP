# MANUAL
O Bootstrap é um framework popular para desenvolvimento front-end de sites e aplicativos web. Usar o CDN (Content Delivery Network) do Bootstrap é uma maneira conveniente de começar a usar o framework sem a necessidade de instalar nada em seu próprio servidor. 

## CONCEITOS:
É importante entender que existem várias maneiras de incorporar o Bootstrap em um projeto, cada uma com suas próprias vantagens e casos de uso. Vou explicar brevemente as diferentes abordagens e por que escolhemos nos concentrar exclusivamente no uso do CDN neste curso:

### DIFERENTES MANEIRAS DE USAR O BOOTSTRAP EM UM PROJETO:
1. **Via CDN (Content Delivery Network):**
   O CDN do Bootstrap permite incluir os arquivos CSS e JavaScript do Bootstrap diretamente em seu projeto, referenciando os URLs hospedados em servidores de terceiros. Isso proporciona uma maneira rápida e fácil de começar a usar o Bootstrap sem a necessidade de baixar ou gerenciar os arquivos localmente.

2. **Via CID (Component Identifier):**
   O CID do Bootstrap é uma abordagem mais avançada que permite personalizar quais componentes do Bootstrap você deseja incluir em seu projeto, reduzindo o tamanho total dos arquivos baixados. Isso é feito instalando o Bootstrap através de um gerenciador de pacotes como npm ou yarn e compilando os arquivos de origem.

3. **Via Zip (Download dos arquivos e execução com Node.js):**
   Esta abordagem envolve baixar o pacote zip do Bootstrap, extrair os arquivos e executá-los localmente usando Node.js. Isso pode ser útil em cenários onde você deseja trabalhar offline ou precisa de um controle mais granular sobre os arquivos do Bootstrap.

### FOCO NO CDN NO CURSO:
Neste curso, optamos por nos concentrar exclusivamente no uso do CDN do Bootstrap por algumas razões:

- **Facilidade de uso:** O CDN é a maneira mais simples e rápida de começar a usar o Bootstrap em um projeto. Não há necessidade de configurar nada ou baixar arquivos manualmente.

- **Acessibilidade:** O CDN torna mais fácil para os alunos acessarem e compartilharem o código do curso, já que não há dependência de arquivos locais ou configurações específicas do ambiente.

- **Economia de tempo:** Ao evitar a configuração local do Bootstrap, podemos nos concentrar mais nos conceitos e práticas de desenvolvimento web em vez de lidar com questões de configuração e ambiente.

- **Amplamente utilizado na indústria:** O uso do CDN reflete a maneira como o Bootstrap é frequentemente usado na indústria, onde a conveniência e a velocidade de implementação são prioridades.

## TUTURIAL:
### 01) USANDO O CDN DO BOOTSTRAP:
1. **Incluir os arquivos CSS e JavaScript:**
   No `<head>` do seu documento HTML, adicione os seguintes links para importar os arquivos CSS e JavaScript do Bootstrap:

   ```html
   <!-- CSS do Bootstrap -->
   <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">

   <!-- JavaScript do Bootstrap (opcional, mas necessário para alguns recursos do Bootstrap, como modais, dropdowns, etc.) -->
   <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
   ```

2. **Incluir o JavaScript do Bootstrap (opcional):**
   O Bootstrap Bundle inclui o JavaScript necessário para recursos interativos como modais, dropdowns, etc. Se você não precisar desses recursos, pode simplesmente incluir o CSS do Bootstrap.

3. **Estrutura básica do HTML:**
   Agora, você pode começar a usar as classes do Bootstrap em seu HTML para construir o layout e os componentes desejados.

### 02) USANDO O CID DO BOOTSTRAP:
O CID (Component Identifier) do Bootstrap é uma funcionalidade mais avançada que permite personalizar quais componentes do Bootstrap você deseja incluir em sua construção final, diminuindo o tamanho total dos arquivos baixados. Para usar o CID, você precisa instalar o Bootstrap através de um gerenciador de pacotes como npm ou yarn e depois compilar os arquivos de origem.

1. **Instalação via npm:**
   Abra seu terminal e navegue até o diretório do seu projeto. Em seguida, execute o seguinte comando para instalar o Bootstrap via npm:

   ```
   npm install bootstrap
   ```

   Isso instalará o Bootstrap e suas dependências em seu projeto.

2. **Compilação com CID:**
   Após a instalação, você pode compilar o Bootstrap com o CID para incluir apenas os componentes que precisa. Você precisará configurar sua ferramenta de compilação (por exemplo, Webpack, Parcel, etc.) para fazer isso.

   - Para o Webpack, você pode usar o plugin `babel-plugin-import` para importar componentes individualmente no seu código JavaScript.

   - Para o Parcel, você pode usar o plugin `parcel-plugin-bootstrap`.

   Certifique-se de consultar a documentação específica da ferramenta de compilação que está usando para obter instruções detalhadas sobre como configurar o CID do Bootstrap.

### 03) BAIXANDO O PACOTE ZIP DO BOOTSTRAP:
1. **Visite o site oficial do Bootstrap:**
   Acesse o site oficial do Bootstrap em [getbootstrap.com](https://getbootstrap.com).

2. **Vá para a página de download:**
   No menu de navegação do site, clique em "Get started" ou "Download" para ir para a página de download.

3. **Selecione a versão e faça o download:**
   Na página de download, você terá a opção de selecionar a versão do Bootstrap que deseja baixar. Escolha a versão desejada e clique no botão de download para baixar o pacote zip do Bootstrap.

4. **Extraia o conteúdo do arquivo zip:**
   Após o download ser concluído, extraia o conteúdo do arquivo zip para um diretório de sua escolha em seu computador.

### 04) EXECUTANDO COM NODE.JS:
1. **Instale o Node.js:**
   Se você ainda não tiver o Node.js instalado em seu sistema, faça o download e instale a versão adequada para o seu sistema operacional a partir do site oficial: [nodejs.org](https://nodejs.org).

2. **Abra o terminal:**
   Abra o terminal ou prompt de comando no seu sistema.

3. **Navegue até o diretório do projeto:**
   Use o comando `cd` para navegar até o diretório onde você extraiu os arquivos do Bootstrap.

4. **Inicialize um projeto Node.js (opcional):**
   Se você planeja usar o Node.js para gerenciar dependências ou executar scripts adicionais, pode inicializar um projeto Node.js no diretório do seu projeto usando o seguinte comando:
   ```
   npm init -y
   ```

5. **Instale o pacote http-server (opcional):**
   Para facilitar a execução do projeto localmente, você pode instalar o pacote `http-server` globalmente usando o seguinte comando:
   ```
   npm install -g http-server
   ```

6. **Inicie o servidor local:**
   Execute o comando abaixo para iniciar um servidor local que servirá os arquivos do Bootstrap:
   ```
   http-server
   ```

7. **Acesse o projeto no navegador:**
   Abra um navegador da web e acesse o endereço `http://localhost:8080` (ou outra porta, se especificada) para visualizar o seu projeto Bootstrap em execução.


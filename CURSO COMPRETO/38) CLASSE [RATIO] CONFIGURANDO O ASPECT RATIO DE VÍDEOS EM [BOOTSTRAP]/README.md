# CLASSE [RATIO] CONFIGURANDO O ASPECT RATIO DE VÍDEOS EM [BOOTSTRAP]

No Bootstrap 5, a classe `ratio` permite configurar o aspect ratio (proporção) de elementos, como vídeos, para garantir que eles mantenham uma relação de tamanho específica, independentemente do tamanho da tela. Essa classe é útil ao incorporar vídeos responsivos em seu site.

A classe `ratio` é seguida por um número que representa a largura e a altura da relação. Por exemplo, se você deseja que o vídeo tenha uma proporção de 16:9, você pode usar a classe `ratio-16x9`. Aqui está um exemplo de como usar essa classe para criar um vídeo com uma proporção de 16:9:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Classe de Aspect Ratio em Bootstrap</title>

    <!-- Inclua os arquivos CSS do Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>

    <div class="container mt-4">
        <div class="ratio ratio-16x9">
            <iframe src="https://www.youtube.com/embed/VIDEO_ID" allowfullscreen></iframe>
        </div>
    </div>

    <!-- Inclua os arquivos JavaScript do Bootstrap (incluindo a dependência do Popper.js) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>

</body>
</html>
```

Neste exemplo, usamos a classe `ratio-16x9` para criar um contêiner com uma proporção de 16:9. Em seguida, incorporamos um vídeo do YouTube dentro desse contêiner usando uma tag `<iframe>`. O vídeo manterá a proporção de 16:9, independentemente do tamanho da tela.

Você pode ajustar a classe `ratio` para corresponder à proporção desejada para o seu vídeo. Certifique-se de substituir `"VIDEO_ID"` no exemplo acima pelo ID do vídeo do YouTube ou o URL do vídeo que deseja incorporar. Certifique-se também de incluir os arquivos CSS e JavaScript do Bootstrap em seu projeto para que a classe de aspect ratio funcione corretamente.
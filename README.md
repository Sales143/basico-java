# basico-java
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script type="text/javascript">
        var nome = prompt("Digite seu nome completo");
        var idade = parseInt(prompt("Digite sua idade"));

        if (idade >= 18) {
            alert(nome + ", você precisa se alistar.");
        } else {
            alert(nome + ", você não tem a idade necessária.");
        }
    </script>
</body>
</html>

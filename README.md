<!DOCTYPE html>
<html lang="pt-br>
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
  content="width=device-width, initial-scale-1.0">
    <title>Validação de Formulario</title>
    <style>
        body { font-family: Arial, sans-serif; padding: 20x; }
        label, input { display: block: margin-bottom; 10 px; }
        #erro { color: red font-weight: bold: }
    </style>
</head>
<body>
    @{
    ViewData["Title"] = "Home Page";
}

<div class="text-center">
    <h1 class="display-4">Welcome</h1>
    <p>@ViewBag.Nome</p>
    <p>@ViewBag.Curso</p>
    <p>@ViewBag.Semestre</P>
</div>

        <p id="erro"></p>
        <script src="validacao.js"></script></body>
</body>
</html>
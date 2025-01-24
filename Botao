<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Copiar Código</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        #codigo {
            padding: 10px;
            background-color: #f0f0f0;
            border: 1px solid #ccc;
            border-radius: 5px;
            display: inline-block;
            margin-bottom: 10px;
            font-size: 18px;
        }
        button {
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>Copiar Código</h1>
    <p id="codigo">27cb4b83-1fa9-4553-b5d2-5320d989c2f8</p>
    <button onclick="copiarCodigo()">Copiar Código</button>

    <script>
        function copiarCodigo() {
            const codigo = document.getElementById('codigo').innerText;
            navigator.clipboard.writeText(codigo).then(() => {
                alert('Código copiado! Pode colar no seu banco.');
            }).catch(err => {
                console.error('Erro ao copiar código:', err);
            });
        }
    </script>
</body>
</html>

# java20_05
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        function operaçao(op){
            console.log (op);
            if (op === "*"){
                resultado.value = parseFloat(valor.value) * parseFloat(v2.value);
            }
    }

    </script>
   
   <h1> Produto </h1>
   Descrição: <input type="text" id="Coca" value=""><br>
   Quantidade: <input type="text" id="valor" value="0"><br>
 Preço unitário: <input type="text" id="v2" value="0"><br>
   <input type="button" value="Calcular" onclick="operaçao('*')"><br>
   
 Preço total: <input type="text" id="resultado" value="0" readonly><br>


</body>
</html>

# site-de-soma
pequeno script de soma
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Somando Números</title>
</head>
<body>
    <h1>SomandoValores </h1>
        <input type="number" name="txtn1" id= "txtn1"> +
        <input type="numer" name="txtn2" id="txtn2">
        <input type="button" value="Somar" onclick="somar()">
        <div id="res">Resultado</div>
    <script>
        function somar() {
            var tn1 = window.document.getElementById('txtn1')
            var tn2 = window.document.getElementById('txtn2')
            var res = window.document.getElementById('res')
            var n1 = Number(tn1.value)
            var n2 = Number(tn2.value) 
            var s = n1 + n2
            res.innerHTML = "a soma dos valores ${n1} e ${n2} é de ${s}"
        
        }

    </script>
</body>
</html>

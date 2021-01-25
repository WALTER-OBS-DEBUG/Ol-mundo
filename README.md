# Site-simples-com-CSS-e-JS-no-mesmo-arquivo-do-HTML.

<!DOCTYPE html>
<html lang="pt-br">
<head>  /* Cabeçalho da página */
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Walter Jonas</title>
    <style> /* ABRE A TAG STYLE PARA O CÓDIGO CSS */
        body{
            background-color: rgb(102, 52, 59);
            color: whitesmoke;
            font: normal 20pt arial;
        }
    </style> /* FECHA A TAG STYLE */
</head>
<body> /* CORPO DA PÁGINA*/
    <h1>BEM VINDO, MEU NOME É WALTER JONAS :)</h1>  
    <script>/* ABRE A TAG  SCRIPT PARA O CÓDIGO JS*/
       var res=window.confirm("ESTÁ GOSTANDO ?");/* APARECE UMA CAIXA DE CONFIRMAÇÃO NA PÁGINA */
       if(res){
        */SE O USUÁRIO CLICAR EM "OK" IRÁ APARECER O SEGUINTE ALERTA */
           alert('VOCÊ CLICOU EM OK');
       }
       else{
        */SE O USUÁRIO CLICAR EM "CANCELAR" IRÁ APARECER O SEGUINTE ALERTA */
           alert('VOCÊ CLICOU EM CANCELAR');
       }
    </script>
</body>
</html>

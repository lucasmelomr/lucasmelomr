<htmlh>
    <head>
        <meta charset="UTF-8">
        <title>Lucas DS102</title>
    </head>
    <body>
        <h1>DIGITE SEU NOME:</h1>
        <br>NOME:<input id="nome" type="text"></input>
        <br><br>SOBRENOME: <input id="sobrenome" type="text"></input>
        <button onClick="enviar()">ENVIAR</button>
        <script>
            function enviar(){
            var nome=document.getElementById('nome').value;
            var sobrenome=document.getElementById('sobrenome').value;
            var nomeCompleto=nome+' '+sobrenome;
            alert(nomeCompleto);
            }
        </script>
    </body>
</htmlh>

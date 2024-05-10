# proj-de-divulga-o-1

<!--criando um site teste do zero com ajuda do youtube
https://www.youtube.com/watch?v=edDCEK5QWE8 
LANDING PAGE COM HTML E CSS   --- até 28 min -->


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles.css">
</head>
</head>
<style>
    body {
        background-color:black; /* Azul marinho */
        color: #ffffff; /* Cor do texto */
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;


        background-color: rgb(34 , 34, 34);
    color: white;
    /*max-width: 12px;
    /*margin: 5%;*/
    
    
    }
    header{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        

    }
    li{
        display: inline-block;
        margin: 16px;
    }
    a{
        color:white;
    }

    a:hover{
        color:rgb(132, 14,201)
        transition: o,3s all;
    }

    #inscreva{
        border: 3px solid;
        padding: 10px;
        border-radius: 12px;
    }

    main{
        display: flex;
        flex-direction: row;
        margin-top: 50px;
    }
    h3{
        font-size: 55px;
        line-height: 10px;
        font-family: poppinsmediun;
    
    }
    span{
        color: rgb(132, 14,201)
    }
    p{
        line-height: 15px;
        max-width: 450px;
        font-family: popinslight;
    }
    image{
        width: 20px;
    }

    form{
        display: flex;
        flex-direction: column;
        width: 35%;
    }

    form [type="submit"]{
        height: 30px;
        width: 70px;
        background-color: rgb(132,14,201);
        color: white;
        font-weight: bold;
        

    }

    form [type="submit"]:hover{
        cursor: pointer;
    }
    
    

    


    input{
        margin-top: 12px;
        height: 20px;
        padding: 5px;
        border-radius: 20px;
        border: nome;
        font-size: 15px;
    }

    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.container {
    width: 80%;
    margin: 0 auto;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 20px;
}

th, td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: left;
}

th {
    background-color: #f2f2f2;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

footer p {
    margin: 0;
}

/* Estilos para a bandeira do Brasil */

.bandeira-do-japao {
    width: 300px;
    height: 200px;
    position: relative;
}

.retangulo {
    background-color: #FFFFFF;
    width: 200px;
    height: 150px;
    position: absolute;
    top: 25px;
    left: 50px;
}

.circulo {
    background-color: #FF0000;
    border-radius: 50%;
    width: 150px;
    height: 150px;
    position: absolute;
    top: 25px;
    left: 75px;
}
</style>
<header>
        <div>
            <div>
                <p>"Eu falhei repetidamente na minha vida. E é por isso que eu consegui."</p>
            </div>
            <h3>marketing  </h3>
            <h3> de divulgação</h3>
            <div>
                <div>
                    "Eu posso aceitar a falha, todos falham em algo. Mas eu não posso aceitar não tentar."
                </div>

            </div>
            
        </div>
        
        <ul>
        <span><P> 😳</P>
            
        <a href="a"></a><li>inicio</li>
        <a href="a"></a><li>sobre</li>
        <a href="a"></a><li>contato</li>
        <a href="a" id="inscreva"></a>
        
        </span>
        <aside>
            <div>
                <body>
                    <div class="bandeira-do-japao">
                        <div class="retangulo"></div>
                        <div class="circulo"></div>
                    </div>
                </body>
            </div>
        </aside>
              
        </ul>
    </header>
    <main>
    <aside>
        <h2><span>increva - se agora</span></h2>
        <h2>seja um patracinador</h2>
    
    
   <p><h5>
    este é um  site pessoal para divulgação do meu trabalho,
    caso voce queira saber meis click no botão saber mais e
     acesse minhas redes 
    sociais no instagram e facebook
   </h5></p>
   <form >
        <input type="text" placeholder="nome">
        <input type="email" placeholder="email">
        <input type="submit" value="enviar >  " >

</form>
   </aside>
    <article>
        
        <img src="./WhatsApp Image 2023-10-22 at 20.59.03.jpeg" alt="imagem guadra" width="600 " height="300">
        
        <body>
            <div class="container">
                <h1>Planos</h1>
                <table>
                    <tr>
                        <th></th>
                        <!--<th>Recursos</th>
                        <th>Preço</th>-->
                    </tr>
                    <tr>
                        <td>"Eu posso aceitar a falha, todos falham em algo. Mas eu não posso aceitar não tentar."</td>
                       <!-- <td>Recursos básicos</td>
                        <td>R$ 10/mês</td>-->
                    </tr>
                    <tr>
                        <td>"O talento vence jogos, mas o trabalho em equipe e a inteligência vencem campeonatos."</td>
                        <!--<td>Recursos padrão</td>
                        <td>R$ 20/mês</td>-->
                    </tr>
                    <tr>
                        <td>"Não é sobre o quão duro você pode bater, é sobre quão duro você pode ser atingido e continuar seguindo em frente."</td>
                        <!--<td>Recursos premium</td>
                        <td>R$ 30/mês</td>-->
                    </tr>
                </table>
            </div>
            <footer>
                <div class="container">
                    
                    <p>"Eu jogo para vencer, seja durante os treinos ou em um jogo real."</p>
                    <p>Rodapé - © 2024 Planos Inc.</p>
                </div><hr>
                    
            </footer>
        </body>
        </html>
</article>
    </style>
    </main>
    <div class="container">
        <h2>Verificar Positivo ou Negativo</h2>
        <label for="valor1">Valor 1:</label>
        <input type="number" id="valor1">
        <br>
        <label for="valor2">Valor 2:</label>
        <input type="number" id="valor2">
        <br>
        <button onclick="verificarPositivoNegativo()">Verificar</button>
        <p id="resultado"></p>
      </div><hr> 
    <script>
        function verificarPositivoNegativo() {
          var valor1 = parseFloat(document.getElementById("valor1").value);
          var valor2 = parseFloat(document.getElementById("valor2").value);
          var resultadoElemento = document.getElementById("resultado");
    
          if (isNaN(valor1) || isNaN(valor2)) {
            resultadoElemento.textContent = "Por favor, insira valores numéricos válidos.";
          } else {
            if (valor1 > 0 && valor2 > 0) {
              resultadoElemento.textContent = "Ambos os valores são positivos.";
            } else if (valor1 < 0 && valor2 < 0) {
              resultadoElemento.textContent = "Ambos os valores são negativos.";
            } else {
              resultadoElemento.textContent = "Um valor é positivo e o outro é negativo.";
              
            }
    }
}
</body>
</html>

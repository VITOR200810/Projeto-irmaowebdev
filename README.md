<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="estudo.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Empresa</title>
</head>
<body>
    <header>

        <h1>Adidas</h1>
        <nav>

            <a href="#">Inicio</a>
            <a href="#">Sobre</a>
            <a href="#">Contato</a>
         </nav>
    </header>


    <div>
    <section class=" hero">

        <h2> Seção principa</h2>
        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet, sit?</p>

        <button> Saiba mais </button>

    </section>

    <section class="services">

        <article>
            <h2> Sapato:</h2>
            <p> Lorem ipsum dolor sit 
                amet consectetur adipisicing elit.</p>



        </article>

        <article>

         <h2> Blusa:</h2>
            <p> Lorem ipsum dolor sit 
                amet consectetur adipisicing elit.</p>


        </article>
    </section>
    
    <aside>

        <h2> 112870565:</h2>

        <p>
            Entre em contato com agente
        </p>

    </aside>
    </div>

    <form action="1">

        <h3> CADASTRO</h3>

        <P> Se cadastre abaixo:</P>


        <label for="nome"> Nome:</label>
        <input type="text" id="nome" name="nome"><br>

        <label for="idade">Idade:</label><br>
        <input type="number" id=" idade" name="idade"><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br>

        <label for="Mensagem">Mensagem:</label>
        <textarea name="Mensagem" id="Mensagem" name="Mensagem"></textarea>

        <label for="enviar">Enviar</label><br>
        <input type="submit" id="enviar" name="enviar">


    </form>

    <footer>
        <p> © 2026 Vitor)</p>
    </footer>
    
    


    
</body>
</html>
body{
    background-color: rgb(250, 245, 238);
    margin: 0px;
    
}
h1{
    text-shadow: 0 0 10px;
}
header{
    background-color: aliceblue;
    padding: 5px;
    text-align: center;
    color: rgb(48, 50, 53);
}
header a{
    margin: 10px;
    color: rgb(3, 4, 5);
}
div{
    display: flex;
}
section{
    background-color: aliceblue;
    padding: 10px;
    margin: 10px;

}
aside{
    background-color: rgb(208, 208, 230);
    padding: 10px;
    margin: 10px;

}
main{
    background-color: rgb(205, 216, 238);
    margin: 10px;
}
form{
    background-color: rgb(187, 187, 248);
    margin: 10px;
    width: 100%;
}
input{
    margin: 5px;
    width: 100%;
}
textarea{
    width: 100%;
}
h3{
    text-align: center;
}
footer{
    text-align: center;
    background-color: rgb(12, 11, 9);
    width: 100%;
    color: aliceblue;
}
h2{
    text-align: center;
}
button{
    padding: 5px;
    border-radius: 5px;
    
}
button:hover{
    background-color: blueviolet;
    color: rgb(194, 214, 13);
    text-shadow: 0 0 100px;

}
a:hover{
    background-color: rgb(34, 133, 219);
    border-radius: 5px;
    text-shadow: 0 0 10px;
}


<html>
    <head>
        <style>
            body {
                margin: 0px;
                background-color: #EEE;
            }
            form {
                width: 230px;
                height: 240px;
                background-color: #DDD;
                margin: auto;
                padding: 20px;
                margin-top: 20px;
            }
            input {
                padding: 5px;
                font-size: 13px;
            }
            .topo{
                width: 400px;
                height: 200px;
                margin: auto;
                padding: 20px;
                margin-top: 20px;
                text-align: center;
            }
        </style>
    </head>
    <body>
        <div>
            <div class="topo">
                <h1>Área de Login</h1>
                <h3>Apenas Tecnicos</h3>
            </div>
            <form method="POST">
                Login:<br>
                <input type="text" name="usuario" size="20" autofocus placeholder="Usuario"/><br><br>
                Senha:<br/>
                <input type="password" name="senha" size="20" placeholder="Senha"/><br><br>
                <input type="submit" name="enviar" class="enviar"/>
            </form>
        </div>
    </body>
</html>

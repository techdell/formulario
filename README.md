# formulario
area de login
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8"/>
        <title>Area de Login</title>
        <style>
            body {
                margin: 0px;
                background-color: #EEE;
            }
            form {
                width: 300px;
                height: 300px;
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
                <input type="text" name="usuario" autofocus placeholder="Usuario"/><br><br>
                Senha:<br/>
                <input type="password" name="senha" placeholder="Senha"/><br><br>
                <input type="submit" name="enviar" class="enviar"/>
            </form>
        </div>
    </body>
</html>

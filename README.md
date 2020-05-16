<html>
    <head>
        <style>
            body {
                background-size:1370px;
                height: 900px;
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
                border: 1px solid #111;
                border-radius: 10px;
            }
            .topo{
                width: 400px;
                height: 200px;
                margin: auto;
                padding: 20px;
                margin-top: 20px;
                text-align: center;
            }
            h1 {
                font-weight: bold;
                color: #FFFFFF;
            }
            h3 {
                font-weight: bold;
                color: #FFFFFF;
            }
        </style>
    </head>
    <body background="https://cdn.pixabay.com/photo/2017/03/25/17/55/color-2174045_960_720.png">
        <div>
            <div class="topo">
                <h1>Área de Login</h1>
                <h3>Apenas Tecnicos</h3>
            </div>
            <form method="POST">
                Login:<br>
                <input type="text" name="usuario" autocomplete="off" required size="20" autofocus placeholder="Usuario"/><br><br>
                Senha:<br/>
                <input type="password" name="senha" autocomplete="off" required maxlength="8" size="20" placeholder="Senha"/><br><br>
                <input type="submit" name="enviar" class="enviar"/>
            </form>
        </div>
    </body>
</html>

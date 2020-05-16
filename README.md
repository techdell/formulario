<html>
    <head>
        <style>
            body {
                background-size:1370px;
                height: 597px;
            }
            form {
                width: 300px;
                height: 300px;
                background-color: #DDD;
                margin: auto;
                padding: 20px;
                margin-top: 20px;
                box-shadow: rgba(24, 23, 23, 0.678) 7px 7px 10px;
                font-size: 20px;
                border-radius: 10px;
            }
            input {
                padding: 8px;
                font-size: 15px;
                border: 1px solid #111;
                border-radius: 10px;
                box-shadow: rgba(24, 23, 23, 0.678) 7px 7px 7px;
            }
            .topo{
                width: 400px;
                height: 150px;
                margin: auto;
                padding: 20px;
                margin-top: 20px;
                text-align: center;
            }
            h1 {
                font-weight: bold;
                color: #FFFFFF;
                text-shadow: rgba(24, 23, 23, 0.678) 2px 2px 1px;
            }
            h3 {
                font-weight: bold;
                color: #FFFFFF;
                text-shadow: rgba(24, 23, 23, 0.678) 2px 2px 1px;
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
                <input type="text" name="usuario" autocomplete="off" size="50px" required autofocus placeholder="Usuario"/><br><br>
                Senha:<br/>
                <input type="password" name="senha" autocomplete="off" required maxlength="8" size="30px" placeholder="Senha"/><br><br>
                <input type="submit" name="enviar" size="21" class="enviar"/>
            </form>
        </div>
    </body>
</html>

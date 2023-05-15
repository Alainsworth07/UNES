<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Contato</title>

    <link rel="stylesheet" href="estilos.css">
        
</head>

    <body>
        <header>
                <nav>
                    <ul id="MenuSup">
                        <li><a href="..//UNES/index.html" target="#">Home</a></li>
                        <li><a href="..//UNES/quemsomos.html" target="#">Quem somos</a></li>
                        <li><a href="..//UNES/contato.html" target="#">Contato</a></li>
                    </ul>
                </nav>

        </header>

        <div class="Img">
            <img src="..//UNES/IMAGES/logo01.png">
        </div>
        
        <br>
            <div class="div01">
                <h2>Entre em contato</h2>

                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse sit amet mollis nisl.</p>

                <hr>

                <form>

                    E-mail:
                    <br>
                        <input type="email" name="e-mail">
                    <br>

                    Assunto:
                    <br>
                        <input type="text" name="Assunto">
                    <br>

                    Descrição:
                    <br>
                        <textarea></textarea>
                    <br>

                <form>

                <br>
                    <input type="button" value="Enviar" onclick="msg()">
                </form>
              
                <script>
              function msg() {
                alert("Enviado");
                }
                </script>
              
            </form>
        </div>

        <footer style="margin-top: 310px;">Todos os direitos reservados</footer>

    </body>

</html>

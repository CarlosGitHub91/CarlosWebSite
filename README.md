# CarlosWebSite
Primer proyecto, en creación de perfil
<!DOCTYPE html>
<html>
    <head>
        <title>TODO supply a title</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        <div>
            <form method ="post" action="procesaDatos.php">
                <p>
                    <label for ="nombre">Nombre:</label><input id ="nombre" type = "text" size = "20"/><br/>
                    <label for ="apellido">apellido:</label><input id ="apellido" type = "text" size = "20"/><br/>
                    <label for ="email">email:</label><input id ="email" type = "text" size = "20"/><br/>
                    <label for ="clave">clave:</label><input id ="clave" type = "text" size = "20"/><br/>
                    <input type= "submit" value="Enviar información"/>
                    <input type="reset" value= "Borrar Selección"/>            
                </p>
            </form>
        </div>  
        <div>
            <table border ="1">
                <tr>
                    <td>Casilla1</td>
                    <td>Casilla2</td>
                </tr>
                 <tr>
                    <td>Casilla3</td>
                    <td>Casilla4</td>
                </tr>
                 <tr>
                    <td>Casilla5</td>
                    <td>Casilla6</td>
                </tr>
            </table>
            <br></br>
        </div>
        <div>
            <table border ="1">
                <tr>
                    <td>1</td>
                    <td>2</td>
                    <td>3</td>
                    <td>4</td>
                    <td>5</td>
                </tr>
                <tr>
                    <td>6</td>
                    <td>7</td>
                    <td>8</td>
                    <td>9</td>
                    <td>10</td>
                </tr>
            </table>
        </div>
    </body>
</html>

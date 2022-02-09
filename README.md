<!DOCTYPE html>
<html>
<head>
    <title>
        Aula 02.02
    </title>
</head>
    <body bgcolor="Gray">
        <h1>Formulario</h1>
        <form>
           <label>Nome</label><div>
            <input type="text" id="nome" required><br>
                </div>
            <label>E-mail</label> <div>
            <input type="email" id="mail" required><br>
                </div>
            <label>Idade</label> <div>
            <input type="number" id="idade" required><br>
                </div>
           <label>Password</label> <div>
            <input type="password" id="senha" required>
            
                </div>
            Sexo <div>
            <select>
                <option value="Masculino">Masculino</option>
                <option value="Femenino"> Femenino</option>
                <option value="NaoInformado">No informado</option>
                </select>
                <br>
                        </div>
                        <input type="submit">
                        <input type="submit" onmouseover="exibeResultado()" value ="Ola">
            
        </form>
        <hr>
        <script>
            function exibeResultado(){
                alert ("Ola,bem-vindo");
            }
        </script>

    </body>
</html>

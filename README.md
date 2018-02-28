<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Gameera, tu buscador de juegos</title>
</head>
<body>
  <header>
      <h1>Busca tus juegos al mejor precio</h1>
      <nav>
        <form id='form' name='form' method='post' action='resultados.php'>
          <input id='search' name='search' type='text' placeholder='Escribe aquí...' onfocus='if(this.placeholder =='')this.placeholder ='Busca aquí'' />
          <input type='submit' name='Submit' id='button' value='Buscar' />
        </form>
        <form id='form' name='form' method='post' action='login.php'>
          <input type='submit' name='Submit' id='button' value='Iniciar sesión' />
        </form>
        <form id='form' name='form' method='post' action='register.php'>
          <input type='submit' name='Submit' id='button' value='Únete' />
        </form>
      </nav>
    </header>
</body>
<footer>
  <ul>
    <li><a href="contacto" href="link">Contacta con nosotros</a></li>
  </ul>
</footer>
</html>

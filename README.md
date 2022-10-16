# TP_Codo_a_Codo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/Practica_Obligatoria_css.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap" rel="stylesheet">
     <!-- Bootstrap CSS -->
     <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

</head>
<body> 
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Codo a Codo</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Inicio</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link disabled">Desactivado</a>
              </li>
            </ul>
            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="Buscar" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Buscar</button>
            </form>
          </div>
        </div>
      </nav>

      <div class="card-group">
        <div class="card">
          <img src="hmtl5.png" class="card-img-top" alt="imagen1">
          <div class="card-body">
            <h5 class="card-title">Titulo 1</h5>
            <p class="card-text">Contenido de Card.</p>
            <p class="card-text"><small class="text-muted">Ultima actualizacion 1</small></p>
          </div>
        </div>
        <div class="card">
          <img src="css3.png" class="card-img-top" alt="imagen2">
          <div class="card-body">
            <h5 class="card-title">Titulo 2</h5>
            <p class="card-text">Contenido de Card.</p>
            <p class="card-text"><small class="text-muted">Ultima actualizacion 1</small></p>
          </div>
        </div>
        <div class="card">
          <img src="bootstrap.png" class="card-img-top" alt="imagen3">
          <div class="card-body">
            <h5 class="card-title">Titulo 3</h5>
            <p class="card-text">Contenido de Card.</p>
            <p class="card-text"><small class="text-muted">Ultima actualizacion 1</small></p>
          </div>
        </div>
      </div>

      <form>
        <div class="mb-3">
          <label for="exampleInputEmail1" class="form-label">Email</label>
          <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
          <div id="emailHelp" class="form-text">Nunca comparta su email.</div>
        </div>
        <div class="mb-3">
          <label for="exampleInputPassword1" class="form-label">Contraseña</label>
          <input type="password" class="form-control" id="exampleInputPassword1">
        </div>
        <div class="mb-3 form-check">
          <input type="checkbox" class="form-check-input" id="exampleCheck1">
          <label class="form-check-label" for="exampleCheck1">Verificar</label>
        </div>
        <button type="submit" class="btn btn-primary">Enviar</button>
      </form>
</body>
</html>

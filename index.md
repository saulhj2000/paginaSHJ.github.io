<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina principal</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
    
    
    <style>
      .bd-placeholder-img {
        font-size: 1.125rem;
        text-anchor: middle;
        -webkit-user-select: none;
        -moz-user-select: none;
        user-select: none;
      }

      @media (min-width: 768px) {
        .bd-placeholder-img-lg {
          font-size: 3.5rem;
        }
      }

      .b-example-divider {
        height: 3rem;
        background-color: rgba(0, 0, 0, .1);
        border: solid rgba(0, 0, 0, .15);
        border-width: 1px 0;
        box-shadow: inset 0 .5em 1.5em rgba(0, 0, 0, .1), inset 0 .125em .5em rgba(0, 0, 0, .15);
      }

      .b-example-vr {
        flex-shrink: 0;
        width: 1.5rem;
        height: 100vh;
      }

      .bi {
        vertical-align: -.125em;
        fill: currentColor;
      }

      .nav-scroller {
        position: relative;
        z-index: 2;
        height: 2.75rem;
        overflow-y: hidden;
      }

      .nav-scroller .nav {
        display: flex;
        flex-wrap: nowrap;
        padding-bottom: 1rem;
        margin-top: -1px;
        overflow-x: auto;
        text-align: center;
        white-space: nowrap;
        -webkit-overflow-scrolling: touch;
      }
    </style>

    
</head>
<body>
  
    <main>
        <div>
            <header class="p-3 bg-dark text-white">
                <div class="container">
                    
                  <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
                    
                    <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
                      <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"/></svg>
                    </a>

                    <div id="sidemenu" class="menu-collapsed">
                        <div id="titulo"></div>
                    </div>
            
                    <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
                      <li><a href="index.html" class="nav-link px-2 text-white">Bienvenida</a></li>
                      <li><a href="album.html" class="nav-link px-2 text-white">Álbum</a></li>
                      <li><a href="acerca.html" class="nav-link px-2 text-white">Acerca de</a></li>
                    </ul>
            
                    <form class="col-12 col-lg-auto mb-3 mb-lg-0 me-lg-3" role="search">
                      <input type="search" class="form-control form-control-dark text-white bg-dark" placeholder="Search..." aria-label="Search">
                    </form>
            
                    <div class="text-end">
                      <button type="button" class="btn btn-outline-light me-2">
                        <a href="login.html" class="nav-link px-2 text-white">Iniciar Sesion</a>
                      </button>
                      
                      <button type="button" class="btn btn-warning">
                        <a href="Registro.html" class="nav-link px-2 text-white">Registrarse</a>
                      </button>
                    </div>
                  </div>
                </div>
              </header>
        </div>
      </main>

      <main>
        <link href="carousel.css" rel="stylesheet">
        <div id="myCarousel" class="carousel slide" data-bs-ride="carousel">
          <div class="carousel-indicators">
            
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active" align="center">
              <img src="img/ico.jpg" alt="">
              
            </div>
            
            <div class="carousel-item">
              <svg class="bd-placeholder-img" width="100%" height="100%" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" preserveAspectRatio="xMidYMid slice" focusable="false"><rect width="100%" height="100%" fill="#777"/></svg>
      
              <div class="container">
                <div class="carousel-caption text-end">
                  <h1>One more for good measure.</h1>
                  <p>Some representative placeholder content for the third slide of this carousel.</p>
                  <p><a class="btn btn-lg btn-primary" href="#">Browse gallery</a></p>
                </div>
              </div>
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#myCarousel" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#myCarousel" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
       
          <div class="container marketing">

            <!-- Three columns of text below the carousel -->
            <div class="row bg-success p-2 text-dark bg-opacity-25" >
              <div class="col-lg-4 ">
                <svg class="bd-placeholder-img rounded-circle" width="140" height="140"  role="img" aria-label="Placeholder: 140x140" preserveAspectRatio="xMidYMid slice" ><img src="img/otras.jpg"><title>Placeholder</title></svg>
                <h2 class="fw-normal">Productos</h2>
                <p>Productos, buenos y baratos</p>
                <p><a class="btn btn-secondary" href="#">Contáctanos &raquo;</a></p>
              </div><!-- /.col-lg-4 -->
              <div class="col-lg-4">
                <svg class="bd-placeholder-img rounded-circle" width="140" height="140"  role="img" aria-label="Placeholder: 140x140" preserveAspectRatio="xMidYMid slice" ><img src="img/category.png"  width="280" height="280"><title>Placeholder</title></svg>
        
                <h2 class="fw-normal">Servicios</h2>
                <p>Recargas, impresiones, enmicados y mucho mas</p>
                <p><a class="btn btn-secondary" href="#">Contáctanos &raquo;</a></p>
              </div><!-- /.col-lg-4 -->
              <div class="col-lg-4">
                <svg class="bd-placeholder-img rounded-circle" width="140" height="140"  role="img" aria-label="Placeholder: 140x140" preserveAspectRatio="xMidYMid slice" ><img src="img/bolsas de regalo.jpg"><title>Placeholder</title></svg>
                <h2 class="fw-normal">Regalos</h2>
                <p>Para toda ocasion</p>
                <p><a class="btn btn-secondary" href="#">Contáctanos &raquo;</a></p>
              </div><!-- /.col-lg-4 -->
            </div><!-- /.row -->
        
        
            <!-- START THE FEATURETTES -->
        
            <hr class="featurette-divider">
        
            <div class="row featurette bg-success p-2 text-dark bg-opacity-50">
              <div class="col-md-7" align="center">
                <h2 class="featurette-heading fw-normal lh-1">Ubicación<span class="text-muted"></span></h2>
                <p class="lead">Carretera Federal Mtz de la Torre- Tlapacoyan</p>
                <p class="lead">Papeleria y novedades Maped</p>
                <p class="lead">Telefono: 2321022481</p>
              </div>
              <div class="col-md-5">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2466.1750386371673!2d-97.16312949361996!3d20.015499865533062!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x85dafd3699979537%3A0xd354f2a3e7d1003f!2sPapeleria%20y%20Novedades%20Maped!5e0!3m2!1ses!2smx!4v1655150976983!5m2!1ses!2smx" width="500" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
              </div>
            </div>
        
          </div><!-- /.container -->
        

      </main>

      <footer >
        <div class="container p-3 mb-2 bg-info" align="center" >
          
          <p class="mb-1">Copyright &copy; Saul Hernandez Jacobo</p>
          <p class="mb-0">Junio 2022, Papeleria y Novedades Maped</p>
          <p class="mb-0">El Jobo, Tlapacoyan,Veracruz.</p>
        </div>
      </footer>
        

        

        
    
</body>
</html>

<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./CSS/style.css">
    <link rel="stylesheet" href="./CSS/bootstrap.min.css">
    <!-- iconos fontawesome -->
    <script src="https://kit.fontawesome.com/1852a29f64.js" crossorigin="anonymous"></script>
    <title>Holl Consulting</title>
</head>

<body>
    <header>
        <section class="grid">
            <nav class="navbar fixed-top justify-content-center navbar-expand-lg navbar-light " id="navbar_top">
                <div class="container-fluid">
                    <a class="navbar-brand flex-grow-1" href="#">
                        <img src="./img/logo.png" alt="" width="250" height="60">
                    </a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                        data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false"
                        aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                        <div class="navbar-nav text-uppercase">
                            <a class="nav-link text-light active" aria-current="page" href="#">Inicio</a>
                            <a class="nav-link text-light" href="#sobre_nosotros">sobre nosotros</a>
                            <a class="nav-link text-light" href="#servicios">nuestros servicios</a>
                            <a class="nav-link text-light" href="#contacto" tabindex="-1"
                                aria-disabled="true">contáctenos</a>
                        </div>
                    </div>
                    <div id="navbarNavAltMarkup" class="mr-100">
                        <div class="social d-none d-sm-none d-md-block">
                            <a href=""> <i class="menu__icon m-20 text-dark fab fa-facebook-square"></i></a>
                            <a href=""><i class="menu__icon text-dark fab fa-instagram-square"></i></a>
                            <a href=""><i class="menu__icon text-dark fab fa-whatsapp-square"></i></a>
                        </div>
                    </div>
                </div>
            </nav>



            <div class="grid__texts">
                <h2 class="grid__title">Consultoria </h2>
                <h2 class="grid__title grid__title--transform">personalizada</h2>
                <button type="button" class="btn btn-secondary btn-lg w-25 text-align-right">
                    <a class="text-decoration-none" href="#sobre_nosotros">Ver Mas</a></button>
            </div>

        </section>
    </header>
    <h2 class="about__title text-center fs-1" id="sobre_nosotros">SOBRE NOSOTROS</h2>

    <div class="container">
        <div class="row">
            <div class="col col-sm-9">

                <p>Durante más de 20 años hemos estado actualizando los procesos de negocio y las estructuras de
                    TI mediante
                    la
                    implementación y el soporte de soluciones de negocio. Utilizamos siempre las tecnologías que
                    mejor se
                    adaptan a las necesidades de cada proyecto. Además de los sistemas Microsoft Dynamics ERP y
                    CRM, nuestra
                    plataforma incluye soluciones digitales de áreas como datos y análisis, inteligencia
                    artificial (IA),
                    colaboración y las tecnologías de automatización e intercambio de datos conocidas como
                    "Industria 4.0".

                    Nuestros sistemas pueden funcionar tanto en la nube como de forma tradicional en el propio
                    centro de
                    datos
                    de la empresa. Están disponibles en la oficina desde su PC o en el campo desde teléfonos
                    inteligentes o
                    tabletas. Nuestras soluciones sectoriales para la industria manufacturera, las empresas de
                    servicios, el
                    sector de la construcción y el comercio adoptan un enfoque holístico, están diseñadas para
                    estar a
                    prueba
                    del futuro y han demostrado su eficacia en la práctica. Como proveedor de soluciones
                    integrales, podemos
                    cubrir sin problemas todos los procesos de negocio de nuestros clientes utilizando
                    soluciones de última
                    generación.</p>


                </section>

            </div>

            <div class="col col-md-3">
                <div class="accordion accordion-flush w-25 m-auto " id="accordionFlushExample">

                    <div class="accordion-item">

                        <h2 class="accordion-header" id="flush-headingOne">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                                data-bs-target="#flush-collapseOne" aria-expanded="false"
                                aria-controls="flush-collapseOne">
                                01. Años de experiencía
                            </button>
                        </h2>
                        <div id="flush-collapseOne" class="accordion-collapse collapse"
                            aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body">Aún y cuando Holl Consulting es una idea nueva los socios
                                cuentan con
                                años de experiencia trabajando en asuntos regulatorios.</div>
                        </div>
                    </div>
                    <div class="accordion-item">
                        <h2 class="accordion-header" id="flush-headingTwo">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                                data-bs-target="#flush-collapseTwo" aria-expanded="false"
                                aria-controls="flush-collapseTwo">
                                02. Disponibilidad virtual
                            </button>
                        </h2>
                        <div id="flush-collapseTwo" class="accordion-collapse collapse"
                            aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body">Cuánto tiempo toma trasladarse para reunirse con tus
                                consultores cuando
                                puedes tener reuniones virtuales en cualquier momento.</div>
                        </div>
                    </div>
                    <div class="accordion-item">
                        <h2 class="accordion-header" id="flush-headingThree">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                                data-bs-target="#flush-collapseThree" aria-expanded="false"
                                aria-controls="flush-collapseThree">
                                03. Análisis de inteligencia
                            </button>
                        </h2>
                        <div id="flush-collapseThree" class="accordion-collapse collapse"
                            aria-labelledby="flush-headingThree" data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body">La definición del problema es el primer y más importante
                                paso.
                                Comprender los pasos para afrontarlo es vital para ayudarlo en su negocio. </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- FIN SOBRE NOSOTROS -->


    <!-- NUESTROS SERVICIOS -->
    <div class="services">
        <h2 id="servicios" class="text-center text-light">NUESTROS SERVICIOS</h2>

        <div class="container">
            <div class="row justify-content-center ">
                <div class="col-12 col-lg-4 col-md-6 col-sm-12 text-center">
                    <i class="fas fa-balance-scale"></i>
                    <h2 class="text-light">Políticas Públicas</h2>
                    <p class="text-light">El sector empresarial se ve afectado en menor o mayor medida por la ejecución
                        de políticas
                        públicas.Conocemos y entendemos el proceso de diseño de políticas públicas en
                        México, lo que nos permite brindar asesorías para evitar riesgos en las empresas. </p>

                </div>
                <div class="col col-lg-4 col-md-6 col-sm-12 text-center ">
                    <i class="fas fa-file-alt"></i>
                    <h2 class="text-light">Regulaciones técnicas</h2>
                    <p class="text-light">Es esencial cumplir con las reglas, especificaciones, directrices y
                        características aplicables a
                        un producto, proceso o servicio que establecen las Normas Oficiales Mexicanas y Estándares para
                        brindar seguridad y certeza jurídica a los consumidores.</p>
                </div>
                <div class="col-12 col-lg-4 col-md-6 col-sm-12 text-center">
                    <i class="fas fa-search-location"></i>
                    <h2 class="text-light">Comercio Exterior</h2>
                    <p class="text-light">Se prestan servicios integrales de asesoría jurídica en las operaciones
                        comerciales
                        internacionales, a fin de dar cumplimiento a los requisitos legales para importar y exportar en
                        un mercado competitivo que permita eficientar los proyectos de nuestros clientes. </p>
                </div>
                <div class="col col-lg-4 col-md-12 col-sm-12 text-center">
                    <i class="fas fa-brain"></i>
                    <h2 class="text-light">Propiedad intelectual</h2>
                    <p class="text-light">ofrece soluciones estratégicas con un enfoque nacional e internacional, para
                        proteger marcas y
                        demás aspectos relacionados con la mismas, así como avisos comerciales, nombres comerciales y,
                        en general, cualquier asunto en materia de propiedad intelectual.</p>
                </div>
                <div class="col col-lg-4 col-md-6 col-sm-12 text-center">
                    <i class="fas fa-building"></i>
                    <h2 class="text-light">Mercados Regulados</h2>
                    <p class="text-light">El proceso regulatorio en México respecto a mercados específicos como agua,
                        energía y
                        telecomunicaciones es un laberinto donde los objetivos legítimos de política pública no son del
                        todo claros y precisos. Ayudamos a nuestros clientes a evitar contingencias legales y a
                        participar activamente en los mecanisos de participación establecidos en la ley. </p>
                </div>
                <div class="col col-lg-4 col-md-6 col-sm-12 text-center">
                    <i class="fas fa-poll"></i>

                    <h2 class="text-light">Resolución de controversias</h2>
                    <p class="text-light"> proporciona asesoría y representación jurídica para la resolución de
                        controversias que puedan
                        surgir por la constante interacción de las empresas con autoridades, socios y/o clientes.
                        Nuestras estrategias son encaminadas a obtener resultados favorables y eficientes. </p>
                </div>
            </div>
        </div>




    </div>

    <!-- FORMULARIO -->
    <div class="contact">
        <div class="container">
            <div class="row">
                <div class="col col-lg-8 col-md-12 col-sm-12">
                    <div class="container">
                        <div class="row">
                            <div class="col-md-12">
                                <div class="well well-sm">
                                    <form class="form-horizontal" method="post">
                                        <fieldset>
                                            <legend class="text-center header">Contact us</legend>

                                            <div class="form-group">
                                                <span class="col-md-1 col-md-offset-2 text-center"><i
                                                        class="fa fa-user bigicon"></i></span>
                                                <div class="col-md-8">
                                                    <input id="fname" name="name" type="text" placeholder="First Name"
                                                        class="form-control">
                                                </div>
                                            </div>
                                            <div class="form-group">
                                                <span class="col-md-1 col-md-offset-2 text-center"><i
                                                        class="fa fa-user bigicon"></i></span>
                                                <div class="col-md-8">
                                                    <input id="lname" name="name" type="text" placeholder="Last Name"
                                                        class="form-control">
                                                </div>
                                            </div>

                                            <div class="form-group">
                                                <span class="col-md-1 col-md-offset-2 text-center"><i
                                                        class="fa fa-envelope-o bigicon"></i></span>
                                                <div class="col-md-8">
                                                    <input id="email" name="email" type="text"
                                                        placeholder="Email Address" class="form-control">
                                                </div>
                                            </div>

                                            <div class="form-group">
                                                <span class="col-md-1 col-md-offset-2 text-center"><i
                                                        class="fa fa-phone-square bigicon"></i></span>
                                                <div class="col-md-8">
                                                    <input id="phone" name="phone" type="text" placeholder="Phone"
                                                        class="form-control">
                                                </div>
                                            </div>

                                            <div class="form-group">
                                                <span class="col-md-1 col-md-offset-2 text-center"><i
                                                        class="fa fa-pencil-square-o bigicon"></i></span>
                                                <div class="col-md-8">
                                                    <textarea class="form-control" id="message" name="message"
                                                        placeholder="Enter your massage for us here. We will get back to you within 2 business days."
                                                        rows="7"></textarea>
                                                </div>
                                            </div>

                                            <div class="form-group">
                                                <div class="col-md-12 text-center">
                                                    <button type="submit" class="btn btn-primary btn-lg">Submit</button>
                                                </div>
                                            </div>
                                        </fieldset>
                                    </form>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>


                <div class="col col-lg-4 col-md-12 col-sm-12">

                    <h2 class="text-center text-light fs-1">Para mas información</h2>
                    <div class="col col-lg-12">
                        <i class="fas fa-phone text-light "><b> 750-341-15</b></i><br>
                        <i class="fab fa-whatsapp text-light"><b> 54-34-24-55-12</b></i><br>
                        <i class="fab fa-google text-light "><b> hollconsulting@info.com</b></i><br>
                        <i class="fas fa-search text-light"><b> Patos #456-D Las arboledas C.P. 54327 Cd. Carmen</b></i>
                    </div>
                </div>




            </div>
        </div>
    </div>


    <!-- FOOTER -->
    <footer class="text-center text-white" style="background-color:rgb(3, 140, 158);">
        <!-- Grid container -->
        <div class="container pt-4">
            <!-- Section: Social media -->
            <section class="mb-4">
                <!-- Facebook -->
                <a class="btn btn-link btn-floating btn-lg text-dark m-1" href="#!" role="button"
                    data-mdb-ripple-color="dark"><i class="fab fa-facebook-f"></i></a>

                <!-- Twitter -->
                <a class="btn btn-link btn-floating btn-lg text-dark m-1" href="#!" role="button"
                    data-mdb-ripple-color="dark"><i class="fab fa-twitter"></i></a>

                <!-- Google -->
                <a class="btn btn-link btn-floating btn-lg text-dark m-1" href="#!" role="button"
                    data-mdb-ripple-color="dark"><i class="fab fa-google"></i></a>

                <!-- Instagram -->
                <a class="btn btn-link btn-floating btn-lg text-dark m-1" href="#!" role="button"
                    data-mdb-ripple-color="dark"><i class="fab fa-instagram"></i></a>

                <!-- Linkedin -->
                <a class="btn btn-link btn-floating btn-lg text-dark m-1" href="#!" role="button"
                    data-mdb-ripple-color="dark"><i class="fab fa-linkedin"></i></a>
                <!-- Github -->
                <a class="btn btn-link btn-floating btn-lg text-dark m-1" href="#!" role="button"
                    data-mdb-ripple-color="dark"><i class="fab fa-github"></i></a>
            </section>
            <!-- Section: Social media -->
        </div>
        <!-- Grid container -->

        <!-- Copyright -->
        <div class="text-center text-dark p-3" style="background-color: rgba(0, 0, 0, 0.2);">
            © 2021 Copyright:
            <a class="text-dark" href="#">Abraham Torres</a>
        </div>
        <!-- Copyright -->
    </footer>
















</body>

<script src="./js/bootstrap.bundle.min.js"></script>
<script src="./js/custom.js"></script>

</html>


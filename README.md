# alexis
<!doctype html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title></title>
    <meta name="description" content=" ">
    <meta name="viewport" content="width=device-width, initial-scale=1 shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">


    <meta property="og:title" content="">
    <meta property="og:type" content="">
    <meta property="og:url" content="">
    <meta property="og:image" content="">

    <link rel="manifest" href="site.webmanifest">
    <link rel="icon" href="icon.png" type="image/png" />
    <link rel="shortcut icon" href="favicon.ico" />

    <link rel="stylesheet" href="css/normalize.css">
    <link rel="stylesheet" href="css/main.css">
    <!-- Custom styles for this template -->
    <link href="carousel.css" rel="stylesheet">

    <meta name="theme-color" content="#fafafa">
</head>

<body>

    <!-- Barre de Navigation -->

    <header>
        <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
            <div class="container-fluid">
                <div class="collapse navbar-collapse" id="navbarCollapse">
                    <ul class="navbar-nav me-auto mb-2 mb-md-0">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="https://www.w3schools.com/html/default.asp">HTML5</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="https://www.w3schools.com/css/default.asp ">CSS3</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="web-jobs.html"> Page Jobs</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link " href="https://www.w3schools.com/bootstrap5/index.php ">Bootstrap</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <!-- Fin Barre de Navigation -->

    <main role="main">
        <!-- Zone de défilement Textes/Images (Carousel) -->
        <div id="myCarousel" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="0" class="active"
                    aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="images/www.jpg" alt=".." />

                    <div class="container">
                        <div class="carousel-caption text-start">
                            <h1>WWW</h1>
                            <p>Le World Wide Web (WWW), littéralement la « toile (d’araignée) mondiale », communément appelé
le  Web,   et  parfois  la  Toile,  est  un  système  hypertexte  public  fonctionnant  sur  Internet.  Le  Web
permet de consulter, avec un navigateur, des pages accessibles sur des sites.</p>
                            <p><a class="btn btn-lg btn-primary" href="https://fr.wikipedia.org/wiki/World_Wide_Web ">Sign up today</a></p>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="images/www.jpg" alt=".."

                    <div class="container">
                        <div class="carousel-caption">
                            <h1>Another example headline.</h1>
                            <p>Some representative placeholder content for the second slide of the carousel.</p>
                            <p><a class="btn btn-lg btn-primary" href="#">Learn more</a></p>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <svg class="bd-placeholder-img" width="100%" height="100%" xmlns="http://www.w3.org/2000/svg"
                        aria-hidden="true" preserveAspectRatio="xMidYMid slice" focusable="false">
                        <rect width="100%" height="100%" fill="#777" />
                    </svg>

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
        </div>

        <!-- Fin Zone de défilement Textes/Images (Carousel) -->

        <!-- Trois colonnes de textes + images -->

        <div class="container marketing">

            <!-- Three columns of text below the carousel -->
            <div class="row">
                <div class="col-lg-4">
                    <img src="images/html250.png" class="img-thumbnail" alt="...">

                    <h2>Html5</h2>
                    <p>Le HTML n'est pas un langage de programmation. On parle plutôt de balisage
de  texte.  HTML  est  l'acronyme  de  Hyper  Text  Mark-up  Language.  HyperText  est  un  système  qui
contient des hyperliens ( pouvoir accéder à des documents externes via un lien externe).</p>
                    <p><a class="btn btn-secondary" href="https://www.w3schools.com/html/html_intro.asp">View details &raquo;</a></p>
                </div><!-- /.col-lg-4 -->
                <div class="col-lg-4">
                    <img src="images/css250.png" class="img-thumbnail" alt="...">

                    <h2>Heading</h2>
                    <p>Another exciting bit of representative placeholder content. This time, we've moved on to the
                        second column.</p>
                    <p><a class="btn btn-secondary" href="#">View details &raquo;</a></p>
                </div><!-- /.col-lg-4 -->
                <div class="col-lg-4">
                    <img src="images/bootstrap250.png" class="img-thumbnail" alt="...">

                    <h2>Heading</h2>
                    <p>And lastly this, the third column of representative placeholder content.</p>
                    <p><a class="btn btn-secondary" href="#">View details &raquo;</a></p>
                </div><!-- /.col-lg-4 -->
            </div><!-- /.row -->

            <!-- Fin Trois colonnes de textes + images -->


            <!-- Zone de news -->

            <hr class="featurette-divider">

            <div class="row featurette">
                <div class="col-md-7">
                    <h2 class="featurette-heading">First featurette heading. <span class="text-muted">It’ll blow your
                            mind.</span></h2>
                    <p class="lead">Some great placeholder content for the first featurette here. Imagine some exciting
                        prose here.</p>
                </div>
                <div class="col-md-5">
                    <img src="images/html500.png" class="img-thumbnail"alt="...">

                </div>
            </div>

            <hr class="featurette-divider">

            <div class="row featurette">
                <div class="col-md-7 order-md-2">
                    <h2 class="featurette-heading">Oh yeah, it’s that good. <span class="text-muted">See for
                            yourself.</span></h2>
                    <p class="lead">Another featurette? Of course. More placeholder content here to give you an idea of
                        how this layout would work with some actual real-world content in place.</p>
                </div>
                <div class="col-md-5 order-md-1">
                    <img src="images/css500.png" class="img-thumbnail"  alt="...">

                </div>
            </div>

            <hr class="featurette-divider">

            <div class="row featurette">
                <div class="col-md-7">
                    <h2 class="featurette-heading">And lastly, this one. <span class="text-muted">Checkmate.</span></h2>
                    <p class="lead">And yes, this is the last block of representative placeholder content. Again, not
                        really intended to be actually read, simply here to give you a better view of what this would
                        look like with some actual content. Your content.</p>
                </div>
                <div class="col-md-5">
                    <img src="images/bootstrap500.png" class="img-thumbnail" alt=".."

                </div>
            </div>

            <hr class="featurette-divider">

            <!-- Fin Zone de news -->

        </div><!-- /.container -->


        <!-- FOOTER -->
        <footer class="container">
            <p class="float-end"><a href="#">Back to top</a></p>
            <p>&copy; 2017–2021 Company, Inc. &middot; <a href="#">Privacy</a> &middot; <a href="#">Terms</a></p>
        </footer>
    </main>
    </main>



    <!-- Javascript. -->
    <script src="js/vendor/modernizr-3.11.2.min.js"></script>
    <script src="js/plugins.js"></script>
    <script src="js/main.js"></script>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
        integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"
        integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
        crossorigin="anonymous"></script>

    <!-- Google Analytics: change UA-XXXXX-Y to be your site's ID. -->
    <script>
        window.ga = function () {
            ga.q.push(arguments)
        };
        ga.q = [];
        ga.l = +new Date;
        ga('create', 'UA-XXXXX-Y', 'auto');
        ga('set', 'anonymizeIp', true);
        ga('set', 'transport', 'beacon');
        ga('send', 'pageview')
    </script>
    <script src="https://www.google-analytics.com/analytics.js" async></script>
</body>

</html>

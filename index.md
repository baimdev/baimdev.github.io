<!doctype html>
<html lang="id">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

    <!-- Custom CSS -->
    <!-- <link href="./dist/css/style.css" rel="stylesheet"> -->

    <!-- Font Awesome -->
    <script src="https://kit.fontawesome.com/13aac80ab3.js" crossorigin="anonymous"></script>

    <!-- Favicon -->
    <link rel="shortcut icon" href="./dist/img/favicon.ico">

    <title>Baim Development Labs</title>
</head>

<body class="d-flex flex-column h-100">
    <!-- Navbar Start -->
    <nav class="navbar navbar-expand-md navbar-light bg-light fixed-top" aria-label="Navbar">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">
                <img src="./dist/img/logo.webp" height="45px" />
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarsExample04" aria-controls="navbarsExample04" aria-expanded="false" aria-label="Toggle navigation">
                <i class="fas fa-bars fa-fw fa-lg"></i>
            </button>

            <div class="collapse navbar-collapse" id="navbarsExample04">
                <ul class="navbar-nav me-auto mb-2 mb-md-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">
                            <i class="fas fa-home fa-fw"></i> Home
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">
                            <i class="fas fa-info-circle fa-fw"></i> About
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">
                            <i class="fas fa-desktop fa-fw"></i> Showcase
                        </a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="repositories" data-bs-toggle="dropdown" aria-expanded="false"><i class="fab fa-github fa-fw"></i> Repo</a>
                        <ul class="dropdown-menu" aria-labelledby="repositories">
                            <li><a class="dropdown-item" href="#"><i class="fas fa-folder-open fa-sm fa-fw"></i> Web CMS Codeigniter</a></li>
                            <li><a class="dropdown-item" href="#"><i class="fas fa-folder-open fa-sm fa-fw"></i> Web Template Bootstrap</a></li>
                            <li><a class="dropdown-item" href="#"><i class="fas fa-folder-open fa-sm fa-fw"></i> Android</a></li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#"><i class="fas fa-at fa-fw"></i> Contact</a>
                    </li>
                </ul>
                <form>
                    <input class="form-control" type="text" placeholder="Search" aria-label="Search">
                </form>
            </div>
        </div>
    </nav>
    <!-- Navbar End -->

    <!-- Begin page content -->
    <main class="flex-shrink-0">
        <h1>Hello</h1>
    </main>
    <!-- Footer Start -->
    <footer class="footer mt-auto py-3 bg-light">
        <div class="container d-flex justify-content-center">
            <p class="text-muted text-center">
                Copyrights &copy; 2020 - <?= date('Y'); ?> - Baim Development Labs.
            </p>
        </div>
    </footer>
    <!-- Navbar End -->

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    -->
</body>

</html>

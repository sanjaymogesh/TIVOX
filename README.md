<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>TIVOX</title>
    <!-- Favicon link (Make sure the path is correct) -->
    <link rel="icon" href="Grey Professional Monogram Circular Brand Logo_20250124_121707_0000.png" type="image/png">
    <link rel="" href="" type="login.css">
     <img src="" alt="">
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        .hero {
            background: url('hero-bg.jpg') no-repeat center center/cover;
            padding: 100px 20px;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 1.5rem;
            margin-bottom: 20px;
        }

        .card {
            margin-bottom: 20px;
        }

        .card img {
            height: 500px;
            object-fit: cover;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">TIVOX</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Shop</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Cart</a></li>
                    <li class="nav-item"><a class="nav-link" href="http://127.0.0.1:5500/contact.html">Contact</a></li>
                    <li class="nav-item"><a class="nav-link" href="http://127.0.0.1:5500/login1.html">Login</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="hero text-center text-white">
        <h1>Exclusive T-Shirt Collection</h1>
        <p>Shop the latest styles now!</p>
        <a href="#" class="btn btn-primary">Shop Now</a>
    </header>

    <div class="container mt-5">
        <h2 class="text-center mb-4">Featured T-Shirts</h2>
        <div class="row">

            <!-- T-Shirt 1 -->
            <div class="col-md-4">
                <div class="card">
                    <img src="tshirt1.jpg" class="card-img-top" alt="T-Shirt 1">
                    <div class="card-body text-center">
                        <h5 class="card-title">Cool Black Tee</h5>
                        <p class="card-text">$19.99</p>
                        <a href="#" class="btn btn-success">Add to Cart</a>
                    </div>
                </div>
            </div>

            <!-- T-Shirt 2 -->
            <div class="col-md-4">
                <div class="card">
                    <img src="https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcTonqsKTqp-qU9amI9THi_aALmxnROBuGmnPerEnN5rpa7z8e3iNN-f8_G1FQTsGSMH_mZ2z-KJLBuKtjjK7EPnlztBFAJkNFPkZ2AMrPQ&usqp=CAE" class="card-img-top" alt="T-Shirt 2">
                    <div class="card-body text-center">
                        <h5 class="card-title">Minimalist White Tee</h5>
                        <p class="card-text">$24.99</p>
                        <a href="#" class="btn btn-success">Add to Cart</a>
                    </div>
                </div>
            </div>

            <!-- T-Shirt 3 -->
            <div class="col-md-4">
                <div class="card">
                    <img src="https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcTbiJ2A0qxdrWk4zIiZUWQXikExZJYy6f8BQmQrIce9EEQJr7so75arY2ECZq__WEIv5b6xbjIl7bFzkXLVRvx56O_mXizVaK_swU_GT40r5skjxKTOYqQcpQ&usqp=CAE" class="card-img-top" alt="T-Shirt 3">
                    <div class="card-body text-center">
                        <h5 class="card-title">Graphic Print Tee</h5>
                        <p class="card-text">$29.99</p>
                        <a href="#" class="btn btn-success">Add to Cart</a>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3 mt-5">
        &copy; 2025 T-Shirt Store | All rights reserved.
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>

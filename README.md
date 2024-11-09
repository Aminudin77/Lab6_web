# Lab6_web
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Layout</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* Tambahkan CSS custom di sini */
        .sidebar {
            background-color: #f8f9fa;
            padding: 20px;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#">Project Ngatur Bumi</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contact</a>
                </li>
            </ul>
            <ul class="navbar-nav">
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        Username
                    </a>
                    <div class="dropdown-menu dropdown-menu-right" aria-labelledby="navbarDropdown">
                        <a class="dropdown-item" href="#">Profile</a>
                        <a class="dropdown-item" href="#">Sign Out</a>
                    </div>
                </li>
            </ul>
        </div>
    </nav>
    <div class="container-fluid">
        <div class="row">
            <!-- Sidebar -->
            <nav class="col-md-3 col-lg-2 sidebar">
                <h5>Hewan Random</h5>
                <ul class="nav flex-column">
                    <li class="nav-item"><a class="nav-link active" href="#">Monyet</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Kucing</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Sapi</a></li>
                </ul>
            </nav>

                       <!-- Main content -->
                       <main class="col-md-9 col-lg-10 content">
                        <div class="jumbotron">
                            <h1 class="display-4">Kerandoman Hewan Bumi</h1>
                            <p>Hanya disini tempat mengocok perut anda</p>
                            <a class="btn btn-primary btn-lg" href="#" role="button">Learn more »</a>
                        </div>
                        <div class="row">
                            <div class="col-md-4">
                                <h2>Korban Kecelakaan Hewan</h2>
                                <p>Kecelakaan tunggal</p>
                                <p><a class="btn btn-secondary" href="#" role="button">View details »</a></p>
                                <img {
                                    border: 5px solid #ddd;
                                    border-radius: 5px;
                                    padding: 5px;
                                    width="250px";
                                    src="img/Picture.jpg"}/>
                            </div>
                            <div class="col-md-4">
                                <h2>Kucing Nikah</h2>
                                <p>Road to jannah</p>
                                <p><a class="btn btn-secondary" href="#" role="button">View details »</a></p>
                                <img {
                                    border: 5px solid #ddd;
                                    border-radius: 5px;
                                    padding:5px ;
                                    width="300px";
                                    src="/img/image.png"}/>
                            </div>
                            <div class="col-md-4">
                                <h2>Sapi Terbang</h2>
                                <p>Takut di sembelih sapi ini kabur karena masih ingin makan enak </p>
                                <p><a class="btn btn-secondary" href="#" role="button">View details »</a></p>
                                <img {
                                    border: 5px solid #ddd;
                                    border-radius: 5px;
                                    padding:5px ;
                                    width="250px";
                                    src="/img/sapi terbang.jpg"}/>
                            </div>
                        </div>
                    </main>
                </div>
            </div>
                <!-- Bootstrap JavaScript -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html> 

#Penjelasan 
pada tampilan ini menunjukan website yang masih kosong
![Screenshot 2024-11-09 214035](https://github.com/user-attachments/assets/3d73062c-2a78-4b84-82dc-f57345b21de8)

pada tampilan ini menunjukan sebuah wesite yang sudah ada header dan sidebar nya
![Screenshot 2024-11-09 214154](https://github.com/user-attachments/assets/e4d7e32e-d255-47c4-8a45-dcfb6348405d)

pada tampilan ini menunjukan sebuah website finishing yang sudah ada hider, sidebar, dan gambar beserta keterangan gambarnya
![Screenshot 2024-11-09 214251](https://github.com/user-attachments/assets/91871196-9ad9-43bf-9c80-136452c55b3a)

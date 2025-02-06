
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cards ao lado</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
       
        .main-container {
            background-color: #000;
            color: white;
            min-height: 100vh;
            padding: 20px;
        }

        .card-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: flex-start;
        }

        .card {
            max-width: 18rem;
            border-radius: 15px;
            overflow: hidden;
        }

        .card-img-top {
            object-fit: cover;
            height: 200px;
            width: 200px;
        }

        .card-body {
            background-color: #222; 
            color: white; 
        }

        .card:hover {
            box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.3);
        }
    </style>

    <div class="main-container">
        <div class="card-container">
            <!-- Card 1 -->
            <div class="card">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRSyV2hELYCFuRVh2iZoEEb4OKWEpOBeeezhg&s" class="card-img-top" alt="Imagem do card">
                <div class="card-body">
                    <p class="card-text">O Diabo</p>
                </div>
            </div>

            <!-- Card 2 -->
            <div class="card">
                <img src="https://i1.sndcdn.com/artworks-6cYUaUXwyUyZ7DTl-QAGXEA-t500x500.jpg" class="card-img-top" alt="Imagem do card">
                <div class="card-body">
                    <p class="card-text">Arthur</p>
                </div>
            </div>

            <!-- Card 3 -->
            <div class="card">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSXgIMVWSrGaDTu9A7KKGeOzI8kU5rp0fbOrA&s" class="card-img-top" alt="Imagem do card">
                <div class="card-body">
                    <p class="card-text">Agatha</p>
                </div>
            </div>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>


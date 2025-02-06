
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
            <img src="https://steamuserimages-a.akamaihd.net/ugc/1852665111686684791/BA24B1425962A575189981B02A9A9F5AD2D29F19/?imw=512&&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false" class="card-img-top" alt="Imagem do card">
            <div class="card-body">
                <p class="card-text">Anfitrião</p>
            </div>
        </div>

        <!-- Card 2 -->
        <div class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRczthbZHdcJAoBQMCS6Tv7mSqOpvBMXM6LWQ&s" class="card-img-top" alt="Imagem do card">
            <div class="card-body">
                <p class="card-text">Kaiser</p>
            </div>
        </div>

    <!-- Card 3 -->
    <div class="card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTupPGG3OOe5_OMihg3eWX89dabgk-F2BxCPw&s" class="card-img-top" alt="Imagem do card">
        <div class="card-body">
            <p class="card-text">Erin</p>
        </div>
    </div>
    
    <!-- Card 4 -->
    <div class="card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRvdkFgLMybKBZdZ31ud46RXgLolEonQUchfw&s" class="card-img-top" alt="Imagem do card">
        <div class="card-body">
            <p class="card-text">Rubens</p>
        </div>
    </div>

      <!-- Card 5 -->
      <div class="card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRaNgcO1llN9KLDTu1PwcmMNIU9yEL84zBIJw&s" class="card-img-top" alt="Imagem do card">
        <div class="card-body">
            <p class="card-text">Amelie</p>
        </div>
    </div>
    </div>
</div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>


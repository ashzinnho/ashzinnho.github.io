
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
            background-color: #222; /* Fundo escuro nas áreas do card */
            color: white; /* Texto branco dentro do card */
        }

        .card:hover {
            box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.3);
        }
    </style>
<div class="main-container">
<div class="card-container">
    <!-- Card 1 -->
    <div class="card">
        <img src="https://static.wikia.nocookie.net/3adf0d0b-9875-4c58-80b3-75ebd94356f3/scale-to-width/755" class="card-img-top" alt="Imagem do card">
        <div class="card-body">
            <p class="card-text">Deus da morte</p>
        </div>
    </div>

    <!-- Card 2 -->
    <div class="card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTdvQLEqyYfa4DUqbRtiorSQTh2aFTXVv2vbQ&s" class="card-img-top" alt="Imagem do card">
        <div class="card-body">
            <p class="card-text">Dante</p>
        </div>
    </div>

<!-- Card 3 -->
<div class="card">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSGiH6t0J-jgd1J3gp3WJ5M-4FM5HiiEAEZg&s" class="card-img-top" alt="Imagem do card">
    <div class="card-body">
        <p class="card-text">Gal</p>
    </div>
</div>

<!-- Card 4 -->
<div class="card">
    <img src="https://steamuserimages-a.akamaihd.net/ugc/1612841999145546430/6E9D35F8A14F2DC686FBB2CE14194DABAAEC040C/?imw=512&&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false" class="card-img-top" alt="Imagem do card">
    <div class="card-body">
        <p class="card-text">Joui</p>
    </div>
</div>
</div>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>


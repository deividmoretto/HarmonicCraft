<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 20px;
            cursor: pointer; /* Adiciona o estilo do cursor de mão (pointer) */
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
        }
        h1 {
            margin: 0;
        }
        main img {
            display: block;
            margin: 0 auto;
            width: 100%;
            height: 60%;
        }
        .catalogo {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            text-align: center;
        }
        .item {
            border: 1px solid #ccc;
            padding: 10px;
            transition: transform 0.2s ease-in-out;
        }
        .item:hover {
            transform: scale(1.05);
        }
        .item img {
            max-width: 100%;
        }
    </style>
    <title>Meu Site</title>
</head>
<body>
    <header>
        <h1>HARMONIC CRAFT</h1>
    </header>

    <main>
        <img src="https://i.ibb.co/3h4mbCQ/logo.png" alt="logo" border="0" />
    </main>

    <h1>NEWS</h1>

    <div class="catalogo">
        <div class="item">
            <img src="https://i.ibb.co/KzPgqGn/Design-sem-nome-1.jpg" alt="Design-sem-nome-1" border="0">
            <p>Low Frequencies (Now Relised)</p>
        </div>
        <div class="item">
            <img src="https://i.ibb.co/z591qPf/Ilustrac-a-o-Floral-Capa-de-CD.jpg" alt="Ilustrac-a-o-Floral-Capa-de-CD" border="0">
            <p>You are lived (29/09/2023)</p>
        </div>
        <div class="item">
            <img src="https://i.ibb.co/58QsQZ0/Disappear.jpg" alt="Disappear" border="0">
            <p>Disappear (06/10/2023)</p>
        </div>
        <!-- Adicione mais itens conforme necessário -->
    </div>

    <footer>
        <p>&copy; 2023 HARMONIC CRAFT</p>
    </footer>
</body>
</html>

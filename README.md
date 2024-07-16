# woodheadS3github.io
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Helpful site</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Helpful site</h1>
    </header>
    <main>
        <section class="item">
            <h2>Nom de l'objet</h2>
            <img src="image.jpg" alt="Description de l'image">
            <p class="legend">Légende de l'image</p>
            <p class="review">Avis sur l'objet</p>
            <div class="rating">
                <span>★</span><span>★</span><span>★</span><span>★</span><span>☆</span>
            </div>
        </section>
        <!-- Ajoutez d'autres sections pour chaque objet -->
    </main>
    <footer>
        <p>© 2024 Helpful site</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

h1 {
    margin: 0;
    font-size: 2.5rem;
}

main {
    padding: 2rem;
}

.item {
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    margin-bottom: 2rem;
    padding: 1rem;
    transition: transform 0.3s;
}

.item:hover {
    transform: scale(1.05);
}

h2 {
    font-size: 1.5rem;
    color: #333;
}

img {
    max-width: 100%;
    border-radius: 8px;
}

.legend {
    font-style: italic;
    color: #666;
}

.review {
    margin-top: 1rem;
    font-size: 1rem;
    color: #333;
}

.rating {
    margin-top: 1rem;
    font-size: 1.5rem;
    color: #ffcc00;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
    position: fixed;
    width: 100%;
    bottom: 0;
}

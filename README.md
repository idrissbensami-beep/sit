<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Kick-Boxing Masterclass</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Kick-Boxing Pro</h1>
        <p>Apprenez l'art du combat à la maison.</p>
    </header>

    <section id="cours">
        <h2>Nos Modules</h2>
        <div class="card">
            <h3>Niveau Débutant</h3>
            <p>Apprenez la garde et les coups de poing de base.</p>
            <button onclick="afficherMessage()">S'inscrire</button>
        </div>
    </section>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    background-color: #1a1a1a; /* Noir sportif */
    color: white;
    text-align: center;
}

header {
    background-color: #d32f2f; /* Rouge combat */
    padding: 2rem;
}

.card {
    background: #333;
    border-radius: 10px;
    padding: 20px;
    margin: 20px auto;
    width: 300px;
    border-bottom: 5px solid #d32f2f;
}

button {
    background: #d32f2f;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    font-weight: bold;
}function afficherMessage() {
    alert("Bravo ! Préparez vos gants, le cours va commencer.");
}

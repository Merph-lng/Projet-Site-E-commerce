# Projet-Site-E-commerce
 This is a famous project to create an online e-commerce site, dedicated to ArtéNova Shop. It's one of my projects as a beginner in full stack web development. Thank you for your contributions and improvements to this project.

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma Boutique E-commerce</title>

    <style>
        /* Style général pour le corps de la page */
        body {
            font-family: sans-serif; /* Une police simple et lisible */
            margin: 0; /* Enlève la marge par défaut du navigateur */
        }

        /* --- On dessine nos boîtes avec des bordures --- */

        /* On met une bordure à nos 3 blocs principaux pour bien les voir */
        header, main, footer {
            border: 2px solid blue;
            margin: 8px;
            padding: 8px;
        }

        /* On met une bordure à nos sections dans le main */
        section {
            border: 1px dashed green;
            margin: 8px;
            padding: 8px;
        }

        /* Et une bordure pour chaque produit */
        article {
            border: 1px dotted red;
            margin: 4px;
            padding: 4px;
            text-align: center; /* On centre le texte à l'intérieur */
        }

        /* --- Un peu de mise en page pour que ça ressemble à notre dessin --- */
        
        /* On aligne le logo et le menu sur la même ligne */
        header {
            display: flex;
            justify-content: space-between; /* Pousse les éléments aux extrémités */
            align-items: center; /* Centre verticalement */
        }

        /* On met nos produits côte à côte */
        .product-list {
            display: flex;
            justify-content: space-around; /* Espace équitablement les produits */
        }
    </style>
</head>
<body>

    <header>
        <h1>ArtéNova Shop</h1>
        <nav>
            <a href="/">Accueil</a> |
            <a href="/produits">Produits</a> |
            <a href="/panier">Panier</a>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h2>Produit du mois !</h2>
            <p>Découvrez notre offre exceptionnelle.</p>
        </section>
        <section class="product-list">
            <article>
                <p>Adidas Camps</p>
            </article>
            <article>
                <p>Air Force One</p>
            </article>
            <article>
                <p>Complet Chemise Plissée</p>
            </article>
        </section>
    </main>
    <footer>
     <div class="newsletter">
        <h4>Restez informé !</h4>
        <p>Recevez nos offres spéciales et nouveautés directement dans votre boîte mail.</p>
        <form>
            <input type="email" placeholder="Votre adresse e-mail">
            <button type="submit">S'inscrire</button>
        </form>
    </div>

    <div class="footer-links">
        <div class="column">
            <h4>À propos</h4>
            <ul>
                <li><a href="/a-propos">Notre histoire</a></li>
                <li><a href="/contact">Nous contacter</a></li>
                <li><a href="/faq">FAQ</a></li>
            </ul>
        </div>
        <div class="column">
            <h4>Service Client</h4>
            <ul>
                <li><a href="/livraison">Livraison et Commande</a></li>
                <li><a href="/retours">Politique de retour</a></li>
                <li><a href="/confidentialite">Politique de confidentialité</a></li>
            </ul>
        </div>
    </div>

    <div class="copyright">
        <p>&copy; 2025 ArtéNova Shop - Tous droits réservés.</p>
    </div>
    </footer>
</body>
</html>

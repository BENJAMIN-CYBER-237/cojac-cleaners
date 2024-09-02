<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COJAC CLEANERS</title>
    <style>
        body {
            background-color: #87CEEB; /* Jaune citron */
            font-family: Tahoma, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #007BFF; /* Rose clair */
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        header .slogan {
            font-style: italic;
            margin: 0.5em 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 10px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }

        section {
            padding: 2em 0;
            background-color: #fff;
        }

        section h2 {
            color: #007BFF; /* Rose clair */
        }

        .service, .testimonial, .comment, .login-form, .order-form {
            margin-bottom: 1.5em;
        }

        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 10px;
        }

        .gallery-grid img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }

        form {
            display: flex;
            flex-direction: column;
        }

        form label {
            margin-top: 10px;
        }

        form input, form textarea {
            padding: 10px;
            margin-top: 5px;
        }

        form button {
            margin-top: 10px;
            padding: 10px;
            background-color: #007BFF; /* Rose clair */
            color: #fff;
            border: none;
            cursor: pointer;
        }

        footer {
            background-color: #007BFF; /* Rose clair */
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }

        footer a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
    </style>
</head>
<body>
    <!-- En-tête -->
    <header>
        <div class="container">
            <h1>COJAC CLEANERS</h1>
            <p class="slogan">VOTRE ÉLÉGANCE, NOTRE PRIORITÉ</p>
            <nav>
                <ul>
                    <li><a href="#accueil">Accueil</a></li>
                    <li><a href="#about">À propos</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#gallery">Galerie</a></li>
                    <li><a href="#training">Formation</a></li>
                    <li><a href="#testimonials">Témoignages</a></li>
                    <li><a href="#comments">Commentaires</a></li>
                    <li><a href="#order">Commander</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Accueil -->
    <section id="accueil">
        <div class="container">
            <h2>Bienvenue chez COJAC CLEANERS</h2>
            <p>Qui sommes nous ? 
                COJAC: de l'acronyme "Commission jeunesse et animation culturelle", nous sommes un groupe de jeune chretiens de societe ST ALPHONSE MARIE DE LIGUORIE, qui est une eglise catholique qui est resté attaché à la forme extraordinaire de la sainte eucharistie (messe traditionnelle), cette société contient plusieurs église à travers le monde des USA au BRESIL; du CAMEROUN au CONGO, en passant par le GABON, jusqu'à en ASIE ou nous sommes représenté au PHILIPINES.
               Nous sommes donc un ensemble de jeune dynamique qui avons décidé de faire vivre nos paroisses grace à des chants des prière et bien d'autre. A cet effet nous avons eu l'occasion de ménés plusieurs activité à savoir : des concers réligieux, des kermesses culturelle, des veillées de prière et bien d'autres 
                Le supérieur du discrit d'Afrique son excellence Mgr Hypolite Emile PAGLAN
            <p>Nous offrons des services de blanchisserie modernes, la fabrication et la vente de savons liquides et d'eau de javel, ainsi que des formations sur la fabrication de ces produits.</p>
        </div>
    </section>

    <!-- À propos -->
    <section id="about">
        <div class="container">
            <h2>À propos de nous</h2>
            <p>COJAC CLEANERS est dédié à offrir des services de blanchisserie de haute qualité et des produits de nettoyage innovants. Notre mission est de garantir votre élégance avec une attention méticuleuse.</p>
        </div>
    </section>

    <!-- Services -->
    <section id="services">
        <div class="container">
            <h2>Nos Services</h2>
            <div class="service">
                <h3>Blanchisserie</h3>
                <p>Nous nettoyons vos vêtements avec soin. Nos tarifs sont :</p>
                <ul>
                    <li>Chemise : 500 FCFA</li>
                    <li>Ensemble veste : 1500 FCFA</li>
                    <li>Ensemble pagne : 1000 FCFA</li>
                    <li>Robe classique : 1000 FCFA</li>
                    <li>Robe moderne : 1500 FCFA</li>
                </ul>
                <p>Nous proposons également la collecte et la livraison à domicile.</p>
            </div>
            <div class="service">
                <h3>Produits</h3>
                <p>Nous fabriquons et vendons des savons liquides et de l'eau de javel. Contactez-nous pour plus d'informations.</p>
            </div>
            <div class="service">
                <h3>Formation</h3>
                <p>Nous offrons des formations sur la fabrication de savons et d'eau de javel :</p>
                <ul>
                    <li>Formation accélérée : 15 000 FCFA</li>
                    <li>Formation classique : 10 000 FCFA</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Galerie -->
    <section id="gallery">
        <div class="container">
            <h2>Galerie</h2>
            <div class="gallery-grid">
                <!-- Ajoute ici des images de tes produits, services, etc. -->
                <img src="image1.jpg" alt="Image 1">
                <img src="image2.jpg" alt="Image 2">
                <img src="image3.jpg" alt="Image 3">
                <img src="image4.jpg" alt="Image 4">
            </div>
        </div>
    </section>

    <!-- Témoignages -->
    <section id="testimonials">
        <div class="container">
            <h2>Témoignages</h2>
            <div class="testimonial">
                <p>"Excellent service ! Mes vêtements sont toujours impeccables. Je recommande vivement COJAC CLEANERS." - <strong>Marie Dupont</strong></p>
            </div>
            <div class="testimonial">
                <p>"Les produits de nettoyage sont de très bonne qualité. La formation est aussi très instructive." - <strong>Jean Martin</strong></p>
            </div>
        </div>
    </section>

    <!-- Commentaires -->
    <section id="comments">
        <div class="container">
            <h2>Commentaires</h2>
            <form>
                <label for="comment-name">Nom :</label>
                <input type="text" id="comment-name" name="comment-name" required>
                <label for="comment-message">Commentaire :</label>
                <textarea id="comment-message" name="comment-message" required></textarea>
                <button type="submit">Envoyer</button>
            </form>
        </div>
    </section>

    <!-- Commande -->
    <section id="order">
        <div class="container">
            <h2>Passer une commande</h2>
            <form action="mailto:ton-email@example.com" method="post" enctype="text/plain">
                <label for="order-name">Nom :</label>
                <input type="text" id="order-name" name="order-name" required>
                <label for="order-email">E-mail :</label>
                <input type="email" id="order-email" name="order-email" required>
                <label for="order-item">Article :</label>
                <select id="order-item" name="order-item" required>
                    <option value="chemise">Chemise - 500 FCFA</option>
                    <option value="ensemble-veste">Ensemble veste - 1500 FCFA</option>
                    <option value="ensemble-pagne">Ensemble pagne - 1000 FCFA</option>
                    <option value="robe-classique">Robe classique - 1000 FCFA</option>
                    <option value="robe-moderne">Robe moderne - 1500 FCFA</option>
                </select>
                <label for="order-message">Message :</label>
                <textarea id="order-message" name="order-message"></textarea>
                <button type="submit">Envoyer la commande</button>
            </form>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact">
        <div class="container">
            <h2>Contactez-nous</h2>
            <p>Adresse : EKIE, YAOUNDE CAMEROUN</p>
            <p>Téléphone : +237659903573</p>
            <p>E-mail : benjamindoriaebede10@gmail.com</p>
        </div>
    </section>

    <!-- Pied de page -->
    <footer>
        <div class="container">
            <p>&copy; 2024 COJAC CLEANERS. Tous droits réservés.</p>
            <p><a href="#contact">Contact</a> | <a href="#services">Services</a></p>
        </div>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>La Pomme Bleue d'Ezra - Naturopathie & Aromathérapie</title>
  <meta name="description" content="Produits d'aromathérapie et soins naturopathiques pour votre bien-être naturel. Huiles essentielles bio, consultations personnalisées."/>
  <style>
    :root {
      --bleu: #4a6fa5;
      --vert: #5a8c4a;
      --blanc: #fff;
      --gris: #f8f9fa;
      --texte: #333;
    }
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: var(--texte);
      background: var(--gris);
      line-height: 1.6;
    }
    header {
      background: var(--bleu);
      color: white;
      padding: 1rem 2rem;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 2px 10px rgba(0,0,0,0.15);
    }
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }
    .logo {
      font-size: 1.8rem;
      font-weight: bold;
    }
    .logo span { color: #ffd700; } /* pomme jaune/or pour contraste */
    .menu {
      display: flex;
      gap: 2rem;
    }
    .menu a {
      color: white;
      text-decoration: none;
      font-weight: 500;
    }
    .menu a:hover { text-decoration: underline; }

    .hero {
      background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://images.unsplash.com/photo-1608571423902-eed4a5ad8108?ixlib=rb-4.0.3&auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 12rem 2rem 8rem;
    }
    .hero h1 {
      font-size: 3.5rem;
      margin: 0 0 1rem;
    }
    .hero p {
      font-size: 1.4rem;
      max-width: 800px;
      margin: 0 auto 2rem;
    }
    .btn {
      display: inline-block;
      background: var(--vert);
      color: white;
      padding: 1rem 2rem;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    .btn:hover { background: #4a703c; transform: translateY(-3px); }

    section {
      padding: 5rem 2rem;
      max-width: 1200px;
      margin: 0 auto;
    }
    h2 {
      text-align: center;
      color: var(--bleu);
      margin-bottom: 3rem;
      font-size: 2.8rem;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
    }
    .card {
      background: white;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      transition: 0.3s;
    }
    .card:hover { transform: translateY(-10px); }
    .card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }
    .card-content {
      padding: 1.5rem;
      text-align: center;
    }
    footer {
      background: var(--bleu);
      color: white;
      text-align: center;
      padding: 3rem 1rem;
    }
    footer a { color: #c0d4ff; text-decoration: none; }
    @media (max-width: 768px) {
      .menu { flex-direction: column; gap: 1rem; }
      .hero { padding: 8rem 1rem 6rem; }
      .hero h1 { font-size: 2.5rem; }
    }
  </style>
</head>
<body>

  <header>
    <nav>
      <div class="logo">La Pomme Bleue <span>d'Ezra</span></div>
      <div class="menu">
        <a href="#accueil">Accueil</a>
        <a href="#produits">Boutique</a>
        <a href="#consultations">Consultations</a>
        <a href="#apropos">À propos</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>
  </header>

  <section class="hero" id="accueil">
    <h1>La Pomme Bleue d'Ezra</h1>
    <p>Nous croyons en la puissance des médecines naturelles pour favoriser la santé et le bien-être.<br>
    Une gamme complète de produits d’aromathérapie et de soins naturopathiques pour améliorer votre qualité de vie.</p>
    <a href="#produits" class="btn">Découvrir nos produits</a>
    <a href="#consultations" class="btn" style="margin-left:1rem; background:var(--bleu);">Prendre RDV</a>
  </section>

  <section id="produits">
    <h2>Nos Produits Naturels</h2>
    <div class="grid">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1608571423902-eed4a5ad8108?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Huiles essentielles">
        <div class="card-content">
          <h3>Huiles Essentielles Bio</h3>
          <p>Sélection pure et biologique pour le bien-être physique et émotionnel.</p>
          <a href="#" class="btn">Voir la gamme</a>
        </div>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1617890686219-509e671a0d4e?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Mélanges aromatiques">
        <div class="card-content">
          <h3>Mélanges Aromatiques</h3>
          <p>Synergies sur-mesure pour relaxation, sommeil, énergie, etc.</p>
          <a href="#" class="btn">Voir la gamme</a>
        </div>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1629909613654-28e377c37b09?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Soins naturopathiques">
        <div class="card-content">
          <h3>Soins Naturopathiques</h3>
          <p>Produits complémentaires pour une approche holistique de la santé.</p>
          <a href="#" class="btn">Voir la gamme</a>
        </div>
      </div>
    </div>
  </section>

  <section id="consultations" style="background:#e8f5e9;">
    <h2>Consultations de Naturopathie</h2>
    <p style="text-align:center; max-width:800px; margin:0 auto 3rem;">
      Bilan personnalisé + recommandations adaptées à vos besoins et votre état de santé.<br>
      Disponible en présentiel ou en téléconsultation (visioconférence).<br><br>
      <strong>Durée :</strong> 60 à 90 min | <strong>Tarif :</strong> 60 € – 140 €
    </p>
    <div style="text-align:center;">
      <a href="#contact" class="btn">Réserver une consultation</a>
    </div>
  </section>

  <section id="apropos">
    <h2>À propos</h2>
    <p style="max-width:900px; margin:0 auto; text-align:center;">
      Notre équipe est dédiée à vous accompagner dans votre parcours de santé avec des produits et conseils naturels.<br>
      Nous privilégions le bio, le respect de l’environnement et une approche globale (corps-esprit).<br><br>
      La Pomme Bleue d'Ezra, c’est l’alliance de la sagesse naturelle et du bien-être moderne.
    </p>
  </section>

  <section id="contact" style="background:var(--bleu); color:white;">
    <h2>Contactez-nous</h2>
    <form style="max-width:600px; margin:0 auto;">
      <input type="text" placeholder="Votre nom" required style="width:100%; padding:1rem; margin:0.5rem 0; border-radius:8px; border:none;"/>
      <input type="email" placeholder="Votre email" required style="width:100%; padding:1rem; margin:0.5rem 0; border-radius:8px; border:none;"/>
      <textarea placeholder="Votre message" rows="6" required style="width:100%; padding:1rem; margin:0.5rem 0; border-radius:8px; border:none;"></textarea>
      <button type="submit" class="btn" style="background:white; color:var(--bleu); width:100%;">Envoyer</button>
    </form>
  </section>

  <footer>
    <p>© 2026 La Pomme Bleue d'Ezra – Tous droits réservés</p>
    <p>
      <a href="#">Mentions légales</a> • 
      <a href="#">Politique de confidentialité</a> • 
      <a href="#">CGV</a>
    </p>
    <p>Produits naturels – Naturopathie – Aromathérapie – Bien-être holistique</p>
  </footer>

</body>
</html>

---
hide:
  - navigation
  - toc
---

<style>
  /* Image de fond en plein écran */
  .md-main {
    background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.6)), 
                url('https://images.unsplash.com/photo-1451187580459-43490279c0fa?q=80&w=2000');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    min-height: 100vh;
  }

  /* Style du texte d'accueil */
  .hero-text {
    text-align: center;
    padding: 100px 20px 50px;
    color: white;
  }

  .hero-text h1 { color: white !important; font-size: 3rem !important; text-shadow: 2px 2px 10px rgba(0,0,0,0.5); }
  .hero-text p { color: white !important; font-size: 1.2rem; }

  /* Style des Cartes "Catalogue" (Effet Verre) */
  .grid.cards > ul > li {
    background: rgba(255, 255, 255, 0.1) !important;
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.2) !important;
    border-radius: 15px !important;
    padding: 20px !important;
    transition: transform 0.3s ease;
    list-style: none !important;
  }

  .grid.cards > ul > li:hover {
    transform: translateY(-10px);
    background: rgba(255, 255, 255, 0.2) !important;
  }

  /* Correction des textes et icônes dans les cartes */
  .grid.cards li strong { color: white !important; display: inline-block; margin-bottom: 10px; }
  .grid.cards li p { color: white !important; opacity: 0.9; }
  
  /* Style des boutons */
  .grid.cards li a { 
    display: inline-block;
    margin-top: 15px;
    background: white !important; 
    color: black !important; 
    padding: 10px 20px !important; 
    border-radius: 8px !important; 
    text-decoration: none !important;
    font-weight: bold;
  }
  
  .grid.cards li a:hover {
    background: #e0e0e0 !important;
  }

  /* Taille des icônes */
  .grid.cards .lg { font-size: 2.5rem; display: block; margin-bottom: 10px; color: white; }
</style>

<div class="hero-text">
  <h1>Bienvenue sur mon Portail de Données Géographiques</h1>
  <p>Explorez mes guides, projets GDAL et ressources cartographiques.</p>
</div>

<div class="grid cards" markdown>

- :material-terminal:{ .lg } **Guide d'Installation Bash**
    ---
    Toutes les commandes pour configurer votre Mac 2013 de A à Z.
    [:octicons-arrow-right-24: Voir le guide](installation.md)

- :material-map-legend:{ .lg } **Projets Cartographiques**
    ---
    Visualisation de données VRT et analyses spatiales avancées.
    [:octicons-arrow-right-24: Explorer](projets.md)

- :material-github:{ .lg } **Dépôts GitHub**
    ---
    Accès direct au code source, scripts et historiques de requêtes.
    [:octicons-external-link-16: Ouvrir GitHub](https://github.com/Mirjanaed)

</div>
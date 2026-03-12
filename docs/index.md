---
hide:
  - navigation
  - toc
---

<style>
  .md-main {
    background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.7)), 
                url('https://images.unsplash.com/photo-1451187580459-43490279c0fa?q=80&w=2000');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    min-height: 100vh;
  }

  .hero-text {
    text-align: center;
    padding: 80px 20px 40px;
    color: white;
  }

  .hero-text h1 { color: white !important; font-size: 3rem !important; text-shadow: 2px 2px 10px rgba(0,0,0,0.5); }
  .hero-text p { color: white !important; font-size: 1.2rem; opacity: 0.9; }

  .grid.cards > ul {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1rem;
    list-style: none !important;
    padding: 0;
  }

  .grid.cards > ul > li {
    background: rgba(255, 255, 255, 0.1) !important;
    backdrop-filter: blur(12px);
    -webkit-backdrop-filter: blur(12px);
    border: 1px solid rgba(255, 255, 255, 0.2) !important;
    border-radius: 12px !important;
    padding: 24px !important;
    width: 300px;
    flex-grow: 1;
  }

  .grid.cards li strong { color: white !important; font-size: 1.2rem; display: block; margin-bottom: 8px; }
  .grid.cards li p { color: white !important; margin-bottom: 16px; font-size: 0.95rem; line-height: 1.5; }
  .grid.cards hr { border: 0; border-top: 1px solid rgba(255,255,255,0.2); margin: 10px 0; }

  /* Style du bouton forcé en blanc */
  .custom-btn {
    display: inline-block;
    background-color: white !important;
    color: black !important;
    padding: 10px 20px;
    border-radius: 6px;
    text-decoration: none !important;
    font-weight: bold;
    transition: 0.3s;
  }

  .custom-btn:hover {
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
  }
</style>

<div class="hero-text">
  <h1>Bienvenue sur mon Portail de Données Géographiques</h1>
  <p>Explorez mes guides, projets GDAL et ressources cartographiques.</p>
</div>

<div class="grid cards">
  <ul>
    <li>
      <strong>Guide d'Installation Bash</strong>
      <hr>
      <p>Toutes les commandes pour configurer votre Mac 2013 de A à Z.</p>
      <a href="installation.md" class="custom-btn">Voir le guide →</a>
    </li>
    <li>
      <strong>Projets Cartographiques</strong>
      <hr>
      <p>Visualisation de données VRT et analyses spatiales avancées.</p>
      <a href="projets.md" class="custom-btn">Explorer →</a>
    </li>
    <li>
      <strong>Dépôts GitHub</strong>
      <hr>
      <p>Accès direct au code source, scripts et historiques de requêtes.</p>
      <a href="https://github.com/Mirjanaed" class="custom-btn" target="_blank">Ouvrir GitHub ↗</a>
    </li>
  </ul>
</div>
---
layout: default
title: "Acceuil "
nav_exclude: true
---

<style>
  /* Masquer le titre et le fil d'ariane */
  .breadcrumb-nav { display: none !important; }
  
  /* Masquer la barre latérale sur cette page */
  .side-bar { display: none !important; }
  
  /* Ajuster le contenu pour qu'il prenne toute la largeur sans la barre latérale */
  .main { margin-left: 0 !important; }

  /* Appliquer le fond vert clair à toute la page */
  body, .main-content-wrap, .main-content {
    background-color: #e8f5e9 !important; /* Un vert très doux */
  }
  .search, .search-placeholder { display: none !important; }

  .main-content { text-align: center; }
</style>

# 🎓 Mes Outils Mathématiques

Bienvenue sur le site de Mr Antoine, Choisissez votre module :

<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: nowrap; margin: 30px auto; max-width: 100%;">

  <a href="./exercices" style="text-decoration: none; color: inherit; width: 200px;">
    <div style="border: 2px solid #007bff; border-radius: 12px; padding: 20px; background-color: white; transition: transform 0.2s;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
      <span style="font-size: 40px;">📝</span>
      <h2 style="margin: 10px 0; color: #007bff; font-size: 1.1em;">Exercices</h2>
      <p style="font-size: 0.8em; color: #555;">Par chapitre</p>
    </div>
  </a>

  <a href="./devoirs" style="text-decoration: none; color: inherit; width: 200px;">
    <div style="border: 2px solid #28a745; border-radius: 12px; padding: 20px; background-color: white; transition: transform 0.2s;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
      <span style="font-size: 40px;">📚</span>
      <h2 style="margin: 10px 0; color: #28a745; font-size: 1.1em;">Devoirs</h2>
      <p style="font-size: 0.8em; color: #555;">Sujets complets</p>
    </div>
  </a>

</div>

# sano-logistic


.carousel-item {
  height: 100vh;
  /* La hauteur de chaque item du carousel est 100% de la fenêtre */
}

.carousel-item1 {
  height: 100vh;
  /* La hauteur de chaque item du carousel est 100% de la fenêtre */
}


/* Pour les écrans de petite taille (smartphones) */
@media (max-width: 576px) {
  .carousel-item {
    height: 80vh; /* Réduit la hauteur pour les petits écrans */
  }

  .hero {
    flex-direction: column; /* Aligne le contenu verticalement */
    text-align: center; /* Assure un alignement central */
  }
}

/* Pour les écrans moyens (tablettes) */
@media (min-width: 577px) and (max-width: 768px) {
  .carousel-item {
    height: 70vh; /* Ajuste la hauteur pour les tablettes */
  }

  .hero {
    padding: 15px; /* Ajuste les marges pour un écran moyen */
  }
}

/* Pour les écrans larges (ordinateurs) */
@media (min-width: 769px) and (max-width: 1200px) {
  .carousel-item {
    height: 90vh; /* Ajuste légèrement la hauteur pour les écrans larges */
  }

  .hero {
    padding: 30px; /* Ajoute un peu plus d'espace */
  }
}

/* Pour les écrans très larges */
@media (min-width: 1201px) {
  .carousel-item {
    height: 100vh; /* Conserve la pleine hauteur */
  }

  .hero {
    padding: 40px; /* Plus d'espace pour un rendu esthétique */
  }
}
  🛒 ALDI Mobile Inventaire Picking 📦

  > "Parce que compter des cartons ne devrait pas être une punition, mais une expérience Turbo-chargée !"

  Bienvenue dans l'outil ultime de picking pour les super-héros du quotidien chez ALDI. Fini le papier, le crayon qui casse et la connexion Wi-Fi qui vous lâche au
  milieu de l'allée 4. Cette application transforme votre smartphone en un scanner de compétition, même si vous êtes enterré au fond de la réserve !

  <a href="https://github.com/Lud972vic/Mobile-Inventaire-Picking/blob/main/Demo.mp4" target="_blank">Regarder la vidéo</a>

  <a href="https://github.com/Lud972vic/Mobile-Inventaire-Picking/blob/main/Demo.mp4" target="_blank">Regarder la vidéo</a>
  
  ---

  🤔 Pourquoi ce projet ?

  Imaginez : vous êtes devant une pile de 40 palettes de chocolat. Votre mission ? Compter. Le problème ? Le Wi-Fi du magasin est aussi stable qu'une tour de yaourts
  en promotion. 
  ALDI Picking est né pour résoudre ce drame mondial. 

  🚀 Les super-pouvoirs de l'app :

   * Mode "Écureuil" (Offline First) : Pas de réseau ? Pas de stress. L'app stocke vos scans localement. Dès que le signal revient, hop ! Ça synchronise tout seul vers
     le serveur.
   * Navigation Turbo : Grâce à Hotwired Turbo (https://turbo.hotwired.dev/), passer du scanner à l'historique est plus rapide que de scanner un article à la caisse 1.
     C'est du "Single Page Application" sans la complexité.
   * Scanner Laser (virtuel) : Utilisez la caméra de votre téléphone pour lire les EAN. Trop sombre ? Le bouton "Saisie Manuelle" est là pour vous sauver.
   * Calculatrice Intégrée : "3 couches de 12 colis de 6 boîtes... ça fait combien ?" L'app le calcule pour vous. Reposez votre cerveau, gardez vos forces pour
     soulever les cartons.
   * Export Excel : Un clic et paf ! Tout l'historique est prêt pour le comptable (ou pour faire de jolis graphiques).

  ---

  🛠️ Le Cerveau de l'opération (Stack Tech)

  On n'est pas là pour trier des lentilles, on a utilisé du lourd :

   * Backend : Symfony 7+ (Le moteur de camion robuste).
   * Frontend : HTML5 / JavaScript pur (Pas de framework lourd, juste de la vitesse).
   * Design : CSS3 Custom "Special ALDI Edition" (Bleu nuit, Rouge passion, Bleu ciel).
   * Magie : 
       * Turbo Drive : Pour une navigation fluide sans rechargement.
       * SweetAlert2 : Pour des alertes plus jolies que les vieux messages gris du navigateur.
       * Intro.js : Des guides interactifs sur chaque page (parce qu'on oublie tous comment ça marche après les vacances).
       * Html5-Qrcode : Pour transformer la caméra en œil de lynx.

  ---

  ⚙️ Installation (Pour les courageux)

   1. Cloner le dépôt :

   1     git clone : bientôt
   2. Installer les dépendances PHP :
   1     composer install
   3. Préparer la base de données :

   1     php bin/console doctrine:database:create
   2     php bin/console doctrine:schema:update --force
   4. Lancer le serveur :

   1     symfony serve
   5. C'est prêt ! Rendez-vous sur localhost:8000 et commencez à scanner tout ce qui bouge (ou pas).

  ---

  🛡️ Administration

  L'espace Admin est réservé aux chefs. Vous pouvez :
   * Gérer l'équipe : Créer des accès, révoquer les traîtres (ou juste ceux qui partent).
   * Gérer le catalogue : Ajouter les nouveaux produits, modifier les caractéristiques techniques. 
   * Synchroniser le cache : Un clic sur le badge bleu et tous les mobiles reçoivent la mise à jour du catalogue.

  ---

  👨‍💻 L'auteur

  Réalisé avec ❤️ par Lud972vic. 
  Si vous croisez un bug, ne lui lancez pas de tomates, ouvrez une Issue !

  ---

  ⚖️ Licence

  Sous licence "Faites-en bon usage". (MIT)

  ---

  > Note technique : Ce projet utilise une architecture refactorisée où le JS et le CSS sont centralisés. Si vous modifiez shared.js, vous changez le monde (ou au
  moins l'app). Faites attention !

  ---

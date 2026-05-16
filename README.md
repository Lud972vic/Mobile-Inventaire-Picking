  🛒 ALDI Mobile Inventaire Picking 📦

  > "Parce que compter des cartons ne devrait pas être une punition, mais une expérience Turbo-chargée !"

  Bienvenue dans l'outil ultime de picking pour les super-héros du quotidien chez ALDI. Fini le papier, le crayon qui casse et la connexion Wi-Fi qui vous lâche au
  milieu de l'allée 4. Cette application transforme votre smartphone en un scanner de compétition, même si vous êtes enterré au fond de la réserve !
  
<table>
      <tr>
        <td><img width="150" alt="Capture d’écran 1" src="https://github.com/user-attachments/assets/7ca4727b-42cd-46db-addc-66d6474f85bf" /></td>
        <td><img width="150" alt="Capture d’écran 1" src="https://github.com/user-attachments/assets/0bd4a334-fc20-4d70-90a1-abe22b6ee7ce" /></td>
        <td><img width="150" alt="Capture d’écran 1" src="https://github.com/user-attachments/assets/8ebdb8d9-a894-48ac-ae57-7d92d8e79071" /></td>
        <td><img width="150" alt="Capture d’écran 1" src="https://github.com/user-attachments/assets/05258bd4-df03-44cd-9b78-9328d9d2e0a4" /></td>
        <td><img width="150" alt="Capture d’écran 1" src="https://github.com/user-attachments/assets/d53f243a-7692-4a3c-a650-6e45879a7622" /></td>
        <td><img width="150" alt="Capture d’écran 1" src="https://github.com/user-attachments/assets/e0b8ce31-025c-4900-b781-b27966bc4fbb" /></td>
        <td><img width="150" alt="Capture d’écran 1" src="https://github.com/user-attachments/assets/303f0993-c6b7-4f5c-8cf8-c6fb21c81f1e" /></td>
        <td><img width="150" alt="Capture d’écran 1" src="https://github.com/user-attachments/assets/6d3bee94-9dd9-4682-914a-cc8784e239d7" /></td>
        <td><img width="150" alt="Capture d’écran 1" src="https://github.com/user-attachments/assets/dce0ae35-b893-46ad-baf5-5390617b0b46" /></td>
        <td><img width="150" alt="Capture d’écran 1" src="https://github.com/user-attachments/assets/075ede2d-4b08-4ca8-869b-a823a2f50dbf" /></td>
        <td><img width="150" alt="Capture d’écran 1" src="https://github.com/user-attachments/assets/2711b137-d121-404f-9d04-325657084795" /></td>
        <td><img width="150" alt="Capture d’écran 1" src="https://github.com/user-attachments/assets/f06b789b-bcf3-4b8a-b29f-34412c5d9a11" /></td>
        <td><img width="150" alt="Capture d’écran 1" src="https://github.com/user-attachments/assets/f289680f-155b-4775-96d1-cb0e696389a1" /></td>
      </tr>
</table>

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

   1     git clone (privé) https://github.com/Lud972vic/Aldi---Mobile-inventaire-picking
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

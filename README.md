# GitHub

### Ajouter un fichier
* Cliquez **Add file**, sélectionnez **Upload files**.
* Après avoir sélectionné votre fichier, ajoutez un commentaire au commit puis cliquez **Commit changes**.

### Modifier un fichier
* Pour modifier un fichier, il faut ajouter un fichier (*GitHub/Ajouter un fichier*) en veillant à garder le nom du fichier identique. Cela aura pour effet d'override l'ancien fichier.
* Pour actualiser les données de ce fichier, rendez-vous dans la section *PowerBI/Mettre à jour les données*.

# PowerBI

### Connecter un fichier csv

* Sur PowerBI, dans l'onglet **Accueil**, sélectionnez la liste déroulante **Obtenir les données**, puis **Web**.
* Pour récupérer l'URL de votre CSV, il faut se rendre sur **Github**, dans la liste des fichiers, ouvrez le fichier que vous voulez upload en cliquant sur son nom.
* Une fois le fichier ouvert, dans l'en-tête cliquez sur **Raw**, puis copier-coller l'URL de votre fichier brut dans l'URL de PowerBI.
* Pnsez à **Renommer** la table.
* Dans l'onglet **Transformer**, sélectionnez **Utiliser la première ligne pour les en-têtes**.
* Si vous avez besoin de modifier des caractères, sélectionnez **Remplacer les valeurs** (schématisé par 1->2) /!\ Vous pouvez utiliser cette fonctionnalité pour remplacer les '.' (PowerBI n'accepte pas ce format) par des ','.
* Ensuite Vérifiez le type de vos colonnes, pour ce faire sélectionnez une ou plusieurs colonnes, puis **Détecter le type de données**. Le nouveau type de donnée va s'afficher dans **Type de données**.
* (Si le type de la colonne n'est toujours pas valide, veuillez revenir à l'étape modification de caractères.)
* Pour chaque transformation que vous avez réalisé sur la partie droite de l'écran, sont affichées les **Etapes appliquées**. Vous pouvez supprimer ou sélectionner une étape pour modifier votre table.

**TIPS** : Vous pouvez copier-coller un fichier ayant le même traitement pour la mise en forme et seulement modifier la source accessible via **Etapes appliquées**.

### Mettre à jour les données
*En attendant que cette action soit automatisée*.

* Allez dans l'**éditeur Power Query**.
* Dans l'onglet **Accueil**, Cliquez sur actualiser l'aperçu. Attention, il faut attendre quelques minutes après avoir upload les données sur github avant de réaliser cette action pour que cela fonctionne. 

### Télécharger un fichier depuis Github

* Cliquez sur le fichier souhaité.
* Une fois le fichier ouvert, dans l'en-tête cliquez sur **Raw**.
* Puis faite **clic-droit** > **Enregistrer sous...**

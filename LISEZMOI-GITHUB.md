# DiaboData sur GitHub : données chiffrées, sans mot de passe

## Une seule fois
1. Dans votre dépôt DiaboData, remplacez `index.html` par le nouveau fichier `index.html` (version vide, sans donnée).
2. Ouvrez votre page, déposez vos CSV, puis cliquez sur **Copier le lien d'accès**.
3. Collez ce lien dans un endroit sûr (gestionnaire de mots de passe), puis envoyez-le à vos collègues.
   Il ressemble à `https://leloarerpi-max.github.io/DiaboData/#cle=…`. Gardez-le privé.

## Chaque fin de mois
1. Sur votre page : ajoutez vos CSV, puis cliquez sur **Exporter pour GitHub (chiffré)**. Le fichier `donnees.enc` se télécharge.
2. Sur GitHub : dossier `data` (à créer la première fois : Add file > Create new file, nom `data/lisezmoi.txt`), puis Add file > Upload files, déposez `donnees.enc` (il remplace l'ancien) et Commit.
3. Au bout de 1 à 10 minutes, tout collègue qui ouvre le lien voit les données, sans rien faire.

## Pour vos collègues
Cliquer une fois sur le lien d'accès. La clé est gardée dans leur navigateur : ensuite l'adresse normale suffit.
Les données qu'ils ajouteraient eux-mêmes restent sur leur appareil.

## À savoir
- Le fichier `donnees.enc` est public mais illisible sans la clé. Cela reste des données personnelles : ne diffusez pas le lien en dehors de l'équipe.
- Si le lien fuite ou si quelqu'un quitte l'équipe : cliquez sur **Changer la clé**, puis **Copier le lien d'accès** et **Exporter pour GitHub**, et remplacez `donnees.enc` : l'ancien lien ne marchera plus. Si vous avez perdu la clé, les anciens fichiers sont perdus : gardez le lien.

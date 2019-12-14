# Base-ESX

1. Récupérer la base en cliquant sur télécharger
2. Décompresser la base et placer le dossier ESX-base dans le dossier de votre choix.
3. Dirigez-vous vers [ce site](https://runtime.fivem.net/artifacts/fivem/build_server_windows/master/) pour ouvrir le serveur sous Windows.
4. Décompresser le zip télécharger et déplacer tous les fichiers dans le dossier ESX-base précédemment téléchargée
5. Rendez-vous dans ESX-base puis ouvrait le fichier **server.cfg**.
 5.1. Modifier à la ligne 5 votre identifiant et mot de passe de la base de données.
 5.2. Modifier le RCON password à la ligne 22
 5.3. Modifier la ligne 24 (le nom de votre serveur)
 5.4. Modifier à la ligne 117 et 118 le `steam_webApiKey` et `sv_licenseKey` (suivant les liens)
6. Importer la base de données `bdd.sql` dans votre base de données
7. Modifier le fichier `start.bat` dans le dossier ESX-base est remplacé CHEMIN_ACCES par le chemin d'accès de votre dossier ESX-BASE (ligne 2 et 13)
8. Double cliquez sur start.bat puis sur ENTER, lancer votre jeu (FiveM), allez dans direct connect est entrée `localhost:30120` si le serveur est sur votre PC, sinon `IPSERVER:30130`.

[Mon Discord](https://discord.gg/rdwRFGZ)
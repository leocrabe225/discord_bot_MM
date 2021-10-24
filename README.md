# discord_bot_MM
Pour commencer, il faut installer nodejs, vous pouvez le télécharger ici -> https://nodejs.org/en/  
Installez la version "Current" avec les dernières features (La version LTS veut dire "Long Time Support" ce qui veut dire que des gens continuent à travailler sur celle là pendant des années, fix les bugs etc, mais ça reste une ancienne version, elle ne bénéficie donc pas des dernières features (fonctionnalités))

Lancez l'installateur que vous avez téléchargé n'acceptez que les conditions d'utilisation, mais pas l'installation de logiciels supplémentaires (pas nécessaire)

Une fois nodejs installé, il va falloir préparer notre dossier, pour cela, créez un dossier dans lequel vous allez ranger votre bot, ouvrez un terminal (cmd dans le menu windows) et déplacez 
vous jusqu'à celui-ci (Pour vous déplacer dans votre terminal utilisez les commandes "cd <nom_du_dossier>" pour aller dans un dossier, "cd .." pour retourner en arrière 
et "dir" pour voir la liste des fichiers/dossier là où vous êtes). Une fois dans le bon dossier, utilisez "npm init -y" qui va créer un fichier de configuration, 
puis "npm install discord.js dotenv" qui va installer les dépendances nécéssaires à un bot discord.

Une fois tout ça fait, lancez visual studio code, pas avant. (Vous pouvez le télécharger ici si vous ne l'avez pas -> https://code.visualstudio.com/ )  
Ouvrez votre dossier (File -> Open Folder) et copiez-collez le fichier index.js DANS le dossier de votre bot. Créez votre fichier .env avec à l'intérieur 

token=<votre_token_de_bot>

(token trouvable sur la page de votre bot)  
Pour ceux qui n'ont pas encore leur bot discord, allez sur le discord developper portal -> https://discord.com/developers/applications , "New application" en 
haut à droite, cliquez sur l'application que vous venez de créer, allez dans bot et créez votre bot. Ensuite allez dans OAuth2, dans scopes cliquez sur "bot" 
et dans bot permissions cliquez sur "administator" maintenant copiez le lien dans scopes et collez le dans votre navigateur, puis choisissez le serveur dans 
lequel vous voulez insérer votre bot.

Une fois tout ça terminé, vous ouvrez un terminal via visual studio code et pour lancer votre bot il suffit d'écrire "node index.js"

Documentation -> https://discord.js.org/#/docs/main/stable/general/welcome

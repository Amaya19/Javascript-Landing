<div align="center">
  <h1>Les pré-requis</h1>
  <p>Dans ce tuto, vous allez voir comment bien débuter avec votre bot.</p>
</div>


<p>
<br>
  
Bon, pour commencer, il vous faudra une appli pour lire vos codes. Je vous conseille d'utiliser Sublime Text, ça prends pas de place, et c'est bien.

### Créer votre Dossier

Dans votre ordi, vous allez créer un dossier que vous allez nommer avec le nom de votre bot. Puis, ouvre Sublime Text, allez dans `File` puis `Open Folder`, et vous choisissez le dossier de votre bot. Une fois ceci fait, une petite "fênetre" va s'ouvrir a gauche, puis vous cliquez sfaites clique droit sur le nom du dossier, et vous faites `new file`, puis vous faitez `ctrl+s`, puis vous entrez comme nom `index.js`, et vous faites `enter`. Votre index est créer. Votre bot marchera grâce a ce fichier !

### Installer Nodejs

Il faudra installer `Node.js`pour ue votre bot puisse marcher. Voici les démarches :

#### Sur Linux (Distro en debian)

```sudo apt install nodejs
sudo apt install npm
```

#### Sur Mac & Windows :

Rendez-vous sur le site de node, puis téléchargez le.

### Installer les modules :

#### Mac :
Ouvrez le terminal, puis faites `cd chemin_du_dossier` puis faites `enter`, et faites

```npm i -s discord.js
```

#### Linux :

Allez dans le dossier de votre bot, et faites clique droit, puis cliquez sur `ouvrir dans un terminal`, et faites :

```npm i -s discord.js
```

#### Windows :

Allez dans le dossier de votre bot, faite `shift+clique droit` et cliquez sur `ouvrir dans powershell`, et faites :

```npm i -s discord.js
```

Clonage : Clonez le dépôt forké vers votre machine locale :
git clone https://github.com/VOTRE_UTILISATEUR/votre-fork.git

Mise en Place : Configurez le dépôt original comme "upstream" pour pouvoir récupérer les mises à jour 
git remote add origin https://github.com/NOM_UTILISATEUR/projet-original.git

Création d'une Branche : Avant de faire des modifications, créez une nouvelle branche :
git checkout -b nom-de-votre-branche

Développement : Faites vos modifications et committez-les :
git add .
git commit -m "Description de vos modifications"


Push : Une fois vos modifications terminées et synchronisées, poussez-les vers votre fork :
git push origin nom-de-votre-branche

Pull Request : Sur GitHub, ouvrez une pull request (demande de tirage) en expliquant clairement les modifications apportées et en référençant les problèmes liés, le cas échéant.# projrtWeb

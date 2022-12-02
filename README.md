# Tdeploy
Afin de Déployer une application sur la plateforme Mogenius nous avons tout d'abord, crée un fichier html simple et on le push sur un reprosoterie github avec un fihier
docker contenant le code suivant :  FROM nginx
                                    COPY . /usr/share/nginx/html
Ensuite, après avoi créer un compte Mogenius nous allons créer un cloudspace en laison avec notre compte github (et avec le represoteries de l'application) et en 
précisant le port 80.

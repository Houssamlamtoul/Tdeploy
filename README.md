# Tdeploy
Afin de Déployer une application sur la plateforme Mogenius nous avons tout d'abord, crée un fichier html simple et on le push sur un reprosoterie github avec un fihier
docker contenant le code suivant :  FROM nginx
                                    COPY . /usr/share/nginx/html
Ensuite, après avoi créer un compte Mogenius nous allons créer un cloudspace en laison avec notre compte github (et avec le represoteries de l'application) et en 
précisant le port 80.

![image](https://user-images.githubusercontent.com/76660024/205343983-23d15389-50b5-45f6-aafb-1d8bce5f74b4.png)
![image](https://user-images.githubusercontent.com/76660024/205344015-2909de53-6dca-46dc-a415-cbcfba23cf9a.png)


Vu que j’ai tardé en essayant de faire marcher et mettre en place un build local (docker build) d’une application angular, malheureusement j’ai pas eu le temps de tout finir.

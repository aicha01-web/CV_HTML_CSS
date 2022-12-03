# HelloWorld
Projet Hello World crée en utilisant Angular 15 avec nginx sous docker.

## PREREQUIS
1-Installez node: https://nodejs.org/en/          
2-Installez npm: https://docs.npmjs.com/cli/v9/commands/npm-install         
3-Installez Angular CLI: npm install -g @angular/cli   
4-Installez Docker Desktop :
    -Sur windows:https://docs.docker.com/desktop/install/windows-install/
    -Sur MAC: https://docs.docker.com/desktop/install/mac-install/
    -Sur Linux: https://docs.docker.com/desktop/install/linux-install/ 



## A FAIRE
1-Installez docker desktop                                    
2-Clonez le projet: 
  git clone https://github.com/aicha01-web/Hello_world.git                               
3-Tapez la commande ng build pour builder le projet ce qui va créer le répertoir dist/                                                                
4-Créer l'image à partir du dockerfile en utilisant cette commande: docker build -t "nom_image" .                          
5-Créer un conteneur à travers l'image que l'on a crée précédemment :
  docker run -d --name "nom_conteneur" -p numero_port_externe:numero_port_interne "nom_image"
6-Il reste à tester !                                         


## ALTERNATIVE
L'étape 3 peut être sauté en décommentant dans le dockerfile la première partie:
    # FROM node:18.10 as node                      
    # WORKDIR /app                               
    # COPY . .                            
    # RUN npm install                           
    # RUN npm run build                                      


## AIDE
sokhnaaichasarr@gmail.com



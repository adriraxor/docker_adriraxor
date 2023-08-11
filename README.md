# Credits 

Mise à jour de https://github.com/cnadal/machine_docker aujourd'hui obsolète  

# Description 

**Testé sous DEBIAN 10 et ubuntu 23.04**

L'objectif de ce projet et de pouvoir commencer un projet web localement et rapidement avec un ensemble d'outils et de dépendances pré-installés. En exploitant la technologie de containerisation Docker. 

# Containers 

- PHP 8.0.13 
- MYSQL 8.0.32
- PHPMYADMIN

# Installation 

Prêt à l'emploi pour des projets Symfony v6.0.x : 

1) apt install git sudo
2) git clone https://github.com/adriraxor/docker_adriraxor.git
3) chmod 755 ./get-docker.sh 
4) ./get-docker.sh
5) chmod 755 ./install-docker-compose
6) ./install-docker-compose 
7) /!\ nano .env (configuration par défaut) /!\
8) docker-compose build
9) docker-compose up -d

# Note obsolète car les installations se font désormais à partir du dockerfile donc lors de la création de l'image. 

--- Installation des dépendances manuellement ---

- NodeJS Installation - 

1) sudo apt install nodejs npm -y
2) node -v

- NodeJS Mise à jour - 

1) sudo npm cache clean -f (facultatif, mais recommandé) 
2) sudo npm install -g n
3) sudo n stable

- Yarn installation - 

1) npm install --global yarn

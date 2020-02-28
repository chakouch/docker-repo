#

# Clone du repository git dans un répertoire nouvellement créé
git clone https://github.com/chakouch/docker-repo
cd docker-repo

# Création de l'image Docker depuis le Dockerfile
docker build -t projet/chabo .
# Exécution de l'image docker sur le port 8888
docker run -p 8888:5000 projet/chabo

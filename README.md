# app-fullstack-docker
mkdir app-fullstack-docker
cd app-fullstack-docker
mkdir frontend backend
touch docker-compose.yml
touch frontend/Dockerfile backend/Dockerfile
git init
git add .
git commit -m "Estrutura inicial do projeto com docker-compose e Dockerfiles"
git remote add origin <URL_DO_REPO>
git push -u origin master

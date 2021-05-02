# Hey! 👤

[![Github Badge](https://img.shields.io/badge/-Github-000?style=flat-square&logo=Github&logoColor=white&link=https://github.com/luciolemos)](https://github.com/luciolemos)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/lucio-lemos-a550441a1/)](https://www.linkedin.com/in/lucio-lemos-a550441a1/)
[![Twitter Badge](https://img.shields.io/badge/-Twitter-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/lucciolemos)](https://twitter.com/lucciolemos)
[![Youtube Badge](https://img.shields.io/badge/-YouTube-ff0000?style=flat-square&labelColor=ff0000&logo=youtube&logoColor=white&link=https://studio.youtube.com/channel/UCrNM1nr2nw0lSqMD10m6rLw)](#)
## APP_PROJECT 📌:
Este `docker_project` está localizado no seguinte caminho:

    luciolemos@dev:~/my_docker_projects/app$
### Git CLI 💻
#### Linhas de comando para inicializar, adcionar ao repostório local, commitar, branchear e pushear.
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/luciolemos/docker_project.git
    git push -u origin main

### Versões instaladas do `node`, `yarn` e `npm`, respectivamente.
    luciolemos@dev:~$ node -v
    v10.19.0
    luciolemos@dev:~$ yarn -v
    1.22.10
    luciolemos@dev:~$ npm -version
    6.14.4
### Docker CLI 💻
#### Para verificar se você pode acessar e baixar imagens do Docker Hub, digite: `docker run hello-world`. A saída indicará que o Docker está funcionando corretamente:
    luciolemos@dev:~$ docker run hello-world
#### Para ver todos os subcomandos disponíveis, digite:
    luciolemos@dev:~$ docker
#### Para pesquisar imagens disponíveis no Docker Hub (ubuntu, por exemplo), use a seguinte linha de comando:
    luciolemos@dev:~$ docker search ubuntu
### Manipulando imagens
#### Para listar as imagens disponíveis, use `docker ps`:
    luciolemos@dev:~$ docker ps
#### Navegue até o diretório raiz do projeto `app` e crie a imagem do contêiner usando o `docker build`. Este comando usou o Dockerfile para construir uma nova imagem de contêiner. 
    luciolemos@dev:~/my_docker_projects/app$ docker build -t getting-started .
### Manipulando contêineres
#### Inicie seu contêiner usando `docker run` e especifique o nome da imagem criada:
    luciolemos@dev:~/my_docker_projects/app$ docker run -dp 3000:3000 getting-started
#### Para visualizar os contêineres ativos, use `docker ps`:
    luciolemos@dev:~$ docker ps
#### Para visualizar todos os contêineres ativos e inativos, execute `docker ps` com a flag `-a`:
    luciolemos@dev:~$ docker ps -a 
#### Para visualizar o último contêiner criado, passe a flag `-l`:
    luciolemos@dev:~$ docker ps -l
#### Para interromper um contêiner em execução, use o comando `docker stop`, seguido do ID do contêiner, ou do `NAME` atribuído ao contêiner pelo docker: 
    luciolemos@dev:~$ docker stop 7082a41023e6 (ID)
    luciolemos@dev:~$ docker stop friendly_allen (NAME)
#### 

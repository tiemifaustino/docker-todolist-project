
# Projeto Docker Todo List


Projeto realizado no módulo de Back-end durante o curso de Desenvolvimento Web pela [Trybe](https://www.betrybe.com/), a escola que te ensina a programar, a aprender e a trabalhar.

## Descrição

Neste projeto foi fornecido pela [Trybe](https://www.betrybe.com/) uma aplicação full-stack (**um aplicativo de tarefas**) dividida em `Front-end`, `Back-end` e um aplicativo de  `teste` que valida se as aplicações estão se comunicando. 

- **⚠️ Essa aplicação conta com um [**README.md**](./docker/todo-app/README.md) próprio, (fornecido pela [Trybe](https://www.betrybe.com/)) que foi usado como referência na criação dos scripts!**

Para essa aplicação fornecida funcionar, foi desenvolvido os arquivos de configuração para cada frente específica, criando as imagens para as aplicações e essas imagens configuradas com o `docker-compose`



## 👩‍💻 Tecnologias Utilizadas

- Docker
- Dockerfile
- Docker Compose


## 🛠️ Habilidades Utilizadas

- Conteinerização de aplicações;
- Criar uma conexão entre elas;
- Orquestrar seu funcionamento.


## 📂 Arquivos desenvolvidos

- Caminho `/docker/docker-commands/`
    - Arquivos `command01.dc` a `command12.dc`
    - docker-compose.yml
- Caminho `/docker/todo-app/back-end/`
    - Arquivo Dockerfile
- Caminho `/docker/todo-app/front-end/`
    - Arquivo Dockerfile
- Caminho `/docker/todo-app/tests/`
    - Arquivo Dockerfile


## Instalando Dependências

1. Clone o repositório
* `git clone git@github.com:tiemifaustino/docker-todolist-project.git`
* Entre na pasta do repositório que você acabou de clonar:
  * `cd docker-todolist-project`

2. Instale as dependências:
  * `npm install`
# :whale: Projeto Docker To-Do List :whale:

Nesse projeto foram realizadas 3 tarefas principais:

- Criação de imagens e containers para as aplicações de backend, frontend e testes, por meio de comandos CLI presentes no diretório docker-commands;
- Criação dos Dockerfiles para as aplicações de backend, frontend e testes, seguindo as especificações definidas pelo projeto;
- Orquestração dos containers por meio do docker-compose.yml, utilizando as imagens "buildadas" anteriormente e seguindo as especificações definidas pelo projeto.

Os demais arquivos foram desenvolvidos pela Trybe.

Para inicializar o projeto:
- git clone git@github.com:sthefanimartinelli/project-17-back-end-docker-todo-list.git
- cd docker
- docker image build -t todobackend ./todo-app/back-end/
- docker image build -t todofrontend ./todo-app/front-end
- docker image build -t todotests ./todo-app/tests
- docker compose up

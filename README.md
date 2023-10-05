# :whale: Docker To-Do List Project :whale:

In this project, 3 main tasks were carried out:

- Creation of images and containers for back-end, front-end, and testing applications, using CLI commands present in the docker-commands directory;
- Creation of Dockerfiles for back-end, front-end, and testing applications, following the specifications defined by the project;
- Orchestration of containers through docker-compose.yml, using previously built images and following the specifications defined by the project.

The remaining files were developed by Trybe.

### To start the project:
Clone the repository and run the commands below:
```
- cd docker
- docker image build -t todobackend ./todo-app/back-end/
- docker image build -t todofrontend ./todo-app/front-end
- docker image build -t todotests ./todo-app/tests
- docker compose up
```

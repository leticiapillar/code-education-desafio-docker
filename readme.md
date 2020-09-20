### Curso Code.Education

#### Desafio Docker


- **Desafio 1**: host e a porta do nginx definidos em no docker-compose.yaml
    - *local do projeto*: desafios/desafio-02-docker/desafio-nginx
    - No terminal execute:
    > docker-compose up -d
    - Acompanhe os logs da aplicação laravel:
    > docker logs app -f
    - Quando a aplicação estiver ok, pode ser acessada em: http://localhost:8000/
    
>

- **Desafio 2**: imagem go
    - *local do projeto*: desafios/desafio-02-docker/desafio-golang
    - *local da imagem*: [docker hub](https://hub.docker.com/r/leticiapillar/codeeducation)
    - No terminal execute:
    > docker run leticiapillar/codeeducation
    - O resultado será o print de `Code.education Rocks!` no seu terminal
    
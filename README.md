# Master Class Bases de datos Session I [Dockerized]

- Instalar docker:  
https://store.docker.com/search?type=edition&offering=community

- Instalar docker-compose (en linux solamente):  
https://docs.docker.com/compose/install/

- Instalar pgAdmin4:  (opcional)
https://www.pgadmin.org/download/

- Instalar NoSQL Booster:  (opcional)
https://nosqlbooster.com/downloads  

- Clonar este repositorio, entrar y ejecutar:  
```
docker-compose build
docker-compose up -d
```
  
- Debeis obtener el token de jupyter que se encuentra en los logs:  
```
docker logs master_class_bd_session_1_notebook
```
  
- Con el token puedes entrar en http://localhost:8888/ e introducirlo para comenzar.

- Al terminar la clase, ejecutar:
```
docker-compose down
```
## Links interesantes:

- [Diagrama comparativo modelos](https://docs.google.com/drawings/d/1pncEgJMPd8r69JI0d9bn1tCCmSivYgzp7o-5kpBMeGs/edit?usp=sharing)

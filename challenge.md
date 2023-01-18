# Challenge-docker

        
MundoSE, solicita al Equipo de DevOps Trainer, la contenerizacion de su aplicacion y despliegues usando docker-compose que incluye:

- APP
- Consumer

```
Version de Python Soportada:
python:3.8-alpine
python:3.10.8-alpine
```
Este ejemplo crea una API basica de `flask`, con un consumidor que accede desde el service a la API. 

La Aplicacion se expone en el puerto port: 8000, ademas para que el consumidor lo pueda tomar es necesario que el contenedor se llame service-flask-app

El consumidor requiere esta variable de entorno
```
          env:
            - name: PYTHONUNBUFFERED
              value: "1"
```    

**Requisitos**

- Docker
- docker-compose

**Desafío**

- Crear el Dockerfile de la APP y Consumer
- Crear el Docker-Compose
- Push de la imagen en el Registry de Docker-hub
- Apunta a las buenas practicas
- Puedes Desplegar ambas aplicaciones usando en Lets Play Docker, Killercoda, EC2, etc



**Resultados**
![](docs/Resultado.png)


### ------------------

⌨️ con ❤️ por [roxsross](https://github.com/roxsross) 😊

No olvides revisar mi blog [roxsross](https://blog.295devops.com) 😊

y mi linktree [roxsross](https://roxs.295devops.com) 😊

"No se trata de cambiar el mundo, creo que creas un cambio pequeño, pero que te importe estás cambiando las cosas".
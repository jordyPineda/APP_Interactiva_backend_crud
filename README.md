# APP_Interactiva_backend_crud

El API APP_Interactiva_backend_crud proporciona interfaces para la manipulación (CRUD) de los datos almacenados en una base de datos relacional postgresql. 

## Especificaciones Técnicas

### Tecnologías Implementadas y Versiones

- [Golang](https://github.com/udistrital/introduccion_oas/blob/master/instalacion_de_herramientas/golang.md)
- [BeeGo](https://github.com/udistrital/introduccion_oas/blob/master/instalacion_de_herramientas/beego.md)
- [Docker](https://docs.docker.com/engine/install/ubuntu/)
- [Docker Compose](https://docs.docker.com/compose/)

### Variables de Entorno

```shell
# No definidas actualmente
```

### Ejecución del Proyecto

```shell
#1. Obtener el repositorio con Go
go get github.com/jordyPineda/APP_Interactiva_backend_crud.git

#2. Moverse a la carpeta del repositorio
cd $GOPATH/src/github.com/APP_Interactiva_backend_crud

# 3. Moverse a la rama **develop**
git pull origin develop && git checkout develop
bee run

```
## Arquitectura

![](arquitectura.png)

## Dependencias Utilizadas

### CLIENTES

## Estado CI

| Develop | Release 0.0.1 | Master |
| -- | -- | -- |


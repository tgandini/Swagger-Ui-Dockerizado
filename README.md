# Swagger-Ui-Dockerizado
Repo que levanta un container con un nginx que adentro tiene el html para renderizar Swagger-ui. Está hecho para poder inyectar un yaml cualquiera seteando la variable de environment API_URL: docs/{Fichero yaml}

### Instrucciones: 
1: El docker-compose levanta una imagen de swaggerapi/swagger-ui, lo único que hay que parametrizar es en environment/API_URL la URL del yaml base con la cual queremos renderizar la documentación. Hay unos ejemplos comentados. En el repo está como ejemplo el archivo yaml que usamos para el challenge de Swagger
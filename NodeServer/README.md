Servidor en el cual se implementan las siguientes funcionalidades

## Rutas
Se manejan las siguientes rutas:

| Recurso       | Método | Descripción                    |
| ------------- | ------ | ------------------------------ |
| uploadImageS3 | POST   | Sube una imagen a un bucket S3 |
| saveImageInfoDDB | POST | Sube una imagen a un bucket S3 y guarda el registro en una tabla de DynamoDB |


## Archivos
Se utilizan los siguientes archivos para manejar los credenciales de manera segura, se recomienda agregarlos a .gitignore para que no se suban al repositorio. De esta forma solo tienen que copiar estos archivos en los servidores dónde se requieran utilizarlos

| Archivo                       | Descripción              |
| ----------------------------- | ------------------------ |
| aws_keys_template.js | Plantilla de una estructura para las credenciales de un servicio de AWS |
| db_credentials_template.js | Plantilla de una estructura para las credenciales de una base de datos |
En este proyecto tengo una aplicacion CRUD generadora de datos falsos utilizando flask y python  cada servicio esta implementado en el archivo docker-compose de la carpeta Docker-compose-services-master es decir 
toda esta aplicacion esta construida sobre docker-compose , la base de datos a la que se conecta el servicio faker-service es una base de datos
postgresql vigente en Heroku

En la carpeta de Kubernetes_deployment tengo la misma app pero implementada en kubernetes , para realizar esta migracion deje especificado el proceso 
en la documentacion del archivo .docx
Gracias!!!


Si se desea correr en cualquier maquina el proyecto en docker-compose solo deben clonar el repositorio en sus maquinas y en la raiz ejecutar
docker-compose up

y luego debera ver 3 contenedores corriendo y simplemente para interactuar con la app principal debe ir a la direccion 
http://localhost:5002

para correr el deployment con kubernetes se encuentra la documentacion del archivo Implementación desde docker-compose hacia kubernetes.docx

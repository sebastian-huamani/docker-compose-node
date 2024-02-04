
create docker conteiner from image in port 81 , listening port 3000 at proyect:


##### web container 
`docker run -p 81:3000 -d --name node_app node_app:v1`

##### api container 
`docker run -p 82:3000 -d --name node_api node_api:v1`
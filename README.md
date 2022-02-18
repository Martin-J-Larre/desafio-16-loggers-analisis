## LOGGERS Y GZIP
-  la diferencia de cantidad de bytes devueltos en un caso y otro en ruta: *http://localhost:8081/info*
### Con cosole.log()
![alt text](https://github.com/Martin-J-Larre/desafio-16-loggers-analisis/blob/main/assets/info-con-comp.JPG?raw=true)

### Sin cosole.log()
![alt text](https://github.com/Martin-J-Larre/desafio-16-loggers-analisis/blob/main/assets/info-sin-comp.JPG?raw=true)



## Forever
 - ### Modo Fork 
  - **desafio-15-e> node>** `npx forever start index.js`
  - **desafio-15-e> node>** `npx forever list`
  - **desafio-15-e> node>** `npx forever stopall`
 - ###  Modo Cluster 
  - **desafio-15-e> node>** `npx forever start index.js CLUSTER`
  - **desafio-15-e> node>** `npx forever list`
  - **desafio-15-e> node>** `npx forever stopall`

## PM2
- ### **Correr como aministrador nginx.exe borrar para cambiar de prueba**
- ### Modo Fork con watching y puerto
  - **desafio-15-E > node>** `npx pm2 start index.js --name="modoFork" --watch 8080`
- ###  Modo Cluster con watching y puerto
  - **desafio-15-E > node >** `npx pm2 start index.js --name="modoCluster" --watch -i max -- 8081`
- ###  Modo Fork NGINX *ruta: http://localhost/api/random/*
  - **desafio-15-E > node >** `npx pm2 start index.js --name="fork1" --watch 8081`
  - **desafio-15-E > node >** `npx pm2 start index.js --name="cluster1" --watch -i max -- 8081` // mantiene solo el último pid
- ###  Modo Fork NGINX repartidas *ruta: http://localhost/api/random/*  
  - **desafio-15-E > node >** `npx pm2 start index.js --name="fork2" --watch 8082`
  - **desafio-15-E > node >** `npx pm2 start index.js --name="fork3" --watch 8083`
  - **desafio-15-E > node >** `npx pm2 start index.js --name="fork4" --watch 8084`
  - **desafio-15-E > node >** `npx pm2 start index.js --name="fork5" --watch 8085`
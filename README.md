# LOGGERS Y GZIP
-  la diferencia de cantidad de bytes devueltos en un caso y otro en ruta: *http://localhost:8081/info*
### Con compresión
![alt text](https://github.com/Martin-J-Larre/desafio-16-loggers-analisis/blob/main/assets/info-con-comp.JPG?raw=true)

### Sin compresión
![alt text](https://github.com/Martin-J-Larre/desafio-16-loggers-analisis/blob/main/assets/info-sin-comp.JPG?raw=true)

## Nota:
- No se si hice algo mal, pero me da lo mismos valores.
- Decidí por mi cuenta hacer los mismo con la ruta : *http://localhost:8081/api/random*

### Con compresión
![alt text](https://github.com/Martin-J-Larre/desafio-16-loggers-analisis/blob/main/assets/random-con-comp.JPG?raw=true)

### Sin compresión
![alt text](https://github.com/Martin-J-Larre/desafio-16-loggers-analisis/blob/main/assets/random-sin-comp.JPG?raw=true)

## Rutas para logs con log4js:
- `http://localhost:8081`
- `http://localhost:8081/info`
- `http://localhost:8081/api/random`
- `http://localhost:8081/mensajes`
- `http://localhost:8081/productos`
- `http://localhost:8081/cualquiera`

## --prof / --prof-process / --inspect

### Con console.log()
![alt text](https://github.com/Martin-J-Larre/desafio-16-loggers-analisis/blob/main/assets/chrome-inspect-bloq.JPG?raw=true)

![alt text](https://github.com/Martin-J-Larre/desafio-16-loggers-analisis/blob/main/assets/chome-inspect-bloq.JPG?raw=true)


### Sin console.log()
![alt text](https://github.com/Martin-J-Larre/desafio-16-loggers-analisis/blob/main/assets/xhome-inspect-late-1.JPG?raw=true)

![alt text](https://github.com/Martin-J-Larre/desafio-16-loggers-analisis/blob/main/assets/chome-inspect-late-2.JPG?raw=true)

## Autocannon-0x
- Nota: todo lo de autocannon y 0x esta y se explica en la carpeta:
> *desafio-16-loggers-analisis\autocannon-0x*
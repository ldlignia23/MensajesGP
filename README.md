# _WebSocketChat_

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

Este es un servidor de express listo para ejecutarse junto a la carpeta public en la web para la materia de aplicaciones distribuidas.

> Integrantes: `Kevin Armas,
Pepe Carrillo,
Sebastián Soberón,
Jhonnatan Tipan`

## _Instalación_

Se debe reconstruir los módulos de node con el comando

```
npm install
```

## _Ejecución_

Se puede ejecutar la aplicación con el comando npm start que se encuentra predefinido en nuestro package.json en donde "start": "node server/server.js".

```
npm start
```

O se puede ejecutar con el comando de node de la siguiente manera

```
node server/server.js
```

O también accediendo primero a la carpeta server y ejecutando el server.js de la siguiente manera:

```
cd server
node server.js
```

> Nota: `El servidor está corriendo en el puerto 3000 en caso de que no le deje correr el programa asegurese de liberar el puerto o a su vez cambiar el puerto de ejecución.`

## _Recursos utilizados_

Esta aplicación hace uso de un template de chat encontrado en la página de [Bootdey](https://www.bootdey.com/snippets/view/white-chat "Templates de chat") para el tema de front que se encuentra creado en la carpeta public.

Para el backend por otro lado hacemos uso de algunas librerías de [Node](https://nodejs.org/en/) tales como [Express](http://expressjs.com "El servidor de confianza en Node") y de [Socket.io](https://socket.io "Para el funcionamiento de la aplicacion con Sockets").

## _Licencia_

MIT

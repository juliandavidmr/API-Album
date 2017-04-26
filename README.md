# API-Album

API de álbum de fotos. Servidor de fotografías para demostración en Taller Apps Ionic.

### **Instalando servidor**

Antes de ejecutar la aplicación, es necesario **instalar
un servicio REST**. Para esto, se deben realizar los
siguientes pasos: 

- Instalar la herramienta [json-server](https://github.com/typicode/json-server) para 
crear rapidamente servicios.

```bash
$ npm install -g json-server
```

- Descargar repositorio. Contiene el código necesario para
que `json-server` trabaje correctamente:

```bash
$ git clone https://github.com/juliandavidmr/API-Album.git
```

- Correr servicio:
```
$ cd API-Album
$ json-server --watch db.json
```
Despues de esto, `json-server` va a tomar el archivo `db.json` _(Ubicado en **API-Album**)_ para crear todo el servicio completo, de esta forma los metodos POST, GET, PUT, DELETE, y demás, estarán disponibles para su uso.

> Nota: Una vez creado el servidor, se debe dejar el proceso en ejecución, es decir, la terminal debe quedar abierta, si no desea depender de la terminal, puede probar [PM2](http://pm2.keymetrics.io)
# LocalStorage

LocalStorage es una característica de almacenamiento en el navegador que permite a las aplicaciones web almacenar datos de manera persistente en el navegador del usuario. Está diseñado para ser una forma simple de almacenar claves y valores en pares, y los datos almacenados persisten incluso después de cerrar la ventana del navegador.

* Almacenar Datos

```javascript
const nombre = "Alejandro"

localStorage.setItem("nombre", nombre);
```

* Obtener Datos

```javascript
const nombre = localStorage.getItem("nombre");
```

* Eliminar Datos

```javascript
localStorage.removeItem("nombre");
```

* Almacenar JSON

```javascript
//Guardar en formato JSON
const usuario = { nombre: 'John', edad: 30 };
localStorage.setItem('usuario', JSON.stringify(usuario));

//Obtener JSON parseado a objeto
const usuarioRecuperado = JSON.parse(localStorage.getItem('usuario'));
```

LocalStorage es útil para almacenar datos en el navegador a nivel de clave-valor, pero es importante tener en cuenta que tiene limitaciones en términos de capacidad de almacenamiento y no debe utilizarse para almacenar información crítica o sensible sin cifrado adecuado. Además, siempre es una buena práctica verificar si el almacenamiento local está disponible y manejar cualquier excepción que pueda surgir durante el uso.

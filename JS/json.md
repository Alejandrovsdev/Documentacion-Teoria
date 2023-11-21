# JSON (Javascript Object Notation)

Es un formato ligero de intercambio de datos que se utiliza para estructurar la información de manera legible para humanos y fácil de interpretar para las máquinas. Aunque su nombre incluye "JavaScript", JSON es un formato independiente del lenguaje y se utiliza en una variedad de contextos y lenguajes de programación.

### Sintaxis básica de JSON

---

* Un objeto JSON se define entre llaves {} y contiene pares clave-valor separados por comas.

* Un arreglo JSON se define entre corchetes [] y contiene valores separados por comas.


Ejemplo de un objeto JSON

```JSON
  "nombre": "Juan",
  "edad": 30,
  "ciudad": "EjemploCity",
  "casado": false,
  "hobbies": ["leer", "viajar", "programar"]
```

### Convertir un objeto a JSON (Serialización)

---

En la mayoría de los lenguajes de programación, puedes convertir un objeto a JSON utilizando funciones o métodos específicos proporcionados por las bibliotecas estándar o bibliotecas externas. Aquí hay un ejemplo en Javascript utilizando el módulo json

```javascript
// Crear un objeto en JavaScript
const persona = {
  nombre: "Juan",
  edad: 30,
  ciudad: "EjemploCity",
  casado: false,
  hobbies: ["leer", "viajar", "programar"]
};

// Convertir el objeto a una cadena JSON
const jsonPersona = JSON.stringify(persona);

console.log(jsonPersona);
```

En este ejemplo, **JSON.stringify()** toma un objeto JavaScript y lo convierte en una cadena JSON.

### Convertir un JSON a objeto (Deserialización)

---

Al igual que la serialización en la mayoria de los lenguajes de programación se pueden convertir un objeto a JSON utilizando funciones o metodos proporcionados por dichos lenguajes o librarias. Aqui un ejemplo

```javascript
// JSON como cadena
const jsonPersona = '{"nombre": "Juan", "edad": 30, "ciudad": "EjemploCity", "casado": false, "hobbies": ["leer", "viajar", "programar"]}';

// Convertir la cadena JSON a un objeto JavaScript
const persona = JSON.parse(jsonPersona);

console.log(persona);
```

En este caso, **JSON.parse()** toma una cadena JSON y la convierte de nuevo en un objeto JavaScript.

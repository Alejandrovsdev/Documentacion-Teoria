# Selectores JS

## 1. getElementBy

es un método de JavaScript que se utiliza para seleccionar un elemento específico del DOM, este método puede obtener elementos según diferentes selectores:

* **getElementById:**

  * Descripción: Selecciona un elemento por su atributo de identificación (id)

  * Caso de uso: Acceder y manipular un elemento específico de la página

Devuelve un solo elemento o null si no se encuentra ningún elemento con el ID especificado.

```javascript
document.getElementById("id");
```

* **getElementsByClassName:**

  * Descripción: Selecciona varios elementos por su atributo de clase (class)

  * Caso de uso: Estilizar o manipular varios elementos con la misma clase.

Devuelven una HTMLCollection que contiene todos los elementos que coinciden con la clase.

```javascript
document.getElementsById("clase");
```

* **getElementsByTagName:**

  * Descripción: Selecciona todos los elementos de una etiqueta especifica

  * Caso de uso: Manipular o estilizar todos los elementos de un tipo particular

Devuelven una HTMLCollection que contiene todos los elementos que coinciden con la tag.

```javascript
document.getElementByTagName("p");
```

## 2. querySelector y querySelectorAll

* **querySelector:**

Es un método de JavaScript que se utiliza para seleccionar el primer elemento que coincide con un selector CSS especificado.

Devuelve el primer elemento que cumple con el criterio de selección o null si no se encuentra ningún elemento.

```javascript
//Selecciona un tag
document.querySelector("p");
//Selecciona una clase
document.querySelector(".clase");
//Selecciona un id
document.querySelector("#id");
```

como se puede observar en el código entre los parentesis funciona igual a las reglas de cascada de css, podria tener incluso selectores combinados como por ejemplo:

```javascript
//Selector combinado tag y clase
document.querySelector("p.clase");
```

* **querySelectorAll:**

Se utiliza para seleccionar todos los elementos que coinciden con el selector. La elección entre ellos dependerá de si necesitas acceder a un solo elemento o a múltiples elementos que cumplan con ciertos criterios de selección.

devuelve una NodeList incluso si solo se encuentra un elemento, y si no se encuentra ningún elemento, la NodeList estará vacía.

```javascript
document.querySelector(".clases");
```

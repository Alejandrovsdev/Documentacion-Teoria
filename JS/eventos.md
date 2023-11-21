# eventos addEventListener("evento", )

El método addEventListener() es una forma de agregar un evento a un elemento HTML.

* **click**:

  * Descripción: Se activa cuando se hace clic en un elemento.

  * Uso común: Manejar acciones de clic en botones, enlaces u otros elementos interactivos.

```javascript
        const button = document.querySelector("button");
        // Evento de click en el botón
        button.addEventListener("click", function() {
                alert("¡Hola, mundo!");
        });
```

---

* **mouseover**:

  * Descripción: Ocurre cuando el puntero del mouse se coloca sobre un elemento.

  * Uso común: Cambiar estilos o mostrar información adicional cuando el mouse pasa sobre un elemento.

```javascript
        const button = document.querySelector("button");
        // Evento al pasar el mouse por el botón
        button.addEventListener("mouseover", function() {
                console.log("El cursor del mouse está sobre el botón.");
        });
```

---

* **mouseout**:

  * Descripción: Se dispara cuando el puntero del mouse sale de un elemento.

  * Uso común: Restablecer estilos o ocultar información adicional cuando el mouse deja un elemento.

```javascript
        const button = document.querySelector("button");
        // Evento al sacar el mouse del botón
        button.addEventListener("mouseout", function() {
                console.log("El cursor del mouse salió del botón.");
        });
```

---

* **mousedown**:

  * Descripción: Sucede cuando se presiona un botón del mouse sobre un elemento.

  * Uso común: Iniciar acciones mientras se mantiene presionado un botón del mouse.

```javascript

```

---

* **mouseup**:

  * Descripción: Se activa cuando se libera un botón del mouse sobre un elemento.

  * Uso común: Finalizar acciones después de soltar un botón del mouse.

```javascript

```

---

* **keydown**:

  * Descripción: Ocurre cuando una tecla del teclado está siendo presionada.

  * Uso común: Capturar la entrada del teclado para activar eventos según las teclas presionadas.

```javascript

```

---

* **keyup**:

  * Descripción: Se activa cuando se libera una tecla del teclado.

  * Uso común: Realizar acciones después de soltar una tecla, como enviar datos de formulario.

```javascript

```

---

* **change**:

  * Descripción: Se dispara cuando el valor de un elemento de formulario cambia (por ejemplo, un campo de entrada).

  * Uso común: Validar o actualizar datos cuando cambian en formularios.

```javascript

```

---

* **submit**:

  * Descripción: Ocurre cuando se envía un formulario.

  * Uso común: Validar datos del formulario antes de enviarlos al servidor.

```javascript

```

---

* **input**:

  * Descripción: Se activa cuando el contenido de un elemento de entrada cambia.

  * Uso común: Realizar acciones en tiempo real mientras el usuario escribe, como la validación de entrada.

```javascript

```

---

* **focus**:

  * Descripción: Sucede cuando un elemento recibe el foco.

  * Uso común: Activar efectos visuales o cargar información adicional cuando un usuario selecciona un elemento.

```javascript

```

---

* **blur**:

  * Descripción: Se dispara cuando un elemento pierde el foco.

  * Uso común: Validar datos o realizar acciones cuando un usuario deja un campo de entrada.

```javascript

```

---

* **load**:

  * Descripción: Ocurre cuando un recurso y sus dependencias han terminado de cargar.

  * Uso común: Inicializar scripts o cargar recursos adicionales después de que la página se haya cargado.

```javascript

```

---

* **unload**:

  * Descripción: Se activa cuando se descarga la página o se navega fuera de ella.

  * Uso común: Realizar limpieza o guardar datos antes de que el usuario abandone la página.

```javascript

```

---

* **resize**:

  * Descripción: Sucede cuando la ventana del navegador se redimensiona.

  * Uso común: Ajustar dinámicamente el diseño de la página en respuesta a cambios en el tamaño de la ventana.

```javascript

```

---

* **scroll**:

  * Descripción: Se dispara cuando se realiza un desplazamiento en un elemento.

  * Uso común: Implementar efectos de desplazamiento personalizados o cargar contenido adicional mientras el usuario se desplaza.

```javascript

```

---

* **contextmenu**:

  * Descripción: Ocurre cuando se hace clic con el botón derecho del mouse en un elemento.

  * Uso común: Mostrar menús contextuales o realizar acciones específicas cuando el usuario hace clic con el botón derecho.

```javascript

```

---

* **DOMContentLoaded**:

  * Descripción: Se activa cuando el DOM ha sido completamente cargado, sin esperar a que se carguen imágenes y recursos externos.

  * Uso común: Iniciar scripts o acciones que dependen de la existencia de elementos en el DOM.

```javascript

```

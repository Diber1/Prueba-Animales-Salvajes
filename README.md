Repositorio con el código de:
Prueba / módulo 4 llamado **"Programación avanzada en JavaScript"** de la beca **"Desarrollo de aplicaciones Full Stack Javascript Trainee"** dictado por Desafío Latam.

<h1>REQUISITOS</h1> 

![Requisitos Hoja 1 y 2](./assets/imgs/screenshots/requisitos_uno_dos.webp)
![Requisitos Hoja 3 y 4](./assets/imgs/screenshots/requisitos_tres_cuatro.webp)
![Requisitos Hoja 5](./assets/imgs/screenshots/requisitos_cinco.webp)

PASO a PASO DE LOS **REQUISITOS**:

### 1. Crear clases representadas en el diagrama implementando su herencia indicada:

![Código de las Clases](./assets/imgs/screenshots/code_clases.webp)

### 2. Crear instancias de las clases utilizando los datos del formulario.

Creo la instancia una vez que recibo la data del formulario de manera dinámica como muestro en la línea 5:

![Código Creación de Instancias](./assets/imgs/screenshots/code_instancias.webp)

### 3. Realizar una consulta asíncrona utilizando una función async/await para obtener las imágenes correspondientes a los animales:

Realizo una IIFE [Immediately Invoked Function Expression] que hace fetch a la data almacenada en el archivo **animales.json**. 

Luego de cargada la data, procedo a almacenarla en una variable global.
La variable global se utiliza para crear un objeto que posee la **clase respectiva** a la que pertenece el animal y esta clase se usa para crear la instancia.

![Código Consulta a animales.json](./assets/imgs/screenshots/code_consulta_asincrona.webp)

### 4. Realizar por lo menos una función autoejecutable IIFE

El código en el punto 3 anterior es IIFE

### 5. Dividir el código en módulos

Archivo **modulos.js** el cual posee todas las clases para luego exportarlas y crear objetos en el archivo **script.js**

### 6. Utilizar la manipulación del DOM para mostrar en la tabla los animales registrados con el formulario.

Para mostrar el animal en el canvas izquierdo se crea la función **mostrarAnimalAgregado** la cual posee como parámetro el objeto creado al completar los campos del formulario y al hacer click en el botón **Agregar** del formulario.

![Código Mostrar en Canvas](./assets/imgs/screenshots/code_mostrar_animal.webp)

### 7. Validar que el usuario haya asignado todos los datos del animal antes de que éste sea agregado a la tabla. (Opcional)

Se aplica validación en html no permitiendo el ingreso de valores en blanco ya sea en 'los select' y en el 'textarea' vía atributo **required**

### 8. Devolver el formulario en un estado inicial luego de registrar a cada animal. (Opcional)

Para resetear formulario se crea la función **resetearFormulario** la cual presenta como parámetros los input del formulario los cuales luego sus valores son configurados a una cadena vacía

![Código Reset Formulario](./assets/imgs/screenshots/code_reset_formulario.webp)

### 9. Programar la interacción del botón de audio, en donde deberás reproducir el sonido del animal en el sitio web. (Opcional)

Para reproducir audio de cada animal he creado la función **reproducirSonido**:

![Código Reproducir Sonido](./assets/imgs/screenshots/code_reproducir_audio.webp)

### 10. Mostrar el detalle de cada animal en una ventana modal al ser presionada su imagen. (Opcional)

función **cargarModal** para mostrar Modal, es el siguiente:

![Código Cargar Modal](./assets/imgs/screenshots/code_modal.webp)

Modal operando:

![Screenshot Modal](./assets/imgs/screenshots/screenshot_modal.webp)

Funcionalidad para eliminar los elementos ya agregados al canvas, con la función **controlEliminarAnimal**:

![Código Eliminar Animal](./assets/imgs/screenshots/code_eliminar_animal.webp)

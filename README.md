# Laboratorio-2-HTML-y-CSS
# Universidad Tecnológica de Panamá

## Facultad de Ingeniería en Sistemas

# Laboratorio #2: HTML5 y CSS

**Módulo II: Diseño Web con HTML5 y CSS**

---

## 📌 Descripción

Durante el desarrollo de este laboratorio se realizaron diferentes ejercicios utilizando HTML5, CSS3 y PHP, con el propósito de practicar la estructura y presentación de páginas web.

Se trabajó con tablas, metadatos, hojas de estilo externas, selectores CSS, hipervínculos, etiquetas semánticas y validaciones de formularios. Cada uno de los ejercicios fue probado en el navegador para comprobar su funcionamiento y observar el resultado de los estilos aplicados.

---

## 🎯 Objetivos

- Aplicar la estructura básica de un documento HTML5.
- Utilizar metadatos dentro de la etiqueta `<head>`.
- Organizar información utilizando tablas HTML.
- Aplicar estilos mediante CSS.
- Utilizar clases, identificadores y diferentes selectores CSS.
- Implementar hipervínculos para la navegación web.
- Utilizar etiquetas semánticas de HTML5.
- Aplicar validaciones básicas en formularios.

---

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3
- PHP
- Visual Studio Code
- WampServer
- Servidor web con soporte para PHP

## 🧪 Desarrollo del laboratorio

### Ejercicio 1 - Tabla de gastos de viaje

En este ejercicio se creó una tabla para representar un informe de gastos de viaje. La información se organizó utilizando filas, encabezados y celdas para mostrar los gastos de comida, hotel, transporte y subtotales correspondientes a Buenos Aires y Córdoba.
También se agregaron diferentes metadatos dentro de la etiqueta <head>, incluyendo descripción, palabras clave, autor, configuración para robots y un favicon.
Archivo: Tabla1.html

### Resultado
<img width="705" height="432" alt="Tabla1" src="https://github.com/user-attachments/assets/9a63366d-93e6-4e16-b860-1e200cc284f1" />

### Ejercicio 2 - Tabla con estilos CSS

En este ejercicio se creó una segunda tabla para mostrar información sobre la fecha, unidades vendidas, precio por unidad e ITBMS.
Para modificar su presentación se utilizó una hoja de estilos externa llamada EstlTbls.css. En ella se definieron estilos para la tabla, sus encabezados y las clases modo1 y modo2, permitiendo modificar propiedades como la fuente, tamaño, alineación, bordes, fondo y color del texto.
Archivos: Tabla2.html y Css/EstlTbls.css

### Resultado
<img width="937" height="235" alt="Tabla2" src="https://github.com/user-attachments/assets/4d01c9a2-144a-44ea-97c3-d1c228d1b0f2" />

### Ejercicio 3 - Selectores en párrafos

En este ejercicio se trabajó con un párrafo que contiene elementos <strong> dentro de su contenido.
Mediante la hoja de estilos EstlParrafos.css se utilizó el selector descendiente p strong para aplicar estilos únicamente a los elementos <strong> que se encuentran dentro de un párrafo.
Archivos: Parrafos.html y Css/EstlParrafos.css

### Resultado
<img width="890" height="176" alt="Parrafos" src="https://github.com/user-attachments/assets/8e944022-109e-4573-9010-33924270bf29" />

### Ejercicio 4 - Navegación web con clases e ID

En este ejercicio se creó una sección que contiene un hipervínculo hacia una página externa relacionada con PHP.
Se utilizaron clases CSS como .card-seccion y .link-externo para modificar la apariencia de la sección y del enlace. También se utilizó el identificador #footer-recurso para aplicar estilos específicos al pie de la sección.
El enlace utiliza los atributos target="_blank" y rel="noopener" para abrir el recurso externo en una nueva pestaña.
Archivo: Ejmpl.html

### Resultado
<img width="2555" height="582" alt="Ejmpl" src="https://github.com/user-attachments/assets/9f0f22e9-1bbb-4b76-b253-81449ff78646" />

### Ejercicio 5 - Secciones semánticas de HTML5

En este ejercicio se desarrolló una página utilizando diferentes etiquetas semánticas de HTML5 para organizar correctamente el contenido.
Entre las etiquetas utilizadas se encuentran:
- <header>
- <nav>
- <main>
- <section>
- <article>
- <aside>
- <footer>
La página contiene una cabecera, un menú de navegación, una sección de cursos, artículos independientes, información complementaria y un pie de página.
En el pie de página también se utilizó PHP para mostrar automáticamente el año actual.
Archivo: Secciones.php

### Resultado
<img width="2559" height="1542" alt="Secciones" src="https://github.com/user-attachments/assets/10115f85-3c26-4e88-a9d3-6951a25d48dd" />

### Ejercicio 6 - Validaciones de formulario

En este ejercicio se utilizó un campo de tipo email con el atributo required para comprobar las validaciones proporcionadas por HTML5.
También se aplicaron los selectores CSS input:required:invalid e input:required:valid para modificar el borde del campo dependiendo de si la información introducida cumple o no con el formato solicitado.
Cuando se introduce una dirección de correo inválida, el navegador muestra automáticamente un mensaje indicando el error.
Archivo: Validaciones.html

### Resultado
<img width="749" height="271" alt="Validaciones" src="https://github.com/user-attachments/assets/ae30ab5c-c9cb-4bc1-97e5-7b14837b69b9" />

## 🎨 Selectores CSS utilizados
Durante el laboratorio se trabajó con diferentes formas de seleccionar elementos mediante CSS. Entre ellas se encuentran:
- Selectores de etiqueta.
- Selectores de clase, por ejemplo .card-seccion.
- Selectores de ID, por ejemplo #footer-recurso.
- Selectores descendientes, por ejemplo p strong.
- Pseudoclases como :hover, :valid e :invalid.
Estos selectores permiten aplicar estilos a elementos específicos sin modificar directamente la estructura del documento HTML.

## ▶️ Ejecución del proyecto
Los archivos .html pueden abrirse desde un navegador web o mediante un servidor web.
Para ejecutar correctamente el archivo Secciones.php es necesario utilizar un servidor que tenga soporte para PHP.
También es importante mantener las carpetas Css e img con los mismos nombres utilizados dentro del código para que las hojas de estilo, el favicon y las imágenes puedan cargarse correctamente.

## 📚 Referencias
- Material proporcionado para el Laboratorio #2: HTML5 y CSS3.
- MDN Web Docs - HTML.
- MDN Web Docs - CSS.

## 👤 Información del estudiante
Nombre: Andres Dommar
Asignatura: Desarrollo Web
Universidad: Universidad Tecnológica de Panamá
Instructor:	Ing. Irina Fong

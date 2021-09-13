[`Kotlin-Intermedio`](../Readme.md) > `Sesión 1`

## Sesión 1: Proyecto Android y Views

<img src="../images/android-kotlin.png" align="right" height="120" hspace="10">
<div style="text-align: justify;">

### 1. Objetivos :dart: 

- Reconocer el IDE Android Studio con el que desarrollan aplicaciones móviles.
- Conocer la estructura de un proyecto android y todos los archivos generados por el IDE
- Modificar el proyecto por defecto
- utilizar los controles esenciales para generar interfaces básicas.

### 2. Contenido :blue_book:

---

<img src="images/tools.png" align="right" height="90">

#### <ins>Setup inicial</ins>

Se detalla como crear un proyecto android desde nuestra IDE __Android Studio__, explicando el significado de los distintos campos y opciones para su configuración.

- [**`EJEMPLO 1`**](Ejemplo-01/Readme.md)

---

<img src="images/structure.png" align="right" height="90"> 

#### <ins>Estructura del proyecto</ins>

Con el proyecto nuevo creado, analizamos la estructura del proyecto y explicamos cada sección de esta y su propósito.

- [**`EJEMPLO 2`**](Ejemplo-02/Readme.md)

---

<img src="images/emulator.jpg" align="right" height="90"> 

#### <ins>Emulación de dispositivos</ins>

Ahora que tenemos mayor conocimiento de nuestro proyecto, vamos a configurar un emulador de algún dispositivo móvil para poder correr nuestra aplicación! :iphone:

- [**`EJEMPLO 3`**](Ejemplo-03/Readme.md)
- [**`RETO 1`**](Reto-01/Readme.md)

---

<img src="images/chaomi.png" align="right" height="110"> 

#### <ins>Correr en un dispositivo físico</ins>

Basta de emulaciones, utilizaremos un dispositivo móvil físico para instalar nuestra primera aplicación a nuestro móvil. :iphone:

- [**`EJEMPLO 4`**](Ejemplo-04/Readme.md)

---



### Introducción a Views

Un ___View___ es una clase que representa la base de todos los componentes para la interfaz gráfica y su representación gráfica está delimitada por un rectángulo. La descripción gráfica de un View así como su posición en la pantalla está determinado por un archivo layout en lenguaje XML, y se encuentran distribuidos jerárquicamente en un árbol de Vistas. Un tipo especial de View es el ___ViewGroup___, que es un contenedor de Views y otros ViewGroups con un formato de orden específico. 

<img src="images/view_tree.png" align="right">



<img src="./images/button.png" align="right" height="90"> 

#### <ins>Botones y textos</ins>

Se crearán Vistas desde cero mediante código y las utilizaremos para detonar eventos sencillos como modificar un texto.

- [**`EJEMPLO 5`**](Ejemplo-05/Readme.md)

---

<img src="./images/text_input.png" align="right" height="90"> 

#### <ins>Inputs e imágenes</ins>

Ampliaremos el dominio a ImageViews para la visualización de imágenes y EditTexts para ingresar un texto desde el teclado del móvil, y explorando los eventos que este detona. 

- [**`EJEMPLO 6`**](Ejemplo-02/Readme.md)
- [**`RETO 2`**](Reto-02/Readme.md)

---

<img src="./images/url_image.png" align="right" height="90"> 





### 3. Proyecto (Postwork) :hammer:

Aplica los lineamientos que vienen en esta guía para definir y comenzar el desarrollo de tu proyecto.

- [**`PROYECTO SESIÓN 1`**](Proyecto/Readme.md)



### 4. Temas adicionales 📖

#### <ins>Imágenes mediante URL</ins>

Mostrar imágenes en un ImageView por medio de URLS, utilizando la librería coil disponible en _mavenCentral()_. 

- [**`EJEMPLO 7`**](Ejemplo-07/Readme.md)



<br/>

[`Anterior`](../Readme.md) | [`Siguiente`](../Sesion-02/Readme.md)      

</div>


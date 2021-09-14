# Angular 11

![GitHub last commit](https://img.shields.io/github/last-commit/YanniMartinez/Angular11_Fundamentals?logo=github&style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/YanniMartinez/Angular11_Fundamentals?logo=github&style=for-the-badge)
![GitHub](https://img.shields.io/github/license/YanniMartinez/Angular11_Fundamentals?label=LICENSE&logo=github&style=for-the-badge) <br>
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&logoColor=fff&colorB=555)](https://www.linkedin.com/in/yanni-mart%C3%ADnez-220864207/) <br>

![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![Angular.js](https://img.shields.io/badge/angular.js-%23E23237.svg?style=for-the-badge&logo=angularjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

## Contenido:

* [¿Qué es Angular?](#qué-es-angular)
* [Partes de una App en Angular](#partes-de-una-app-en-angular-más-comunes)
* 

## ¿Qué es Angular?

Hoy en día Angular es una plataforma que puede ejecutarse en: 

* Moviles
* Servidores 
* Navegadores

Está pensado con la filosofía MobileFirst, es decir busca adaptarse a todas las plataformas buscando un rendimiento impresionante. Un aspecto importante es que es una plataforma sostenida por Google y Microsoft.

Siempre estará basado en un módulo principal el cual nos permitirá acceder a diferentes partes de las aplicaciones.

* **Componente:** Es la unidad fundamental dentro de Angular, podemos tener componentes para desplegar información, acciones e incluso componentes embebidos que hacen cada vez más compleja la app.

Cada componente está pensado para estar encapsulado, es decir, si tenemos un componente anidado dentro de otro, no va a poder comunicarse con los componentes en los que está trabajando, así sea dentro de la misma pantalla. 

Para poder comunicar los componentes y toda la aplicación en general, vamos a trabajar con el concepto de servicios, que pueden transportar la información a lo largo de nuestras aplicaciones. 

Un componente tiene un tiempo de vida que va a depender de el tiempo de uso. En muchos casos, en la mayoría de ellos, el componente se va a encontrar funcional y en memoria mientras nosotros lo tengamos en pantalla. Si salimos de una ruta o dejamos de utilizar ese componente, el componente se destruye. 

<div align="center"><img src="descripcion/img/1.png" width="70%"/></div>

El código fuente que se verá a lo largo de este proyecto va a ser un conjunto de archivos en TypeScript, CSS, JavaScript, HTML.

## Partes de una APP en Angular más comunes

* Módulos: Es el punto de entrada, toda app tiene almenos 1 modulo principal. Además permite agrupar las funcionalidades de la app.

<div align="center"><img src="descripcion/img/2.png" width="70%"/></div>

* Componentes: Es un bloque central de la app, basicamente se trata de cualquier elemento interactivo, es el bloque fundamental de construcción por lo que pueden ir anidados. El bloque tiene un ciclo de vida dependiendo de la aplicación. Cuando dejemos de usarlo se elimina haciendo eficiente las aplicaciones de angular respecto a la memoria.

Los componentes pueden comunicarse entre sí con: `inputs, outputs` y `servicios`. Para poder darnos una idea podemos imaginar una página de wikipedia en función de componentes y como podrían llegar a presentarse:

<div align="center"><img src="descripcion/img/3.png" width="70%"/></div>

Si le dieramos un vistazo general a la estructura del código de un componente podría verse de la siguiente manera:

<div align="center"><img src="descripcion/img/4.png" width="70%"/></div>

* Plantillas: En resumen es HTML al cual se le puden inyectar datos, es la parte visual del componente.

<div align="center"><img src="descripcion/img/5.png" width="70%"/></div>


* Servicios: Los servicios principalmente nos sirven para almacenar información y están activos mientras esté viva la aplicación. La unica manera de borrar la información de un servicio es cerrar la aplicación y despues abrirla.

Pueden comunicarse con cualquier componente de la aplicación:

<div align="center"><img src="descripcion/img/6.png" width="70%"/></div>

Si le dieramos un vistazo rápido al código podriamos ver algo como lo siguiente:

<div align="center"><img src="descripcion/img/7.png" width="70%"/></div>

* Directivas: Se trata de un componente sin plantilla. Existen 2 tipos de plantillas; las estructurales las cuales permiten agregar o eliminar elementos. Y las de atributo que pueden cambiar la apariencia o comportamiento de un elemento.

<div align="center"><img src="descripcion/img/8.png" width="70%"/></div>

<div align="center"><img src="descripcion/img/9.png" width="70%"/></div>

Si vieramos un ejemplo básico de código tendriamos lo siguiente:

<div align="center"><img src="descripcion/img/10.png" width="70%"/></div>

Imagenes recopilaras de curso Angular 11 del grande [Carlos_Solís](https://www.linkedin.com/in/carlossolisdavila/?trk=lil_course) y basado en los ejercicios de [este](https://github.com/siddharta1337/Angular-4-Esencial) repositorio.
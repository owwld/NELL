# NELL – Nest Living León 0.1
**Universidad Tecnológica de León** | **Grupo:** LDSM 406

---

## 1. Problemática y Justificación

Los estudiantes foráneos que llegan a León, Guanajuato, enfrentan dificultades para encontrar una vivienda que se adapte a su presupuesto, ubicación y necesidades debido a la información dispersa en redes sociales y sitios no especializados. Asimismo, los arrendadores carecen de una herramienta organizada para publicar sus propiedades y gestionar prospectos. 

**NELL** se desarrolla como una plataforma web accesible que centraliza esta información, reduciendo el tiempo de búsqueda para los estudiantes y brindando a los arrendadores un sistema integral de administración de solicitudes.

---

## 2. Objetivo del Proyecto

Diseñar una propuesta inicial de aplicación web que **facilite a los estudiantes la búsqueda de viviendas** en León, Gto., y permita a los **arrendadores ofrecer sus propiedades de manera organizada**, incorporando funciones de administración y moderación.

---

## 3. Integrantes y Roles

A continuación se definen los roles del equipo, sus responsabilidades y las evidencias de trabajo de cada integrante:

*Nota: Equipo conformado por MARTINEZ MEJIA CHRISTIAN OSWALDO, CARDENAZ OROZCO AARON y ZARAGOZA ALVAREZ JUAN MANUEL.*

| Rol   | Miembro Asignado | Responsabilidades principales |
| :--- | :--- | :--- | :--- |
| **1. Coordinador y gestor del repositorio** | *[ MARTINEZ MEJIA CHRISTIAN OSWALDO]* | Organiza el tablero de tareas y las reuniones breves, administra ramas y pull requests, verifica el cumplimiento del cronograma e integra la versión final en `main`. 

| **2. Diseñador UX/UI** | *[MARTINEZ MEJIA CHRISTIAN OSWALDO ]* | Define la guía de estilo y los wireframes, cuida la consistencia visual y la jerarquía, y desarrolla `css/estilos.css` y los componentes compartidos. 

Desarrollador Front-End EN COLABORACION DE EL EQUIPO MARTINEZ MEJIA CRHISTIAN OSWALDO, ZARAGOZA ALVAREZ JUAN MANUEL Y CARDENAS OROZCO AARON
---

## 4. Módulos del Sistema

1. **Acceso y registro:** Inicio de sesión y creación de cuentas con asignación de roles.
2. **Búsqueda y consulta de viviendas:** Filtros interactivos (precio, ubicación, características) y vista de detalles.
3. **Solicitudes de renta:** Envío, seguimiento y gestión (aceptar/rechazar) de solicitudes.
4. **Gestión de viviendas:** Panel para publicar, editar y administrar el catálogo de propiedades.
5. **Gestión del perfil:** Configuración de información personal según el tipo de cuenta.
   ***SOLO VISTA NADA PROGRAMADO POR NECESIDAD DE UNA BASE DE DATOS***

---
## 5. Tecnologías Utilizadas

* **Frontend:** HTML5 (Semántica) y CSS3 (Flexbox, CSS Variables, Diseño Responsivo).
* **Control de Versiones:** Git y GitHub.
* **Despliegue:** GitHub Pages.
* **Diseño UI/UX:** Prototipado centrado en usabilidad y consistencia visual en Dark Mode.

---

## 6. Instrucciones de Ejecución

**Opción A: Visualización en línea (Recomendada)**
Acceder al enlace oficial del despliegue en GitHub Pages: 
> https://owwld.github.io/NELL/html/index.html

## 7. Declaración de Uso de IA

Para el desarrollo de la interfaz y documentación de este proyecto, se utilizó la herramienta de Inteligencia Artificial *Google Gemini* como asistente técnico colaborativo. El apoyo consistió específicamente en:

* **Estructuración de Navegación HTML:** Adaptación de etiquetas `<button>` a enlaces `<a>` para permitir la navegación directa entre vistas locales (como el paso del Login al Dashboard) sin necesidad de usar JavaScript.
* **Depuración de CSS3:** 
  * Solución de errores de visualización en los menús desplegables (`<select>`), forzando el contraste de texto negro sobre fondo blanco para solucionar la herencia del "Dark Mode".
  * Corrección de estilos de botones para que los enlaces mantuvieran el formato de bloque, ancho completo y sin subrayado.
  * Implementación de una arquitectura de nombres de clases con prefijos (ej. `.inicio-`) para encapsular los estilos y evitar choques entre el CSS del Login y el Dashboard.
* **Soporte en Control de Versiones:** Asesoría con comandos de Git (como `git pull`) para la integración del código del equipo y guía paso a paso para el despliegue del repositorio en GitHub Pages.
* **Documentación:** Apoyo en la redacción, formato Markdown y estructuración de este archivo `README.md`

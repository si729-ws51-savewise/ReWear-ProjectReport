# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo
## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática 
### 1.2.2.Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3 Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas
## 1.3. Segmentos objetivo

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores
## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. As-is Scenario Mapping

# Capútlo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Mapping
## 3.4. Product Backlog

# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
### 4.7.2. Class Dictionary

## 4.8. Database Design
### 4.8.1. Database Diagram

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
En esta sección se detallan las decisiones y normas que posibilitarán que el equipo garantice la coherencia a lo largo de todo el ciclo de vida de desarrollo de nuestra solución.
### 5.1.1. Software Development Environment Configuration

En la siguiente sección, vamos a describir con precisión los programas y plataformas que empleamos para llevar a cabo nuestro proyecto ReWear

GitHub: En este espacio, estableceremos el repositorio para llevar a cabo los progresos de nuestra Startup. Asimismo, facilita una supervisión más efectiva del trabajo en equipo, ya que permite visualizar el progreso de cada miembro mediante los commits.
https://github.com/ 

Git: Sistema de gestión de versiones más popular y es necesario para llevar a cabo los commits en Github.
https://git-scm.com/downloads 

Discord: Esta es una herramienta de mensajería que facilita la creación de grupos con personas seleccionadas. También ofrece funciones como llamadas, videollamadas, carga de archivos, entre otras. Utilizamos esta aplicación para comunicarnos eficazmente, coordinar tareas y resolver preguntas en grupo.
https://discord.com/download 

Visual Studio Code: Se trata de un editor de código que posibilita la programación en varios lenguajes y ofrece la posibilidad de ampliar sus capacidades mediante extensiones, lo que mejora la experiencia de trabajo en equipo.
https://code.visualstudio.com/download 

Figma: Es una herramienta esencial en nuestro conjunto de software para el desarrollo de nuestro startup. Esta plataforma nos permite colaborar de manera efectiva en el diseño y prototipado de nuestras aplicaciones y productos. Con Figma, podemos crear y compartir diseños en tiempo real, lo que facilita la revisión y la retroalimentación por parte de todo el equipo. Además, esta herramienta nos ayuda a mantener una coherencia visual en nuestros proyectos, lo que es fundamental para la experiencia del usuario. 
https://www.figma.com/

UxPressia: Es una plataforma en línea especializada en el mapeo de la trayectoria del cliente. Nos ayuda a crear mapas de impacto y perfiles de usuario, como User Personas, Empathy Maps y Journey Maps. 
https://uxpressia.com/

Webstorm: Es un entorno de desarrollo de JetBrains, una empresa especializada en software, orientado al desarrollo web en JavaScript. Esta herramienta proporciona facilidades para probar sitios web en navegadores como Google Chrome. En nuestro proyecto, utilizaremos webstorm para trabajar con lenguajes como HTML, CSS y JavaScript.
https://www.jetbrains.com/webstorm/

### 5.1.2. Source Code Management

En la siguiente sección, presentaremos los medios que usaremos para el seguimiento del código de ReWear, usaremos GitHub como plataforma ysistema de control de versiones.
Repositorio en GitHub para el Landing Page:
[Repositorio Landing Page](https://github.com/si729-ws51-savewise/ReWear-LandingPage)

Repositorio en GitHub para el registro de Acceptance Test Files:
[Repositorio Acceptance Test Files](https://github.com/si729-ws51-savewise/ReWear-Feature)

En este momento detallaremos la aplicación de GitFlow como un WorkFlow para el control de versiones en el desarrollo de ramas o branches.

**Main Branch:**
Este es nuestro branch principal y la raíz para nuestras ramificaciones. Aquí se mostrará el estado actual del código fuente, que posteriormente será enviado a producción. Una vez finalizadas las tareas en las otras ramas, se integrarán en el producto final. 

**Develop Branch:**
En esta rama se encuentra el código fuente más actualizado y podemos observar el estado actual de los últimos cambios realizados en el desarrollo. Todos los cambios que estén listos para ser publicados se fusionarán con la rama principal (main Branch) junto con una etiqueta que identifica el número de la publicación. Asimismo, cada modificación efectuada en esta rama será posteriormente fusionada de nuevo con la rama principal como una nueva versión del producto.

**Feature Branches:**
Estas ramas serán empleadas para crear nuevas funciones destinadas a una próxima versión. Se derivarán del develop Branch y, una vez completado el desarrollo, se fusionarán de nuevo en la misma rama develop. En caso de que la función no obtenga resultados satisfactorios, se descartará. Se seguirá una convención de nomenclatura secuencial para nuestros Feature Branches, como por ejemplo: Feature001, Feature002, Feature003, y así sucesivamente. Se exceptúan las palabras master, develop, release y hotfix.

**Release Branches:**
Estas ramas facilitan la preparación de nuestro proyecto para la última fase de pruebas o testing, permitiéndonos corregir bugs y garantizar la optimización de la interfaz antes de lanzar la versión definitiva. Se derivan del develop y se fusionan nuevamente en él para indicar una "próxima versión".

**Convenciones Release Branches:**

| Release | Descripción |
|-------------|-------------|
| Release 0.1.0     | Comenzar con la versión del desarrollo inicial de nuestro landing page. |
| Release 1.0.0     | Se realiza la implementación de la API pública. |
| Release 1.1.0     | Se ha implementado una nueva funcionalidad en la API pública que es compatible con versiones anteriores.  |
| Release 1.1.1     | Se corrigen bug o errores compatibles con las versiones anteriores. |
| Release 2.0.0     | Se implementan funciones incompatibles con versiones anteriores en la API pública. |

**Hotfix branches:**
Son utilizadas para abordar rápidamente problemas o errores en la versión actual de producción. Estas ramas se crean a partir de la main Branch. Una vez solucionado el problema se fusionará.

| Hotfix | Descripción |
|-------------|-------------|
| Hotfix 1.1.0 | Alguna funcionalidad de la API pública esta marcada como obsoleta. |
| Hotfix 1.1.1 | Se introduce nuevas funciones o metodos para la corrección de errores compatibles con versiones anteriores |

**Conventional Commits:**
Es una convención para escribir mensajes de confirmación en un repositorio de control de versiones como Git. Esta convencion tiene como objetivo estandarizar y hacer mas comprensibles los mensajes de confirmación.

La estructura de un mensaje de confirmacion es la siguiente:

    <type>[optional scope]: <description>
    [optional body]
    [optional footer(s)]

**fix:** usamos este commit del tipo fix cuando se arregla un bug que afecta al usuario.

**feat:** usamos este commit del tipo feat cuando se agrega una nueva característica para el usuario.

**BREAKING CHANGE:** Es un commit que tiene un como footer (como se vió en la estructura) **BREAKING CHANGE:** o agrega un ! esto con el fin de comunicar un cambio grande realizado en el API.

También se permiten distintos tipos de **feat:** y **fix:** basados en la convención Angular estos son:

**perf:** Cambios que mejoran el rendimiento del sitio.
**build:** Para los cambios en el sistema de build.
**ci:** Para los cambios en la integración continua.
**docs:** Para cambios en la documentación.
**refactor:** Cuando se realiza una refactorización del código como cambios de nombre de variables o funciones.
**style:** Para los cambios de formato, tabulaciones, espacios o puntos y coma, etc;
**test:** Cuando se añade tests o refactoriza uno existente.
Por otro lado, también se pueden proporcionar footers que no sean **BREAKING CHANGE:** <description> y poder seguir otra convención similar.

### 5.1.3. Source Code Style Guide & Conventions
Para el desarrollo de los prodcutos del proyecto se usarán las siguientes nomenclaturas:

- Declaración del tipo de documento.
En nuestro archivo index.html en la primera línea de código colocaremos la instrucción ```<!DODCTYPE html>```
- Atributo Lang
Con este atributo podemos permitir que los motores de búsqueda puedan identificar y configurar nuestro idioma. ```<html lang="es">```
- Se dara uso a las etiquetas ```<body></body>  <header></header> <section> </section>  <nav></nav>  <p></p>  <img/> <iframe></iframe>  <h1></h1> <h2></h2>```
- Para distribuir texto en parrafos utilizatemos la siguiente etiqueta ```<p> Somos <p>```
- Implementaremos la etiqueta meta data

Esta nos servirá para que, en nuestro documento HTML, pueda proporcionar información codificada a navegadores y motores de búsqueda acerca de nuestra página web

Para las convenciones de nomenclatura en CSS:

- En nuestra codificación de nuestro proyecto, usaremos las minusculas para nombrar estos archivos con el fin de no tener conflictos con los nombres de nuestros archivos html.
- Se evitará el uso de las tildes para los nombres de estas.
- Se abreviarán los nombres con el fin de tener una mejor practicidad.

Convenciones para la nomenclatura en JavaScript:
- Paquetes
El prefijo del nombre en un paquete se escribirá con el código ASCII. El nombre del paquete será escrito en minúsculas y debe ser uno de los nombres de dominio de alto nivel. com.sun.eng
- Clases
Usaremos palabras simples. En caso sea una sola palabra todo irá en minuscula, Por otro lado, si el nombre fuese una frase compuesta usaremos el tipo 'StudlyCaps'; es decir, cada inicio de una palabra del nombre compuesto va en mayúscula. Así, diferenciarlo de otras estructuras. Usaremos palabras completas, sin abreviatura. class PetOwner;
- Variables 
Usaremos el camelCase para nombrar a nuestras variables. Además se evitará el uso de los caracteres especiales con el fin de evitar posibles errores en nuestro proyecto.
- Constantes
Seran nombradas en mayúsculas. En caso el nombre sea compuesto se usará un guion abajo como separador (_) .
**Archivos .Feature**
En nuestro proyecto, utilizaremos el lenguaje Gherkin para definir y comprender las características. Este lenguaje nos permitirá describir nuestras historias de usuario siguiendo la estructura proporcionada.

"Feature, Scenario, Given, When, Then, Examples".

Comprador

US01:

    Feature: Sección Registro en la aplicación
    Como usuario
    Quiero poder crear una cuenta segura con mi correo electrónico y contraseña
    Para acceder a la aplicación.

    Scenario Outline: Se valida el registro del usuario
    Given que el usuario ha descargado la aplicación y no tiene una cuenta creada
    And el usuario ha ingresado a la sección de Login de la aplicación
    When el usuario selecciona la opción de "Crear cuenta"
    Then se le pide que ingrese su <correo electrónico> y una <contraseña> segura de al menos 8 caracteres.
    And el sistema muestra un <mensaje> que el usuario pudo registrarse correctamente

    Examples: INPUT
        | Usuario  | Correo Electrónico   | Contraseña  |
        | Usuario1 | usuario1@example.com | Password123 |
        | Usuario2 | usuario2@example.com | SecurePass1 |
        | Usuario3 | usuario3@example.com | Secret12345 |
    Examples: OUTPUT
        | mensaje |

US02:

    Feature: Sección Inicio de sesión en la aplicación
     Como comprador registrado
     Quiero iniciar sesión en la aplicación 
     Para acceder a mi cuenta.

    Scenario Outline: Se valida el Inicio de sesión del usuario
    Given el usuario se haya registrado
    And el usuario ha ingresado a la sección de Login de la aplicación
    When el usuario selecciona la opción de "Iniciar Sesión"
    Then se le pide que ingrese su <correo electrónico> y <contraseña>
    And el sistema muestra un <mensaje> que el usuario pudo ingresar correctamente

    Examples: INPUT
        | Usuario  | Correo Electrónico   | Contraseña  |
        | Usuario1 | usuario1@example.com | Password123 |
        | Usuario2 | usuario2@example.com | SecurePass1 |
        | Usuario3 | usuario3@example.com | Secret12345 |
    Examples: OUTPUT
        | mensaje |

US03:

    Feature: Sección recuperacion de contraseña en la aplicación
    Como comprador registrado
    Quiero poder restablecer mi contraseña si la olvido
    Para acceder a mi cuenta.

    Scenario Outline: Se valida el restablecimiento de contraseña de usuario
    Given el usuario no se acuerde su contraseña
    And el usuario ha ingresado a la sección de Login de la aplicación
    When el usuario selecciona la opción de "Reset Password"
    Then se le pide que ingrese su <codigo> y <contraseña nueva>
    And el sistema muestra un <mensaje> que el usuario pudo restablecio su contraseña correctamente

    Examples: INPUT
        | Codigo    |  Contraseña  |
        | 1a2b      |  Password123 |
        | 2a2c      |  SecurePass1 |
        | a11z      |  Secret12345 |
    Examples: OUTPUT
        | mensaje |

US04:

    Feature: Sección recuperacion de contraseña en la aplicación
    Como comprador 
    Quiero poder seleccionar productos 
    personalizarlos (talla y color).

    Scenario Outline: Se valida el restablecimiento de contraseña de usuario
    Given el usuario no se acuerde su contraseña
    And el usuario ha ingresado a la sección de Login de la aplicación
    When el usuario selecciona la opción de "Reset Password"
    Then se le pide que ingrese su <codigo> y <contraseña nueva>
    And el sistema muestra un <mensaje> que el usuario pudo restablecio su contraseña correctamente

    Examples: INPUT
        | Codigo    |  Nueva Contraseña  |
        | 1a2b      |  Password123 |
        | 2a2c      |  SecurePass1 |
        | a11z      |  Secret12345 |
    Examples: OUTPUT
        | mensaje |

Vendedores

US01:

    Feature: Sección Publicación de Productos en la aplicación
    Como vendedor
    Quiero poder publicar productos en la plataforma, incluyendo información detallada como talla, color y marca
    Para tener mejor visibilidada en la aplicación.

    Scenario Outline: Se valida la publicación de productos del usuario
    Given el usuario tenga productos para publicar
    And el usuario ha ingresado a su cuenta
    When el usuario selecciona la opción de "Publish Product"
    Then se le pide que ingrese los detalles del producto <talla>, <color> y <marca>
    And el sistema muestra un <mensaje> de publicacion con exito.

    Examples: INPUT
        | talla    |  color  |   marca  |
        |   M      |  rojo  |  Nike  |
        |   S     |  coral  |  Adidas  |
        |   L     |  blue   |  AYNI  |
    Examples: OUTPUT
        | mensaje |

US02:

    Feature: Sección Edición de Producto en la aplicación
    Como vendedor 
    Quiero poder editar la información de productos que he publicado previamente
    Para poder actualizar los datos del producto.

    Scenario Outline: Se valida la Edición de Producto del usuario
    Given el usuario tenga productos para editar
    And el usuario ha ingresado a su panel
    When el usuario selecciona la opción de "Editar Producto"
    Then se le pide que ingrese los detalles a editar del producto <talla>, <color> y <marca>
    And el sistema muestra un <mensaje> de publicacion con exito.

    Examples: INPUT
        | talla    |  color  |   marca  |
        |   M      |  rojo  |  Nike  |
        |   S     |  coral  |  Adidas  |
        |   L     |  blue   |  AYNI  |
    Examples: OUTPUT
        | mensaje |

US03

    Feature: Sección Eliminacion de Producto en la aplicación
    Como vendedor 
    Quiero poder Eliminacion la información de productos que ya no estén disponibles en mi inventario.

    Scenario Outline: Se valida la Edición de Producto del usuario
    Given el usuario tenga productos con 0 de stock
    And el usuario ha ingresado a su panel
    When el usuario selecciona la opción de "Eliminar Producto"
    Then se le pide que selecciones el producto a eliminar confirmar a eliminacion.
    And el sistema muestra un <mensaje> de producto eliminado con exito.

    Examples: INPUT
        | Selecicon de Producto    |
    Examples: OUTPUT
        | mensaje |


### 5.1.4. Software Deployment Configuration
Para el despliegue de nuestra landing page usamos GitHub donde primero realizamos la creación de nuestro repositorio donde se desarrollará el código de nuestra landing page

![creation](https://i.ibb.co/HPgWqRD/create.png)

Una vez creado nuestro repositorio, creamos las ramas necesarias para que cada integrante pueda trabajar sin complicaciones en las tareas asignadas.
![branches](https://i.ibb.co/TLW1WTv/branches.png)

En el apartado de build and deployment selecciónamos la rama que queremos que se despliegue, en nuestro caso sería la rama develop, en la cual se unirán todas las ramas creadas.

![deploy](https://i.ibb.co/2W6503w/deploy.png)

Le damos a guardar y veremos el despliegue de nuestra landing en Github Pages, nos generará un link con el cual podemos acceder a nuestro landing page.

![landing](https://i.ibb.co/Pw99FWz/result.png)

**Link de la Landing Page desplegada:**  https://si729-ws51-savewise.github.io/ReWearLanding/

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
En esta sección, se detalla el proceso completo de implementación y despliegue de la Landing Page. Se aborda de manera grupal, detallando planificación del avance desde la concepción del Product Backlog hasta la puesta en producción de este componente en nuestro proyecto.
#### 5.2.1.1. Sprint Planning 1
En el Sprint Planning 1 se planificó para la elaboración de la landing page del proyecto. Mediante una reunión grupal se determinaron y acordaron distintos puntos para su elaboración

|             Sprint #             |                                                                                                                               Sprint 1                                                                                                                                | 
|:--------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|  **Sprint Planning Background**  |                                                                                                                                                                                                                                                                       |
|               Date               |                                                                                                                              	2023-09-22                                                                                                                              |
|               Time               |                                                                                                                               08:00 PM	                                                                                                                               |
|             Location             |                                                                                                                          	Virtual (Discord)                                                                                                                           |
|           Prepared By            |                                                                                                                          	  Daniel Valverde                                                                                                                           |
|            Attendees             |                                                                                 Fabrizio / Juan Jesús Calisaya Sánchez / Josue Daniel Valverde Lopez / Sebastian Jesus              	                                                                                 |
|    Sprint 1 - Review Summary     | Se asignaron tasks para los integrantes del grupo para la elaboración de la landing page. Se acordó que la fecha de entrega de los tasks será hasta el 23 de septiembre de 2023                                                                                     	 |
| Sprint 1 - Retrospective Summary |                              los miembros se mostraron conformes con las tareas y fechas asignadas en el sprint planning 1                                                                                                             	                              |
|  **Sprint Goal & User Stories**  |                                                                                                                                                                                                                                                                       |
|          Sprint 1 Goal           |                                         Despliegue de la landing page en su totalidad, en un lapso de 3 días                                                                                                               	                                          |
|        Sprint 1 Velocity         |                                                                                                  15                                                                	                                                                                                  |
|       Sum of Story Points        |                                                                                                                  4                                	                                                                                                                   |

#### 5.2.1.2. Sprint Backlog 1
El objetivo principal del Sprint 1 es lograr la implementación de la landing page del proyecto, a continuación se muestra una tabla en la cual se presentan las historias de usuario y las tareas que se desprenden de cada una. Se destaca en importancia la asignación y el estado de la tarea.

<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td align="center" colspan="7"> <strong>Sprint 1</strong> </td>
  </tr>

   <tr>
    <td align="center" colspan="2"> <strong>User Story</strong></td>
    <td align="center" colspan="6"> <strong>Work-item/Task</strong></td>
  </tr>
  <tr>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title</strong></td>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title</strong></td>
    <td align="center"> <strong>Description</strong></td>
    <td align="center"> <strong>Estimation (Hours)</strong></td>
    <td align="center"> <strong>Assigned To</strong></td>
    <td align="center"> <strong> Status (To-do/In-Process/To-Review/Done) </strong></td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <td rowspan="2" align="center"> US00 </td>
    <td rowspan="2" align="center">  </td>
    <td align="center">  </td>
    <td align="center"> </td>
    <td align="justify"> </td>
    <td align="center">  </td>
    <td align="center">   </td>
    <td align="center"></td>
  </tr>

  <tr>
    <td align="center"> </td>
    <td align="center"> </td>
    <td align="center"> </td>
    <td align="center"> </td>
    <td align="center">  </td>
    <td align="center"></td>
  </tr>


</table>

#### 5.2.1.3. Development Evidence for Sprint Review
En esta sección presentamos la evidencia del desarrollo de la landing page detallando las ramas usadas y los commits realizados por los integrantes del grupo

|                      Repository                      |                      Branch                      |                            Commit Id                            |            Commit Message            | Commit Message Body |  Committed on (Date)   |
|:----------------------------------------------------:|:------------------------------------------------:|:---------------------------------------------------------------:|:------------------------------------:|:-------------------:|:----------------------:|
| https://github.com/si729-ws51-savewise/ReWearLanding |                       main                       |          f8efd04cc711be91eeff1927da7c7f72292b539e  	 	          |  feat(main): added structure   	 	   |    ---      	 	     | 09/09/2023        	 	  |
|                                                      |                    develop  	                    | 7120bd2d162272ffffb218567e71f7dc3e1c4aaf                   	 	  | feat(develop): added images     	 	  |    ---       	 	    | 27/09/2023         	 	 |
|                                                      |            feature/update-header    	            | d190ae154f0d989c0ae6dc52ee68e1f293186af1                   	 	  |     feat: update header     	 	      |    ---       	 	    | 27/09/2023         	 	 |
|                                                      |       feature/create-section-shoppers   	        |  0e9592d20687e64601bdce1f9e8cf305e3e9e457                  	 	  | feat:create section-shoppers     	 	 |    ---       	 	    | 27/09/2023         	 	 |
|                                                      | feature/create-section-retailers               	 |  7d05ede1af6f518bc63ee101b93841590727b859                  	 	  | feat: added section retailers    	 	 |    ---       	 	    | 27/09/2023         	 	 |
|                                                      |         feature/header-style          	          | 75987cc075721dd482fcdec2c2a87434f9a7ed12                   	 	  |   feat:added header-styles    	 	    |    ---       	 	    | 27/09/2023         	 	 |
|                                                      |      feature/responsive-style             	      | 7a23faedcc721797877865ffa440283d5d79a457                   	 	  |  feat:added responsive-style    	 	  |    ---       	 	    | 27/09/2023         	 	 |
|                                                      |    feature/comment-section                 	     | 9ba0620f8d9e2e5896ec299c1f29a2e061d96ca2                   	 	  |  feat:added comment section    	 	   |    ---       	 	    | 27/09/2023         	 	 |
|                                                      |   feature/contact-section                    	   | 1c34c9586bbab20273b1f087fc03dae8bf380e86                    	 	 |  feat:added contact section     	 	  |    ---       	 	    | 27/09/2023         	 	 |
|                                                      |   feature/segments-style                     	   | be2d0aca6b1c7ca59a7df1f8e5e5b1196649cf6d                    	 	 |  feat: added segments style     	 	  |    ---       	 	    | 27/09/2023         	 	 |
|                                                      |    feature/contact-style                    	    | f2b0ce1337a8cfe34954a1959c9f75804b2c4b55                    	 	 |   feat:added contact styles    	 	   |    ---       	 	    | 27/09/2023         	 	 |
|                                                      |   feature/footer-section                    	    | 2741a80d93784cb1dcccf60338910aa7f6a1d61b                    	 	 | feat: added footer section      	 	  |    ---       	 	    | 27/09/2023         	 	 |
|                                                      |      feature/toggle-menu                  	      | 1a77b840f297168be7d037128719eb813016026a                   	 	  |   feat: added toggle menu     	 	    |    ---       	 	    | 27/09/2023         	 	 |
|                                                      |     feature/footer-style                   	     | b08dab619976d469f045046a1df05651f3b81818                   	 	  |  feat: added footer styles     	 	   |    ---       	 	    | 27/09/2023         	 	 |

#### 5.2.1.4. Testing Suite Evidence for Sprint Review
En esta sección presentamos los Acceptance Tests automatizados  utilizando el lenguaje Gherkin.
Gherkin Facilita la especificación del funcionamiento del software sin entrar en los detalles de su implementación, al mismo tiempo que posibilita la documentación de las funcionalidades mientras creamos pruebas automáticas.

|                      Repository                       | Branch |                   Commit Id                    |           Commit Message            | Commit Message Body |  Committed on (Date)   |
|:-----------------------------------------------------:|:------:|:----------------------------------------------:|:-----------------------------------:|:-------------------:|:----------------------:|
| https://github.com/si729-ws51-savewise/ReWear-Feature | master | c8176225d3334c64bf24502bdd3c1eedacfb6257   	 	 | features Gherkin implemented    	 	 |    ---      	 	     | 09/09/2023        	 	  |


#### 5.2.1.5. Execution Evidence for Sprint Review
En este Sprint 1 se logró la implementación de la landing page de ReWear, los miembros cumplieron con las tareas asignadas durante el sprint y gracias a esto se concretó con su implementación y despliegue. A continución, una vista de las principales pantallas de la landing page.

Es fundamental resaltar que el principal propósito de la Landing Page es transformar a los visitantes en potenciales clientes o usuarios regulares de nuestro servicio. Para alcanzar este objetivo, empleamos llamados a la acción (Call To Action) que los dirigen hacia nuestra aplicación web. A continuación, se muestran imágenes de la Landing Page

En el home presentamos una imagen de fondo referente, se muestran opciones de navegación y un botón call to action 'Rewear web', para acceder directamente a la aplicación.

![home](https://i.ibb.co/MDGhGt6/home-rewear.png)

En esta siguiente sección mostramos los beneficios para el sector de 'Compradores', además agregamos otro call to action button 'Shop Now!', el cual dirige directamente a los compradores a la vista correspondiente para este segmento en la aplicación web.

![shopper](https://i.ibb.co/1rsQkCY/shoppers-rewear.png)

En esta sección mostramos los beneficios para el sector de 'Vendedores', además agregamos otro call to action button 'Start Now!', el cual dirige directamente a los vendedores a la vista correspondiente para este segmento en la aplicación web.

![retailer](https://i.ibb.co/By9jJLK/retailers-rewear.png)

La siguiente sección que mostramos es también importante para llamar la atención de los usuarios de los dos segmentos, ya que mostramos a través de comentarios las calificaciones que recibe nuestra aplicación web.

![comments](https://i.ibb.co/K08wx4Q/comments-rewear.png)

Por último añadimos una sección de contacto, con datos de la startup y la opción de enviar un mensaje directamente a la startup. En el footer agragamos enlaces a las redes sociales de la startup, también enlaces correspondientes a los términos y política de la startup

![contact](https://i.ibb.co/qp9KhRH/contact-rewear.png)

Presentación de landing en video (enlace): https://n9.cl/presentacion_landing 

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
En este primer sprint no se configuraron servicios en el proyecto

#### 5.2.1.7. Software Deployment Evidence for Sprint Review
Para la implementación de nuestra página, optamos por utilizar GitHub Pages. En este proceso, creamos un repositorio en GitHub donde gestionamos el control de versiones. En la sección de Configuración, publicamos el proyecto almacenado en la rama "develop" donde se unieron las demás  ramas.

**Link de la Landing Page desplegada:**  https://si729-ws51-savewise.github.io/ReWearLanding/

#### 5.2.1.8. Team Collaboration Insights during Sprint
En esta entrega, nuestra meta principal fue la implementación de la Landing Page. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub, Visual Studio Code, WebStorm, HTML, CSS y JavaScript. A continuación, vamos a presentar los diagramas que representan los commits realizados por cada miembro del equipo

![pull](https://i.ibb.co/vvHF9Mm/pull.png)

En la imagen se evidencia el gráfico de barras de la cantidad de commits realizadas por cada uno de los integrantes del equipo.

![commits](https://i.ibb.co/MkDxK4T/commits.png)

Los siguientes gráficos ofrecen una representación visual de las clonaciones registradas en nuestro repositorio, junto con la fecha en que cada una de estas acciones se llevó a cabo. Además, se presenta información sobre la cantidad de visitantes que ha tenido el repositorio de nuestro equipo a lo largo del tiempo.

![traffic](https://i.ibb.co/RzH08wW/traffic.png" )

A continuación se muestra una línea de tiempo con el flujo de las ramas del proyecto, finalmente se unen todas las ramas en develop para el despliegue de la landing page.

![network](https://i.ibb.co/S3yZGQV/network.png)

## 5.3. Validation Interviews
### 5.3.1. Diseño de Entrevistas

### 5.3.2. Registro de Entrevistas
### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product
 
# Conclusiones
## Conclusiones y recomendaciones.
## Video About-the-Team.
# Bibliografía
# Anexos

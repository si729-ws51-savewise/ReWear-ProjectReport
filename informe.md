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

Para el desarrollo del Landing Page se usarán las siguientes nomenclaturas:

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
- Clases
- Variables
- Constantes

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

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
#### 5.2.1.2. Sprint Backlog 1
#### 5.2.1.3. Development Evidence for Sprint Review
#### 5.2.1.4. Testing Suite Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint

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

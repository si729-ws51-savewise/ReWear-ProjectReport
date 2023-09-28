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

**Segmento: Compradores**
Escenario To Be del segmento compradores
![to-be-compradores](https://i.ibb.co/sst3qMw/to-be-compradores.png)

**Segmento: Vendedores**
Escenario To Be del segmento vendedores
![to-be-vendedores](https://i.ibb.co/q10QBVJ/to-be-vendedores.png")

## 3.2. User Stories
Para elaborar user stories que pertenecen a un epic. A continuación, las epics que consideramos como equipo:

| Código | Título | Epic | 
|--------|--------|------|
|EP01|Autenticación y Registro de usuarios|Como usuario de la plataforma quiero registrarme en la página web para poder acceder a los beneficios de la aplicación.|
|EP02|Vistas y Control de la Pagina Web |Como posible usuario quiero poder desplazarme por la página web para visualizar todas las herramientas que me brinda. |
|EP03|Gestión de Eventos |Como usuario quiero realizar la gestión de eventos con todas las herramientas para poder publicar y modificar futuros eventos. |
|EP04|Compra y Manejo de Productos |Como usuario quiero poder comprar y manejar las distintas herramientas de los productos para poder realizar una compra exitosa. |
|EP05|Gestión de herramientas de vendedor |Como usuario vendedor quiero poseer herramientas de gestión para que me ayuden al manejo de mis productos. |
|EP06|Manejo de información del usuario |Como usuario quiero poder tener un completo manejo de mi información para poder visualizar y actualizar mis datos. |
|EP07|Sistema de comunicación en el aplicativo |Como usuario quiero un sistema de comunicación para resolver posibles dudas o problemas.  |

A continuacion, la realizacion de los user stories con sus criterios de aceptacion con escenarios e ID de Epica:

| ID de Historia de Usuario | Título | Descripción | Criterios de Aceptación con Escenarios | ID de Épica |
|--------------------------|--------|-------------|----------------------------------------|-------------|
| US01 | Registro de usuarios compradores en la plataforma | Como usuario comprador que realiza compras de prendas de segunda mano no registrado deseo crearme una cuenta para poder acceder a las características de la app. | **E01: Registro exitoso** **CA01:** Dado que me encuentro en el formulario de registro de cuenta. Cuando ingrese un correo electrónico no registrado, una contraseña válida (mayor o igual a 8 caracteres que incluyan al menos una letra y un número) junto a la confirmación de contraseña. Y presione el botón “Registrarse” Entonces la aplicación me mostrará un mensaje indicando que estoy registrado, pero que tengo que confirmar mi cuenta abriendo el enlace de confirmación enviado a mi correo electrónico. **E02:** **Registro inválido CA02:** Dado que me encuentro en el formulario de registro de cuenta Cuando complete mis datos, pero alguno o muchos de ellos sean incorrectos. Y presione el botón “Registrarse” Entonces la aplicación me mostrará un mensaje relacionado con la solución para el error o errores cometidos. **E03: Verificación de la cuenta** **CA03:** Dado que el usuario recibe el código de verificación en su correo electrónico. Cuando ingresa el código en el apartado de verificación. Y pulsa en el botón “OK”. Entonces la aplicación web lo redirige al apartado de inicio.| EP01: Autenticación y Registro de Usuarios |
| US02 | Registro de usuarios vendedores en la plataforma  | Como vendedor de prendas de segunda mano no registrado en la aplicación, deseo crearme una cuenta, para poder acceder a las características de la aplicación | **E01: Registro exitoso** **CA01:** Dado que se encuentra en el formulario de registro de cuenta para vendedores. Cuando ingresa su correo electrónico asociado (no registrado), y una contraseña válida (mayor o igual a 8 caracteres que incluyan al menos una letra y un número) junto a la confirmación de contraseña (la misma contraseña escrita correctamente). Y presiona el botón “Registrarse”. Entonces la aplicación le mostrará un mensaje diciéndole que está registrado, pero que tiene que confirmar la cuenta abriendo el enlace de confirmación enviado a su correo electrónico. **E02: Registro invalido** **CA02:** Dado que se encuentra en el formulario de registro de cuenta para empresas. Cuando completa los datos requeridos, pero alguno o muchos de ellos son incorrectos. Y presiona el botón “Registrarse”. Entonces la aplicación le muestra un mensaje relacionado con la solución para el error o errores cometidos. **E03: Verificación de la cuenta** **CA03:** Dado que el usuario recibe el código de verificación en su correo electrónico. Cuando ingresa el código en el apartado de verificación. Y pulsa en el botón “OK”. Entonces la aplicación móvil lo redirige al apartado de inicio.| EP01: Autenticación y Registro de Usuarios |
| US03 | Inicio de sesión de usuarios compradores en la plataforma | Como usuario comprador que realiza compras de prendas de segunda mano registrado en la aplicación, deseo iniciar sesión en la aplicación. | **E01: Inicio de sesión exitosa.** **CA01:** Dado que se encuentra en el formulario de inicio de sesión para compradores. Cuando ingresa su correo electrónico y contraseña registrada en la aplicación. Y presiona el botón “Ingresar”. Entonces la aplicación enviará el formulario, se verificará la autenticidad de las credenciales y se redirige al usuario al panel de comprador. **E02:** Inicio de sesión con credenciales incorrectas. **CA02:** Dado que se encuentra en el formulario de inicio de sesión para compradores. Cuando ingresa su correo electrónico y la contraseña registrada en la aplicación de manera errónea. Y presiona el botón “Ingresar”. Entonces la aplicación enviará el formulario, se verificará que las credenciales ingresadas son erróneas y les saldrá un recuadro donde señale el error cometido con el mensaje de “Credenciales incorrectas”. |EP01: Autenticación y Registro de Usuarios |
| US04 |Inicio de sesión de usuarios vendedores en la plataforma | Como usuario vendedor de prendas de segunda mano registrado en la aplicación, deseo iniciar sesión en la aplicación. | **E01: Inicio de sesión exitosa** **CA01:** Dado que se encuentra en el formulario de inicio de sesión para vendedores. Cuando ingresa su correo electrónico y contraseña registrada en la aplicación. Y presiona el botón “Ingresar”. Entonces la aplicación enviará el formulario, se verificará la autenticidad de las credenciales y se redirige al usuario al panel de vendedor. **E02: Inicio de sesión con credenciales incorrectas** **CA02:** Dado que se encuentra en el formulario de inicio de sesión para vendedores. Cuando ingresa su correo electrónico y la contraseña registrada en la aplicación de manera errónea. Y presiona el botón “Ingresar”. Entonces la aplicación enviará el formulario, se verificará que las credenciales ingresadas son erróneas y les saldrá un recuadro donde señale el error cometido con el mensaje de “Credenciales incorrectas”.| EP01: Autenticación y Registro de Usuarios |
| US05 | Recuperación de contraseña para usuarios registrados | Como usuario registrado en la página web, deseo poder restablecer mi contraseña si la olvido. | **E01: Recuperación de contraseña exitosa** **CA01:** Dado que se encuentra en el formulario de inicio de sesión para usuarios. Cuando acceda a la opción de “Olvide mi contraseña”, deberá proporcionar su correo electrónico. Y presiona el botón de “Enviar”. Entonces la aplicación enviara un enlace de restablecimiento de contraseña por correo electrónico. **E02: Recuperación de contraseña fallida** **CA02:** Dado que se encuentra en el formulario de inicio de sesión para usuarios. Cuando acceda a la opción de “Olvide mi contraseña”, proporcione un correo electrónico que no este registrado en la página. Y presiona el botón de “Enviar”. Entonces la aplicación le mostrara un recuadro con el mensaje de que el correo electrónico brindado no esta registrado en la página. | EP01: Autenticación y Registro de Usuarios |
| US06 | Selección de Producto | Como usuario comprador de prendas de segunda mano registrado en la aplicación, deseo seleccionar productos y personalizarlos en cuanto a la talla.  | **E01: Selección de productos exitosa** **CA01:** Dado que se encuentra en la interfaz de compra para los usuarios compradores. Cuando acceda a alguna prenda de su interés. Y seleccione la prenda con la talla de preferencia. Entonces podrá visualizar posibles opciones de compra, como agregar al carrito de compras o agregar a prendas favoritas. **E02: Selección de productos fallida** **CA02:** Dado que me encuentro en la interfaz de compra para los usuarios compradores. Cuando acceda a alguna prenda de su interés. Y no seleccione la talla de su preferencia. Entonces no podrá visualizar posibles opciones de compra, como agregar al carrito de compras o agregar a prendas favoritas. | EP04: Compra y manejo de Productos |
| US07 | Filtrado de Productos | Como usuario comprador de prendas de segunda mano registrado en la aplicación, deseo poder filtrar productos por tipos de prendas y precio. | **E01: Filtrado de productos exitosa** **CA01:** Dado que me encuentro en la interfaz de búsqueda para los usuarios compradores. Cuando seleccione el filtro del tipo de prenda que deseo con el filtro de precio. Y presione en el botón “Buscar”. Entonces podre visualizar las prendas de acuerdo con los filtros aplicados. **E02: Filtrado de productos, solo con el filtro de tipo de prenda** **CA01:** Dado que me encuentro en la interfaz de búsqueda para los usuarios compradores. Cuando seleccione el filtro del tipo de prenda que deseo, pero sin el filtro de precio. Y presione en el botón “Buscar”. Entonces podre visualizar las prendas de mi interés, con todos los precios posibles y disponibles. **E03: Filtrado de productos, solo con el filtro de precio**  **CA03:** Dado que me encuentro en la interfaz de búsqueda para los usuarios compradores. Cuando no seleccione el filtro del tipo de prenda y solamente coloque el filtro de precio. Y presione en el botón “Buscar”. Entonces podre visualizar todas las prendas disponibles en el rango de precio que he colocado. **E04: Filtrado de productos fallida** **CA04:** Dado que me encuentro en la interfaz de búsqueda para los usuarios compradores. Cuando no seleccione ningún tipo de filtro para mi búsqueda. Y presione en el botón “Buscar”. Entonces podre visualizar todas las prendas disponibles que se encuentran en la página, sin ningún tipo de filtro. | EP04: Compra y manejo de Productos |
| US08 |Añadir a la canasta  | Como usuario comprador de prendas de segunda mano registrado en la aplicación, deseo poder agregar productos a mi canasta de compra para comprarlos en cualquier momento. | **E01:  Añadir a la canasta de manera exitosa** **CA01:** Dado que me encuentro en la interfaz de compra para los usuarios compradores. Cuando tenga un producto que me interesaría comprar en otro momento. Y presione en el botón de “Agregar a la canasta”. Entonces podre visualizar el producto en el apartado de “Mi Canasta”. **E02:  Añadir a la canasta de manera errónea** **CA02:** Dado que me encuentro en la interfaz de compra para los usuarios compradores. Cuando tenga un producto que me interesaría comprar en otro momento. Y no presione en el botón de “Agregar a la canasta”. Entonces no podre visualizar el producto en el apartado de “Mi Canasta”| EP04: Compra y manejo de Productos |
| US09 | Añadir a mis favoritos  | Como usuario comprador de prendas de segunda mano registrado en la aplicación, deseo poder guardar productos de mi interés. | **E01:  Añadir a mis favoritos de manera exitosa** **CA01:** Dado que me encuentro en la interfaz de compra para los usuarios compradores. Cuando tenga un producto de mi interés que me gustaría guardar en mi colección. Y presione en el botón de “Favorito”. Entonces podre visualizar el producto en el apartado de “Prendas Favoritas”. **E02:  Añadir a mis favoritos de manera erronea** **CA02:** Dado que me encuentro en la interfaz de compra para los usuarios compradores. Cuando tenga un producto de mi interés que me gustaría guardar en mi colección. Y no presione en el botón de “Favorito”. Entonces no podre visualizar el producto en el apartado de “Prendas Favoritas”.| EP04: Proceso de Compra |
| US10 | Desplazarse fácilmente entre las secciones de la página web  | Como usuario quiero desplazarme entre las secciones de la página web para visualizar la información importante para mí. | **E01: Desplazamiento correcto**  **CA01:** Dado que me encuentro la página web. Cuando quiera acceder a otra sección. Y seleccione el botón correspondiente a esta. Entonces me redirigirá a la selección elegida.  **CA02:** Dado que quiero conocer todas las secciones. Cuando visualice los botones de menú de navegación. Y presione el botón de mi preferencia. Entonces se mostrará la sección correspondiente| EP02: Vistas y control de la pagina web |
| US11 | Sección de la página web para los segmentos de usuario | Como usuario quiero ver una sección de la página web con información relacionada al segmento que corresponde para ver sus beneficios. |**E01: Visualización correcta para compradores** **CA01** Dado que me encuentro en la página web. Cuando visualice la opción de compradores. Y seleccione dicho botón. Entonces se me mostrara la sección para compradores. **E02: Visualización correcta para vendedores** **CA02** Dado que me encuentro en la página web. Cuando visualice la opción de vendedores. Y seleccione dicho botón. Entonces se me mostrara la sección para vendedores | EP03: Gestion de Eventos |
| US12 | Visualizar información personal | Como usuario registrado en la aplicación, deseo visualizar mi información para confirmar mis datos personales. | **E01: El usuario visualiza su información.** **CA01:** Dado que me registre satisfactoriamente. Cuando me dirija a la sección “Mi perfil”. Y seleccione dicha sección. Entonces la aplicación me mostrará mis datos personales básicos.| EP06: Manejo de informacion del usuario |
| US13 | Actualizar información personal | Como usuario quiero actualizar mi información para que la plataforma muestre mis datos actuales. | **E01: El usuario actualiza su información personal de manera correcta.** **CA01:** Dado que me encuentro en el apartado de actualizar mis datos personales. Cuando realice los cambios de mis datos con los caracteres correctos. Y presione en el botón de “Guardar cambios”. Entonces podre visualizar mis datos actualizados según como lo coloque en el formulario de actualización. **E02: El usuario actualiza su información personal de forma errónea.** **CA02:** Dado que me encuentro en el apartado de actualizar mis datos personales. Cuando realice los cambios de mis datos con los caracteres erróneos. Y presione en el botón de “Guardar cambios”. Entonces me mostrara un recuadro con el aviso de que mis datos no tienen los caracteres adecuados. | EP06: Manejo de informacion del usuario |
| US14 | Iniciar chat con vendedor  | Como usuario comprador de prendas de segunda mano registrado en la aplicación, deseo poder iniciar un chat con el vendedor para hacer preguntas o aclaraciones sobre un producto.  | **E01: Chat con vendedor** **CA01:** Dado que me encuentro en el apartado del producto. Cuando visualice la información del vendedor. Y presione el botón de “Chat con el vendedor”. Entonces podre enviar y recibir mensajes en tiempo real. | EP07: Sistema de comunicacion en el aplicativo |
| US15 | Notificaciones de mensajes | Como usuario comprador de prendas de segunda mano registrado en la aplicación, quiero recibir notificaciones cuando reciba un mensaje de un vendedor. | **E01: Notificaciones de vendedor en segundo plano.** **CA01:** Dado que me encuentro en el apartado de mensajes. Cuando reciba el mensaje de algún vendedor. Y me encuentre en la pagina o en segundo plano. Entonces debo recibir la notificación en tiempo real. **E02: Notificaciones de vendedor sin tener la pagina abierta** **CA02:** Dado que me encuentro en el apartado de mensajes. Cuando reciba el mensaje de algún vendedor. Y no me encuentre en la página, ni en segundo plano. Entonces no recibiré ninguna notificación en tiempo real.| EP07: Sistema de comunicacion en el aplicativo |
| US16 | Revisión de Pedido | Como usuario comprador de prendas de segunda mano registrado en la aplicación, deseo poder revisar mi pedido antes de confirmarlo.  | **E01: Revision de pedido** **CA01:** Dado que me encuentro en la interfaz de compra. Cuando este a punto de realizar el pago. Y seleccione el botón de “Detalles de Compra”. Entonces podre visualizar los detalles de mi pedido para poder confirmarlo. | EP04: Compra y manejo de Productos |
| US17 | Selección de Método de pago | Como usuario comprador de prendas de segunda mano registrado en la aplicación, deseo poder seleccionar un método de pago. | **E01: Método de Pago** **CA01:** Dado que me encuentro en la interfaz de compra. Cuando este a punto de realizar el pago. Y presione sobre el botón de “Elija su método de pago”. Entonces la página web me redijera al sitio web del método de pago seleccionado para completar la transacción. | EP04: Compra y manejo de Productos |
| US18 | Búsqueda de Ferias | Como usuario comprador de prendas de segunda mano registrado en la aplicación, deseo poder buscar y ver una lista de ferias en garajes físicos de ropa disponible cerca de mi ubicación.  | **E01: Búsqueda de Ferias**  **CA01:** Dado que me encuentro en la interfaz de navegación de ferias. Cuando seleccione el navegador para buscar una feria. Y presione sobre el botón “Buscar feria”. Entonces me saldrán los resultados de la búsqueda donde me mostrarán una lista de ferias con detalles. | EP03: Gestión de Eventos |
| US19 | Publicación de Productos | Como vendedor de prendas de segunda mano registrado en la aplicación, deseo publicar productos en la plataforma, incluyendo detalles. | **E01: publicación de productos.** **CA01:** Dado que me encuentro en el panel de publicación de producto. Cuando llene el formulario con todos los detalles del producto, tales como: talla, color y marca. Y presione sobre el botón “Publicar producto”. Entonces se completará la publicación del producto y aparecerá en la lista de disponibles. | EP05: Gestion de herramientas de vendedor |
| US20 | Edición de Productos | Como vendedor de prendas de segunda mano registrado en la aplicación, deseo editar la información de productos que he publicado previamente. | **E01: edición de productos** **CA01:** Dado que me encuentro en el panel de edición de producto. Cuando llene el formulario con todos los detalles del producto, tales como: talla, color y marca. Y presione sobre el botón “Publicar producto”. Entonces se completará la publicación del producto y aparecerá en la lista de disponibles. | EP05: Gestion de herramientas de vendedor |
| US21 | Eliminación de Productos  | Como vendedor de prendas de segunda mano registrado en la aplicación, deseo eliminar un producto previamente publicado. | **E01: eliminación de productos** **CA01:** Dado que me encuentro en el panel de eliminación de producto. Cuando seleccione el producto a eliminar. Y presione sobre el botón “Eliminar producto”. Entonces se completará la eliminación y dicho producto desaparecerá del listado de productos disponibles.|  EP05: Gestion de herramientas de vendedor |
| US22 | Visualización de Pedidos | Como vendedor de prendas de segunda mano registrado en la aplicación, deseo poder visualizar una lista de pedidos realizados por los compradores. | **E01: visualización de pedidos** **CA01:** Dado que me encuentro en el panel de pedidos. Cuando ingrese a la interfaz. Y presione sobre el botón “Visualizar pedidos”. Entonces podre visualizar la lista de pedidos con detalles como numero de pedido, fecha y estado. | EP05: Gestion de herramientas de vendedor |
| US23 | Publicación de Eventos de Venta | Como vendedor de prendas de segunda mano registrado en la aplicación, deseo publicar eventos en la plataforma. | **E01: publicación de eventos** **CA01:** Dado que me encuentro en el panel de publicación de eventos. Cuando llene el formulario con detalles del evento, incluyendo fecha, hora, ubicación, temática y fotos. Y presione sobre el botón “Publicar evento”. Entonces el evento aparecerá en la lista de eventos de venta disponibles. | EP03: Gestion de Eventos |
| US24 | Edición de Evento de Venta | Como vendedor de prendas de segunda mano registrado en la aplicación, deseo editar eventos en la plataforma. | **E01: edición de eventos.** **CA01:** Dado que me encuentro en el panel de edición de eventos. Cuando llene el formulario con detalles del evento, incluyendo fecha, hora, ubicación, temática y fotos. Y presione sobre el botón “Editar evento”. Entonces el evento aparecerá actualizado con los nuevos datos en la lista de eventos de venta disponibles. | EP03: Gestion de Eventos |
| US25 | Eliminación de Evento de Venta  | Como vendedor de prendas de segunda mano registrado en la aplicación, deseo eliminar eventos en la plataforma. | **E01: eliminación de eventos** **CA01:** Dado que me encuentro en el panel de eliminación de eventos. Cuando seleccione el evento el cual deseo eliminar. Y presione sobre el botón “Eliminar evento”. Entonces el evento desaparecerá del panel de eventos disponibles. | EP03: Gestion de Eventos |

## 3.3. Impact Mapping
![impact-map-rewear](https://i.ibb.co/qMmrcwQ/impact-map-rewear.png")

## 3.4. Product Backlog
**Segmento: Compradores**
| Número de Orden | ID de Historia de Usuario | Descripción | Story Points |
|-----------------|--------------------------|-------------|--------------|
| 1 | US01 | Como comprador, quiero registrarme en la aplicación web para poder realizar compras. | 3 |
| 2 | US02 | Como comprador registrado, quiero iniciar sesión en la aplicación para acceder a mi cuenta. | 3 |
| 3 | US03 | Como comprador registrado, quiero poder restablecer mi contraseña si la olvido. | 2 |
| 4 | US04 | Como comprador, quiero poder seleccionar productos y personalizarlos (talla y color). | 3 |
| 5 | US05 | Como comprador, quiero poder filtrar productos por género y precio para encontrar lo que busco más fácilmente. | 3 |
| 6 | US06 | Como comprador, quiero poder agregar productos a mi canasta de compra para comprarlos más tarde. | 2 |
| 7 | US07 | Como comprador, quiero poder iniciar un chat con el vendedor para hacer preguntas o aclaraciones sobre un producto. | 5 |
| 8 | US08 | Como comprador, quiero recibir notificaciones cuando reciba un mensaje de un vendedor. | 5 |
| 9 | US09 | Como comprador, quiero poder seleccionar un método de pago (como PayPal) para completar mi compra. | 3 |
| 10 | US10 | Como comprador, quiero poder revisar mi pedido antes de confirmarlo. | 3 |
| 11 | US11 | Como comprador, quiero recibir una confirmación de mi compra una vez que haya completado el proceso de pago. | 3 |
| 12 | US12 | Como comprador, quiero poder buscar y ver una lista de ferias en garajes físicos de ropa disponible cerca de mi ubicación. | 5 |
| 13 | US13 | Como comprador, quiero poder ver detalles específicos de una feria, como la lista de vendedores y los productos disponibles en cada stand. | 5 |

**Segmento: Vendedores**
| Número de Orden | ID de Historia de Usuario | Descripción | Story Points |
|-----------------|--------------------------|-------------|--------------|
| 1 | US01 | Como vendedor, quiero poder publicar productos en la plataforma, incluyendo información detallada como talla, color y marca. | 5 |
| 2 | US02 | Como vendedor, quiero poder editar la información de productos que he publicado previamente. | 5 |
| 3 | US07 | Como vendedor, quiero poder publicar eventos de venta en la plataforma, incluyendo detalles como fecha, hora, ubicación, temática y fotos. | 5 |
| 4 | US04 | Como vendedor, quiero poder ver una lista de pedidos realizados por los compradores. | 3 |
| 5 | US08 | Como vendedor, quiero poder editar la información de eventos de venta que he publicado previamente. | 3 |
| 6 | US05 | Como vendedor, quiero poder actualizar el estado de un pedido, como "En preparación" o "Enviado". | 3 |
| 7 | US06 | Como vendedor, quiero recibir confirmación de entrega de parte del comprador una vez que el pedido ha sido entregado. | 3 |
| 8 | US09 | Como vendedor, quiero poder eliminar eventos de venta que ya no se realizarán. | 3 |
| 9 | US03 | Como vendedor, quiero poder eliminar productos que ya no estén disponibles en mi inventario. | 2 |
| 10 | US12 | Como vendedor, quiero registrarme en la aplicación web para poder realizar compras. | 2 |
| 11 | US11 | Como vendedor registrado, quiero iniciar sesión en la aplicación para acceder a mi cuenta. | 2 |
| 12 | US12 | Como vendedor registrado, quiero poder restablecer mi contraseña si la olvido. | 1 |
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
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
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

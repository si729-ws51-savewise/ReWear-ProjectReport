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
| ID de Historia de Usuario | Título | Descripción | Criterios de Aceptación con Escenarios | ID de Épica |
|--------------------------|--------|-------------|----------------------------------------|-------------|
| HU01 | Registro de usuarios compradores en la plataforma | CComo usuario comprador que realiza compras de prendas de segunda mano no registrado deseo crearme una cuenta para poder acceder a las características de la app. | E01: Registro exitoso CA01: Dado que me encuentro en el formulario de registro de cuenta 
Cuando ingrese un correo electrónico no registrado, una contraseña válida (mayor o igual a 8 caracteres que incluyan al menos una letra y un número) junto a la confirmación de contraseña. Y presione el botón “Registrarse” Entonces la aplicación me mostrará un mensaje indicando que estoy registrado, pero que tengo que confirmar mi cuenta abriendo el enlace de confirmación enviado a mi correo electrónico.
E02: Registro inválido CA02: Dado que me encuentro en el formulario de registro de cuenta 
Cuando complete mis datos, pero alguno o muchos de ellos sean incorrectos.
Y presione el botón “Registrarse” 
Entonces la aplicación me mostrará un mensaje relacionado con la solución para el error o errores cometidos. 
E03: Verificación de la cuenta CA03: 
Dado que el usuario recibe el código de verificación en su correo electrónico. 
Cuando ingresa el código en el apartado de verificación.
Y pulsa en el botón “OK”. 
Entonces la aplicación móvil lo redirige al apartado de inicio.
 | EP01: Autenticación y Registro de Usuarios |
| US02 | Inicio de Sesión | Como comprador registrado, quiero iniciar sesión en la aplicación para acceder a mi cuenta. | - El usuario debe poder acceder a la página de inicio de sesión. - Debe ingresar su correo electrónico y contraseña. - Al enviar el formulario, se verifica la autenticidad de las credenciales y se redirige al usuario al panel de comprador. | EP01: Autenticación y Registro de Usuarios |
| US03 | Recuperación de Contraseña | Como comprador registrado, quiero poder restablecer mi contraseña si la olvido. | - El usuario debe poder acceder a la opción de "Olvidé mi contraseña". - Debe proporcionar su correo electrónico registrado. - Se le enviará un enlace de restablecimiento de contraseña por correo electrónico. | EP01: Autenticación y Registro de Usuarios |
| US04 | Selección de Producto | Como comprador, quiero poder seleccionar productos y personalizarlos (talla y color). | - Debe haber una lista de productos disponibles. - El usuario debe poder seleccionar un producto y personalizarlo eligiendo talla y color. - La selección debe reflejarse en la descripción del producto. | EP02: Compra de Productos |
| US05 | Filtrado de Productos | Como comprador, quiero poder filtrar productos por género y precio para encontrar lo que busco más fácilmente. | - Debe haber opciones de filtro por género y rango de precios. - Al aplicar un filtro, la lista de productos debe actualizarse de acuerdo con los criterios seleccionados. | EP02: Compra de Productos |
| US06 | Añadir a la Canasta | Como comprador, quiero poder agregar productos a mi canasta de compra para comprarlos más tarde. | - Debe haber un botón "Agregar a la Canasta" en cada producto. - Al hacer clic en el botón, el producto se agrega a la canasta del usuario. - El usuario debe poder ver los productos en su canasta. | EP02: Compra de Productos |
| US07 | Iniciar Chat con Vendedor | Como comprador, quiero poder iniciar un chat con el vendedor para hacer preguntas o aclaraciones sobre un producto. | - Debe haber un botón de "Chat con el Vendedor" en la página de cada producto. - Al hacer clic en el botón, se inicia un chat en tiempo real con el vendedor. - El usuario debe poder enviar y recibir mensajes. | EP03: Comunicación con el Vendedor |
| US08 | Notificaciones de Mensajes | Como comprador, quiero recibir notificaciones cuando reciba un mensaje de un vendedor. | - El usuario debe recibir notificaciones en tiempo real cuando un vendedor le envíe un mensaje. - Las notificaciones deben ser visibles incluso si la aplicación está en segundo plano. | EP03: Comunicación con el Vendedor |
| US09 | Selección de Método de Pago | Como comprador, quiero poder seleccionar un método de pago (como PayPal) para completar mi compra. | - En la página de proceso de compra, debe haber opciones de pago disponibles. - El usuario debe poder seleccionar su método de pago preferido (por ejemplo, PayPal). - El sistema debe redirigir al usuario al sitio web del método de pago seleccionado para completar la transacción. | EP04: Proceso de Compra |
| US10 | Revisión de Pedido | Como comprador, quiero poder revisar mi pedido antes de confirmarlo. | - En la página de proceso de compra, el usuario debe ver un resumen detallado de su pedido, incluyendo productos, cantidades y precios. - El usuario debe tener la opción de realizar modificaciones en su pedido (cambiar cantidad, eliminar productos, etc.). - El usuario debe poder confirmar el pedido una vez que esté satisfecho con la revisión. | EP04: Proceso de Compra |
| US11 | Confirmación de Compra | Como comprador, quiero recibir una confirmación de mi compra una vez que haya completado el proceso de pago. | - Después de completar la transacción, el usuario debe recibir una pantalla de confirmación que incluya los detalles de la compra (número de pedido, fecha, productos, precio total, etc.). - Se debe enviar un correo electrónico de confirmación al usuario con la misma información. | EP04: Proceso de Compra |
| US12 | Búsqueda de Ferias | Como comprador, quiero poder buscar y ver una lista de ferias en garajes físicos de ropa disponible cerca de mi ubicación. | - Debe haber una función de búsqueda de ferias por ubicación o por nombre. - Los resultados de la búsqueda deben mostrar una lista de ferias cercanas con detalles como nombre, fecha y lugar. - El usuario debe poder hacer clic en una feria para ver más información. | EP05: Visualización de Ferias |
| US13 | Detalles de Feria | Como comprador, quiero poder ver detalles específicos de una feria, como la lista de vendedores y los productos disponibles en cada stand. | - Al hacer clic en una feria de la lista, el usuario debe ver una página de detalles con información sobre la feria, incluyendo una lista de vendedores y productos. - Debe haber una opción para filtrar productos por género y precio dentro de la feria. | EP05: Visualización de Ferias |
| US01 | Publicación de Productos | Como vendedor, quiero poder publicar productos en la plataforma, incluyendo información detallada como talla, color y marca. | - En el panel de vendedor, debe haber una opción para "Publicar Producto". - El vendedor debe completar un formulario con detalles del producto, incluyendo talla, color y marca. - Una vez completada la publicación, el producto debe aparecer en la lista de productos disponibles. | EP01: Gestión de Productos |
| US02 | Edición de Producto | Como vendedor, quiero poder editar la información de productos que he publicado previamente. | - En el panel de vendedor, debe haber una opción para "Editar Producto". - El vendedor debe seleccionar un producto existente y actualizar los detalles, como talla, color y marca. - Los cambios realizados deben reflejarse en la información del producto en la plataforma. | EP01: Gestión de Productos |
| US03 | Eliminación de Producto | Como vendedor, quiero poder eliminar productos que ya no estén disponibles en mi inventario. | - En el panel de vendedor, debe haber una opción para "Eliminar Producto". - El vendedor debe seleccionar un producto existente y confirmar la eliminación. - El producto debe desaparecer de la lista de productos disponibles. | EP01: Gestión de Productos |
| US04 | Visualización de Pedidos | Como vendedor, quiero poder ver una lista de pedidos realizados por los compradores. | - En el panel de vendedor, debe haber una sección de "Pedidos". - El vendedor debe poder acceder a una lista de pedidos con detalles como número de pedido, fecha y estado. - Al hacer clic en un pedido, debe poder ver los detalles del pedido y la información del comprador. | EP03: Gestión de Pedidos |
| US05 | Actualización de Estado de Pedido | Como vendedor, quiero poder actualizar el estado de un pedido, como "En preparación" o "Enviado". | - En la página de detalles del pedido, el vendedor debe tener la opción de cambiar el estado del pedido. - Debe haber opciones predefinidas de estado, como "En preparación", "Enviado" o "Entregado". - Cuando se actualiza el estado, el comprador debe recibir una notificación por correo electrónico. | EP03: Gestión de Pedidos |
| US06 | Confirmación de Entrega | Como vendedor, quiero recibir confirmación de entrega de parte del comprador una vez que el pedido ha sido entregado. | - En la página de detalles del pedido, el comprador debe tener la opción de confirmar la entrega. - Una vez confirmada la entrega, el estado del pedido debe cambiar a "Entregado". - El vendedor debe recibir una notificación de confirmación de entrega. | EP03: Gestión de Pedidos |
| US07 | Publicación de Eventos de Venta | Como vendedor, quiero poder publicar eventos de venta en la plataforma, incluyendo detalles como fecha, hora, ubicación, temática y fotos. | - En el panel de vendedor, debe haber una opción para "Publicar Evento de Venta". - El vendedor debe completar un formulario con detalles del evento, incluyendo fecha, hora, ubicación, temática y fotos. - El evento debe aparecer en la lista de eventos de venta disponibles. | EP04: Gestión de Eventos |
| US08 | Edición de Evento de Venta | Como vendedor, quiero poder editar la información de eventos de venta que he publicado previamente. | - En el panel de vendedor, debe haber una opción para "Editar Evento de Venta". - El vendedor debe seleccionar un evento existente y actualizar los detalles, como fecha, hora, ubicación, temática y fotos. - Los cambios realizados deben reflejarse en la información del evento en la plataforma. | EP04: Gestión de Eventos |
| US09 | Eliminación de Evento de Venta | Como vendedor, quiero poder eliminar eventos de venta que ya no se realizarán. | - En el panel de vendedor, debe haber una opción para "Eliminar Evento de Venta". - El vendedor debe seleccionar un evento existente y confirmar la eliminación. - El evento de venta debe desaparecer de la lista de eventos disponibles. | EP04: Gestión de Eventos |
| US10 | Registro de Cuenta | Como vendedor, quiero registrarme en la aplicación web para poder realizar compras. | - El usuario debe poder acceder a la página de registro. - Debe proporcionar su nombre, correo electrónico y contraseña. - Al enviar el formulario, se crea una cuenta y se redirige al usuario al inicio de sesión. | EP05: Autenticación y Registro de Usuarios |
| US11 | Inicio de Sesión | Como vendedor registrado, quiero iniciar sesión en la aplicación para acceder a mi cuenta. | - El usuario debe poder acceder a la página de inicio de sesión. - Debe ingresar su correo electrónico y contraseña. - Al enviar el formulario, se verifica la autenticidad de las credenciales y se redirige al usuario al panel de comprador. | EP05: Autenticación y Registro de Usuarios |
| US12 | Recuperación de Contraseña | Como vendedor registrado, quiero poder restablecer mi contraseña si la olvido. | - El usuario debe poder acceder a la opción de "Olvidé mi contraseña". - Debe proporcionar su correo electrónico registrado. - Se le enviará un enlace de restablecimiento de contraseña por correo electrónico. | EP05: Autenticación y Registro de Usuarios |

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

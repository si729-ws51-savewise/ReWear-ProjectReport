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

<div align="center">
  <img src="https://i.ibb.co/x8CK698/estilos.png"  width="500px" height="300px" />
</div>

Con respecto a Style Guidelines, estamos utilizando la tipografíaa Poppins, Estilos de tipo Bold, Regular y Medium. Textos h1 encabezado de 64 px, h2 de 32 px, h3 y texto de 20 px. colores claros y oscuros para hacer contraste en nuestra interfaz y de esta manera poder captar la atención del usuario, siendo estos también usados para la creación del logo de nuestro startup.
*	Hemos seleccionado el color rosado. Simboliza la amabilidad, lo positivo, sentimental, sensibilidad, cortesía, buena educación, infancia e inocencia 
*	Hemos seleccionado como una de las fuentes a Poppins, Aporta una vista moderna y armoniosa ya que denota redondez.
*	Hemos seleccionado los colores negro y blanco para tener contraste dentro de nuestra, la intención también es tener 
una vista minimalista.

## 4.2. Information Architecture
### 4.2.1. Organization Systems
<div align="center">
  <img src="https://i.ibb.co/vVJM2x3/Concept-map.jpg" alt="Concept-map" width="500">
</div>

### 4.2.2. Labeling Systems
<div align="center">
  <img src="https://i.ibb.co/njDKBGv/Concept-map-1.jpg" alt="Concept-map-1" width="500">
</div>

### 4.2.3. SEO Tags and Meta Tags

Landing Page: 

- Title: Aplicación de prendas de vestir de segunda mano   
- Meta Tags: Aplicación para encontrar prendas de vestir de segunda mano con precios accesibles. 
- Description: En esta aplicacion podrás encontrar prendas de vestir de segunda mano. 
- Keywords: Prendas de vestir y Segunda mano.
- Author: ReWear
  
Web Application: 

- Title: Aplicación de prendas de vestir de segunda mano   
- Meta Tags: Aplicación para encontrar prendas de vestir de segunda mano con precios accesibles. 
- Description: En esta aplicacion podrás encontrar prendas de vestir de segunda mano. 
- Keywords: Prendas de vestir y Segunda mano.
- Author: ReWear
 
### 4.2.4. Searching Systems
<div align="center">
  <img src="https://i.ibb.co/hmGCj7G/Concept-map-2.jpg" alt="Concept-map-2" width="500">
</div>

### 4.2.5. Navigation Systems
<div align="center">
  <img src="https://i.ibb.co/B464xf7/Concept-map-3.jpg" alt="Concept-map-3" width="500">
</div>

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
En el siguiente enlace hacia Figma, se encuentran los Wireframes de la landing page de ReWear, se optó la subida de estos archivos en la nube, ya que reducirán el espacio usado
https://www.figma.com/file/XxGTOhyTgyTxhOCTGGLy4b/ReWear?type=design&node-id=0%3A1&mode=design&t=l5T5stfrDtwGW9VY-1

### 4.3.2. Landing Page Mock-up
En el siguiente enlace hacia Figma, se encuentran los Mock-ups de la landing page de ReWear, se optó la subida de estos archivos en la nube, ya que reducirán el espacio usado
https://www.figma.com/file/XxGTOhyTgyTxhOCTGGLy4b/ReWear?type=design&node-id=0%3A1&mode=design&t=l5T5stfrDtwGW9VY-1

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
En el siguiente enlace hacia Figma, se encuentran los Mock-ups de la Web Applications de ReWear, se optó la subida de estos archivos en la nube, ya que reducirán el espacio usado
https://www.figma.com/file/QF02Bas5sOLb5RbBylDGir/Angular-Material-(Material-3-Design-Component-Figma-Library-For-Angular)-(Community)?type=design&node-id=6%3A2&mode=design&t=NtnHNS4TjDEE8HOT-1
### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
![Diagrama de base de datos ReWear](https://i.ibb.co/2y3Svp1/Main.jpg")
### 4.7.2. Class Dictionary

#### Buyer (Comprador):
La clase "Buyer" representa a los usuarios que actúan como compradores en el sistema "ReWear". Estos son individuos que están interesados en comprar ropa de segunda mano. La clase almacena información relevante sobre los compradores, como su identificación única, nombre completo, dirección de correo electrónico y un historial de compras que incluye los productos adquiridos. Los compradores también pueden utilizar el método `getPurchases()` para obtener una lista de sus compras anteriores en el sistema.

#### Seller (Vendedor):
La clase "Seller" representa a los usuarios que actúan como vendedores en la plataforma "ReWear". Estos son individuos o tiendas que desean vender ropa de segunda mano a los compradores. La clase almacena información importante sobre los vendedores, como su identificación única, nombre completo, dirección de correo electrónico, número de teléfono de contacto y un registro de ventas que incluye los productos vendidos. Los vendedores también pueden utilizar el método `getSales()` para obtener una lista de sus ventas registradas en el sistema.

#### Purchase (Compra):
La clase "Purchase" representa las compras realizadas por los compradores en "ReWear". Cada instancia de esta clase registra detalles de una compra, como una identificación única, fecha de compra, costo total y una lista de productos adquiridos. Estos productos están representados por instancias de la clase "Product". La información de compra se utiliza para mantener un historial de transacciones y facilitar la gestión de pedidos y devoluciones.

#### Sale (Venta):
  La clase "Sale" representa las ventas realizadas por los vendedores en la plataforma "ReWear". Cada instancia de esta clase almacena información relacionada con una venta, como una identificación única, fecha de venta, monto total y una lista de productos vendidos. Al igual que en la clase "Purchase", los productos vendidos están representados por instancias de la clase "Product". La información de ventas se utiliza para realizar un seguimiento de las transacciones realizadas por los vendedores.

#### Product (Producto):  
La clase "Product" representa los productos que están disponibles para su compra en "ReWear". Cada producto tiene una identificación única, un nombre descriptivo y un precio asociado. Los productos pueden ser prendas de ropa de segunda mano de diversas categorías. Esta clase es utilizada tanto por los compradores al seleccionar productos como por los vendedores al listar productos para su venta. Los productos se asocian con compras y ventas a través de las clases "Purchase" y "Sale".

## 4.8. Database Design
### 4.8.1. Database Diagram

![Diagrama de base de datos](https://i.ibb.co/nMHQ08G/Re-Wear-2023-09-22-12-13.png")

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

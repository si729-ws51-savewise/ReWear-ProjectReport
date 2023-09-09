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
### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
![Diagrama de base de datos ReWear](https://i.ibb.co/9H9nwk9/BD-Rewear.png")
### 4.7.2. Class Dictionary
#### Entidad: Ubicación
- **IDUbicacion** (Clave Primaria - INT)
- Ciudad (VARCHAR(255) NOT NULL)
- Estado (VARCHAR(255) NOT NULL)
- País (VARCHAR(255) NOT NULL)
- Código Postal (VARCHAR(10))
- Calle (VARCHAR(255))
- Número (INT)

#### Entidad: Categoría
- **IDCategoria** (Clave Primaria - INT)
- Nombre de la Categoría (VARCHAR(255) NOT NULL)

#### Entidad: Comprador
- **IDComprador** (Clave Primaria - INT)
- Nombre (VARCHAR(255) NOT NULL)
- Correo Electrónico (VARCHAR(255) UNIQUE NOT NULL)
- IDUbicación (INT) (Clave Foránea hacia Ubicación)

#### Entidad: Vendedor
- **IDVendedor** (Clave Primaria - INT)
- Nombre (VARCHAR(255) NOT NULL)
- Correo Electrónico (VARCHAR(255) UNIQUE NOT NULL)
- IDUbicación (INT) (Clave Foránea hacia Ubicación)

#### Entidad: Productos
- **IDProducto** (Clave Primaria - INT)
- Nombre (VARCHAR(255) NOT NULL)
- IDCategoría (INT NOT NULL) (Clave Foránea hacia Categoría)
- Precio (DECIMAL(10, 2) NOT NULL)
- IDVendedor (INT) (Clave Foránea hacia Vendedor)

#### Entidad: CarritoDeCompra
- **IDCarrito** (Clave Primaria - INT)
- IDComprador (INT) (Clave Foránea hacia Comprador)

#### Tabla Intermedia: ProductosEnCarrito
- **ID** (Clave Primaria - INT)
- IDCarrito (INT) (Clave Foránea hacia CarritoDeCompra)
- IDProducto (INT) (Clave Foránea hacia Productos)
- Cantidad (INT)

#### Entidad: Evento
- **IDEvento** (Clave Primaria - INT)
- Nombre (VARCHAR(50) NOT NULL)
- Descripción (VARCHAR(50) NOT NULL)
- Fecha (DATE NOT NULL)
- Temática (VARCHAR(50) NOT NULL)
- IDVendedor (INT) (Clave Foránea hacia Vendedor)
## 4.8. Database Design
### 4.8.1. Database Diagram

```sql
CREATE DATABASE Rewear;

CREATE TABLE Ubicacion (
    IDUbicacion INT PRIMARY KEY,
    Ciudad VARCHAR(255) NOT NULL,
    Estado VARCHAR(255) NOT NULL,
    Pais VARCHAR(255) NOT NULL,
    CodigoPostal VARCHAR(10),
    Calle VARCHAR(255),
    Numero INT
);

CREATE TABLE Categoria (
    IDCategoria INT PRIMARY KEY,
    NombreCategoria VARCHAR(255) NOT NULL
);

CREATE TABLE Comprador (
    IDComprador INT PRIMARY KEY,
    Nombre VARCHAR(255) NOT NULL,
    CorreoElectronico VARCHAR(255) UNIQUE NOT NULL,
    IDUbicacion INT,
    FOREIGN KEY (IDUbicacion) REFERENCES Ubicacion(IDUbicacion)
);

CREATE TABLE Vendedor (
    IDVendedor INT PRIMARY KEY,
    Nombre VARCHAR(255) NOT NULL,
    CorreoElectronico VARCHAR(255) UNIQUE NOT NULL,
    IDUbicacion INT,
    FOREIGN KEY (IDUbicacion) REFERENCES Ubicacion(IDUbicacion)
);

CREATE TABLE Productos (
    IDProducto INT PRIMARY KEY,
    Nombre VARCHAR(255) NOT NULL,
    IDCategoria INT NOT NULL,
    Precio DECIMAL(10, 2) NOT NULL,
    IDVendedor INT,
    FOREIGN KEY (IDCategoria) REFERENCES Categoria(IDCategoria),
    FOREIGN KEY (IDVendedor) REFERENCES Vendedor(IDVendedor)
);

CREATE TABLE CarritoDeCompra (
    IDCarrito INT PRIMARY KEY,
    IDComprador INT,
    FOREIGN KEY (IDComprador) REFERENCES Comprador(IDComprador)
);

CREATE TABLE ProductosEnCarrito (
    ID INT PRIMARY KEY,
    IDCarrito INT,
    IDProducto INT,
    Cantidad INT,
    FOREIGN KEY (IDCarrito) REFERENCES CarritoDeCompra(IDCarrito),
    FOREIGN KEY (IDProducto) REFERENCES Productos(IDProducto)
);

CREATE TABLE Evento (
    IDEvento INT PRIMARY KEY, -- Puedes quitar AUTO_INCREMENT si no es necesario
    Nombre VARCHAR(50) NOT NULL,
    Descripcion VARCHAR(50) NOT NULL,
    Fecha DATE NOT NULL,
    Tematica VARCHAR(50) NOT NULL,
    IDVendedor INT,
    FOREIGN KEY (IDVendedor) REFERENCES Vendedor(IDVendedor)
);

```

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

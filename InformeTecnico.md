
# Proyecto 1: 

## Desarrollando una aplicación web:  
### De la teoría a la práctica

### Informe técnico

---

**Asignatura:** Desarrollo Web - Entorno al Cliente  
**Fecha:** 24/09/2024  
**Nombre:** Pablo González Silva  

---

## ¿Qué contiene?

- Un análisis de los modelos de ejecución cliente/servidor, incluyendo ejemplos y comparaciones.
- La evaluación de los lenguajes de programación web seleccionados, destacando sus ventajas y desventajas.
- Un estudio sobre la compatibilidad en navegadores, identificando posibles problemas y soluciones, y cómo estas consideraciones afectan la elección de tecnologías.
- Un análisis de los mecanismos de integración de los lenguajes de marcas con los lenguajes de programación de clientes web.
- La evaluación de herramientas de programación para clientes web, explicando sus funciones y ventajas distintivas.
- Un análisis de mercado que detalle la competencia existente y cómo la propuesta se diferencia y aporta valor nuevo.

---

## Análisis de los modelos de ejecución cliente/servidor, incluyendo ejemplos y comparaciones

### En la parte del cliente:
Proporciona una interfaz interactiva, ejecuta el código en el navegador y procesa los eventos y acciones del usuario en nuestra página. En este caso, **TypeScript** se usaría para toda la funcionalidad de la web, como la validación de formularios, manejo de eventos o el consumo de APIs, entre otros.

### En la parte del servidor:
Hace de intermediario entre las peticiones del cliente y las fuentes de datos, entre las que se podrían encontrar las APIs, trasladando los datos necesarios al cliente y administrando la lógica de negocio de la aplicación (administración de productos en alquiler, gestión de clientes, control de transacciones y seguimiento de disponibilidad). Esta parte estaría construida con **Spring Boot**, que permitirá manejar solicitudes HTTP.

---

## Evaluación de los lenguajes de programación web seleccionados, destacando sus ventajas y desventajas

### 1. TypeScript (Angular)

**Ventajas:**
- **Tipado estático:** Mejora la seguridad y reduce errores en el desarrollo.
- **Mantenibilidad:** Ideal para proyectos grandes, facilitando el mantenimiento del código.
- **Compatibilidad con JavaScript:** Se compila a JavaScript, lo que lo hace compatible con todos los entornos donde se ejecute JavaScript.

**Desventajas:**
- **Curva de aprendizaje:** Requiere tiempo para desarrolladores acostumbrados a JavaScript.
- **Compilación necesaria:** Añade un paso extra al ciclo de desarrollo.
- **Sobrecarga en proyectos pequeños:** El tipado puede ser una complejidad innecesaria en proyectos pequeños.

### 2. Java (Spring Boot)

**Ventajas:**
- **Robustez y escalabilidad:** Lenguaje maduro ideal para aplicaciones empresariales.
- **Soporte para Spring Boot:** Facilita el desarrollo rápido de aplicaciones backend.
- **Amplia comunidad y ecosistema:** Gran cantidad de bibliotecas, herramientas y soporte.

**Desventajas:**
- **Consumo de recursos:** Puede ser más pesado en términos de memoria y rendimiento.
- **Curva de aprendizaje:** La sintaxis y configuración de frameworks como Spring Boot puede ser intimidante.
- **Tiempo de desarrollo:** Requiere más líneas de código y configuración.

### 3. SQL (MySQL)

**Ventajas:**
- **Eficiencia en el manejo de datos:** Optimizado para realizar consultas complejas rápidamente.
- **Estabilidad y fiabilidad:** MySQL es una opción confiable para grandes volúmenes de datos.
- **Facilidad de uso:** SQL tiene una sintaxis relativamente sencilla.

**Desventajas:**
- **Limitaciones con datos no estructurados:** Menos flexible frente a bases de datos NoSQL.
- **Escalabilidad horizontal limitada:** Puede ser difícil escalar MySQL a gran escala.
- **Curva de aprendizaje para optimización:** Consultas complejas requieren un conocimiento profundo.

---

## Estudio sobre la compatibilidad en navegadores

La mayoría de los navegadores modernos son compatibles con **ES6** y, aunque **TypeScript** se transcompila a JavaScript compatible con navegadores más antiguos, es esencial verificar el rendimiento en navegadores específicos como Internet Explorer 11 o versiones antiguas de Safari, que pueden no soportar ciertas características modernas.

### Problemas con CSS
Algunas propiedades de **CSS3** pueden no ser interpretadas de la misma forma en todos los navegadores, afectando la apariencia de la página.

---

## Análisis de los mecanismos de integración de los lenguajes de marcas con los lenguajes de programación de clientes web

La interacción entre los lenguajes de marcas como **HTML** y los lenguajes de programación del lado del cliente como **TypeScript** es crucial para crear interfaces dinámicas. **HTML** define la estructura y contenido, mientras que **TypeScript** añade interactividad, manipulando dinámicamente el contenido del documento.

---

## Evaluación de herramientas de programación para clientes web

### 1. Visual Studio Code (VS Code)
**Ventajas:**
- **Ligero y personalizable:** Ideal para adaptarse a las necesidades del proyecto.
- **Multiplataforma y gratuito:** Disponible para Windows, macOS y Linux.
- **Excelente para desarrollo web:** Integra bien con frameworks como Angular y Spring Boot.

### 2. GitHub
**Ventajas:**
- **Plataforma ideal para colaboración remota:** Facilita la gestión de proyectos distribuidos.
- **Gran ecosistema de código abierto:** Acceso a una vasta cantidad de proyectos.
- **Integración con múltiples herramientas:** Funciona bien con VS Code y otras herramientas CI/CD.

### 3. Postman
**Ventajas:**
- **Interfaz intuitiva:** Permite probar APIs rápidamente.
- **Automatización de pruebas:** Asegura que el sistema funcione correctamente antes de integrarse.

### 4. MySQL Workbench
**Ventajas:**
- **Interfaz visual amigable:** Facilita la administración de bases de datos.
- **Ideal para proyectos MySQL:** Optimizada para el diseño y mantenimiento de bases de datos MySQL.

### 5. IntelliJ IDEA
**Ventajas:**
- **Soporte completo para Spring Boot:** Facilita la creación de APIs.
- **Depuración avanzada:** Potente herramienta de depuración para backend.
- **Refactorización automática:** Permite modificar el código sin comprometer su estabilidad.

### 6. Spring Boot
**Ventajas:**
- **Configuración mínima:** Permite crear APIs de manera rápida.
- **Escalabilidad:** Adecuado para proyectos que crecen.
- **Integración con herramientas de testing:** Facilita pruebas automatizadas.

---

## Análisis de mercado y diferenciación de la propuesta

El mercado de plataformas web para el alquiler de productos entre particulares ha crecido en los últimos años, impulsado por la economía colaborativa. Aquí se analiza la competencia existente y cómo la propuesta aporta valor nuevo.

### Competencia existente

#### Wallapop
- Plataforma para la compra y venta de artículos de segunda mano.
- **Limitaciones:** No está optimizada para el alquiler, dificultando la gestión de plazos, precios dinámicos o contratos temporales.

#### Fat Llama
- Plataforma global de alquiler de productos.
- **Limitaciones:** Mayores costos de transporte y disponibilidad limitada a nivel local.

### Diferenciación de la propuesta
La plataforma se diferencia al ofrecer:
- **Amplitud de categorías de productos.**
- **Optimización para el alquiler**, incluyendo gestión de contratos, precios dinámicos, sistema de devolución, y más.
- **Fomento de la sostenibilidad**, reduciendo el consumo innecesario.
- **Monetización de bienes infrautilizados**, generando ingresos pasivos para los oferentes.
- **Enfoque local**, reduciendo costos de transporte y tiempos de entrega.

### Aportación de valor nuevo
- **Mejora de la experiencia de usuario.**
- **Mayor flexibilidad para usuarios y oferentes.**
- **Promoción activa del consumo sostenible.**

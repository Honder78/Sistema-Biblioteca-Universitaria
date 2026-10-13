# Sistema  Biblioteca Universitaria

## Objetivo del sistema
El objetivo principal del sistema es gestionar de manera digital los préstamos y devoluciones de libros en la biblioteca universitaria, ofreciendo a estudiantes y administradores una herramienta ágil, segura y organizada para el control de inventarios y alertas de vencimiento.

## Problema que resuelve
El sistema resuelve la dificultad de llevar un control manual de los préstamos y devoluciones, evitando pérdidas de información, retrasos en la devolución de materiales y falta de trazabilidad en el inventario bibliotecario.

## Funcionalidades principales
- Registro digital de préstamos y devoluciones.
- Consulta de disponibilidad de libros en tiempo real.
- Alertas de vencimiento para préstamos próximos a expirar.
- Interfaz de inicio de sesión para estudiantes y administradores.
- Control de inventarios y gestión de base de datos.

## Arquitectura seleccionada
Se seleccionó una arquitectura cliente-servidor:
- **Frontend:** interfaz gráfica para usuarios (login, búsqueda, reservas, alertas).
- **Backend:** lógica de negocio, base de datos y generación de alertas.
- **Comunicación:** API REST que conecta frontend y backend para garantizar el funcionamiento integrado.

## Herramientas utilizadas
- Git y GitHub para control de versiones y gestión de incidencias.
- GitHub Projects para organización de tareas.
- Visual Paradigm Online para diagramas UML (casos de uso, secuencia, actividades).
- ## Estado actual del proyecto
El Sistema de Gestión Bibliotecaria se encuentra en desarrollo con los siguientes avances:
- Diseño de la base de datos en finalizado.
- Interfaz de inicio de sesión en construcción.
- Control de inventarios en desarrollo.
- Módulo de búsqueda en revisión.
- Documentación inicial en README.md.

Pendientes:
- Implementación del menú principal con navegación completa.
- Funcionalidad de reservas en línea.
- Alertas automáticas de vencimiento.
- Pruebas de integración y validación de módulos.
- Optimización de la interfaz gráfica.

## Organización del sistema
- **Frontend:** interfaz gráfica para estudiantes y administradores, que incluye login, búsqueda de libros, reservas y alertas de vencimiento.  
- **Backend:** lógica de negocio, gestión de préstamos y devoluciones, control de inventarios y conexión con la base de datos.  
- **Comunicación:** el frontend se conecta con el backend mediante servicios REST, garantizando la sincronización de datos y el funcionamiento integrado.

## Registro de cambios
1. Definición de la arquitectura inicial del sistema.  
2. Diseño preliminar de la base de datos.  
3. Desarrollo del módulo de inicio de sesión.  
4. Implementación del control de inventarios.  
5. Documentación inicial en README.md.  

- Lenguajes de programación y simuladores para pruebas técnicas.

## Estado actual del proyecto
El sistema se encuentra en una versión inicial consolidada. Se han implementado los diagramas UML, la base de datos, el módulo de login y las alertas de vencimiento. El tablero de GitHub Projects refleja el avance con tareas en progreso y finalizadas. Quedan pendientes pruebas de validación, documentación final y la preparación del video explicativo.

<h1 align="center">MJ LEDGER</h1>

![logo](imagen/logo1.png)

MJ LEDGER es una aplicación desarrollada en Python que permite gestionar el préstamo de artículos de manera organizada, facilitando el registro, control y seguimiento de la información, con el objetivo de evitar pérdidas y mejorar la administración de los recursos.

## PARTICIPANTES

- **Dana Moreno:** Estudio Ingeniería Industrial, una carrera orientada a optimizar procesos, mejorar la productividad y tomar decisiones eficientes dentro de las organizaciones. Me encuentro en quinto semestre, donde he fortalecido mis conocimientos en análisis de sistemas, gestión de procesos y uso de herramientas cuantitativas.

Entre mis principales habilidades y fortalezas, destaco el pensamiento analítico, la capacidad para resolver problemas y la organización. También tengo facilidad para trabajar en equipo, adaptarme a diferentes situaciones y aprender de manera autónoma. Me considero una persona responsable, comprometida y con enfoque en la mejora continua, siempre buscando soluciones eficientes e innovadoras.

- **Valentina Ramírez:** Estudio Ingeniería Industrial y actualmente voy en tercer semestre. Soy una persona curiosa, persistente y colaborativa. Me caracterizo por tener una gran capacidad de organización, claridad en la comunicación y creatividad para encontrar soluciones prácticas. Disfruto aprender cosas nuevas y analizar detalles con precisión, siempre buscando mejorar y aportar valor en lo que hago. Me gusta combinar la exactitud con la estética, y busco que mis resultados sean claros y atractivos.

  ## LICENCIA DEL SOFTWARE

  ## REPORTE DE VISIÓN

El sistema **MJ LEDGER** es una aplicación desarrollada en Python que tiene como propósito gestionar de manera eficiente el préstamo de artículos, permitiendo el registro, control y seguimiento de usuarios, ítems y transacciones asociadas. Este sistema surge como solución a la problemática presentada por MJ, quien enfrenta dificultades para recordar a quién ha prestado sus objetos y en qué condiciones se encuentran, generando desorganización y pérdida de información.

El software está diseñado para centralizar la información de los préstamos, permitiendo registrar usuarios con sus datos, gestionar un inventario de artículos categorizados y controlar el ciclo completo de préstamo y devolución. Además, incorpora funcionalidades adicionales como la generación de certificados de devolución y facturación automática en caso de incumplimiento en los tiempos establecidos, lo que fortalece el control sobre los recursos.

El objetivo principal del sistema es mejorar la organización y trazabilidad de los artículos prestados, reduciendo errores humanos y facilitando la toma de decisiones mediante información clara y estructurada. De igual forma, busca ofrecer una herramienta práctica, confiable y accesible que pueda ser utilizada en entornos donde se requiera llevar un control detallado de préstamos.

Entre los beneficios del sistema se destacan la optimización del tiempo en la gestión de información, la reducción de pérdidas o confusiones sobre los artículos, el acceso a reportes administrativos y la posibilidad de mantener un historial completo de las operaciones realizadas. De esta manera, MJ LEDGER se posiciona como una solución integral para la administración de préstamos, adaptada a las necesidades planteadas en el problema.

## ESPECIFICACIÓN DE REQUISITOS
El sistema **MJ LEDGER** define un conjunto de requisitos que permiten gestionar de manera estructurada el préstamo de artículos, asegurando el control de usuarios, inventario, préstamos, devoluciones y procesos asociados como certificaciones y facturación.

### REQUISITOS FUNCIONALES
1. El sistema debe permitir el registro de usuarios, validando nombre, apellido, documento, correo electrónico y tiempo de préstamo permitido.
2. El sistema debe permitir registrar artículos, incluyendo nombre, categoría, precio de compra, identificador único y estado del ítem.
3. El sistema debe permitir realizar préstamos únicamente a usuarios previamente registrados, asociando el ítem y la fecha correspondiente.
4. El sistema debe validar que un ítem esté disponible antes de ser prestado.
5. El sistema debe permitir registrar devoluciones únicamente de préstamos activos.
6. El sistema debe generar un certificado de devolución cuando un artículo es retornado dentro del tiempo establecido.
7. El sistema debe generar una factura de venta cuando un artículo supere el tiempo máximo de préstamo (30 días), incluyendo el cálculo de impuestos.
8. El sistema debe permitir consultar el estado general de los préstamos, mostrando información organizada por tiempo.
9. El sistema debe almacenar la información en archivos para su posterior consulta.
10. El sistema debe permitir el acceso a un módulo de administrador mediante validación de usuario y contraseña.
11. El sistema debe generar reportes administrativos, incluyendo:
    - Total de préstamos
    - Total de devoluciones
    - Total de ventas
    - Total de pagos
    - Lista de usuarios
    - Usuarios con mayor y menor número de préstamos

### REQUISITOS NO FUNCIONALES
1. **Usabilidad:** El sistema debe contar con un menú claro y organizado que facilite la interacción del usuario.
2. **Rendimiento:** El sistema debe procesar las operaciones de manera rápida y eficiente.
3. **Fiabilidad:** El sistema debe garantizar que los datos almacenados sean correctos y consistentes.
4. **Seguridad:** El sistema debe restringir el acceso al módulo administrativo mediante credenciales válidas.
5. **Portabilidad:** El sistema debe ejecutarse en cualquier entorno compatible con Python.
6. **Mantenibilidad:** El código debe estar bien estructurado utilizando buenas prácticas de programación.
7. **Compatibilidad:** El sistema debe funcionar en diferentes sistemas operativos sin afectar su funcionamiento.

  

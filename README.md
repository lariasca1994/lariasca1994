# ¡Hola! 👋 Soy Luis F Arias C
<img align="right" alt="Coding" width="350" src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif">

## 🚀 Sobre mí
Ingeniero de Sistemas egresado de la Universidad EAN. Mi enfoque se basa en el aprendizaje continuo y la mejora constante, tanto a nivel técnico como personal. Actualmente me encuentro expandiendo mis habilidades a través de cursos especializados y proyectos desafiantes.

💼 Lo que aporto: <br>
🎯 Experiencia real: pruebas funcionales (API REST, validación en Oracle) en el Banco de la República, monitoreo N1 y soporte técnico N2 en Global Hitss y OESIA <br>
📐 Objetividad: metodologías estructuradas de pruebas (equivalence partitioning, boundary value analysis) para decisiones basadas en evidencia <br>
🤝 Compromiso: gestión del ciclo completo de casos hasta el cierre, documentación consistente incluso bajo presión de SLA <br>
📈 Orientación al crecimiento: certificación ITIL v4 y formación continua en SQL, testing y desarrollo Full Stack, buscando siempre aportar valor medible al equipo <br>

🔥 Lo que me diferencia: <br>
✅ Mentalidad de crecimiento: Siempre buscando nuevas tecnologías y metodologías <br>
✅ Impacto empresarial: Enfocado en soluciones que agreguen valor medible <br>
✅ Colaboración efectiva: Experiencia trabajando en equipos multidisciplinarios <br>
✅ Entrega de resultados: Comprometido con la calidad y los tiempos de entrega <br>

<br clear="right"/>

## 🛠️ Tecnologías y Herramientas
<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

</div>

## 🎯 Proyectos Destacados

### 🏛️ Reservas Corferias — Modernización de un sistema legado
**Laravel 12 · PHP 8.3 · SQL Server · PHPUnit · Bootstrap 5**

Reconstrucción completa de un proyecto universitario de 2019 escrito en Lumen 5.8,
conservando el historial de Git original.

Durante el análisis encontré un **defecto de doble reserva**: la condición que
detectaba cruces de fechas solo reconocía el caso en que el rango solicitado
quedaba totalmente contenido dentro de uno ocupado, así que cualquier
solapamiento parcial pasaba como disponible. Lo corregí y lo cubrí con una
batería de pruebas que incluye los casos frontera, más una prueba que reproduce
la lógica original para dejar el error documentado.

El sistema original no tenía base de datos —los datos vivían dentro de los
controladores—, ni autenticación, ni validación en el servidor, ni una sola
prueba. La versión actual incluye modelo relacional, tres roles, notificaciones
por correo con código QR, panel de administración, más de setenta pruebas
automatizadas e integración continua.

- [Ver repositorio](https://github.com/lariasca1994/reservas-corferias)

---

### 📋 TaskFlow — Gestión de tareas con análisis de datos
**Python · FastAPI · MongoDB · pandas · HTMX**

Aplicación construida enteramente en Python, sin JavaScript propio: la
interactividad la resuelve HTMX pidiendo fragmentos de HTML al servidor.

Incluye un módulo de análisis que acepta archivos CSV, Excel y JSON, genera un
perfilado automático de columnas —tipos, nulos, valores únicos y estadísticas
descriptivas— y ofrece un explorador donde se eligen agrupación, medida y tipo de
gráfico. Cada cambio recalcula en el servidor con pandas. Los archivos se
convierten a Parquet al cargarlos, lo que hace viables los filtros interactivos.

Los indicadores se actualizan en vivo mediante Server-Sent Events, y las
contraseñas se protegen con bcrypt más un secreto de servidor que no se almacena
junto a los datos.

- [Ver repositorio](https://github.com/lariasca1994/taskflow)

---

### 🎰 Lottery AI — Análisis estadístico de sorteos
**Node.js · Express · PostgreSQL · Sequelize · Chart.js**

Sistema de recolección y análisis de resultados históricos de Baloto, Revancha y
MiLoto sobre más de mil ochocientos sorteos.

Parte de una premisa explícita: los sorteos son estadísticamente independientes,
así que el sistema no predice nada. Lo que hace es aplicar una **prueba de chi
cuadrado de bondad de ajuste** para responder a una pregunta concreta —¿la
distribución observada es compatible con el azar?— y traducir el resultado a
lenguaje llano, con su valor p, la banda esperada por número y los que quedan
fuera de ella.

El panel se actualiza solo al abrir la página cuando hay sorteos nuevos, con un
tiempo de espera que evita saturar el sitio de origen. Incluye herramientas de
diagnóstico del recolector, porque depende de la estructura HTML de un sitio
ajeno.

- [Ver repositorio](https://github.com/lariasca1994/lottery-ai)

---

### 🧪 Software Testing Portfolio
**Java · JUnit 5 · Mockito · JaCoCo**

Proyecto de pruebas que combina tres técnicas complementarias: pruebas unitarias,
aislamiento de dependencias con objetos simulados para probar componentes cuya
implementación no existe, y medición de cobertura de ramas para distinguir el
código realmente ejercitado del que solo aparenta estarlo.

- [Ver repositorio](https://github.com/lariasca1994/Software_Testing)

---

### 🏠 ColombiaTech
**NestJS (REST + GraphQL + WebSockets) · React · MongoDB**

Plataforma de alquiler de vivienda con backend unificado que expone REST y
GraphQL sobre la misma base de código, autenticación con tokens, control de
acceso por usuario y chat en tiempo real.

- [Ver repositorio](https://github.com/lariasca1994/ColombiaTech2)

---

### 💳 PRPagos — Sistema de pagos
**Java · Swing · Oracle**

Aplicación de escritorio con persistencia en Oracle, contraseñas cifradas,
visibilidad de datos limitada por usuario y registro de auditoría de las
operaciones.

- [Ver repositorio](https://github.com/lariasca1994/Desarrollo-de-Software)

---

### 💼 Portafolio Personal
**HTML · CSS · JavaScript**

Sitio de presentación organizado por área de interés, sin framework ni proceso de
compilación.

- [Ver repositorio](https://github.com/lariasca1994/PWDC)

## 📫 ¡Conectemos!
<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lfac1/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ariascluisf@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lariasca1994)

<!-- Imagen de footer -->
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

**"El único modo de hacer un gran trabajo es amar lo que haces."** 💻✨

![Profile views](https://komarev.com/ghpvc/?username=lariasca1994&color=brightgreen)

</div>

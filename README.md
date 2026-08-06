# ¡Hola! 👋 Soy Luis F Arias C
<picture align="right">
  <source media="(prefers-color-scheme: dark)" srcset="assets/programmer-negro.gif">
  <source media="(prefers-color-scheme: light)" srcset="assets/programmer-blanco.gif">
  <img align="right" alt="Coding" width="350" src="assets/programmer-negro.gif">
</picture>

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

**Lenguajes**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Frameworks**

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**Bases de datos**

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Pruebas y herramientas**

![JUnit](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Appium](https://img.shields.io/badge/Appium-662D91?style=for-the-badge&logo=appium&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

## 🎯 Proyectos Destacados

### 🏛️ Reservas Corferias — Modernización de un sistema legado
**Laravel 12 · PHP 8.3 · Azure SQL Server · PHPUnit · Bootstrap 5**

Tomé un proyecto universitario de 2019 escrito en Lumen 5.8 y lo reconstruí por completo sobre Laravel 12, conservando el historial de Git original.

Durante el análisis del código encontré un **defecto de doble reserva** que había pasado inadvertido: la condición que detectaba cruces de fechas solo reconocía el caso en que el rango solicitado quedaba totalmente contenido dentro de uno ya ocupado, así que cualquier solapamiento parcial pasaba como disponible. El mismo escenario podía reservarse dos veces para las mismas fechas.

Lo corregí, lo cubrí con una batería de pruebas que incluye los casos frontera, y añadí una prueba que reproduce la lógica original para dejar documentado el error y garantizar que no vuelva.

El sistema de 2019 tampoco tenía base de datos —los datos estaban escritos a mano dentro de los controladores—, ni autenticación, ni validación del lado del servidor, ni una sola prueba. La versión actual incluye modelo de datos normalizado, autenticación con tres roles, notificaciones por correo con código QR, panel de administración, más de setenta pruebas automatizadas e integración continua.

- [Ver repositorio](https://github.com/lariasca1994/reservas-corferias)

---

### 🧪 Software Testing Portfolio
**Java · JUnit 5 · Mockito · JaCoCo**

Proyecto de pruebas de software que simula un proceso de control de calidad real: diseñé casos de prueba que encontraron y documentaron un error de clasificación antes de que llegara a producción, y medí la cobertura real de las pruebas sobre el código.

Incluye tres técnicas complementarias: pruebas unitarias con JUnit, aislamiento de dependencias con Mockito para poder probar componentes cuya implementación no existe, y medición de cobertura de ramas con JaCoCo para distinguir el código realmente ejercitado del que solo aparenta estarlo.

- [Ver repositorio](https://github.com/lariasca1994/Software_Testing)

---

### 🏠 ColombiaTech
**NestJS (REST + GraphQL + WebSockets) · React · MongoDB**

Plataforma Full Stack de alquiler de vivienda al estilo Airbnb, con backend unificado que expone REST y GraphQL sobre la misma base de código.

Resuelve tres problemas habituales de este tipo de plataforma: autenticación segura con tokens, control de acceso donde cada usuario solo alcanza su propia información, y comunicación en tiempo real entre arrendador e interesado mediante WebSockets.

- [Ver repositorio](https://github.com/lariasca1994/ColombiaTech2)

---

### 🎰 Lottery AI — Análisis de sorteos
**PostgreSQL (Neon) · Análisis de datos**

Herramienta de análisis de resultados históricos de Baloto, Revancha y MiLoto.

La decisión de diseño que la distingue: los cálculos se basan **únicamente en los sorteos que tuvieron ganador del premio mayor**, no en la frecuencia general de aparición de cada número. Es una distinción importante, porque analizar todos los sorteos mezcla información de resultados que nunca produjeron un acierto completo.

El proyecto se migró de MongoDB a PostgreSQL para trabajar con un modelo relacional y consultas analíticas.

- [Ver repositorio](https://github.com/lariasca1994/lottery-ai)

---

### 💳 PRPagos — Sistema de pagos
**Java · Oracle**

Aplicación de gestión de pagos desarrollada durante el curso de Desarrollo de Software de la Universidad EAN, con persistencia sobre Oracle.

- [Ver repositorio](https://github.com/lariasca1994/Desarrollo-de-Software)

---

### 💼 Portafolio Personal
**HTML · CSS · JavaScript**

Sitio de presentación profesional organizado por área de interés (QA, Análisis de Datos, Soporte y Monitoreo), con formulario de contacto funcional.

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

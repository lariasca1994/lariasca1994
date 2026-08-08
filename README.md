# Luis Felipe Arias Carriazo
### 🚀 Ingeniero de Sistemas | QA Tester | Support L1/L2

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lfac1/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lariasca1994)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ariascluisf@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://tinyurl.com/carraian160)

---

</div>

# 📌 Perfil Profesional

Ingeniero de Sistemas egresado de la **Universidad EAN**, con experiencia en **aseguramiento de calidad de software**, **soporte especializado N1/N2** y **desarrollo full  tack**.

Mi trayectoria incluye pruebas funcionales sobre APIs REST y validación en bases de datos Oracle en el **Banco de la República**, y gestión de incidentes bajo marcos **ITIL v4** en **Global Hitss** y **OESIA**. En paralelo desarrollo proyectos propios donde aplico lo aprendido en testing, análisis de datos y construcción de aplicaciones web.

---

## ⚡ Especialidades & Propuesta de Valor

<div align="center">

| 🧪 QA & Testing | 📊 Datos | 💻 Desarrollo | ⚙️ Operaciones |
| :--- | :--- | :--- | :--- |
| Pruebas unitarias, de integración y de regresión. | Consultas SQL y modelado relacional. | Aplicaciones web con REST y GraphQL. | Monitoreo N1/N2 y gestión de incidentes. |
| Diseño de casos con *Boundary Value Analysis* y *Equivalence Partitioning*. | Perfilado y análisis con Python (*pandas*). | Bases de datos relacionales y NoSQL. | Diagnóstico estructurado y seguimiento de SLA. |
| **Herramientas:** JUnit 5, Mockito, JaCoCo, Selenium, Appium, Postman. | **Herramientas:** Oracle, SQL Server, PostgreSQL, MySQL, MongoDB. | **Herramientas:** Java, PHP (Laravel), Python (FastAPI), Node.js, React. | **Certificación:** ITIL v4 Foundation. |

</div>

---

# 🛠️ Stack Tecnológico

<div align="center">

### Lenguajes
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Frameworks & Librerías
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

### Bases de Datos & Almacenamiento
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

### QA, Testing & Infraestructura
![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🚀 Proyectos

<details open>
<summary><b>🏛️ Reservas Corferias — Modernización de un sistema legado</b></summary>

<br>

* **Stack:** `PHP 8.3` · `Laravel 12` · `SQL Server (Azure)` · `PHPUnit` · `Bootstrap 5`
* **Punto de partida:** un proyecto académico de 2019 escrito en Lumen 5.8, sin base de datos —los datos vivían dentro de los controladores—, sin autenticación funcional, sin validación en el servidor y sin pruebas.
* **Qué hice:**
  * **Defecto encontrado:** la condición que detectaba cruces de fechas solo reconocía el caso en que el rango solicitado quedaba totalmente contenido dentro de uno ya ocupado, así que cualquier solapamiento parcial pasaba como disponible. El mismo escenario podía reservarse dos veces.
  * **Corrección y cobertura:** más de 70 pruebas automatizadas, con una matriz de casos frontera para el solapamiento y una prueba que reproduce la lógica original para dejar el error documentado. Integración continua en GitHub Actions.
  * **Reconstrucción:** modelo de datos normalizado, autenticación con tres roles, contraseñas con bcrypt, notificaciones por correo con código QR y panel de administración.
* 🔗 [Ver repositorio](https://github.com/lariasca1994/reservas-corferias)

</details>

<br>

<details open>
<summary><b>📋 TaskFlow — Gestión de tareas con módulo de análisis</b></summary>

<br>

* **Stack:** `Python` · `FastAPI` · `MongoDB` · `pandas` · `HTMX`
* **Objetivo:** construir una aplicación web íntegramente en Python, sin JavaScript propio, con una capa de análisis de datos real.
* **Qué hice:**
  * **Módulo de análisis:** acepta archivos CSV, Excel y JSON, genera un perfilado automático de columnas —tipos, nulos, valores únicos y estadísticas descriptivas— y ofrece un explorador donde se eligen agrupación, medida y tipo de gráfico. Cada cambio recalcula en el servidor con pandas.
  * **Rendimiento:** los archivos se convierten a Parquet al cargarlos, de modo que cada filtro lee solo las columnas necesarias en lugar de releer el original.
  * **Interfaz:** la interactividad se resuelve con HTMX pidiendo fragmentos de HTML; los indicadores se actualizan en vivo mediante Server-Sent Events.
  * **Seguridad:** contraseñas con bcrypt más un secreto de servidor que no se almacena junto a los datos, sesión con inactividad deslizante y verificación de pertenencia en cada consulta.
* 🔗 [Ver repositorio](https://github.com/lariasca1994/taskflow)

</details>

<br>

<details open>
<summary><b>🎰 Lottery AI — Análisis estadístico de sorteos</b></summary>

<br>

* **Stack:** `Node.js` · `Express` · `PostgreSQL` · `Sequelize` · `Chart.js`
* **Premisa:** los sorteos de lotería son estadísticamente independientes, así que el sistema **no predice nada**. La versión inicial generaba "predicciones" combinando frecuencias con números aleatorios; la reescribí para que describa el histórico y nada más.
* **Qué hice:**
  * **Recolección** de más de 1.800 sorteos de Baloto, Revancha y MiLoto, con detección tolerante de la estructura HTML y scripts de diagnóstico para cuando el sitio de origen cambia.
  * **Prueba de bondad de ajuste:** chi cuadrado sobre la distribución observada, con su valor p, la banda esperada por número y los que quedan fuera de ella, traducido a lenguaje llano para quien no conoce la prueba.
  * **Actualización automática** al abrir el panel, con un tiempo de espera que evita peticiones repetidas al sitio de origen.
* 🔗 [Ver repositorio](https://github.com/lariasca1994/lottery-ai)

</details>

<br>

<details>
<summary><b>🧪 Software Testing — Ejercicio de pruebas con cobertura</b></summary>

<br>

* **Stack:** `Java` · `JUnit 5` · `Mockito` · `JaCoCo`
* **Contexto:** ejercicio académico sobre el caso *CoffeeMaker*, orientado a practicar tres técnicas complementarias.
* **Qué contiene:**
  * Pruebas unitarias sobre las clases de dominio.
  * Uso de Mockito para probar un componente cuya dependencia es una interfaz sin implementación.
  * Medición de cobertura de ramas con JaCoCo, que distingue el código realmente ejercitado del que solo aparenta estarlo.
* 🔗 [Ver repositorio](https://github.com/lariasca1994/Software_Testing)

</details>

<br>

<details>
<summary><b>🏠 ColombiaTech — Plataforma de alquiler de vivienda</b></summary>

<br>

* **Stack:** `NestJS` · `React` · `GraphQL` · `REST` · `MongoDB` · `WebSockets`
* **Qué contiene:** backend que expone REST y GraphQL sobre la misma base de código, autenticación con JWT, aislamiento de información por usuario y mensajería en tiempo real mediante WebSockets.
* 🔗 [Ver repositorio](https://github.com/lariasca1994/ColombiaTech2)

</details>

<br>

<details>
<summary><b>💳 PRPagos y 💼 Portafolio web</b></summary>

<br>

* **PRPagos:** aplicación de escritorio en `Java` con `Swing` y persistencia en `Oracle`. Contraseñas cifradas, visibilidad de datos limitada por usuario y registro de auditoría de las operaciones. Proyecto del curso de Desarrollo de Software de la Universidad EAN.
  🔗 [Ver repositorio](https://github.com/lariasca1994/Desarrollo-de-Software)

* **Portafolio web:** sitio estático en `HTML`, `CSS` y `JavaScript`, sin framework ni proceso de compilación. Organizado por área de interés, con formulario de contacto.
  🔗 [Ver repositorio](https://github.com/lariasca1994/PWDC)

</details>

---

## 📈 Estadísticas de GitHub

<div align="center">

![Estadísticas](https://github-readme-stats.vercel.app/api?username=lariasca1994&show_icons=true&hide_border=true&theme=default&locale=es)

![Lenguajes](https://github-readme-stats.vercel.app/api/top-langs/?username=lariasca1994&layout=compact&hide_border=true&theme=default&locale=es)

</div>

---

## 📫 ¡Conectemos!

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lfac1/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ariascluisf@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lariasca1994)

<br>

**"El único modo de hacer un gran trabajo es amar lo que haces."**

![Visitas](https://komarev.com/ghpvc/?username=lariasca1994&color=brightgreen&label=Visitas)

</div>
---

## 📈 Estadísticas de GitHub

<div align="center">

![Luis Felipe's GitHub stats](https://github-readme-stats.vercel.app/api?username=lariasca1994&show_icons=true&theme=tokyonight&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=lariasca1994&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 📫 ¡Conectemos!

<div align="center">

¿Interesado en colaborar o discutir oportunidades técnicas? **¡Hablemos!**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lfac1/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ariascluisf@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lariasca1994)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://tinyurl.com/carraian160)

</div>

## 👨‍💻 Sobre mí

```javascript
const luisFelipe = {
  nombre: "Luis Felipe Arias",
  rol: "Ingeniero de Sistemas · QA & Automatización",
  enfoqueActual: [
    "🧪 Pruebas funcionales, diseño de casos y validación de servicios API REST",
    "🐍 Backends en Python (FastAPI) conectados a bases de datos",
    "☁️ Fundamentos de AWS Cloud aplicados a proyectos reales",
  ],
  formacionYCertificaciones: [
    "2026 · Software Testing and Automation (Coursera)",
    "2026 · Connecting MongoDB to Python (Mongo University)",
    "2025 · Ingeniería de Sistemas (Universidad EAN)",
    "2024 · AWS Academy Cloud Foundations (AWS Academy)",
    "2024 · Desarrollo Web Full Stack (Talento Tech Bogotá – MinTIC)",
    "2023 · Programación Web Desde Cero (EGGApp)",
    "2023 · Foundation: Introduction to SQL (Simplilearn)",
    "2023 · Aprende a Programar con Python (EANx)",
    "2023 · Testing (PROtalento)",
    "2023 · Análisis Exploratorio de Datos con Python (SENA)",
    "2019 · ITIL v4 Foundation (PeopleCert)",
  ],
  stack: {
    lenguajes: ["Python", "SQL", "PHP", "JavaScript", "C#"],
    basesDeDatos: [
      "MongoDB",
      "Azure SQL",
      "PostgreSQL",
      "MySQL",
      "Oracle Database",
    ],
    testing: [
      "Postman",
      "Pruebas funcionales de API REST",
      "Diseño de casos de prueba",
    ],
    cloud: [
      "AWS Lambda",
      "Azure Container Apps",
      "Google Cloud Run",
      "Vercel",
      "GitHub Pages",
    ],
    metodologias: ["ITIL v4"],
  },
};

const filosofia = () => ({
  pruebas: "Cada funcionalidad se valida antes de entregarse",
  codigo: "Documentado y trazable",
  aprendizaje: "Constante, un curso terminado a la vez",
});
```

---

## ☁️ Ecosistema de despliegue

> Aplicaciones, APIs y proyectos de automatización desplegados en plataformas cloud.

```mermaid
flowchart LR
    PORTFOLIO(["LUIS FELIPE ARIAS<br/>QA · Automatización · Backend · Cloud"])

    AWS(["AWS Lambda<br/>Serverless"])
    AZURE(["Azure Container Apps<br/>Contenedores"])
    GCP(["Google Cloud Run<br/>Servicios cloud"])
    VERCEL(["Vercel<br/>Frontend"])
    GITHUB(["GitHub Pages<br/>Portfolio estático"])

    QA["Gestor de Casos QA"]
    VERIFY["Verificador API"]

    INCIDENTES["Gestor de Incidentes TI"]
    RESERVAS["Reservas Corferias"]
    AFILIACIONES["Calidad Afiliaciones"]

    PAGOS["PRPagos"]
    TASKFLOW["TaskFlow"]

    COLOMBIA["ColombiaTech2"]
    PWDC["PWDC · Portfolio"]

    PORTFOLIO --> AWS
    PORTFOLIO --> AZURE
    PORTFOLIO --> GCP
    PORTFOLIO --> VERCEL
    PORTFOLIO --> GITHUB

    AWS --> QA
    AWS --> VERIFY

    AZURE --> INCIDENTES
    AZURE --> RESERVAS
    AZURE --> AFILIACIONES

    GCP --> PAGOS
    GCP --> TASKFLOW

    VERCEL --> COLOMBIA
    GITHUB --> PWDC

    classDef portfolio fill:#1D4ED8,stroke:#93C5FD,color:#FFFFFF,stroke-width:4px;
    classDef aws fill:#8A3B00,stroke:#FF9900,color:#FFFFFF,stroke-width:3px;
    classDef azure fill:#0078D4,stroke:#7DD3FC,color:#FFFFFF,stroke-width:3px;
    classDef gcp fill:#4285F4,stroke:#93C5FD,color:#FFFFFF,stroke-width:3px;
    classDef vercel fill:#18181B,stroke:#A1A1AA,color:#FFFFFF,stroke-width:3px;
    classDef github fill:#24292F,stroke:#8B949E,color:#FFFFFF,stroke-width:3px;
    classDef project fill:#1E293B,stroke:#64748B,color:#F8FAFC,stroke-width:2px;

    class PORTFOLIO portfolio;
    class AWS aws;
    class AZURE azure;
    class GCP gcp;
    class VERCEL vercel;
    class GITHUB github;
    class QA,VERIFY,INCIDENTES,RESERVAS,AFILIACIONES,PAGOS,TASKFLOW,COLOMBIA,PWDC project;
```

<sub>
🟧 AWS Lambda · 🔷 Azure Container Apps · 🔵 Google Cloud Run · ▲ Vercel · ◉ GitHub Pages
</sub>

---

## 🚀 Proyectos destacados

> Proyectos ordenados por complejidad técnica, alcance funcional y relación con QA, soporte de aplicaciones, automatización y backend.

| Proyecto | Problema que resuelve | Stack principal | Despliegue | Enlaces |
|---|---|---|---|---|
| **ColombiaTech2** | Plataforma de alquiler de vivienda con mensajería en tiempo real entre arrendadores e inquilinos. El backend unifica REST, GraphQL y WebSockets. | ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)<br>![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) | [Demo](https://colombia-tech2.vercel.app/) · [Repositorio](https://github.com/lariasca1994/ColombiaTech2) |
| **Gestor de Casos de Prueba QA** | Plataforma end-to-end para gestionar proyectos, suites, casos de prueba, ejecuciones, defectos y métricas de calidad. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)<br>![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) | ![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=amazonaws&logoColor=white) | [Demo](https://immxew65sfxj7nubwzlszdimfi0qegzc.lambda-url.us-east-1.on.aws/) · [Repositorio](https://github.com/lariasca1994/gestor-casos-qa) |
| **Gestor de Incidentes TI** | Mini ITSM para soporte de aplicaciones: priorización, SLA, escalamiento automático N1 → N2 → N3 y trazabilidad de incidentes. | ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white) ![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)<br>![Azure SQL](https://img.shields.io/badge/Azure_SQL-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) | ![Azure Container Apps](https://img.shields.io/badge/Azure_Container_Apps-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) | [Demo](https://gestorincidentesti.livelywater-fe29fe0b.australiaeast.azurecontainerapps.io/) · [Repositorio](https://github.com/lariasca1994/GestorIncidentesTI) |
| **PRPagos** | Simulador de flujos de pago y validación de reglas transaccionales, con aplicación de escritorio y backend web independiente. | ![Java](https://img.shields.io/badge/Java_Swing-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)<br>![Oracle DB](https://img.shields.io/badge/Oracle_DB-F80000?style=flat-square&logo=oracle&logoColor=white) | ![Google Cloud Run](https://img.shields.io/badge/Google_Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white) | [Demo](https://prpagos-web-1087929107584.southamerica-east1.run.app) · [Repositorio](https://github.com/lariasca1994/PRPagos) |
| **reservas-corferias** | Sistema de reservas para un centro de convenciones: catálogo de escenarios, calendario de disponibilidad y panel administrativo. | ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)<br>![Azure SQL](https://img.shields.io/badge/Azure_SQL-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) | ![Azure Container Apps](https://img.shields.io/badge/Azure_Container_Apps-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) | [Demo](https://reservas-corferias.blueocean-86680030.eastus.azurecontainerapps.io/) · [Repositorio](https://github.com/lariasca1994/reservas-corferias) |
| **calidad-afiliaciones** | Motor de control de calidad para procesos de afiliación: validación de reglas de negocio y seguimiento de inconsistencias. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)<br>![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | ![Azure Container Apps](https://img.shields.io/badge/Azure_Container_Apps-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) | [Demo](https://calidad-afiliaciones.blueocean-86680030.eastus.azurecontainerapps.io/) · [Repositorio](https://github.com/lariasca1994/calidad-afiliaciones) |
| **TaskFlow** | Gestor de tareas con carga de archivos, procesamiento con pandas y generación de reportes y analítica en tiempo real. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)<br>![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) | ![Google Cloud Run](https://img.shields.io/badge/Google_Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white) | [Demo](https://taskflow-812302804238.us-central1.run.app/) · [Repositorio](https://github.com/lariasca1994/taskflow) |
| **verificador-api** | Suite de validación automatizada para endpoints REST: pruebas de contrato, códigos de estado y tiempos de respuesta. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)<br>![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) | ![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=amazonaws&logoColor=white) | [Demo](https://eofvlnitsiuodup4eywdcenxwu0adgbz.lambda-url.us-east-1.on.aws/) · [Repositorio](https://github.com/lariasca1994/verificador-api) |
| **PWDC** | Sitio de portafolio personal construido sin frameworks, con HTML, CSS y JavaScript puro. | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)<br>![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | ![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=github&logoColor=white) | [Demo](https://lariasca1994.github.io/PWDC/) · [Repositorio](https://github.com/lariasca1994/PWDC) |

---

## 📫 Contacto

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ariascluisf@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/carraian160)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/lfac6)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lfac1)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/lariasca1994)

---

![Profile views](https://komarev.com/ghpvc/?username=lariasca1994&color=brightgreen)

**Última actualización:** Septiembre de 2026
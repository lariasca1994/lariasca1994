## 👨‍💻 Sobre mí

```javascript
const luisFelipe: Profesional = {
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
    lenguajes: ["Python", "SQL", "PHP", "JavaScript"],
    basesDeDatos: ["MongoDB", "Azure SQL", "PostgreSQL", "MySQL"],
    testing: ["Postman", "Pruebas funcionales API REST", "Diseño de casos de prueba"],
    cloud: ["AWS Cloud Foundations"],
    metodologías: ["ITIL v4"],
  },
};

const filosofía = () => ({
  pruebas: "Cada funcionalidad se valida antes de entregarse",
  código: "Documentado y trazable",
  aprendizaje: "Constante, un curso terminado a la vez",
});
```

## 🚀 Proyectos

| Nombre | Descripción | Stack | Desplegado en | Demo | Repo |
|---|---|---|---|---|---|
| Gestor de Casos de Prueba QA | App web de gestión de casos de prueba (proyectos, suites, casos, ejecuciones, defectos, dashboard). | `Python` `FastAPI` `MongoDB` | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) | [Ver](https://immxew65sfxj7nubwzlszdimfi0qegzc.lambda-url.us-east-1.on.aws/) | [Ver repo](https://github.com/lariasca1994/gestor-casos-qa) |
| reservas-corferias | Reserva de escenarios de un centro de convenciones: catálogo, agenda, reservas y panel administrativo. | `PHP` `Laravel` `Azure SQL` | ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) | [Ver](https://reservas-corferias.blueocean-86680030.eastus.azurecontainerapps.io/) | [Ver repo](https://github.com/lariasca1994/reservas-corferias) |
| verificador-api | Validación de endpoints de servicios API REST y pruebas automatizadas de respuesta. | `Python` `FastAPI` `PostgreSQL` | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) | [Ver](https://eofvlnitsiuodup4eywdcenxwu0adgbz.lambda-url.us-east-1.on.aws/) | [Ver repo](https://github.com/lariasca1994/verificador-api) |
| calidad-afiliaciones | Tablero y scripts de control de calidad y validación de reglas de negocio en procesos de afiliaciones. | `Python` `FastAPI` `MySQL` | ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) | [Ver](https://calidad-afiliaciones.blueocean-86680030.eastus.azurecontainerapps.io/) | [Ver repo](https://github.com/lariasca1994/calidad-afiliaciones) |
| TaskFlow | Gestor de tareas con módulo de analítica de archivos con pandas y procesamiento en tiempo real. | `Python` `FastAPI` `MongoDB` | — | — | [Ver repo](https://github.com/lariasca1994/taskflow) |
| ColombiaTech2 | Plataforma de alquiler de vivienda con comunicación en tiempo real y arquitectura desacoplada. | `NestJS` `React` `MongoDB` | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) | [Ver](https://colombia-tech2.vercel.app/) | [Ver repo](https://github.com/lariasca1994/ColombiaTech2) |
| PRPagos | Simulación y validación de flujos de pagos y reglas transaccionales. | `Java Swing` `FastAPI` `Oracle DB` | ![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) | [Ver](https://prpagos-web-1087929107584.southamerica-east1.run.app) | [Ver repo](https://github.com/lariasca1994/PRPagos) |
| job-search-automation | Automatización y extracción estructurada de ofertas de empleo mediante web scraping. | `Python` `Selenium` | — | — | [Ver repo](https://github.com/lariasca1994/job-search-automation) |
| PWDC | Sitio de portafolio personal. | `HTML5` `CSS3` `JavaScript` | ![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=github&logoColor=white) | [Ver](https://lariasca1994.github.io/PWDC/) | [Ver repo](https://github.com/lariasca1994/PWDC) |

## 💡 Hoja de ruta

```mermaid
graph TB
    A[Portafolio desplegado] --> AWS[AWS Lambda]
    A --> AZ[Azure Container Apps]
    A --> GCP[Google Cloud Run]
    A --> VER[Vercel]
    A --> GHP[GitHub Pages]
    A --> PEND[Pendiente de desplegar]

    AWS --> AWS1[✅ Gestor de Casos QA]
    AWS --> AWS2[✅ verificador-api]

    AZ --> AZ1[✅ reservas-corferias]
    AZ --> AZ2[✅ calidad-afiliaciones]

    GCP --> GCP1[✅ PRPagos web]

    VER --> VER1[✅ ColombiaTech2]

    GHP --> GHP1[✅ PWDC · portafolio]

    PEND --> PEND1[⏳ TaskFlow]
    PEND --> PEND2[⏳ job-search-automation]

    style A fill:#2563EB,stroke:#1E40AF,color:#fff
    style AWS fill:#D97706,stroke:#B45309,color:#fff
    style AZ fill:#0078D4,stroke:#005A9E,color:#fff
    style GCP fill:#4285F4,stroke:#1A56C4,color:#fff
    style VER fill:#111111,stroke:#000000,color:#fff
    style GHP fill:#24292E,stroke:#0D1117,color:#fff
    style PEND fill:#6B7280,stroke:#4B5563,color:#fff
```

## 📫 Contacto

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ariascluisf@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/carraian160)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/lfac6)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luisfelipeariascarriazo)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/lariasca1994)

🔗 Portafolio: [https://lariasca1994.github.io/PWDC/](https://lariasca1994.github.io/PWDC/)

- **💬 WhatsApp:** @carraian160
- **✈️ Telegram:** @lfac6

---

![Profile views](https://komarev.com/ghpvc/?username=lariasca1994&color=brightgreen)

**Última actualización:** Septiembre 2026
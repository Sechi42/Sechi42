<p align="center">
  <img src="https://github.com/user-attachments/assets/fa1f5f9b-c754-4285-a73f-c3e34dd75ed2" width="800" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sergio-anaya-sanchez/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=Sechi42&color=blueviolet&style=flat-square" alt="Profile Views"/>
</p>


---

### 👨‍💻 Sobre mí

Apasionado por la ciencia de datos, MLOps y automatización de procesos.  
Actualmente curso una **Maestría en Ingeniería y Ciencia de Datos** en la Universidad de Guadalajara y trabajo en una empresa de logística de hidrocarburos desarrollando soluciones serverless y arquitecturas modernas.

- 🚀 Desarrollador de soluciones en la nube con **AWS (Lambda, Step Functions, API Gateway, Textract, etc.)**
- 🏗️ Automatización de infraestructura con **Terraform** y despliegue CI/CD usando **GitHub Actions**.
- 🧠 Enfocado en la eficiencia de datos usando **Polars**, **PostgreSQL** y microservicios en **FastAPI / Flask**.
- 📫 Contacto: [sergio.anayads@gmail.com](mailto:sergio.anayads@gmail.com) | [LinkedIn](https://www.linkedin.com/in/sergio-anaya-sanchez/)

---

### ⚒️ Lenguajes y herramientas

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=py,postgresql,tensorflow,pytorch,sklearn,aws,terraform,docker,fastapi,flask,git,githubactions,polars" alt="Skills" />
</a>

---

### 🧠 Experiencia técnica destacada

- 🧱 Construcción de microservicios serverless en AWS con autenticación personalizada vía Lambda Authorizers.
- 📊 ETLs de alto rendimiento con **Polars** y despliegue automatizado con **Terraform**.
- 🔄 Automatización de pipelines con **GitHub Actions** para CI/CD.
- 🔌 Integraciones externas con APIs de terceros como **Samsara**, **Google Drive**, **Google Sheets**, **PEMEX** y **AWS Textract**.
- 🗃️ Administración de bases de datos relacionales en **Aurora PostgreSQL** y **MySQL**.

---

### 🧩 Arquitectura de un sistema desarrollado

Este sistema está orientado a la automatización de procesos operativos y de auditoría en una comercializadora, integrando múltiples actores y servicios cloud:

```mermaid
graph TD
  subgraph "👥 Actores Humanos"
    COMERCIAL[👤 Comercial]
    ADMIN[👨‍💼 Admin]
    OPERADOR[🚚 Operador]
    CLIENTE[🏢 Cliente]
    AUDITOR[🔍 Auditor]
  end

  subgraph "🤖 Actores del Sistema"
    LAMBDA[⚡ Lambda]
    SCHEDULER[⏰ Scheduler]
    TRIGGER[🔔 Trigger BD]
  end

  subgraph "🔌 Sistemas Externos"
    PEMEX[🏭 API Proveedores]
    DRIVE[☁️ Google Drive]
    SHEETS[📊 Google Sheets]
    TEXTRACT[🔍 AWS Textract]
  end

  COMERCIAL -->|Opera| LAMBDA
  ADMIN -->|Configura| LAMBDA
  OPERADOR -->|Consulta| SHEETS
  CLIENTE -->|Responde| COMERCIAL
  AUDITOR -->|Revisa logs| ADMIN

  LAMBDA -->|Consume| PEMEX
  LAMBDA -->|Escribe| DRIVE
  LAMBDA -->|Sincroniza| SHEETS
  LAMBDA -->|Extrae datos| TEXTRACT
  LAMBDA -->|Ejecuta| TRIGGER

  SCHEDULER -->|Programa| LAMBDA
  TRIGGER -->|Valida reglas| LAMBDA
```
### 🚀 Proyectos Destacados

#### ⚙️ Red Energy API  
Plataforma serverless basada en **AWS SAM** + **Step Functions**, utilizada para la orquestación de microservicios y autenticación mediante tokens personalizados.

- ✔️ Uso de **API Gateway**, **Aurora PostgreSQL**, y **Lambda Authorizer**.  
- 🔐 Seguridad y validación de endpoints con **Lambdas dedicadas**.

---

#### 📈 ETLs con Polars y Terraform  
Automatización de pipelines de datos modernos con **Polars**, desplegados en la nube con **Lambda** y **Terraform**.

- ⚡ Procesamiento rápido y eficiente de grandes volúmenes de datos.  
- 🔄 Despliegue automatizado usando **GitHub Actions** para CI/CD.

---

#### 🚛 Sistema de monitoreo logístico  
Integración de APIs como **Samsara** para trazabilidad y monitoreo en tiempo real de activos y vehículos.

- 🌐 Integración con **Step Functions** y almacenamiento en **Aurora PostgreSQL**.  
- 📡 Visualización de rutas y actividad por cliente o unidad.
---

### 🔥 Mis estadísticas

<div align="center" id="stats">
  <img src="http://github-readme-streak-stats.herokuapp.com?user=Sechi42&theme=dark&background=000000" alt="GitHub Streak"/>
  <br><br>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sechi42&layout=compact&theme=vision-friendly-dark" alt="Top Langs"/>
</div>

---

### 📬 Contacto

<div align="left" id="contact">
  <a href="https://www.linkedin.com/in/sergio-anaya-sanchez/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://x.com/ParaTuVitalidad">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
  </a>
  <a href="mailto:sergio.anayads@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Correo Electrónico"/>
  </a>
</div>

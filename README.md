<h1 align="left">¡Hola! Soy Juan Ma Alvarado 👋</h1>
<h3 align="left">Data Analyst Jr. & Data Scientist Jr. · Colombiano 🇨🇴</h3>

---

### 🧭 Sobre mí

Estudio Administración en Finanzas y Negocios Internacionales (Universidad de Córdoba) y me metí de lleno en datos: bootcamp de Ciencia de Datos en **Henry** y técnico en Procesamiento de Datos en el **SENA**. Me interesa el cruce entre negocio y modelos — traducir un ROC-AUC o una consulta SQL en una decisión que alguien realmente pueda tomar.

Construí un pipeline de clasificación completo (EDA → feature engineering → modelado → calibración → API → app) para predecir intención de compra en e-commerce, y otro para estimar riesgo crediticio en un caso de Fintech, con foco en evitar *data leakage* y en monitorear el modelo una vez en producción.

Ahora estoy buscando mi primera oportunidad como **Data Analyst** o **Data Scientist Jr.**, idealmente en Fintech o Consultoría. Si estás armando algo en esa línea o simplemente querés hablar de datos, escribime.

---

### 🛠️ Stack de tecnologías

**Con las que trabajo:**

<p align="left">
  <img src="https://skillicons.dev/icons?i=py,mysql,sklearn,fastapi,docker,git,github,githubactions,vscode,linux,bash" />
</p>

**Otras herramientas y librerías que uso habitualmente**:

`Pandas` `NumPy` `Power BI` `LightGBM` `XGBoost` `CatBoost` `Optuna` `MLflow` `Streamlit` `Scrum`

**Ahora mismo estoy profundizando en:**

`Inglés técnico`

---

### 🚀 Proyectos destacados

#### 📦 [Metric Mindset — Predicción de intención de compra (E-commerce)](https://github.com/lucasbottino9/Proyecto-Final-Henry)
Proyecto final del bootcamp de Henry (equipo de 4, rol: Data Scientist — modelado y feature engineering). Sobre 12.330 sesiones de usuario (dataset *Online Shoppers Purchasing Intention*, UCI), comparé 5 modelos de clasificación y optimicé el ganador (LightGBM) con Optuna. Apliqué SMOTE, `class_weight` y calibración sigmoide para corregir el desbalance de clases (84,5% / 15,5%), reduciendo el Brier Score en ~33%, y diseñé una segmentación en 3 niveles de intención de compra para priorizar cross-selling y retención.
**Resultado:** ROC-AUC 0,938 · F1 0,690
**Stack:** `Python` `Scikit-learn` `LightGBM` `XGBoost` `CatBoost` `Optuna` `FastAPI` `Streamlit` `Docker` `MLflow` `GitHub Actions`

#### 💳 [PIM5 — Modelo de riesgo crediticio](https://github.com/Juanma-Alvarado/Mlops_Pipeline)
Pipeline de MLOps end-to-end para predecir si un cliente pagará a tiempo un crédito, combinando datos propios con información del buró de crédito. Detecté y eliminé variables con *data leakage* (una con 0,92 de correlación con el target) antes de modelar, y llevé el pipeline a producción: API en FastAPI, app de scoring en Streamlit, monitoreo de *data drift* (PSI/KS) y CI/CD con GitHub Actions, todo containerizado con Docker.
**Resultado:** PR-AUC 3,1x por encima del baseline
**Stack:** `Python` `Scikit-learn` `XGBoost` `Pandas` `FastAPI` `Streamlit` `Docker` `GitHub Actions`

### 📫 Contacto

<p align="left">
  <a href="mailto:juanmanuel3alvarado@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://linkedin.com/in/TU-USUARIO-DE-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

<!--
**Juanma-Alvarado/Juanma-Alvarado** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

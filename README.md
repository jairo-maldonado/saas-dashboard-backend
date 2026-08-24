# 📊 SaaS Analytics API - FastAPI

API REST para la extracción y procesamiento de métricas financieras, resumen de ventas y datos estadísticos para paneles SaaS. Construida con **FastAPI** y estructurada para consumo analítico desde aplicaciones Front-End.

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Uvicorn](https://img.shields.io/badge/Uvicorn-ASGI-blue?style=for-the-badge)

---

## 🚀 Endpoints Principales

* `GET /analytics/summary` - Entrega métricas clave (ingresos totales, usuarios activos, total de ventas, tasa de crecimiento).
* `GET /analytics/chart` - Retorna la serie temporal mensual de ventas y usuarios para renderizado de gráficos.

---

## ⚙️ Instalación y Ejecución Local

### 1. Clonar el repositorio
```bash
git clone [https://github.com/jairo-maldonado/saas-dashboard-backend.git](https://github.com/jairo-maldonado/saas-dashboard-backend.git)
cd saas-dashboard-backend

Crear y activar el entorno virtual
python -m venv venv
# En Windows (PowerShell):
.\venv\Scripts\activate

Instalar dependencias
pip install -r requirements.txt

Iniciar el servidor
uvicorn app.main:app --reload
Servidor disponible en http://127.0.0.1:8000 y documentación Swagger en http://127.0.0.1:8000/docs.

👤 Autor
Jairo Maldonado - Desarrollador Full-Stack Junior

LinkedIn: Jairo Maldonado

GitHub: @jairo-maldonado
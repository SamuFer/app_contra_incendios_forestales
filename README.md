# 🔥 IgnisGuard - Monitoreo e Inteligencia Contra Incendios Forestales (`app_contra_incendios_forestales`)

![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=Leaflet&logoColor=white)

Plataforma de visualización, análisis histórico y prevención temprana de incendios forestales desarrollada para la **Cubethon 2026**.

---

## 🚀 Características Principales

* **🗺️ Visor de Mapa de Calor Interactivo:** Generado con Leaflet.js y CARTO Dark Tiles para identificar puntos de calor y nivel de riesgo por Comunidades Autónomas.
* **📊 Análisis Histórico Comparativo:** Selección de datos por año (2024, 2025, 2026) para detectar recurrencias de incendios y planificar campañas preventivas.
* **🛰️ Simulación de Telemetría Dron (IoT):** Módulo de monitoreo en tiempo real con datos de temperatura térmica, batería y coordenadas GPS.
* **🤖 Algoritmo de Predicción IA:** Evaluación automatizada basada en condiciones meteorológicas (regla de los 30) para alertar sobre riesgos de ignición en las siguientes 24 horas.
* **📞 Marcación Rápida de Emergencia:** Acceso directo e integrado con servicios de respuesta rápida (112).

---

## 🛠️ Stack Tecnológico

* **Frontend:** Astro (Framework ultra ligero orientado a rendimiento)
* **Estilos:** Tailwind CSS
* **Mapas:** Leaflet.js
* **Contenerización:** Docker + Nginx (Multi-stage build)
* **Despliegue:** Dokploy / Cubephas Infraestructure

---

## 💻 Desarrollo Local

```bash
# 1. Clonar el repositorio
git clone [https://github.com/TU_USUARIO/app_contra_incendios_forestales.git](https://github.com/TU_USUARIO/app_contra_incendios_forestales.git)

# 2. Entrar al directorio
cd app_contra_incendios_forestales

# 3. Instalar dependencias
npm install

# 4. Iniciar servidor de desarrollo
npm run dev
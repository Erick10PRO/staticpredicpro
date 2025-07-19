# ⚽ StatPredic Pro

**StatPredic Pro** es una plataforma web avanzada para análisis deportivo en tiempo real, visualización de estadísticas, predicciones inteligentes y chat IA contextual. ¡Ideal para apostadores, analistas deportivos y fanáticos del deporte!

---

## 🚀 Tecnologías

- **Frontend**: React + Vite + TailwindCSS
- **Backend**: FastAPI + Python
- **Base de datos**: PostgreSQL
- **IA**: OpenAI GPT-4 para análisis y preguntas de los usuarios
- **Despliegue**: Railway (backend) + Vercel (frontend)

---

## 📦 Estructura del Proyecto

```
statpredic_pro/
├── backend/          # FastAPI con endpoints deportivos e IA
├── frontend/         # React con diseño moderno y responsivo
├── database/         # Esquema PostgreSQL
├── infra/            # Configuración para Railway y Vercel
├── public/           # Logos SVG modo claro y oscuro
├── docs/             # Guía visual y PDF de presentación
└── README.md         # Esta documentación
```

---

## 🧪 Ejecutar en local

### 1. Clonar el proyecto

```bash
git clone https://github.com/tuusuario/statpredic_pro.git
cd statpredic_pro
```

### 2. Configurar variables de entorno

Crea un archivo `.env` en `backend/` con:

```env
API_SPORTS_KEY=891725a824e1930358ee968b66924944
OPENAI_API_KEY=TU_OPENAI_API_KEY
```

Y en `frontend/.env`:

```env
VITE_BACKEND_URL=http://localhost:8000
```

### 3. Ejecutar backend

```bash
cd backend
uvicorn app.main:app --reload
```

### 4. Ejecutar frontend

```bash
cd frontend
npm install
npm run dev
```

---

## ☁️ Despliegue en producción

### 🔹 Backend en Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/YOUR_TEMPLATE_ID)

1. Haz clic en el botón arriba
2. Agrega las variables de entorno `API_SPORTS_KEY` y `OPENAI_API_KEY`
3. Railway desplegará el backend automáticamente

### 🔹 Frontend en Vercel

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/tuusuario/statpredic_pro)

1. Haz clic en el botón
2. Configura la variable `VITE_BACKEND_URL` con la URL del backend en Railway

---

## 💬 Chat IA Deportivo

El sistema incluye un chatbot contextual con IA que responde preguntas sobre:

- Estadísticas en vivo de partidos
- Predicciones y value-bets
- Análisis de rendimiento de jugadores y equipos

---

## 📊 Extras incluidos

- `PresentacionPremium.pdf`: resumen profesional del sistema
- `GuiaVisual.pdf`: pasos visuales para desplegar y usar la plataforma
- Logos `SVG` en modo claro y oscuro

---

## ✅ Licencia

MIT – puedes usar este sistema para proyectos personales o comerciales.

---

> Hecho con pasión por el deporte y la tecnología 🧠⚽📊

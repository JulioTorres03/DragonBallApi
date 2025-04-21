# 🐉 Dragon Ball Characters Web App

Aplicación web desarrollada en **React** que consume la API oficial de personajes de Dragon Ball (https://dragonball-api.com). La interfaz permite visualizar los personajes en tarjetas visuales, filtrarlos por género, y ver sus detalles usando ruteo con React Router.

---

## 🚀 Características

- ✅ Consumo de API con `fetch`
- ✅ Tarjetas (cards) estilizadas con Material UI (MUI)
- ✅ Rutas dinámicas con `react-router-dom`
- ✅ Filtro por género (`Masculino`, `Femenino`) usando funciones de orden superior
- ✅ Animación flotante en imagen del personaje
- ✅ Navbar fijo y navegación fluida
- ✅ Código modular, limpio y funcional
- ✅ Totalmente responsives

---

## 🧩 Estructura del Proyecto

```
/src
├── components/
│   ├── Navbar.jsx
│   └── CharacterCard.jsx
├── pages/
│   ├── Home.jsx
│   ├── Male.jsx
│   ├── Female.jsx
│   ├── CharacterDetail.jsx
│   └── About.jsx
├── App.jsx
├── App.css
└── index.js
```


## 🔗 Enlaces

- [API Dragon Ball](https://dragonball-api.com)
- [Sitio Web de la API](https://web.dragonball-api.com)
- [Documentación oficial de MUI](https://mui.com)
- [Vercel Deployment (opcional)](https://vercel.com)

---

## 👨‍💻 Tecnologías utilizadas

- React
- React Router DOM
- Material UI
- Fetch API
- CSS personalizado

---

## 🧠 Funcionalidades clave

- **Página Home:** galería de personajes con diseño responsive.
- **Detalle por personaje:** al hacer clic, se muestra la información completa usando `useParams`.
- **Navbar:** navegación entre rutas (`Inicio`, `Masculino`, `Femenino`, `Acerca de`).
- **Filtros por género:** usando `filter()` sobre los resultados de la API.
- **Manejo de errores:** carga y errores con consola segura.

---

## 📌 Autor

Desarrollado por: [Tu Nombre]  
Estudiante de Ingeniería de Sistemas - 2025-I  
Universidad [Nombre de tu universidad]

---

## 📃 Licencia

Este proyecto es solo con fines educativos.

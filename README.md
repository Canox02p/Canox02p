<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=22D3EE&center=true&vCenter=true&width=600&lines=Bienvenido+a+mi+perfil+%F0%9F%91%8B;Soy+Uriel+Cano;Desarrollador+Full+Stack;Enfoque+en+Frontend;Construyendo+el+Futuro+%F0%9F%9A%80)](https://github.com/Canox02p)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=800&color=94A3B8&center=true&vCenter=true&width=600&lines=role+%3D+'Ingeniero+en+sotfware%C3%B3n';stack+%3D+%5B'React'%2C+'TypeScript'%2C+'Node.js'%2C+'Go'%5D;status+%3D+'Disponible+para+freelance')](https://github.com/Canox02p)

![Profile Views](https://komarev.com/ghpvc/?username=Canox02p&color=blueviolet&style=flat-square)

</div>

---

## 🧑‍💻 Sobre mí

Soy **desarrollador full stack con enfoque principal en frontend**, con experiencia construyendo sistemas reales de principio a fin: una **plataforma SaaS de punto de venta para restaurantes**, una **plataforma SaaS multi-tenant para clínicas de optometría** y una **herramienta de conexión remota de baja latencia escrita en Go**.

- 📍 México · Disponible para **freelance y consultoría** — remoto, presencial o híbrido
- 🎓 Estudiante de **Tecnologías de la Información e Innovación Digital (TIID)** en la **Universidad Politécnica de Pachuca (UPP)**
- 🎨 Me especializo en construir **interfaces pulidas y sistemas de diseño consistentes**, respaldadas por backends sólidos (Node.js, Express, Prisma, PostgreSQL)
- 🏛️ Arquitectura limpia (SOLID, Controller → Service → Repository), código mantenible y escalable
- 🎯 Busco proyectos donde el código resuelva **problemas reales de negocio**
- 💼 Abierto a colaborar como **desarrollador y consultor en proyectos freelance**

---

## 🚀 Proyectos Destacados

### 🍽️ [Menu-Master](https://github.com/Canox02p/menu-master) — Sistema POS SaaS para Restaurantes

> Plataforma SaaS de punto de venta **multi-empresa** con pantalla de cocina (KDS) en **tiempo real vía Socket.io**, inventario con recetas y almacenes, módulo económico con IVA, **facturación CFDI 4.0**, panel de super admin con planes y suscripciones, y dos apps (web + móvil) construidas con Expo Router compartiendo lógica en un monorepo.

**Lo más interesante:**
- 🔴 KDS en tiempo real sin polling: comandas por WebSocket con aislamiento por tenant, semáforo de tiempos configurable por estación y **modo offline** (caché + cola de mutaciones)
- 🏢 Multi-tenant real: cada restaurante aísla mesas, inventario, personal, ventas y métricas; multi-rol por empleado con selección de rol al entrar
- 🔐 Seguridad completa: JWT, bcrypt, invalidación de sesiones, auditoría append-only, rate limiting y validación con Zod
- 🎨 Sistema de diseño centralizado (design tokens, tema claro/oscuro, color de marca personalizable)

**Stack:** React Native · Expo Router · TypeScript · Node.js · Express · Prisma · PostgreSQL · Socket.io · Zod

[![Ver repositorio](https://img.shields.io/badge/Ver%20repositorio-181717?style=flat-square&logo=github)](https://github.com/Canox02p/menu-master)

---

### 👁️ [VisionCore](https://github.com/Canox02p/VisionCore) — SaaS Multi-tenant para Ópticas

> Plataforma SaaS para ópticas y consultorios optométricos: pacientes, consultas clínicas (OD/OI), inventario de armazones y micas, punto de venta, taller con tablero Kanban, sistema de suscripción con **30 días de prueba gratis** y panel de super admin con MRR, reportes, reembolsos y auditoría.

**Lo más interesante:**
- 💳 Suscripciones validadas vía JWT (sin queries a BD por request), flujo completo de cancelación y reembolso con modales de confirmación tipográfica
- 🔔 **Notificaciones a Telegram** para tickets nuevos (patrón fire-and-forget, fail-safe)
- 🔒 Aislamiento estricto por tenant en cada controller y pantalla de sesión intervenida con motivo
- 🎨 Tema dinámico (modo claro/oscuro + 8 colores de acento) y landing con identidad de marca propia

**Stack:** React 19 · TypeScript · Vite · Tailwind CSS 4 · Node.js · Express 5 · Prisma 7 · PostgreSQL · motion/react · Recharts

[![Ver repositorio](https://img.shields.io/badge/Ver%20repositorio-181717?style=flat-square&logo=github)](https://github.com/Canox02p/VisionCore)

---

### 🖥️ Media Link Overlay — Conexión Remota de Baja Latencia

> Programa de escritorio desarrollado en **Go** para la **conexión remota entre dispositivos con baja latencia**. Permite enlazar equipos de forma directa priorizando el rendimiento y la mínima demora en la transmisión.

**Lo más interesante:**
- ⚡ Enfoque en **baja latencia** y eficiencia en la comunicación entre dispositivos
- 🧩 Overlay ligero que corre de forma nativa en el escritorio

**Stack:** Go

---

## 🧪 Otros Proyectos

| Proyecto | Descripción | Stack |
|---|---|---|
| 📚 [MindUp](https://github.com/Canox02p/MindUp) | App móvil educativa (proyecto de la asignatura de aplicaciones móviles) para facilitar el estudio de cualquier materia. Integra una **IA que genera preguntas y ejercicios** con un enfoque gamificado estilo Duolingo. | App móvil · IA |
| 🛒 [EL-OFERTON](https://github.com/Canox02p/EL-OFERTON) | Bot de Telegram que recolecta ofertas de **Mercado Libre** mediante un sniffer y las **publica automáticamente** en un canal de Telegram. | Bot de Telegram · Scraping |
| 🤖 [Asistente](https://github.com/Canox02p/asistente) | Proyecto experimental en **Python** que centraliza varias IAs en un solo lugar: toma **apuntes automáticos en videollamadas** y aplica mejoras/limpieza de audio y video en tiempo real. | Python · IA |

---

## 🛠️ Tech Stack

**Frontend**

![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

**Bases de datos**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

**Herramientas**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Canox02p&show_icons=true&theme=tokyonight&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Canox02p&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Canox02p&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

💬 **¿Tienes un proyecto en mente?** Estoy disponible para desarrollo y consultoría freelance.

</div>

# 🎵 Syncro - Plataforma de Conexión para Músicos (Frontend)
**Proyecto Final — Bootcamp Soy Henry | Full Stack Developer**

[![Next.js](https://img.shields.io/badge/Next.js-15.5-black?logo=next.js&logoColor=white)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.0-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.0-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

## 💻 Back
[Backend Repository](https://github.com/Mogo943/musician-social-network-backend)

---
## 📋 Descripción General

Este repositorio aloja la **Interfaz de Cliente (Frontend)** de Syncro, una plataforma colaborativa diseñada para conectar músicos, bandas y oportunidades laborales.

Construido con la arquitectura moderna **App Router de Next.js 15** y **React 19**, el frontend ofrece una experiencia de usuario fluida, reactiva y tipada estáticamente. Implementa un sistema de autenticación robusto con Auth0, gestión de estados complejos y un panel administrativo integral con control de roles (RBAC).

---

## 📚 Documentación de Arquitectura

Para ver el mapa de componentes, jerarquía de proveedores y flujo de autenticación, consulta nuestra documentación viva:

👉 **[Explorar Arquitectura Frontend en DeepWiki](https://deepwiki.com/pf-henry-g3/front)**

---

## 🚀 Funcionalidades Principales

### 🔍 Exploración y Descubrimiento (/home)
* **Interfaz Unificada:** Visualización normalizada de Bandas, Músicos y Vacantes en un solo feed.
* **Filtrado en Tiempo Real:** Capacidades de búsqueda dinámica y filtros combinados.
* **Paginación Optimizada:** Navegación eficiente de grandes volúmenes de datos.

### 🔐 Autenticación y Seguridad
* **Flujo Dual Auth0:** Implementación híbrida usando `@auth0/nextjs-auth0` (Server-side) y `@auth0/auth0-react` (Client-side).
* **Sincronización Backend:** Validación automática de tokens y sincronización de datos de usuario con la API.
* **Persistencia:** Manejo de sesiones mediante `localStorage` y Context API con actualización automática de tokens.

### 🛡️ Panel Administrativo (RBAC)
* **Protección de Rutas:** Redirección inteligente basada en roles (`Admin`, `SuperAdmin`).
* **Gestión de Usuarios:** Herramientas para banear/desbanear usuarios y asignar roles.
* **Moderación:** Control de contenido para publicaciones, reseñas y vacantes.
* **Herramientas:** Envío de correos masivos y visualización de transacciones de pago.

### 🎨 UX/UI Moderna
* **Diseño Responsivo:** Estilizado con **Tailwind CSS 4** y motor Lightning CSS.
* **Formularios Robustos:** Gestión de estado con **Formik** y validación de esquemas con **Yup**.
* **Feedback Visual:** Notificaciones modales integradas con **SweetAlert2**.

---

## 🛠 Stack Tecnológico

| Categoría | Tecnologías |
| :--- | :--- |
| **Core Framework** | Next.js 15.5.6 (App Router), React 19.2.0 |
| **Lenguaje** | TypeScript 5 |
| **Estilos & UI** | Tailwind CSS 4.1, SweetAlert2, React-Select |
| **Estado & Forms** | React Context API, Formik 2.4, Yup 1.7 |
| **Networking** | Axios (con Interceptors y Token Injection) |
| **Autenticación** | Auth0 SDKs (Next.js & React) |

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,html,css,git,github,vscode,npm,vercel" />
  </a>
</p>

---

## ⚙️ Instalación y Configuración

### Prerrequisitos
* Node.js v20+
* NPM

### 1. Clonar el repositorio
```bash
git clone [https://github.com/pf-henry-g3/front.git](https://github.com/pf-henry-g3/front.git)
cd front
2. Instalar dependencias
Bash

npm install
3. Configurar Variables de Entorno
Crea un archivo .env.local en la raíz y configura la conexión con el Backend y Auth0:

Bash

NEXT_PUBLIC_API_URL=http://localhost:3000 # O tu URL de producción
# Credenciales de Auth0 (Client ID, Domain, Secrets)
4. Iniciar Servidor de Desarrollo
Bash

npm run dev
La aplicación estará disponible en http://localhost:3000.
```

### 📫 Autores
- 💼 [**Agostina Gaggioli**](https://www.linkedin.com/in/agostina-gaggioli-4495ba234/)
- 💼 [**Carlos Mogollon**](https://www.linkedin.com/in/carlosmogollon-it/)
- 💼 [**Santiago Rivero**](https://www.linkedin.com/in/santriv06/)
- 💼 [**Fernando Arancibia**](https://github.com/fernando-arancibia)
- 💼 [**Ignacio Aguirre**](https://www.linkedin.com/in/ignacioaguirresite/)
- 💼 [**Nicolas Scilipoti**](https://www.linkedin.com/in/nicolas-scilipoti/)

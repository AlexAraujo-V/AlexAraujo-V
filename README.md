<div align="center">

# ¡Hola, soy Alex! 👋

<img src="https://github.com/alex03av/alex03av/assets/105180364/06b4f0ca-a00c-4f8b-b3a5-a5daeaa4fb32" alt="Banner" width="100%" />

<p>
  <strong>💻 Ingeniero de software Full Stack</strong><br/>
  Web (React · Next.js), backend (Node.js · Laravel), apps iOS/Android nativas y<br/>
  <strong>agentes de IA y orquestadores (LangGraph)</strong> con foco en<br/>
  <em>rendimiento, escalabilidad y experiencia de usuario</em>
</p>

<p>
  <a href="https://alex03av.github.io/Portafolio-Front-End-Developer/">
    <img src="https://img.shields.io/badge/🌐_Portafolio-FF6B6B?style=for-the-badge&logoColor=white" alt="Portafolio"/>
  </a>
  <a href="mailto:aaraujovalles@gmail.com">
    <img src="https://img.shields.io/badge/📧_Email-4ECDC4?style=for-the-badge&logoColor=white" alt="Email"/>
  </a>
  <a href="https://www.linkedin.com/in/alexander-araujo-03840a258/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

</div>

---

## 🚀 Sobre mí

Ingeniero de software con cerca de 4 años de experiencia construyendo interfaces y plataformas
para agencias y productos digitales, en remoto. Empecé en frontend (React, Next.js, WordPress
a medida), desde 2025 trabajo también en backend (APIs, pagos, automatización, paneles de
administración) y desde 2026 desarrollo apps móviles: probé React Native y hoy trabajo en
nativo con Swift (iOS) y Kotlin (Android).

<table>
<tr>
<td width="50%">

### 👨‍💻 Lo que hago
- 🎨 Interfaces con **React / Next.js** y Tailwind
- 📱 Apps móviles: **Swift/SwiftUI** (iOS), **Kotlin/Jetpack Compose** (Android) y **React Native**
- ⚙️ Backend con **Node.js** y **Laravel (PHP 8)**
- 💳 Integración de pagos (Stripe, PayPal) y soporte (Zendesk)
- 🤖 **Agentes de IA multi-agente y orquestadores** (LangChain, LangGraph, OpenAI, Anthropic)
- 🔁 Colas de trabajo y automatización de procesos
- 🧩 Themes y plugins **WordPress** 100 % a medida

</td>
<td width="50%">

### 🧠 Mi filosofía
- 🌱 Aprendizaje continuo y adaptación
- 🧩 Resolver problemas complejos de forma simple
- 🎨 Diseño centrado en el usuario
- ⚡ Código limpio y mantenible

</td>
</tr>
</table>

---

## 🤖 IA, Agentes y Orquestación

Parte de mi trabajo reciente es diseñar y operar **sistemas de IA en producción** para la plataforma CodigosDTC:

- 🧠 **Orquestador multi-agente** (Node.js 20, Express 5, **LangChain + LangGraph**): cada turno del chat corre como un grafo que arma el contexto, invoca al modelo y ejecuta herramientas.
- 🧩 **Especialistas por dominio** (diagnóstico, diagramas, visión e investigación) que corren en *runs* hijos con un plazo propio que nunca supera el del turno padre; si se agota devuelven un resultado parcial en vez de colgar la conversación.
- ⚡ **Tool calling en paralelo** y **tareas en segundo plano cancelables**: los diagnósticos largos se siguen generando y llegan al chat cuando terminan.
- 🔎 **Búsqueda semántica con embeddings** (`text-embedding-3-small`) con caché por hash de contenido, para encontrar el diagrama eléctrico correcto de cada vehículo.
- 👁️ **Visión y lectura de diagramas**: análisis de fotos de fallas y piezas, y lectura de diagramas SVG como datos estructurados (componentes, conectores y pines), sin depender de visión.
- 🎙️ **Voz en tiempo real**: asistente por voz con GPT-Live sobre **WebRTC**, con una conexión *sideband* donde cada delegación se convierte en un turno normal del orquestador.
- 🚗 **Memoria por vehículo** y **decodificación y verificación de VIN** (ISO 3779: dígito verificador, año y fábrica) antes de confiar en lo que lee el modelo.
- 📊 **Telemetría por turno**: pasos, tokens y coste de cada ejecución.
- 🔀 **Multi-modelo**: OpenAI y Anthropic intercambiables desde el panel de administración.
- 🖼️ **Servicio de imágenes con IA**: servicio independiente en TypeScript (arquitectura hexagonal con reglas de dependencias verificadas por pruebas) que genera imágenes con Gemini, valida reglas medibles con `sharp` y las revisa con un modelo de visión (≈ US$ 0,0007 por imagen).
- 🔐 **Seguridad**: adjuntos servidos solo con URLs firmadas que caducan.

---

## 💼 Experiencia reciente

| Periodo | Rol | Qué hice |
|:--|:--|:--|
| **Oct 2026 – Actualidad** | Ingeniero de software · CodigosDTC | Responsable técnico de la plataforma: panel de administración (Next.js 15), orquestador de IA (Node.js, LangChain) y servicio de generación de imágenes con revisión por IA. |
| **Mar 2026 – Actualidad** | Desarrollador de apps móviles (iOS y Android) · CodigosDTC | Primera versión en React Native (Expo) rechazada en App Store; migré a nativo con arquitectura hexagonal: iOS en Swift + SwiftUI (StoreKit 2, Sign in with Apple, push, chat) y Android en Kotlin + Jetpack Compose (Hilt, Room, Socket.IO, Stripe, Google Play Billing). |
| **Ene 2026 – Actualidad** | Programador Full Stack · CodigosDTC | PWA de diagnóstico automotriz con miles de usuarios activos (Next.js 15, React 18, TypeScript), backend Laravel/PHP, chat en tiempo real, Stripe y despliegue en Docker. |
| **Sep 2025 – Ene 2026** | Desarrollador Back-end · Organización privada de tramitación de visados (remoto, España) | Backend Laravel/Node.js de portales multi-país: pagos, panel de administración y cola de procesamiento de solicitudes. Proyectos privados. |
| **Nov 2024 – Sep 2025** | Frontend Web Developer · CodigosDTC (media jornada) | Next.js, TypeScript y Tailwind, multi-idioma y SEO; theme WordPress a medida con plugins propios. |
| **Jul 2024 – Abr 2025** | React Developer · Getalink (Andorra, remoto) | UI/UX de plataforma SaaS de linkbuilding con React, Next.js, SASS y Bootstrap bajo arquitectura hexagonal. |
| **Abr 2023 – Jun 2024** | Frontend Web Developer · Gotta Be Public (España, remoto) | Mantenimiento y desarrollo en Next.js y WordPress para agencia digital; SEO y rendimiento. |
| **Mar 2023 – Jun 2024** | Desarrollador WordPress · Independiente | Themes desde cero, plugins, shortcodes y widgets a medida. |
| **Nov 2022 – Jun 2024** | Frontend Web Developer · Independiente | Interfaces con Next.js, React y Tailwind para clientes freelance. |

---

## 🎓 Formación y certificaciones

- 🎓 **TSU en Informática** — Colegio Universitario de Administración y Mercadeo (2021–2024)
- 📜 **Laravel 12: de cero a experto** — Victor Arana Flores · Udemy, completado el 26/10/2026 · [Ver certificado](https://www.udemy.com/certificate/UC-dffadcce-50ca-40ec-83e9-99dd26ecbd94/)
- 📜 **Máster en APIs RESTful con Node.js** — Express y MongoDB (2024)
- 📜 Diseño web adaptable · Algoritmos y estructuras de datos en JavaScript · React y Bootstrap (2021–2022)

---

## 🛠️ Arsenal Tecnológico

### 🎨 Frontend Development
<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
</p>

### ⚛️ Frameworks & Libraries
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/Astro-FF5D01?style=for-the-badge&logo=astro&logoColor=white" alt="Astro"/>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white" alt="Vue.js"/>
  <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white" alt="Redux"/>
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite"/>
</p>

### 🎨 Styling & Design
<p>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/SASS-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="SASS"/>
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma"/>
</p>

### 📱 Mobile
<p>
  <img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white" alt="Swift"/>
  <img src="https://img.shields.io/badge/SwiftUI-0D96F6?style=for-the-badge&logo=swift&logoColor=white" alt="SwiftUI"/>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin"/>
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose"/>
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native"/>
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo"/>
  <img src="https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase"/>
</p>

### 🗄️ Backend & Database
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express"/>
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"/>
  <img src="https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white" alt="WordPress"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socket.io&logoColor=white" alt="Socket.IO"/>
</p>

### 🤖 IA, Agentes & Integraciones
<p>
  <img src="https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white" alt="Stripe"/>
  <img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal"/>
  <img src="https://img.shields.io/badge/Zendesk-03363D?style=for-the-badge&logo=zendesk&logoColor=white" alt="Zendesk"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI"/>
  <img src="https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white" alt="Anthropic"/>
  <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Google Gemini"/>
  <img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white" alt="WebRTC"/>
</p>

### 🛠️ Tools & Platforms
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code"/>
  <img src="https://img.shields.io/badge/Xcode-147EFB?style=for-the-badge&logo=xcode&logoColor=white" alt="Xcode"/>
  <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white" alt="Android Studio"/>
</p>

---

## 📊 Estadísticas de GitHub

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=AlexAraujo-V&show_icons=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="GitHub Stats"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AlexAraujo-V&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Languages"/>
</div>

---

## 🤝 Conectemos

<div align="center">

<a href="mailto:aaraujovalles@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
<a href="https://www.linkedin.com/in/alexander-araujo-03840a258/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://wa.link/qpfrsb"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/></a>
<a href="https://msng.link/o/?Araujosev=tg"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/></a>

### 🚀 ¿Tienes un proyecto en mente? ¡Hablemos!

<a href="https://alex03av.github.io/Portafolio-Front-End-Developer/">
  <img src="https://img.shields.io/badge/Ver_mi_trabajo-FF6B6B?style=for-the-badge&logoColor=white" alt="Ver Portafolio"/>
</a>

<p>
  <img src="https://komarev.com/ghpvc/?username=AlexAraujo-V&color=blueviolet&style=for-the-badge" alt="Profile Views"/>
</p>

<img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />

</div>

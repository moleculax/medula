# MenuAdmin - Restaurantes Menu QR

Sistema de gestión para restaurantes que permite administrar menús digitales y generar códigos QR dinámicos para cada establecimiento. Solución moderna y escalable para el sector de la restauración.

---

## 🏢 Arquitectura Multi-Tenant

MenuAdmin está diseñado con una arquitectura **multi-tenant**, lo que significa que una única instancia de la aplicación puede atender a múltiples restaurantes de forma aislada y segura.

### ¿Qué significa Multi-Tenant?

Cada restaurante (tenant) opera en su propio espacio dentro de la plataforma, con:

- 🔒 **Aislamiento de datos**: Cada restaurante solo accede a su propia información
- 🎨 **Personalización independiente**: Cada establecimiento puede personalizar colores, logos y diseño
- 📊 **Métricas separadas**: Estadísticas y reportes por cada negocio
- 👥 **Usuarios propios**: Gestión de personal por cada restaurante
- 💰 **Facturación individual**: Planes y suscripciones por establecimiento

### Beneficios del enfoque Multi-Tenant

| Beneficio | Descripción |
|-----------|-------------|
| **Escalabilidad** | Un solo código base sirve a miles de restaurantes |
| **Eficiencia** | Recursos compartidos, costos optimizados |
| **Seguridad** | Aislamiento total de datos entre clientes |
| **Mantenimiento** | Actualizaciones centralizadas para todos |
| **Onboarding rápido** | Nuevos restaurantes operativos en minutos |

### ¿Cómo funciona?

1. **Registro**: Cada restaurante se registra de forma independiente
2. **Aislamiento**: Los datos se almacenan con identificador de tenant
3. **Personalización**: Configuración propia por cada establecimiento
4. **Facturación**: Planes y suscripciones por tenant

---

## 🎯 Descripción

**MenuAdmin** es una aplicación full-stack diseñada para optimizar la gestión de restaurantes mediante menús digitales y códigos QR. Permite a los establecimientos:

- 📋 Administrar sus menús de forma dinámica
- 📱 Generar códigos QR personalizados para cada restaurante
- 📊 Visualizar y analizar datos de consumo
- 🔄 Actualizar información en tiempo real

La plataforma está construida con tecnologías modernas y optimizada para despliegue en entornos cloud.

---


## 🚀 Tecnologías utilizadas

| Capa | Tecnología | Badge | Descripción |
|------|------------|-------|-------------|
| **Frontend** | Next.js | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white) | Framework React con renderizado híbrido (SSR/CSR) y routing avanzado |
| **Backend** | Spring Boot | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white) | Framework Java robusto con endpoints REST personalizados |
| **Base de Datos** | PostgreSQL | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) | Sistema de gestión de bases de datos relacionales |
| **Cliente HTTP** | Axios | ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white) | Cliente para consumir APIs de forma eficiente desde el frontend |
| **Contenedores** | Docker | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) | Contenedores para entornos de desarrollo y producción |
| **Orquestación** | Docker Compose | ![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white) | Orquestación de contenedores multi-servicio |



---

## 🛠️ Características principales

- ✅ Gestión de restaurantes y establecimientos
- ✅ Administración de menús y productos
- ✅ Generación de códigos QR personalizados
- ✅ Visualización de datos y métricas
- ✅ Panel de control intuitivo
- ✅ Diseño responsive

---

## 📦 Requisitos

| Requisito | Versión | Badge |
|-----------|---------|-------|
| **Docker** | 20.10+ | ![Docker](https://img.shields.io/badge/Docker-20.10+-2496ED?style=for-the-badge&logo=docker&logoColor=white) |
| **Docker Compose** | 2.0+ | ![Docker Compose](https://img.shields.io/badge/Docker_Compose-2.0+-2496ED?style=for-the-badge&logo=docker&logoColor=white) |
| **Tomcat** | 9+ | ![Apache Tomcat](https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=apache-tomcat&logoColor=black) |
| **Java** | 17+ | ![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) |
| **PostgreSQL** | 12+ | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-12+-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) |
---

# MenuAdmin - Despliegue en la Nube

## 🌐 Arquitectura de Despliegue

MenuAdmin está diseñado con una arquitectura moderna que permite desplegar sus componentes de forma independiente en diferentes plataformas cloud, optimizando costos y rendimiento.

---

## 📦 Estrategia de Despliegue Recomendada

### Frontend → Vercel
El frontend de MenuAdmin está optimizado para desplegarse en **Vercel**, la plataforma ideal para aplicaciones Next.js.

**Ventajas de Vercel:**
- 🚀 Despliegue automático desde GitHub
- ⚡ CDN global con renderizado ultrarrápido
- 🔄 Previsualización de cambios en tiempo real
- 🔒 Certificados SSL automáticos
- 💰 Plan gratuito generoso para proyectos personales

---

### Backend → Render (desde GitHub)
El backend Spring Boot se despliega en **Render** conectado directamente a tu repositorio de GitHub, lo que permite un flujo de trabajo continuo y automatizado.

**Configuración en Render:**
1. Conecta tu cuenta de GitHub con Render
2. Selecciona el repositorio de MenuAdmin-Backend


## Visita Previa
https://menuadmin.com 
Para ver la plataforma en acción y descubrir cómo puede transformar tu negocio de restauración.

## 📞 Contacto

Para más información:

- 📧Web: http://emilio.beer


---

*MenuAdmin - Simplificando la gestión de restaurantes digitales.*
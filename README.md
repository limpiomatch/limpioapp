# Suroeste Servicios (Aseo y Cuidado) - PWA

Esta es una Aplicación Web Progresiva (PWA) diseñada para conectar a clientes que requieren servicios de aseo doméstico, planchado, cuidado de niños y adultos mayores con profesionales independientes calificados y previamente verificados en los municipios del Suroeste Antioqueño.

El proyecto prioriza la **seguridad de los hogares**, la **facilidad de uso en zonas con conectividad intermitente** y un modelo de negocio justo para ambas partes.

## 🚀 Características Clave

- **Modelo de Billetera Prepago (Wallet):** Los profesionales recargan su saldo mediante transferencias locales (Nequi/Daviplata) y el sistema descuenta automáticamente la comisión por servicio completado, eliminando la fricción del recaudo.
- **Filtro de Confianza Estricto:** Registro de profesionales con verificación previa de antecedentes de seguridad y referencias por parte de la administración.
- **PWA (Progressive Web App):** Instalable en teléfonos móviles sin necesidad de descargas pesadas desde las tiendas de aplicaciones, optimizando el consumo de datos.
- **Direccionamiento Adaptado al Contexto Local:** Soporte para referencias físicas y landmarks comunes en la región, complementando la geolocalización tradicional.

## 🛠️ Stack Tecnológico

- **Frontend:** React / Vue.js (PWA instalable, optimizado para Mobile-First).
- **Backend:** Node.js (Express o NestJS) como API Gateway.
- **Base de Datos:** PostgreSQL en la nube (Alojado en Supabase) con Seguridad a Nivel de Fila (RLS) habilitada.

## 📊 Arquitectura de Datos (PostgreSQL)

La base de datos cuenta con las siguientes entidades principales creadas bajo un entorno seguro en Supabase:

- `users`: Registro general de Clientes, Profesionales y Administradores.
- `professional_profiles`: Información detallada de verificación, habilidades y saldo de billetera virtual.
- `services`: Catálogo y tarifas de servicios disponibles.
- `bookings`: Gestión de estados de servicios, agendas, direcciones y puntos de referencia.
- `wallet_transactions`: Registro contable inmutable de recargas y comisiones.
- `reviews`: Calificaciones de calidad.

---

## ⚙️ Configuración del Entorno de Desarrollo (Próximamente)

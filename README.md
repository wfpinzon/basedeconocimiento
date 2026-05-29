# 📚 Base de Conocimientos Avanzada - TI Nivel 2

Este repositorio ha sido diseñado y estructurado como un proyecto de optimización para el equipo de Soporte Técnico y Operaciones de TI. El objetivo principal es estandarizar los procesos de diagnóstico, mitigar la dependencia de escalamiento hacia niveles superiores y proporcionar soluciones efectivas a incidentes complejos de infraestructura, redes e identidades.

---

## 🎯 Objetivos e Impacto del Proyecto
* **Reducción del MTTR (Mean Time to Resolution):** Disminución estimada de un 25% en tiempos de atención gracias a metodologías de diagnóstico estandarizadas.
* **Eficiencia Operativa:** Reducción del flujo de tickets mal escalados desde Nivel 1 hacia Nivel 2/3.
* **Cultura Documental:** Fomento de las buenas prácticas de ITIL mediante la gestión activa del conocimiento corporativo.

---

## 🛠️ Índice de Guías Técnicas y Troubleshooting

A continuación, se detallan los manuales técnicos enfocados en el análisis de causa raíz para incidencias críticas:

### 1. 🌐 [Conectividad y Redes Locales](https://github.com/wfpinzon/caidas-red.git) 
* **Alcance:** Diagnóstico profundo de direccionamiento IP (DHCP), resolución de nombres (DNS) y técnicas de restablecimiento de la capa de red mediante consola.

### 2. 👥 [Active Directory y Perfiles de Usuario](https://github.com/wfpinzon/active-directory.git)
* **Alcance:** Reparación de canales seguros y relaciones de confianza con el dominio corporativo, junto con la reconstrucción segura de perfiles locales corruptos (`TEMP`).

### 3. 💻 [Sistemas Operativos y Recuperación (BSOD)](https://github.com/wfpinzon/pantallas-azules.git)
* **Alcance:** Uso de herramientas de despliegue e imagen (DISM) en entornos de recuperación (WinRE) para remover actualizaciones fallidas y reparar la integridad del sistema de archivos.

### 4. ☁️ [Gestión de Identidades Modernas (Entra ID / M365)](guias/04-entra-id-mfa.md)
* **Alcance:** Administración avanzada de accesos, auditoría de *Sign-in Logs*, revocación de sesiones globales y resolución de conflictos con la autenticación multifactor (MFA).

### 5. ⚙️ [Auditoría y Diagnóstico de GPOs](guias/05-diagnostico-gpo.md)
* **Alcance:** Análisis avanzado de la aplicación de directivas de grupo mediante reportes estructurados en HTML (`gpresult`) y validación de conectividad con Controladores de Dominio.

---

## 🔧 Tecnologías y Herramientas Documentadas
* **Sistemas Operativos:** Windows Server / Windows Client / Windows RE
* **Administración de Sistemas:** Microsoft Entra ID, Active Directory Domain Services (AD DS), Group Policy Management
* **Automatización y Consola:** Windows PowerShell, CMD (Command Prompt), DISM, Network Shell (`netsh`)
* **Formato:** Markdown estándar para integración nativa con GitHub

---
*Desarrollado con fines de mejora continua y preparación para la transición al rol de Analista Administrador de Sistemas Junior.*

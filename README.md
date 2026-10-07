# Despliegue Continuo con GitHub Actions y Surge.sh

![Deploy Status](https://github.com/francielgod/Electiva2-despliegue-surge-cicd/actions/workflows/main.yml/badge.svg)
![Surge](https://img.shields.io/badge/Hosted%20on-Surge.sh-blue)
![HTML5](https://img.shields.io/badge/Frontend-HTML5%20%2F%20CSS3-orange)

Proyecto práctico enfocado en la implementación de un flujo de Integración y Despliegue Continuo (CI/CD) automatizado mediante **GitHub Actions** hacia la plataforma de alojamiento estático **Surge.sh**.

---

## Enlace del Proyecto en Vivo

- **Sitio Desplegado:** [https://p1electiva2francielbeltre.surge.sh](https://p1electiva2francielbeltre.surge.sh)
- **Repositorio en GitHub:** [francielgod/Electiva2-despliegue-surge-cicd](https://github.com/francielgod/Electiva2-despliegue-surge-cicd)

---

## Objetivos Cumplidos

1. **Estructura del Proyecto:** Creación de un repositorio local con un frontend estático (`index.html`).
2. **Control de Versiones:** Vinculación y sincronización con el repositorio remoto en GitHub.
3. **Pipeline CI/CD:** Definición del workflow automatizado en `.github/workflows/main.yml`.
4. **Gestión Segura de Credenciales:** Uso de GitHub Repository Secrets (`SURGE_LOGIN` y `SURGE_TOKEN`) para evitar la exposición de credenciales sensibles.
5. **Automatización:** Ejecución del pipeline con cada `git push` a la rama `main`, publicando los cambios inmediatamente en Surge.sh.

---

## Tecnologías y Herramientas

| Componente | Herramienta |
| :--- | :--- |
| **Frontend** | HTML5, CSS3 |
| **Control de Versiones** | Git & GitHub |
| **Integración Continua (CI/CD)** | GitHub Actions |
| **Hosting & Despliegue** | Surge.sh |
| **Entorno de Ejecución** | Node.js (Surge CLI) |

---

## Estructura del Repositorio

```text
mi-web-surge/
├── .github/
│   └── workflows/
│       └── main.yml      # Configuración del pipeline de CI/CD
├── index.html            # Interfaz web principal
└── README.md             # Documentación del proyecto
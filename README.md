# Sistema de Gestión para Taller Mecánico — Trabajo de Titulación

Proyecto académico desarrollado para la gestión de un taller mecánico, con funciones de **registro de clientes**, **servicios**, **stock** y **ventas**, además de **reportes** básicos. Este repositorio contiene:

- 📄 Documentación (`/docs`): manual de usuario, manual de procesos y trabajo de titulación.
- 🧰 Binarios de demostración (`/release`): ejecutable `Taller_V1.0.exe` y una base de datos de ejemplo (`sample_db/taller.db`).

> **Nota:** El ejecutable fue empaquetado con **PyInstaller** y utiliza **SQLite** como base de datos local. Por ahora el código fuente no está incluido en este repositorio público. Si te interesa revisarlo, por favor abre un issue.

---

## 🧪 Funcionalidades principales

- ABM de **clientes**, **servicios** y **productos**.
- Gestión de **stock** y **ventas**.
- **Reportes** y consultas básicas.
- Persistencia en **SQLite** (`taller.db`).

## 🗂 Estructura del repositorio

```
.
├─ docs/                    # Documentación en PDF/DOCX
├─ release/
│  ├─ Taller_V1.0.exe      # Ejecutable (demo)
│  └─ sample_db/
│     └─ taller.db         # Base de datos de ejemplo
├─ .gitignore
├─ LICENSE
└─ README.md
```

## 🖥 Requisitos

- **Windows 10/11** para ejecutar el binario.
- Permisos de lectura/escritura en la carpeta donde se ejecuta el .exe (para acceder a la base de datos).

## ▶️ Ejecución (demo)

1. Descarga la carpeta `release/` (o el **.zip** de la sección *Releases* si está disponible).
2. Ejecuta `Taller_V1.0.exe`.
3. Si se requiere, coloca `sample_db/taller.db` junto al ejecutable (misma carpeta) o en la ruta configurada por defecto.

> Si tu antivirus bloquea el ejecutable por tratarse de un binario no firmado, marca como “permitido” o ejecuta como administrador bajo tu propio criterio.

## 📚 Documentación

- **Manual de Usuario** — `/docs/Manual de Usuario.pdf`
- **Manual de Procesos** — `/docs/Manual de Procesos.pdf`
- **Trabajo de Titulación** — `/docs/Trabajo de Titulacion.pdf`

## 🔧 Stack técnico (build)

- **Python** + **PyInstaller** (empaquetado a `.exe`)
- **SQLite** (`taller.db`)

> Históricamente el proyecto se trabajó con metodologías ágiles (Scrum) y control de versiones en GitHub (repositorio privado durante el desarrollo).

## 🗺 Roadmap (sugerido)

- [ ] Publicar código fuente (limpiado) en `/src`.
- [ ] Añadir pruebas unitarias y de integración.
- [ ] Empaquetado reproducible (scripts de build).
- [ ] Exportación/Importación de datos.
- [ ] Interfaz mejorada y tema oscuro.

## 👥 Autores

- **Fabio Renee Romero** — Analista/Desarrollador
- Colaboradores: ver documentación y/o créditos del trabajo

## 📄 Licencia

Este proyecto está bajo la licencia **MIT** (ver `LICENSE`). Si lo usas con fines académicos, agradeceremos la cita correspondiente.
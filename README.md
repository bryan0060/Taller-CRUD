# 🎓 Sistema de Registro de Profesores

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Una aplicación web moderna para la gestión de profesores con diseño neumórfico**


</div>

---

## 🎯 Objetivo del Proyecto

Este sistema web permite realizar un **registro completo de profesores** de manera intuitiva y eficiente. La aplicación facilita la gestión de información académica mediante operaciones CRUD (Crear, Leer, Actualizar, Eliminar) con una interfaz moderna que implementa **diseño neumórfico** para una experiencia de usuario excepcional.

### ✨ Características Principales

- 📝 **Registro de Profesores**: Formulario intuitivo para capturar información completa
- 👥 **Listado Dinámico**: Visualización en tiempo real de todos los profesores registrados
- ✏️ **Edición In-Situ**: Modificación rápida de datos existentes
- 🗑️ **Eliminación Segura**: Confirmación antes de eliminar registros
- 🎨 **Diseño Neumórfico**: Interfaz moderna con efectos de profundidad
- ⚡ **Operaciones Asíncronas**: Sin recarga de página para mejor UX

---

## 🛠️ Tecnologías Utilizadas

<div align="center">

### Backend
| Tecnología | Versión | Propósito |
|-----------|---------|-----------|
| **Python** | 3.8+ | Lenguaje de programación principal |
| **Flask** | 2.0+ | Framework web ligero y potente |
| **SQLite3** | Built-in | Base de datos embebida |

### Frontend
| Tecnología | Propósito |
|-----------|-----------|
| **HTML5** | Estructura semántica de la aplicación |
| **CSS3** | Diseño neumórfico y responsive |
| **JavaScript (ES6+)** | Interactividad y comunicación asíncrona |
| **Fetch API** | Peticiones HTTP sin recarga de página |

</div>

### 🏗️ Arquitectura

```
📦 Sistema de Registro de Profesores
├── 🎨 Capa de Presentación
│   ├── index.html      # Estructura de la interfaz
│   ├── style.css       # Diseño neumórfico
│   └── script.js       # Interactividad del cliente
├── ⚙️ Capa de Lógica de Negocio
│   └── backend.py      # API REST y reglas de negocio
└── 💾 Capa de Datos
    └── productos.db    # Base de datos SQLite
```

---

## 🚀 Instalación y Ejecución

### 📋 Prerrequisitos

```bash
# Verificar versión de Python
python --version  # Debe ser 3.8 o superior
```

### 🔧 Instalación

1️⃣ **Clonar el repositorio**
```bash
git clone https://github.com/bryan0060/Taller-CRUD.git
cd Taller-CRUD
```

2️⃣ **Crear entorno virtual (Recomendado)**
```bash
# Crear entorno virtual
python -m venv venv

# Activar entorno virtual
# En Windows:
venv\Scripts\activate
# En macOS/Linux:
source venv/bin/activate
```

3️⃣ **Instalar dependencias**
```bash
pip install flask
```

### ▶️ Ejecución

```bash
# Ejecutar la aplicación
python backend.py
```

🌐 **Acceder a la aplicación**: Abrir navegador en `http://localhost:5000`

### 🛑 Detener la aplicación

```bash
# Presionar Ctrl + C en la terminal
# Desactivar entorno virtual (opcional)
deactivate
```

---

## 📱 Captura del Resultado

<div align="center">

### 🖥️ Vista Principal
![Captura](https://i.imgur.com/sFqfhNn.png).



> **Nota**: Las capturas muestran el diseño neumórfico implementado con efectos de profundidad y sombras suaves que proporcionan una experiencia visual moderna y profesional.

</div>

---

## 📁 Estructura del Proyecto

```
📂 crud_IS/
├── 📄 backend.py              # Servidor Flask y API REST
├── 📂 static/
│   ├── 🎨 style.css          # Estilos neumórficos
│   ├── ⚡ script.js          # Funcionalidad JavaScript
│   ├── 🖼️ banner.jpg         # Imagen superior
│   └── 🖼️ footer.jpg         # Imagen inferior
├── 📂 templates/
│   └── 📄 index.html          # Plantilla principal
├── 🗄️ productos.db           # Base de datos (generada automáticamente)
└── 📖 README.md              # Este archivo
```

---

## 🚀 Funcionalidades Implementadas

### ✅ Operaciones CRUD Completas

- **✨ Crear**: Registro de nuevos profesores
- **👀 Leer**: Visualización de todos los profesores
- **📝 Actualizar**: Edición de información existente  
- **🗑️ Eliminar**: Eliminación con confirmación

### 🎨 Características de Diseño

- **🌊 Neumorfismo**: Efectos de profundidad y sombras
- **📱 Responsivo**: Adaptable a diferentes dispositivos
- **⚡ Interactivo**: Transiciones y efectos hover
- **🎯 Intuitivo**: Navegación clara y simple

### 🔧 Características Técnicas

- **🔄 SPA Behavior**: Sin recarga de página
- **📡 API REST**: Endpoints bien estructurados
- **🛡️ Validación**: Control de datos de entrada
- **💾 Persistencia**: Almacenamiento en SQLite

---

## 🤝 Contribuir

Las contribuciones son bienvenidas. Para cambios importantes:

1. 🍴 Fork el proyecto
2. 🌿 Crear una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push a la rama (`git push origin feature/AmazingFeature`)
5. 🔃 Abrir un Pull Request

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

---

## 👨‍💻 Créditos del Autor

<div align="center">

### 🎓 Bryan Arias Rios - Alejandro Berrio Ospina - Farly Andres Rivera David

**📧 Contacto Académico**: `barias@unilasallista.edu.co   -   aberrio@unilasallista.edu.co  - frivera@unilasallista.edu.co`  
**🏫 Institución**: Corporación Universitaria Unilasallista
**📚 Curso**: Ingeniería de Software 1  
**📅 Período Académico**: 2025-1  

---


[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tu-usuario)

</div>

---

<div align="center">

**⭐ Si este proyecto te fue útil, no olvides darle una estrella ⭐**

*Última actualización: 28/05/2025*

</div>

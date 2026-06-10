# 💧 Amigos de 5° – Blog Educativo Hugo Leonelli

Plataforma educativa desarrollada para estudiantes de **5° Grado de la Escuela Hugo Leonelli**, diseñada para compartir proyectos, producciones, experiencias de aprendizaje y recursos digitales en un entorno seguro y colaborativo.

---

## ✨ Características Principales

### 👨‍🎓 Acceso para estudiantes

- Inicio de sesión mediante nombre y apellido.
- Publicación de contenidos propios.
- Participación en proyectos del grado.
- Visualización de publicaciones de compañeros.

### 👩‍🏫 Panel de administración docente

- Gestión de alumnos.
- Creación y administración de proyectos.
- Edición y eliminación de publicaciones.
- Control de acceso mediante Firebase Authentication.

### 📰 Sistema de publicaciones

Permite crear:

- 📝 Textos
- 🖼️ Imágenes
- 🎵 Audios
- 🎬 Videos
- 📄 Documentos
- 🔗 Enlaces

### ☁️ Firebase Storage

Almacenamiento seguro de:

- Imágenes
- Audios
- Videos
- Documentos PDF
- Archivos Office

### 📚 Recursos Digitales Integrados

Acceso directo a:

- Matific
- Historias para Armar
- Club de Lectura

---

## 🚀 Tecnologías Utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura de la aplicación |
| CSS3 | Diseño responsivo |
| JavaScript ES6 | Lógica y funcionalidades |
| Firebase Authentication | Gestión de usuarios |
| Firestore Database | Base de datos en tiempo real |
| Firebase Storage | Almacenamiento de archivos |

---

## 🔥 Configuración Firebase

```javascript
const firebaseConfig = {
  apiKey: "TU_API_KEY",
  authDomain: "TU_PROYECTO.firebaseapp.com",
  projectId: "TU_PROYECTO",
  storageBucket: "TU_PROYECTO.firebasestorage.app",
  messagingSenderId: "XXXXXXXX",
  appId: "XXXXXXXX"
};
```

---

## 📂 Estructura de Firestore

### Colección: `students`

```json
{
  "nombre": "Juan",
  "apellido": "Pérez"
}
```

### Colección: `posts`

```json
{
  "title": "Mi proyecto",
  "body": "Contenido...",
  "authorId": "idAlumno",
  "authorName": "Juan Pérez",
  "category": "Guardianes del Oro Azul",
  "date": 123456789
}
```

### Colección: `sections`

```json
{
  "name": "Guardianes del Oro Azul",
  "emoji": "💧",
  "order": 1
}
```

---

## 🔐 Acceso Docente

La autenticación docente se realiza mediante Firebase Authentication.

**Usuario administrador:** `admin@blog5leonelli.app`

**Contraseña** — Formato: `nombre_apellido_DNI`

Ejemplo: `ana_rodriguez_12345678`

Configurada previamente desde:

```
Firebase Console → Authentication → Users
```

---

## 📁 Estructura del Proyecto

```
blog-educativo/
│
├── index.html
├── README.md
│
├── Firebase
│   ├── Authentication
│   ├── Firestore
│   └── Storage
│
├── Publicaciones
│   ├── Texto
│   ├── Imagen
│   ├── Audio
│   ├── Video
│   └── Documento
│
└── Recursos Digitales
    ├── Matific
    ├── Historias para Armar
    └── Club de Lectura
```

---

## 🎯 Objetivos Pedagógicos

Este blog busca:

- Fomentar la escritura digital.
- Desarrollar competencias comunicativas.
- Potenciar el trabajo colaborativo.
- Difundir proyectos escolares.
- Promover la ciudadanía digital responsable.
- Integrar tecnologías emergentes en el aula.

---

## 🌈 Proyectos Iniciales

- 💧 Guardianes del Oro Azul
- 📰 Periodistas del Oro Azul
- 🏗️ Construyendo Ilusiones
- 🌈 Más Allá del Arcoíris

---

## 📱 Diseño Responsivo

Compatible con:

- 💻 Computadoras
- 📱 Celulares
- 📲 Tablets

---

## ❤️ Créditos

**Escuela Hugo Leonelli**
**5° Grado – Ciclo Lectivo 2026**

Docente responsable: **Ana Rodríguez**

Proyecto educativo desarrollado para promover la producción digital, la creatividad, la comunicación y el aprendizaje colaborativo mediante herramientas tecnológicas y Firebase.

---

© 2026 – Amigos de 5° Hugo Leonelli

*"Aprender juntos, crear juntos y compartir nuestras ideas con el mundo."* 🌍✨

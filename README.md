# PROF. YORK | Docente de Programación & Software Developer

Bienvenido/a a mi espacio de GitHub. Este perfil funciona como punto central para el acceso a proyectos de cátedra, guías de actividades, trabajos prácticos, recursos de capacitación y desarrollos de software.

---

## 📌 Para Estudiantes: Estándares de Entrega, Actividades, Guías y Trabajos Prácticos

Para la entrega de actividades, proyectos finales e informes técnicos en las materias a cargo, se deben respetar de manera estricta las siguientes pautas institucionales:

## 🛠️ Control de Versiones (Git & GitHub)
- **Flujo de trabajo obligatorio:** Utilizar ramas `main` (código estable de producción) y `development` (desarrollo e integración de características).
- **Commits:** Mensajes claros, descriptivos y en tiempo presente siguiendo *Conventional Commits* (ej: `feat: agrega validacion de punteros en modulo C++`).
- **Commits limpios:** No subir archivos temporales, binarios compilados (`.exe`, `.o`, `.out`) o carpetas de configuración del IDE (`.vscode`, `node_modules`). Incluir siempre `.gitignore`.

## 📄 Entregables Documentales (Informes Técnicos)
- **Formato:** Todo trabajo escrito o documentación técnica debe entregarse bajo estándar **Informe APA v7**.
- **Estructura:** Debe incluir únicamente el formato de Informe APA v7 con sus correspondientes citas parentéticas y la carátula integrada correctamente según las pautas de cátedra.
- **Formato de archivo:** PDF o exportación limpia desde Markdown/LaTeX.

---

## 💻 Estructura Obligatoria del Repositorio de Entrega
Para los proyectos finales y entregas de código puro, los repositorios de los estudiantes deben respetar la siguiente arquitectura de directorios estándar de la industria:

```text
nombre-del-proyecto-final/
│
├── src/                # (Source) Todo el código fuente de la aplicación (archivos .cpp, .py)
├── include/            # (Sólo para C/C++) Archivos de cabecera (.h, .hpp)
├── docs/               # Documentación, el informe APA v7 en PDF solicitado, manual del programador, manual de usuario
│   ├── InformeEESTX_LPR20XX_GXX_v2.0.0.pdf 
│   └── manuales/
│       ├── manual_programador_v1.0.0.pdf 
│       └── manual_usuario_v1.0.0.pdf
├── assets/             # Imágenes, íconos, bases de datos SQL de prueba
├── test/               # Scripts para probar el código
│
├── .gitignore          # Archivo para ignorar compilados (.exe, .o) y basura del IDE
├── .gitattributes      # Archivo de adición para normalizar saltos de línea (CRLF/LF)
├── CHANGELOG.md        # Historial de versiones (Mejor en la raíz, no dentro de docs)
├── README.md           # Presentación del proyecto y guía de instalación
└── LICENSE             # Licencia del proyecto (MIT, GPL)
```

---

## 💻 Tech Stack & Herramientas

| Categoría | Tecnologías y Herramientas |
| :--- | :--- |
| **💻 Lenguajes:** | ![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) |
| **🌐 Desarrollo Web & DB:** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white) ![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/postgresql-4169e1?style=for-the-badge&logo=postgresql&logoColor=white) |
| **🛠️ Herramientas & IDEs:** | ![VS Code](https://img.shields.io/badge/VS_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white) ![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Lucidchart](https://img.shields.io/badge/Lucidchart-F8991D?style=for-the-badge&logo=lucid&logoColor=white) |
| **🚀 Despliegue & Entornos:** | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white) ![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white) ![Moodle](https://img.shields.io/badge/Moodle-F98012?style=for-the-badge&logo=moodle&logoColor=white) ![Google Classroom](https://img.shields.io/badge/Google_Classroom-008F68?style=for-the-badge&logo=google%20classroom&logoColor=white) |

---

## 📚 Repositorios y Ejercitación

En este perfil encontrarás repositorios categorizados para el cursado y consulta:

- 🔹 **Punteros y Memoria:** Estructuras en C/C++, manipulación de cadenas y punteros (`cadenaspunteros`).
- 🔹 **Algoritmos Base:** Operaciones matemáticas, estructuras de control y lógica pura (`calculadoraedad`, `calculoarea`).
- 🔹 **Proyectos Web & Sistemas:** Estructura modular, bases de datos y desarrollo backend/frontend.

---

## 💼 Capacitaciones & Desarrollo Freelance

Además del ámbito educativo formal, realizo capacitaciones técnicas para empresas y desarrollo de soluciones de software a medida.

- 🛠️ **Servicios:** Capacitaciones en código limpio, arquitectura de software, talleres de Git/GitHub y desarrollo web/backend.
- 📩 **Contacto Profesional e Institucional:**
- [![Email](https://img.shields.io/badge/Gmail-webapplicationsdevelopmentde@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:webapplicationsdevelopmentde@gmail.com)
- 📍 **Ubicación:** Buenos Aires, Argentina

---

> *Clean code, buenas prácticas y arquitectura antes que solo líneas de código.*

## 📊 Mis Estadísticas Docentes y de Desarrollo

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=webappdeved&theme=radical&show_icons=true&hide_border=true&count_private=true" alt="Estadísticas de Prof. York" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=webappdeved&theme=radical&show_icons=true&hide_border=true&layout=compact" alt="Lenguajes más usados" />
</div>

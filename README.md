# 🏥 Sistema de Administración de Clínica - Versión Compilada

Sistema integral para la gestión de consultorios médicos desarrollado en **Java**. Este repositorio contiene la versión compilada del software, lista para su implementación inmediata.

---

## ⚙️ Instalación y Configuración

Al tratarse de una versión compilada, no es necesario realizar procesos de construcción (build). Sigue estos pasos:

1. **Requisitos de Sistema:**
   - Tener instalado **Java Runtime Environment (JRE)** o JDK versión 17 o superior.
   - Verificar la instalación ejecutando `java -version` en tu terminal.

2. **Preparación:**
   - Descarga los archivos de la carpeta `out` o `bin` (donde se encuentren los archivos `.class`).
   - Asegúrate de que todos los archivos de clases estén en el mismo directorio.

3. **Ejecución:**
   - Abre una terminal en la carpeta del proyecto y ejecuta:
     ```bash
     java Main
     ```

---

## 🚀 Uso del Programa

El sistema guía al usuario a través de una interfaz de consola interactiva:

1. **Control de Acceso:** - Ingresa con las credenciales de administrador. (Usuario: `admin` / Clave: `1234`). El acceso se valida mediante un `HashMap` para garantizar seguridad y velocidad.
   
2. **Administración de Datos:**
   - **Doctores y Pacientes:** Regístralos primero. El sistema genera un ID alfanumérico automático (ej. `D-101`, `P-202`) que servirá como llave primaria.
   - **Citas:** Utiliza los IDs generados para vincular a un médico con un paciente.

3. **Base de Datos (CSV):**
   - El programa utiliza archivos `.csv` para la persistencia. Si los archivos no existen, se crearán automáticamente al realizar el primer guardado.
   - **Importante:** Al cerrar el programa usando la opción `0`, se garantiza la integridad de la base de datos.



---

## 👥 Créditos

Proyecto desarrollado como aplicación práctica de conceptos avanzados de Programación Orientada a Objetos, manejo de colecciones y persistencia en sistemas de archivos.

- **Desarrollador:** Jesus Sergio Castro Lainez
- **Institución:** Universidad Tecmilenio 
- **Tecnologías:** Java Standard Edition, File I/O, Streams API.

---

## 📄 Licencia

Este proyecto se distribuye bajo la **Licencia MIT**. Es de código abierto y permite su modificación y distribución para fines educativos y profesionales.

---

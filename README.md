# 🏥 Sistema de Administración de Clínica 

Sistema integral para la gestión de consultorios médicos desarrollado en **Java**. Esta versión ha sido empaquetada en un archivo **Fat JAR**, lo que permite su ejecución inmediata sin necesidad de compilar código fuente.

---

## ⚙️ Instalación y Configuración

Al ser un archivo ejecutable empaquetado, la configuración es mínima:

1. **Requisitos de Sistema:**
   - Tener instalado **Java Runtime Environment (JRE)** o JDK versión 17 o superior.
   - Verificar la instalación abriendo una terminal y escribiendo: `java -version`.

2. **Ubicación:**
   - Coloca el archivo `.jar` en una carpeta dedicada. 
   - **Nota:** El programa creará los archivos de base de datos (`.csv`) en la misma carpeta donde se encuentre el JAR.

3. **Ejecución:**
   - **Windows/Linux/Mac (Terminal):** Abre una terminal en la carpeta del archivo y ejecuta:
     ```bash
     java -jar Consultorio.jar
     ```

---

## 🚀 Uso del Programa

El sistema opera mediante una interfaz de consola interactiva con los siguientes módulos:

1. **Control de Acceso (Login):**
   - El acceso está protegido para administradores.
   - **Usuario:** `admin`
   - **Contraseña:** `1234`
   - *Validación instantánea mediante HashMaps.*

2. **Administración de Entidades:**
   - **Doctores y Pacientes:** Registro con generación de IDs automáticos para evitar colisiones de datos.
   - **Citas:** Vinculación relacional entre un Doctor y un Paciente mediante sus IDs.

3. **Persistencia de Datos (CSV):**
   - El sistema actúa como una base de datos real. Al realizar altas o bajas, los cambios se sincronizan en archivos `doctores.csv`, `pacientes.csv` y `citas.csv`.
   - Para asegurar que no haya pérdida de información, utilice siempre la opción **"0. Salir y Guardar"**.



---

## 👥 Créditos

Proyecto desarrollado para demostrar la implementación de Programación Orientada a Objetos (POO) y persistencia de archivos en Java.

- **Desarrollador:** Jesus Sergio Castro Lainez
- **Tecnologías:** Java 17, Collections Framework, I/O Stream, IntelliJ Artifacts.

---

## 📄 Licencia

Este proyecto se distribuye bajo la **Licencia MIT**. Es de código abierto y permite su libre modificación y distribución para fines académicos o profesionales.

---

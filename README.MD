Aquí tienes el **`README.md`** completo para **EasyFolderLock Pro**, utilizando exactamente la misma estructura profesional, formato de badges, tablas de la imagen/plantilla y diseño GitHub Markdown:

---

#  EasyFolderLock Pro

> ## 🔐 Protección Avanzada de Carpetas mediante Cifrado Seguro para Windows
> 
> 
> **EasyFolderLock Pro** es la versión avanzada de EasyFolderLock, diseñada para usuarios y entornos profesionales que necesitan funciones adicionales de seguridad, integraciones con el sistema operativo y herramientas avanzadas para proteger, administrar y restaurar sus carpetas de forma ágil y cómoda.
> Comprime, cifra y empaqueta tus directorios en un archivo único `.lock` protegido mediante cifrado de grado militar.

---

# ✨ Características Principales

EasyFolderLock Pro incluye todas las funciones de la versión Free y añade herramientas avanzadas de administración e integración:

### 🔐 Protección Criptográfica

* **Cifrado AES-GCM:** Protección simétrica de alta seguridad para la confidencialidad e integridad de tus datos.
* **Derivación Robusta:** Uso de **Salt** y **Nonce** aleatorios por cada operación de cifrado.
* **Formato EFL1:** Estructura de contenedor propia (*EasyFolderLock Format 1*) con verificación de integridad.
* **Protección Anti-sobrescritura:** Previene pérdidas accidentales durante el proceso de restauración.
* **Compresión ZIP Integrada:** Optimiza el espacio comprimiendo los archivos antes de cifrarlos.

### 📂 Administración de Archivos y Menú Contextual

* **Integración con Windows:** Opción para bloquear carpetas y desbloquear archivos `.lock` directamente desde el menú contextual del Explorador de Windows.
* **Asociación de Archivos:** Apertura directa e integración nativa con archivos `.lock`.
* **Arrastrar y Soltar (Drag & Drop):** Soporte intuitivo para cargar carpetas y contenedores al instante.
* **Operaciones Múltiples:** Bloqueo y desbloqueo simultáneo de varios archivos `.lock`.
* **Modo Invisible:** Opción para ocultar archivos `.lock` en el Explorador de Windows.

### ⚡ Funciones Avanzadas Pro

* **Bloqueo Rápido:** Procesa y protege tus datos con un solo clic.
* **Cofres Seguros y Historial:** Monitoreo y registro detallado de operaciones realizadas.
* **Verificación Avanzada:** Comprobación de integridad del archivo antes de la extracción.
* **Modo Portable:** Ejecución flexible en unidades extraíbles.

---

# 🔒 ¿Cómo funciona?

### 📥 Proceso de Bloqueo

```text
Carpeta ➔ Compresión ZIP ➔ Cifrado AES-GCM ➔ Archivo protegido (.lock)

```

### 📤 Proceso de Desbloqueo

```text
Archivo .lock ➔ Contraseña ➔ Verificación ➔ Descifrado ➔ Carpeta restaurada

```

---

# 🛡️ Formato Interno EFL1

Los archivos protegidos por EasyFolderLock Pro utilizan una estructura de contenedor estructurada:

$$\text{EFL1} + \text{Salt} + \text{Nonce} + \text{Datos cifrados}$$

* **`EFL1`**: Cabecera identificadora de formato (*EasyFolderLock Format 1*).
* **Extensión nativa:** `.lock` (Ejemplos: `Documentos.lock`, `Proyectos.lock`, `Fotos.lock`).

---

# 💎 Comparativa de Licencias y Descarga

---

---

# 🔑 Sistema de Licencias y Prueba Gratuita

EasyFolderLock Pro incluye un sistema de gestión de licencias digitales:

* 🧪 **Prueba gratuita de 15 días:** Evalúa todas las funciones avanzadas Pro sin compromiso antes de adquirir una licencia.
* 📅 **Opciones de Licencia:** Disponibilidad de licencias anuales o vitalicias (*Lifetime*).
* 🔒 **Activación Segura:** Validación de licencia local/remota.

> [!NOTE]
> La licencia activa las herramientas y comodidades de la edición Pro, pero la seguridad criptográfica de tus archivos depende de la fortaleza de tu contraseña.

---

# 🚀 Modo de Uso

### Bloquear una Carpeta

1. Haz clic derecho sobre una carpeta y selecciona **Bloquear con EasyFolderLock Pro** (o ábrela desde la app).
2. Ingresa y confirma tu contraseña.
3. Configura las opciones avanzadas (conservar copia, ocultar `.lock`, etc.).
4. Presiona **Bloquear**.

### Desbloquear una Carpeta

1. Haz doble clic en el archivo `.lock` o selecciónalo en la aplicación.
2. Ingresa tu contraseña.
3. Elige la carpeta de destino para restaurar los archivos y confirma.

---

# ⚠️ Importante / Notas de Seguridad

> [!CAUTION]
> **Conserva tu contraseña:** EasyFolderLock **NO** puede recuperar el contenido de un archivo `.lock` si olvidas la clave. Ni siquiera el soporte de licencias Pro puede ignorar o revertir el cifrado.

> [!WARNING]
> Se recomienda mantener copias de seguridad de datos críticos. Asegúrate de emplear contraseñas seguras y complejas.

---

# 📦 Requisitos del Sistema

| Requisito | Especificación |
| --- | --- |
| **Sistema Operativo** | Windows 10 o superior (x64) |
| **Entorno de Ejecución** | Python 3.10+ (si se ejecuta desde el código fuente) |
| **Librerías Requeridas** | `PyQt5`, `cryptography` |

### Instalación de dependencias (Código fuente)

```bash
pip install PyQt5 cryptography

```

---

# 🐛 Reportar un Problema

Si experimentas un error o falla en la aplicación, puedes abrir un **Issue** adjuntando:

* Versión exacta de EasyFolderLock Pro.
* Versión del sistema operativo Windows.
* Pasos para reproducir el error.
* Capturas de pantalla o mensajes de error recopilados.

> [!IMPORTANT]
> **Privacidad:** Nunca adjuntes claves de licencia, contraseñas, archivos `.lock` personales ni información confidencial al reportar un problema.

---

# 📄 Licencia

El software EasyFolderLock Pro es propiedad intelectual de **Escudo Digital SV**. Consulta el archivo de términos y condiciones incluido con el programa para obtener detalles sobre los derechos de uso y distribución.

---

## 🌐 Escudo Digital SV

Desarrollado con ❤️ por **Escudo Digital SV**

🌐 Sitio web oficial: [escudodigitalsv.com](https://escudodigitalsv.com)

© 2026 Escudo Digital SV. Todos los derechos reservados.

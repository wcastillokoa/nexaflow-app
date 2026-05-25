# 🚀 NexaFlow Technologies - MVP Prototipo

Este repositorio contiene el código fuente del Producto Mínimo Viable (MVP) para la plataforma de automatización de procesos con Inteligencia Artificial **NexaFlow**. El diseño ha sido desarrollado aplicando la arquitectura de información "Desktop-First" y bajo la metodología ágil Scrum.

---

## 📋 1. Historias de Usuario Implementadas

A continuación se detallan las 5 Historias de Usuario que describen las necesidades del negocio y cuya solución técnica ya se encuentra integrada en los archivos HTML del proyecto:

### 🔑 Historia de Usuario 1: Acceso al Sistema Automatizado
* **Como:** Usuario registrado de NexaFlow.
* **Quiero:** Iniciar sesión con mi correo y contraseña o mediante redes sociales (Google/GitHub).
* **Para:** Acceder de manera segura a mi panel de control de automatizaciones.
* **Implementación:** Archivo `login.html`. Contiene validaciones `required`, prevención de recarga nativa con JavaScript y enrutamiento directo.

### 📊 Historia de Usuario 2: Visualización de Métricas Críticas (KPIs)
* **Como:** Administrador de operaciones de la empresa.
* **Quiero:** Ver el número de flujos activos, tareas completadas hoy y la tasa de éxito de la IA en un panel centralizado.
* **Para:** Tomar decisiones rápidas sobre la infraestructura y monitorear la salud de los procesos en tiempo real.
* **Implementación:** Archivo `dashboard.html`. Maquetado con CSS Grid, incluye 3 tarjetas de indicadores clave y una sección de analíticas visuales.

### 🔍 Historia de Usuario 3: Filtrado y Búsqueda del Blog Editorial
* **Como:** Usuario interesado en tecnologías de automatización.
* **Quiero:** Filtrar los artículos del blog por categorías (IA, Producto, Casos de uso) y buscar por palabras clave.
* **Para:** Encontrar rápidamente contenido educativo de mi interés.
* **Implementación:** Archivo `blog.html`. Integra componentes interactivos superiores de filtrado temático en línea y barra de búsqueda de texto.

### 🌐 Historia de Usuario 4: Enrutamiento a Casos de Éxito Externos
* **Como:** Cliente potencial evaluando la plataforma.
* **Quiero:** Hacer clic en un artículo destacado de IA para leer la noticia completa en un portal oficial gubernamental.
* **Para:** Validar la veracidad del uso de la IA en el entorno real.
* **Implementación:** Archivo `blog.html`. Tarjeta de artículo destacado enrutada de forma segura hacia el portal del MinTIC usando el atributo perimetral `target="_blank"`.

### 💳 Historia de Usuario 5: Comparativa Visual de Planes de Suscripción
* **Como:** Usuario gratuito buscando escalar el servicio.
* **Quiero:** Visualizar una tabla clara de precios donde el Plan PRO se destaque sobre las demás opciones.
* **Para:** Identificar rápidamente la opción recomendada que ofrece la mejor relación costo-beneficio.
* **Implementación:** Archivo `precios.html`. Caja de suscripción destacada asimétricamente mediante el color de acento `#E94560`, sombras pronunciadas y badge flotante de "Recomendado".

---

## 🛠️ 2. Control de Versiones (Uso de Comandos Git)

El flujo de trabajo y la auditoría del código se estructuraron de forma local simulando las directrices de ingeniería de software con los siguientes comandos requeridos:
1. **`git clone`**: Para la descarga inicial del entorno.
2. **`git status`**: Para auditar el estado del directorio.
3. **`git ignore`**: Configurado vía `.gitignore` para excluir carpetas basura de los editores (`.vscode/`).
4. **`git branch`**: Para la creación de la rama de desarrollo independiente `feature-historias-usuario`.
5. **`git add`** y **`git commit`**: Para el empaquetado y registro cronológico de los cambios.
6. **`git log`**: Para la visualización de la línea de tiempo.
7. **`git remote`** y **`git push`**: Para la gestión de enlaces remotos y subida segura mediante Tokens Personales de Acceso Clásicos (PAT).

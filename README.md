# UPSTART

## 1. Integrantes del proyecto
El proyecto ha sido desarrollado en pareja, dividiendo las responsabilidades en función de las competencias técnicas y de administración de sistemas de cada uno:

* **Sukhdeep Singh Kaur** * **Rol:** Responsable Tecnológico y Administrador de Sistemas.
    * **Responsabilidades:** Arquitectura y programación de la aplicación web, modelado de la base de datos, seguridad de los descriptores de ideas, configuración del servidor local sobre arquitectura (Raspberry Pi) y automatización de despliegues mediante contenedores.
* **Jordi Zalkaliani**
    * **Rol:** Responsable de Negocio, Diseño y Comunidad (Product Owner / Community Manager).
    * **Responsabilidades:** Diseño de la interfaz de usuario, definición de las historias de usuario del foro, gestión y verificación del panel de mentores, estrategias de marketing digital y definición del modelo financiero.

## 2. Objetivos

- Crear un entorno seguro para validar ideas de negocio sin miedo al plagio.

- Conectar el talento joven con la experiencia de mentores consolidados en España.

- Fomentar la colaboración mediante un sistema de gamificación (Karma).

- Ofrecer una alternativa viable y adaptada al mercado local siguiendo modelos de éxito internacionales.

## 3. Explicación del proyecto

**UpStart** es una plataforma web colaborativa planteada conceptualmente como el "Reddit de los fundadores". El proyecto responde a una necesidad real identificada en el ecosistema emprendedor en Cataluña: la falta de métodos eficientes y entornos de confianza para que los emprendedores noveles puedan validar si su idea de start-up puede funcionar antes de gastar recursos económicos u horas de desarrollo. Las estadísticas globales confirman que un 42% de las start-ups fracasan precisamente por lanzar productos que no cubren ninguna necesidad real del mercado.

### Público Objetivo
La plataforma se dirige específicamente a jóvenes de entre 20 y 35 años que tienen ideas de negocio anotadas pero que están paralizados por el desconocimiento, la inseguridad personal o el miedo al robo de la propiedad intelectual.

### Funcionamiento y Funcionalidades Principales
* **Registro Ágil:** El usuario accede mediante el navegador y se registra en pocos clics a través de métodos de autenticación seguros, seleccionando su rol dentro de la comunidad.
* **Publicación de ideas:** Los creadores rellenan un formulario estructurado para poder publicar su idea.
* **Gamificación Peer-to-Peer:** Los usuarios interactúan y reciben críticas constructivas. El creador valora la utilidad de este *feedback* de 1 a 5 estrellas, haciendo que los mentores y usuarios con mejor criterio suban en el ranking público de reputación.
* **Modelo de Negocio:** Se aplica una estructura *Freemium*. El acceso y lectura básicos son gratuitos, pero se ofrece un plan Premium (5€ - 15€/mes) que habilita publicaciones ilimitadas, mejor visibilidad del proyecto en el foro y consultas privadas 1-a-1 con expertos.

## 4. Material del proyecto
Para llevar a cabo tanto el desarrollo del software como el despliegue de la infraestructura de red, se ha separado el material requerido en hardware y software:

### 4.1 Hardware (Maquinaria)
* **Equipos de desarrollo:** Ordenadores portátiles con conexión a internet.
* **Servidor local:** Placa Raspberry Pi para alojar el despliegue del proyecto.

### 4.2 Software (Programas y Aplicaciones)
* **Tecnologías de Aplicación:** Lenguajes estándares del desarrollo web (HTML, CSS, JavaScript y Tailwind CSS).
* **Base de Datos y Backend:** Supabase.
* **Entorno de desarrollo integrado:** Visual Studio Code.
* **Sistema Operativo del Servidor:** *Raspberry Pi OS Lite*.
* **Soporte:** Inteligencias artificiales generativas para resolución de problemas de código.

## 5. Desarrollo y despliegue
### 5.1 Desarrollo de la aplicación web
La página web se ha construido separando la parte visual (frontend) de la gestión de datos (backend):
* **Frontend:** Hemos utilizado **HTML** y **JavaScript** en toda la web para que sea interactiva (por ejemplo, para el modo oscuro o el sistema de valoración por estrellas). Para los estilos visuales, usamos **CSS normal** en la página de inicio y **Tailwind CSS** en el resto de páginas.
* **Backend:** Utilizamos **Supabase** para gestionar de forma segura el registro de usuarios, el inicio de sesión (Login) y guardar todas las ideas y comentarios del foro.
* **Herramientas de apoyo:** Para el apartado gráfico usamos **Design.com** (logo), **Freepik y Pixabay** (iconos y recursos), **Remove.bg** (borrar fondos) y la API de **ui-avatars.com** (generar fotos de perfil automáticamente).

### 5.2 Despliegue del Servidor
Para que la web sea accesible a los usuarios, dividimos el despliegue en dos fases:
* **Fase de pruebas:** Al principio, utilizamos plataformas gratuitas como **GitHub Pages y Vercel** para hacer pruebas rápidas de visualización mientras programábamos.
* **Servidor en Producción (Raspberry Pi):** El despliegue final lo hicimos creando nuestro propio servidor local utilizando la **Raspberry Pi**. 
* **Configuración:** Instalamos el sistema operativo Linux (*Raspberry Pi OS Lite*) porque consume muy pocos recursos. 

## 6. Planificación

### 6.1 Historias de Usuario
Para organizar el desarrollo, definimos historias de usuario clave que guiaron nuestro trabajo:
* *"Como emprendedor, quiero publicar mi idea de negocio ocultando datos sensibles para recibir feedback sin miedo al plagio."*
* *"Como mentor, quiero poder valorar las ideas y comentar para ganar puntos de reputación en la comunidad."*
* *"Como usuario Premium, quiero acceder a chats privados con expertos para recibir un análisis detallado de mi proyecto."*

### 6.2 Sprints y Diagrama de Gantt
#### Sprint 1: Diseño y Maquetación Base de la App
* **Objetivo:** Creación de una página web simple para la comprobación inicial del entorno y preparación del primer despliegue de prueba.
* **Tarea 1:** * [x] Generación de la estructura base del sitio web.
    * [x] Configuración de repositorios y despliegue continuo (GitHub Pages y Vercel).
* **Tarea 2:**
    * [x] Estructuración del sitio web.
    * [x] Desarrollo del código HTML y CSS interactivo.

#### Sprint 2: Documentación Técnica y Elaboración del Informe
* **Objetivo:** Creación del informe para documentar el proyecto y los procesos de desarrollo del servidor y la página web.
* **Tarea 1:** * [x] Creación y redacción detallada del archivo README por apartados.
* **Tarea 2:**
    * [x] Descripción de las herramientas de desarrollo.
    * [x] Especificación de la lógica JavaScript.
    * [x] Creación y estructuración de la presentación final del proyecto.

#### Sprint 3: Desarrollo Avanzado y Funcionalidades de la App
* **Objetivo:** Aplicar lógica de programación avanzada para dotar a la web de características interactivas profesionales.
* **Tarea 1:** * [x] Diseño del módulo de registro (*Login*).
    * [x] Interconexión con la base de datos externa en Supabase.
* **Tarea 2:**
    * [x] Programación con JavaScript dinámico del flujo del foro (publicación de ideas).
    * [x] Estructuración técnica de las ventajas de los planes Premium.

#### Sprint 4: Configuración del Entorno de Servidor Físico
* **Objetivo:** Creación y preparación del servidor local integrado de desarrollo sobre Raspberry Pi.
* **Tarea 1:** * [x] Instalación limpia de la distribución base Linux (Raspberry Pi OS).
    * [x] Puesta en funcionamiento físico de la máquina.

#### Sprint 5: Implementación y Despliegue del Sistema
* **Objetivo:** Implementar la aplicación web dentro del servidor Linux de la Raspberry Pi para su salida a producción local.
* **Tarea 1:**
    * [x] Mejora continua de la página web.
    * [x] Pulido de detalles y funcionalidades adicionales en el entorno de producción local.

#### Sprint 6: Auditorías, Control de Calidad y Revisión Final
* **Objetivo:** Revisar de manera crítica y exhaustiva todo el trabajo realizado para garantizar la entrega del producto final.
* **Tarea 1:**
    * [x] Control de errores de la web y verificación del diseño.
    * [x] Validación de la conectividad de la Raspberry Pi.
* **Tarea 2:**
    * [x] Pruebas integrales del sistema.
    * [x] Corrección estilística final de la memoria escrita.

```mermaid
gantt
    title Planificación del proyecto UPSTART
    dateFormat  YYYY-MM-DD
    axisFormat  %m/%d
    tickInterval 1week

    section SPRINT 1
    SPRINT 1 :active, s1, 2026-04-20, 14d

    section SPRINT 2 
    SPRINT 2 :s2, 2026-04-27, 28d

    section SPRINT 3 
    SPRINT 3 :s3, 2026-05-11, 21d

    section SPRINT 4 
    S.4 :s4_p1, 2026-06-01, 2d

    section SPRINT 5 
    SPRINT 5 :s5, 2026-06-01, 14d

    section SPRINT 6
    SPRINT 6 :crit, s6, 2026-06-15, 12d
```


## 7. Webgrafía


1. Gemini: [Gemini](https://gemini.google.com/?hl=es-ES)
2. CB insights: [CB-insights](https://www.cbinsights.com/research/report/startup-failure-reasons-top/?utm_campaign=newsletter_general_RU_hs&utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_r5i1mlG2vB4AjvIRlyLdHDMBh7jXhgGp-hR6FvVYuLbf6GPeAGr9e26MzcMezVPBUZd3J)
3. BBVA : [BBVA](https://www.bbva.com/es/innovacion/por-que-fracasan-las-startups/)


## 8. Anexos

<p align  ="center">
  <img src="./imagenes/readme/capt1.png" width="600">
  <img src="./imagenes/readme/capt2.png" width="600">
  <img src="./imagenes/readme/capt7.png" width="600">
  <img src="./imagenes/readme/capt3.png" width="600">
  <img src="./imagenes/readme/capt8.png" width="600">
  <img src="./imagenes/readme/capt4.png" width="600">
  <img src="./imagenes/readme/capt5.png" width="600">
  <img src="./imagenes/readme/capt6.png" width="600">
  <img src="./imagenes/readme/capt9.png" width="600">
  <img src="./imagenes/readme/capt10.png" width="600">
  <img src="./imagenes/readme/capt11.png" width="600">
  <img src="./imagenes/readme/capt12.png" width="600">
  <img src="./imagenes/readme/capt13.png" width="600">
  <img src="./imagenes/readme/capt14.png" width="600">
  <img src="./imagenes/readme/capt15.png" width="600">
</p>
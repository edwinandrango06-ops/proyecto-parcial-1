
# Ecuador Destino Vivo - Sitio Web Turístico

## Objetivo del Proyecto

Desarrollar y presentar una plataforma web turística interactiva aplicando estándares modernos de desarrollo con HTML5 semántico y CSS3 puro bajo el enfoque Mobile First.

---

## Tecnologías Utilizadas

* **HTML5 & CSS3:** Estructura semántica, diseño adaptable mediante CSS Grid y Flexbox.
* **Sistemas de Diseño:** Metodología *Mobile First* y diseño responsivo optimizado.
* **Estructura Modular:** Páginas múltiples interconectadas (`index`, `destinos`, `galeria`, `paquetes`, `itinerarios`, `contacto`).
* **Docker:** Contenerización de la aplicación.
* **GitHub & Docker Hub:** Control de versiones y distribución de imágenes.

---

## Estructura del proyecto

```text
Proyecto/
├── css/
│   └── estilo.css
├── img/
├── contacto.html
├── destinos.html
├── galeria.html
├── index.html
├── itinerarios.html
└── paquetes.html

```

### Descripción de componentes

* **`index.html`**: Página principal que contiene el menú de navegación.
* **`destinos.html`**: Sección dedicada a mostrar la información detallada de los cuatro destinos clave (Quito, Baños, Galápagos y Cuenca).
* **`galeria.html`**: Cuadrícula visual adaptativa con imágenes representativas de los atractivos turísticos del país.
* **`paquetes.html`**: Presentación de planes organizados con precios, duración y servicios incluidos.
* **`itinerarios.html`**: Cronograma detallado de actividades organizadas por días y horarios específicos.
* **`contacto.html`**: Formulario interactivo para que los usuarios envíen consultas o solicitudes de viaje.
* **`estilo.css`**: Hoja de estilos unificada que define la paleta de colores moderna, tipografías del sistema, Flexbox y CSS Grid con *auto-fit*.
* **`Carpeta img/`**: Directorio centralizado para los recursos gráficos del sitio web.

---

## Instrucciones para Ejecutar desde Docker Hub

Si deseas descargar y probar la imagen directamente desde tu repositorio en Docker Hub, ejecuta los siguientes comandos en tu terminal:

```bash

docker pull edwinan21/proyecto-parcial-1

docker run -d -p 8080:80 edwinan21/proyecto-parcial-1
```

Una vez ejecutado, abre tu navegador web e ingresa a **`http://localhost:8080`** para visualizar tu proyecto en funcionamiento.

O caso contrario puedes acceder al repositorio de Docker mediante este enlace:

**`https://hub.docker.com/r/edwinan21/proyecto-parcial-1/tags`**

# Landing-Page
Documentacion para manejo y edicion de la landing page

Este proyecto es una página web construida con Astro, React, Angular, y Tailwind CSS. La página es completamente responsiva y adaptada para funcionar tanto en dispositivos móviles como en escritorios. Está diseñada para ofrecer una experiencia de usuario dinámica y moderna utilizando las tecnologías más recientes.

## Tecnologías Usadas
### Astro: 
Generador de sitios estáticos para construir la página web.
### React: 
Librería para construir interfaces de usuario interactivas.
### Angular: 
Framework para crear aplicaciones web robustas y escalables.
### Tailwind CSS: 
Framework de CSS utilitario para un diseño rápido y personalizable.
### JavaScript/TypeScript: 
Lenguajes utilizados para la lógica y comportamiento de la web.

## Instalación
Para comenzar a trabajar en este proyecto, sigue estos pasos:

## Requisitos previos
Asegúrate de tener instalados los siguientes programas en tu máquina:

### Node.js: 
Descargar Node.js (Se recomienda la versión LTS).
### npm:
El gestor de paquetes de Node.js (debería instalarse automáticamente con Node.js).

## Pasos para instalar

### Clona el repositorio:

git clone https://github.com/JuandaBeta1790/Landing-Page

## Navega al directorio del proyecto:

cd tu-repositorio

## Instala las dependencias del proyecto:
### npm install

## Ejecuta el servidor de desarrollo:

### npm run dev
Esto debería iniciar el servidor de desarrollo, y podrás ver la página en http://localhost:3000.

# Estructura del Proyecto
A continuación se describe la estructura básica del proyecto:

## /cta --- Nuestro Equipo
    /assets      	--- Carpeta para guardar imágenes de la seccion
    /components
       - EmailForm.astro --- Datos  del formulario (Desactivado) 
       - InvolvementCard.astro --- Configuracion del formulario (Desactivado) 
     - data.ts      	--- información a mostrar en la seccion
     - GetInvolved.Astro --- Manejo de las características de la seccion
   
  
## /environment --- Impacto Ambiental de Telemetrik 
    /assets           # Carpeta para guardar imágenes específicas de la sección de Impacto Ambiental
    - data.ts          # Información para la sección ambiental
    - EnvironmentalImpact.astro  # Componente para mostrar el impacto ambiental


## /featured --- Nuestra Tecnología
    /assets           # Carpeta para guardar imágenes específicas de la sección de Proyectos Destacados
    /components
      - FeaturedProject.astro  # Componente para mostrar un proyecto destacado
    - data.ts           # Información para la sección de proyectos destacados
    - FeaturedProjects.Astro  

 ## /hero --- Por qué? parte inicial de la pagina
    /assets           # Carpeta para guardar imágenes de la sección Hero
    - Hero.astro       
    - data.ts
 ## /innovations --- Casos de éxito
    /assets           # Carpeta para guardar imágenes relacionadas con las innovaciones
    - LatestInnovations.astro  # Componente para mostrar las últimas innovaciones

 ## /services --- Telemetrik + AWS
    /assets           # Carpeta para guardar imágenes relacionadas con los servicios
    /components
      - ServiceCard.astro   # Componente de tarjeta para mostrar servicios
      - ServiceCopyTextCard.astro   # Componente para mostrar texto adicional de servicio
    - data.ts           # Información para la sección de servicios
    - KeyServices.Astro   # Componente para mostrar los servicios clave

  ## /testimonials --- Nuestros Clientes
    /assets           # Carpeta para guardar imágenes relacionadas con los testimonios
    /components
      - Testimonial.astro  # Componente para mostrar los testimonios de los clientes

 ## /shared -- En esta parte se encuentra el comportamiento de titulos, subtitulos, parrafos, botones etc..
    /assets           # Carpeta común para guardar imágenes reutilizables
    - BtnLink.astro    # Componente de botón de enlace
    - BtnThemeSwitch.astro   # Componente para cambiar el tema
    - Button.astro      # Componente de botón genérico
    - Container.astro    # Componente para contenedor general
    - Correos.astro     # Componente para mostrar correos electrónicos
    - CtaButton.astro   # Botón específico para llamada a la acción
    - FooterNav.astro   # Componente de navegación en el pie de página
    - GradiantText.astro  # Componente para texto con gradiente
    - HoverImage.astro   # Componente para imagen con efecto hover
    - LazyImage.astro    # Componente para imagen con carga diferida
    - Navitem.astro      # Componente de ítem de navegación
    - Paragraph.astro    # Componente para párrafos
    - SubTitle.astro     # Componente para subtítulos
    - SubTitle2.astro    # Variante de subtítulo
    - SubTitle3.astro    # Otra variante de subtítulo
    - Title.astro        # Componente para título principal
    - Title2.astro       # Variante de título
    - Title3.astro       # Otra variante de título
    - Title4.astro       # Otra variante de título

 ## /layouts Pie de pagina, barra de navegacion y tema
    /assets           # Carpeta para guardar imágenes utilizadas en los layouts
    - Footer.astro     # Componente para el pie de página
    - Layout.astro     # Componente para el cambio de color de la pagina, oscuro o claro
    - Navbar.astro     # Componente para la barra de navegación

## Otros archivos importantes
    astro.config.mjs  --- Archivo de configuracion necesario para GitHub
    Tailwind.config.mjs

## Configuración de Tailwind CSS
En este archivo se encuentra la configuracion de los colores como: accent, primary, secondary, complementary1 y complementary2 entre otros. Tambien esta la configuracion del tamaño de las pantallas y la fuente

#### Colores personalizados: Se han definido paletas de colores para los diferentes estados de la página (modo claro y oscuro).
#### Breakpoints personalizados: Los puntos de ruptura están configurados para adaptarse a varios tamaños de pantalla, desde dispositivos móviles hasta pantallas de escritorio HD.
#### Sombras y fuentes personalizadas: Se han agregado sombras y se ha seleccionado la fuente Raleway como la predeterminada.


## Personalización de Tailwind
    Si deseas cambiar los colores, fuentes o tamaños de pantalla, modifica las secciones correspondientes en el archivo tailwind.config.js. Por ejemplo, para cambiar los colores de la paleta primaria:

    
    primary: {
        50: "#f1fcf1",
        100: "#e0f9df",
        200: "#c2f1c1",
        300: "#92e491",
        400: "#5acf59",
        500: "#2045F3",  // Color base
        DEFAULT: "#2045F3",
        600: "#2045F3",
        700: "#1a37e2",
        800: "#1632cc",
        900: "#0e28b8",
        950: "#092a0b",
    },
    
## Desarrollo
Ejecutar el Proyecto en Desarrollo
Durante el desarrollo, puedes utilizar el siguiente comando para iniciar el servidor local y ver los cambios en tiempo real:
npm run dev

## Construir el Proyecto para Producción
Para generar la versión de producción del proyecto, ejecuta:
npm run build
Esto creará los archivos optimizados en la carpeta dist/, listos para ser desplegados.


Notas Adicionales
Modo Oscuro: Este proyecto soporta el modo oscuro activado por una clase dark en el HTML. Si deseas cambiar el modo predeterminado o la forma de activarlo, ajusta la configuración en Layout.astro



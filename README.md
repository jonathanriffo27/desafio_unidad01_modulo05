# 🖥️ Desafío de creación de un proyecto nuevo en Rails

Este repositorio contiene mi solución al desafío de creación de un proyecto nuevo en Rails. La aplicación es un portafolio que muestra mis desarrollos y desafíos implementados en Rails.

## Requerimientos

- Ruby ruby 3.2.2
- Rails 7.0.6

## Instalación

1. Clonar este repositorio en tu máquina local.
2. Ejecutar `rails s` para instalar las dependencias.
2. Ejecutar `bundle exec guard` en una nueva terminal para activar el auto recarga en RoR.

## Uso

La aplicación contiene las siguientes rutas:

1. /home
2. /projects
3. /contact

La ruta raíz de la aplicación es /home.

En la vista de /projects, se agregaron 3 imágenes de proyectos realizados hasta el momento utilizando el componente Card de Bootstrap y se modificó el botón de "ver más" con estilos personalizados desde CSS.

Se agregó un menú de navegación personalizado que se ve en todas las vistas de la aplicación y redirige según corresponda en cada interacción utilizando el helper link_to.

## Consideraciones y recomendaciones

- La versión de Bootstrap recomendada es la 5.3

## Preguntas frecuentes

### ¿Cómo puedo cambiar la ruta raíz de la aplicación?

Para cambiar la ruta raíz de la aplicación, se debe modificar el archivo `routes.rb` y definir la ruta deseada como la raíz de la aplicación utilizando la sintaxis `root 'nombre_controlador#nombre_método'`.

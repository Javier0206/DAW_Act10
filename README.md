# DAW_Act10

Claro, aquí tienes un formato similar para el README.md que puedes utilizar para documentar los cambios realizados en el segundo trabajo:

```markdown
# ChuckJokesVue

Una aplicación Vue que muestra divertidas bromas sobre Chuck Norris, con la implementación de un nuevo componente ChuckCard.

## Descripción

ChuckJokesVue es una pequeña aplicación web desarrollada con Vue.js que muestra una lista de bromas populares sobre Chuck Norris. En esta versión, se ha agregado un nuevo componente llamado ChuckCard para representar cada broma en una tarjeta Bootstrap con imagen y texto. Los datos se pasan entre componentes utilizando props, y se ha asegurado la responsividad de la página utilizando clases de Bootstrap.

## Capturas de pantalla

![Captura de pantalla 1](screenshots/screenshot1.png)
![Captura de pantalla 2](screenshots/screenshot2.png)

## Instalación y Uso

### Instalación

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```

2. Navega al directorio del proyecto:

   ```bash
   cd chuck-jokes-vue
   ```

3. Instala las dependencias:

   ```bash
   npm install
   ```

### Uso

1. Inicia la aplicación:
2. 
   npm run serve

3. Abre tu navegador web y ve a `http://localhost:8080` para ver la aplicación en funcionamiento.

## Tecnologías Utilizadas

- Vue.js
- HTML
- CSS
- Bootstrap

## Cambios Realizados

- Se creó el componente ChuckCard para representar cada broma en una tarjeta Bootstrap con imagen y texto.
- Se actualizaron los datos en App.vue para incluir los nuevos campos 'icon_url'.
- Se utilizaron props para pasar los datos de icon_url y value entre componentes.
- Se aseguró que tres tarjetas se muestren por línea en pantallas grandes y una tarjeta por línea en pantallas pequeñas utilizando clases de Bootstrap para la responsividad.

## Autor

[Nombre del Autor]
Javier Alfredo Vázquez Garza

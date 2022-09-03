# Desafio-sass/css

## Objetivo del proyecto
  Modificar los valores de Bootstrap Sass para personalizar el
componente Card y cambiar su estética.

### Herramientas utilizadas:
- nodejs
- sass
- módulos de bootstrap

### Procedimientos generales:
1. Instalé nodejs, Sass y la extensión de live-server para VScode.
2. Descargué los módulos de Bootstrap mediante el comando npm i bootstrap de manera local en la carpeta del proyecto
3. Edite el Package.jason escribiendo el scripts 
  "scripts": {
    "sass": "sass -w assets/scss/input.scss:assets/css/input.css" -------> Para hacer la traducción mediante Sass (de manera continua)
  }
4. Creé la carpeta assets y dentro de ella las carpetas css y scss con sus archivos respectivos. para este caso los nombré input
5. Mediante la consola "vinculé" el input.scss con el input.css con el comando << sass assets/scss/input.scss:assets/css/input.css >> 
6. Iinicié el proceso de traducción con Sass mediante << npm run sass >> 
7. Copié un html Card de la página de bootstrap e hice link al input.css
8. Importé bootsatrap.scss, functions.scss, variables.scss a mi input.scss
9. Finalmente comencé a sobre escribir en mi input.scss las modificaciones default

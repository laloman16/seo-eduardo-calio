//COMO EMPEZAR A COMPILAR SASS//

1. Abrir la consola en esta carpeta con ctrl+ña. npm instale nodemon node-sass. npm init

2. Abrir el archivo package.json y editarloa. A continuación de && exit 1" coloque una , presione enter y pegue el siguiente texto:"build-css": "node-sass --include-path scss scss/main.scss css/style.css","watch-css" : "nodemon -e scss -x \"npm run build-css\""

3. Crear las carpetas con sus respectivos archivosa. scss/main.scssb. css/style.css4. En la consola correr el comandoa. npm run build -css //Por unica vezb. npm run build -css. Cada vez que se quiera seguir compilando en SASSa. abrir la consola con ctrl+ñb. npm run watch-css//FIN



ultimo:"build-css": "node-sass --include-path scss scss/main.scss css/style.css","watch-css": "nodemon -e scss -x \"npm run build-css\" "


@import './alt39';  ' '
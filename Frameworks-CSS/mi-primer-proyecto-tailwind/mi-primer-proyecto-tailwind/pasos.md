##### 1- npm create vite@latest

##### 2- ir a la raiz del directorio creado

##### 3- si el directorio base se movio a otro directorio tenemos que instalar los modulos de vite

###### - npm install

##### 4- npm install -D tailwindcss @tailwindcss/vite

##### 5- configurar vite.config.js, si el archivo no se creo lo creamos con esta configuracion

import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'

export default defineConfig({
plugins: [tailwindcss()],
})

##### 6- En style.css

###### @import "tailwindcss";

##### 7- probar y PARAR (template)

###### npm run dev

##### 8- al copiar la carpeta en otro directorio para comenzar el proyecto, tenemos que ejecutar el comando

###### npm install

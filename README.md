# HeroesApp

Ejemplo de un CRUD con Firebase y Angular.

## Firebase

Se necesita crear una cuenta en [firebase](https://firebase.google.com/), cuando la cuenta este lista hacer lo siguiente :

1. Crear un proyecto.
2. Crear una base de datos en modo de prueba.
3. Verificar que las reglas esten con valor true. `{ rules : { ".read" : true, ".write" : true } }`
4. Crear una colección en la base datos llamada `heroes`. (Nota: Pueden cambiar el nombre de la colección pero asegurense de cambiarlo tambien en el heroes.service.ts).

## Angular

Deben copiar el link de la base de datos que aparece en firebase y agregarlo en los environments para poder hacer las peticiones HTTP.

## Development server

Ejecutar `npm install` para instalar todas las dependecias del proyecto, luego ejectar `ng serve -o`.
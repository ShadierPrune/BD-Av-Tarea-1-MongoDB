# Información mia

Nombre: Felipe Santiago Parra Díaz
Rol: 202373568-k
Rut: 21.758.067-6
Paralelo: 200

# Consideraciones

- Se ocupó windows 11 (powershell), y se realizaron todas las lines de comando en ella.
- Se usó MongoDB Compass

# Instrucciones de ejecución:

Encontrarse en la altura en que al hacer el comando:

    ls

Vea al archivo "docker-compose.yml"

1. Para ejecutar el docker use:
    
    docker-compose up --build -d

2. Conectarse a MongoDB Compass usando de URI:

    mongodb://localhost:30001,localhost:30002,localhost:30003/?replicaSet=my-replica-set

3. Luego en MongoDB Compass crear la base de datos "Actores"

4. Dentro de "Actors" crear una colección llamada "Voice-actors" y luego añadir el documento con el mismo nombre y extensión ".json". Deberían ser 35 elementos

5. ...

Cuando quiera terminar el proceso debe:

1. Para borrar los volumenes y conetendores, escribir en la terminal:

    docker-compose down -v

2. Para borrar la carpeta de data:

   borre la carpeta "data"




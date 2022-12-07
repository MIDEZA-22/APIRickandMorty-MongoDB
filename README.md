PROYECTO FINAL

Para este proyecto final, se hizo uso de la API "Rick and Morty".

-- Requerimientos --

  Debe insertar los datos obtenidos en una colección de MongoDB.

  Hacer uso de la API para extraer personajes por página. 
  Use la siguiente ruta: https://rickandmortyapi.com/api/character?page=n (Donde "n" es el número de página).

  La estructura del Json obtenido es el siguiente:

    {
        info:{ "Información de la página, conteo de personajes, página siguiente y anterior, etc." },
        results:{ "Array de personajes" }
    }

  Únicamente debe insertar los "results" en la base de datos.

  Crear una vista HTML para listar los datos de los personajes en pantalla haciendo uso de PyMongo.
  
  Los personajes deben estar ordenados por el id de forma descendente.
  
-- Perfil --

  Crear un perfil en el que se pueda visualizar más datos del personaje: Capítulos en los que aparece, etc.

  La vista debe contar con los datos del personaje.

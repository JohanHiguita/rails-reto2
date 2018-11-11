# Tu misión en este reto es crear tu primer modelo en Rails.

Instrucciones
1. Crea una aplicación de Rails.

2. Crea un modelo llamado Movie con los siguientes atributos (decide el tipo de datos para cada uno):

name
duration
year
rating (G, PG, PG-13, R, NC-17)
description
image_url
3. Prueba el modelo desde la consola de Rails:

$ rails console
> m1 = Movie.create(name: "Avengers: Age of Ultron", duration: 141, ...)
> Movie.all

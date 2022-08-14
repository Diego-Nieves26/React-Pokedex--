## Decripcion

Cree una app web con una primera pagina, en la que sólamente hay un input que le preguntará el nombre al usuario. Dicho nombre es almacenado en la store de redux, y será obligatorio para que pueda acceder a las siguientes rutas.

La ruta “/pokedex”, se muetra despues de que el usuario ingreso su nombre, la cuál es una ruta protegida que le da un mensaje de bienvenida al usuario utilizando el nombre almacenado en el store, a la vez, listará los pokemones traídos desde la [PokeApi](https://pokeapi.co/). Cada tarjeta, al darle clic llevara a la informacion mas detallada del pokemon de la tarjeta. La ruta “/pokedex” esta paginada.

Cuenta con una estiqueta select que filtra los pokemones por especie.

Tiene un input para buscar un pokemon en específico por su nombre.

## Funciones y datos del proyecto

- Las rutas /pokedex y /pokedex/:id están protegidas.
- El nombre insertado en el input de la ruta raíz se guarda en la store.
- En /pokedex se listan y se paginan todos los pokemones.
- En /pokedex cada tarjeta es un link que lleva a la ruta /pokedex/:id.
- En /pokedex se pueden filtrar los pokemones por especie.
- En /pokedex hay un input para buscar un pokemon en específico.
- En /pokedex/:id se muestra correctamente la información del pokemon seleccionado.
- Ruta /settings se encarga de: cambiar el número de pokemones por página. (darle a elegir entre 4, 8, 12, 16, 20). Y activar / desactivar un modo oscuro.

## Utilice

- React
- Axios
- Css
- Framer-Motion
- Redux-Toolkit
- React-Router-Dom

## Autor
** Diego Nieves **
* [LinkedIn](https://www.linkedin.com/in/diego-nieves-04b409242/)
* [Portafolio web](https://nvs-dlc.netlify.app)

## Abrir App
- [Poke App](https://lustrous-marigold-b9f6ee.netlify.app/)

## Contratación
Si quieres contratarme puedes escribirme a nieves.diego0426@gmail.com 👍.

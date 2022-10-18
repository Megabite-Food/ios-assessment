# Speer Technologies iOS assessment


## Descripción

El objetivo de esta evaluación es crear una aplicación iOS básica que demuestre tareas comunes, como la obtención de datos, el análisis de entidades de modelo de JSON, la interfaz de usuario y la navegación. Puede escribir la aplicación usando lo que le resulte más cómodo, ya sean guiones gráficos, UIKit puro o SwiftUI. También puede codificar en Swift u Objective-C.


### Requerimientos

Para esta evaluación, deberá familiarizarse con partes de la [API REST de GitHub] (https://docs.github.com/en/rest). Las características requeridas que nos gustaría ver construidas son:

1. Una barra de búsqueda que nos permite obtener perfiles de usuario de GitHub por nombre de usuario:
    - Si no existe ningún usuario con el nombre de usuario proporcionado, presente una vista "Not Found"
    - Si el usuario existe, presente una vista con dicho usuario:
        1. Avatar
        2. Username
        3. Name
        4. Description
        5. Follower count, i.e. *X followers*
        6. Following count, i.e. *X following*
2. Una vista que muestra una lista de los seguidores/siguiendo del usuario.
    - Deberíamos poder navegar a esta vista tocando los recuentos de seguidores/siguientes
    - Si se toca un usuario en esta lista, debería llevarnos a su vista de perfil, es decir, acceder al perfil de un seguidor o siguiendo.
3. La capacidad de navegar hacia atrás a través de la pila de navegación.

Muéstranos lo que puedes hacer en no más de 24 horas. Mantenga un registro del tiempo dedicado e inclúyalo con su presentación (README.md). Tenga en cuenta que no hay diseños a seguir para esta evaluación, por lo que tiene libertad creativa en lo que respecta al diseño, etc.

##### Bonus features

Estas funciones no son obligatorias, pero si tiene más tiempo y desea destacar, no dude en agregar cualquiera de las siguientes:

- Skeleton screens
- Pull to refresh
- Profile caching & cache invalidation


### Grading

Este ejercicio se calificará según una serie de criterios que incluyen, entre otros:
- Clean, readable, and well documented code
- Adherence to the SOLID principles
- Utilization of an architectural pattern, e.g. MVC, MVVM, VIPER


### Submission

Confirme todo su trabajo en un repositorio *privado* de GitHub. Cuando haya terminado, invite a la cuenta [espinozasenior](https://github.com/espinozasenior) y envíe por correo electrónico un enlace del repositorio a [lespinoza@megabitefood.com](mailto: lespinoza@megabitefood.com) con el asunto:

**iOS Developer Assessment - [Your Name]**.


#### Buena suerte!

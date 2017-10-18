# TP 1

## 1 - Enunciado
### 1.1 - Desarrollo
Crear un nuevo frontend para [TMDB](www.themoviedb.org) (The Movie DB) utilizando:
* Un framework de frontend. Se propone Angular pero se admitirán otros. Quienes quieran utilizar otro deberán consultar con los profesores antes de hacerlo.
* Utilizar html 5.
* Crear los css usando un framework (bootstrap, foundation, etc) o un preprocesador (less, sass, stylus).
* El backend a utilizar puede ser la API de TMDB ([api oficial](https://www.themoviedb.org/documentation/api?language=es)) o el backend provisto por la cátedra en este [repositorio](https://github.com/utnfrrottads/tmdb-server)

### 1.2 - Funcionalidad
* Página principal que permita buscar películas en tmdb. Al seleccionar una película debe redirigir a la página de dicha película.
* La página de cada película debe al menos mostrar:
  * Imagen principal de la película
  * Overview
  * User score
  * Reviews
* Debe permitir al usuario
  * Loguearse (no es necesario incluir el registro de usuarios)
  * Puntuar la pelicula

### 1.3 - Planificación y documentación

#### 1.3.1 - Entregas
El equipo deberá planificar y patuar entregas del trabajo práctico con el equipo docente. Indicando las fechas de entrega el alcance y los criterios de aceptación.

Las mismas podrán volverse a pactar con los profesores enviando las correcciones a la misma indicando, causas, acciones correctivas que se tomarán y nuevo cronograma.

#### 1.3.2 - Reuniones de avance
A su vez deberán hacer reuniones periódicas para planificar las acciones a realizar y los responsables entre una reunión y otra. La periodicidad la definirán los miembros del equipo pero no podrá ser menor a 1 por semana.

En la misma deberán indicar: fecha de la reunión, asistentes y por cada asistente:
* Tareas completadas desde la última reunión
* Blockers
* Tareas a realizar hasta la próxima reunión
* A su vez si no se alcanzó lo planificado en la reunión anterior las acciones correctivas que se tomarán.

## 2 - Criterio de correccion
### 2.1 - Sitio
* Usabilidad del sitio: debe ser fácil de usar, elegante y no tener contenido oculto o difícil de acceder
* Diseño adecuado de la interfaz: uso apropiado de los tags html y de los estilos, ya sea utilizando un FW CSS o un preprocesador.
* Calidad del código: uso adecuado de las características del FW y de la API. Para Angular usar la guia de estilos oficial [Angular.io Styleguide](https://angular.io/guide/styleguide) [HTML CSS StyleGuide de google](https://google.github.io/styleguide/htmlcssguide.html)
* Completitud de los requerimientos.

### 2.2 - Planificación
* Progreso en las capacidades para planificar adecuadamente y tomar acciones correctivas.
* Adecuación de las entregas con tiempos y acciones.

### 2.3 - Repositorio
* El desarrollo deberá realizarse en una plataforma de git gratuita. Se recomienda GitHub o GitLab.
* Se evaluará el uso de git: Frecuencia y responsables de los commits, uso de branches y merge.

## 3 - Entrega final
La entrega final deberá hacerse enviando por email a los profesores la URL del repositorio de git.

En el archivo readme.md deberá indicarse, el trabajo, año de cursado e integrantes (legajo, nombre y apellido)

Fecha de entrega final: TBD

# TP 2

## 1 - Enunciado
### 1.1 - Desarrollo
Desarrollar un backend y frontend que permitan llevar estadísitcas de encuentros deportivos con las siguientes caracterísitcas:
* El backend debe ser programado en JavaScript con NodeJS.
* Debe utilizar un framework/middleware. Se dará soporte sobre Express pero podrán utilizarse alternativas si así se prefiere.
* La persistencia debe realizarse utilizando un ODM/ORM con una base de datos acorde a la tecnología que se utilice.
* El frontend debe realizarse con un framework como Angular u otro seleccionado, html 5 y para CSS debe usarse un preprocessador o framework.

### 1.2 - Funcionalidad
#### 1.2.1 - Backend por API REST
* ABMC de equipos deportivos: listar todos, uno, crear, modificar y eliminar.
* Alta de juegos (partidos) indicando los id de los equipos y la fecha y hora de inicio.
* Informe de finalización de juego y baja de juego indicando el id del juego.
* ABMC de tipo de eventos (goles, amonestaciones, cambios): listar todos, uno, crear, modificar y eliminar.
* Informar nuevo evento indicando juego y datos necesarios según el evento (i.e. tipo, equipo, hora, etc).
* Eliminar un evento con su id.
* Consulta de juegos.
* Consulta de juegos activos (no finalizados).
* Consulta de detalle de un juego informando equipos y eventos.

#### 1.2.2 - Frontend
* El frontend solo debe permitir ver la lista de juegos activos, seleccionar uno y ver el detalle.
* El resto de la funcionalidad puede utilizarse mediante una herramienta similar a postman, restclient, curl o wget.

### 1.3 - Planificación y documentación

#### 1.3.1 - Entregas
El equipo deberá planificar y patuar entregas del trabajo práctico con el equipo docente. Indicando las fechas de entrega el alcance y los criterios de aceptación.

Las mismas podrán volverse a pactar con los profesores enviando las correcciones a la misma indicando, causas, acciones correctivas que se tomarán y nuevo cronograma.

#### 1.3.2 - Reuniones de avance
A su vez deberán hacer reuniones periódicas para planificar las acciones a realizar y los responsables entre una reunión y otra. La periodicidad la definirán los miembros del equipo pero no podrá ser menor a 1 por semana.

En la misma deberán indicar: fecha de la reunión, asistentes y por cada asistente:
* Tareas completadas desde la última reunión
* Blockers
* Tareas a realizar hasta la próxima reunión
* A su vez si no se alcanzó lo planificado en la reunión anterior las acciones correctivas que se tomarán.

## 2 - Criterio de correccion
### 2.1 - Sitio
* Diseño adecuado de la API REST.
* Diseño del modelo de datos adecuado.
* Usabilidad del sitio: debe ser fácil de usar, elegante y no tener contenido oculto o difícil de acceder
* Diseño adecuado de la interfaz: uso apropiado de los tags html y de los estilos, ya sea utilizando un FW CSS o un preprocesador.
* Calidad del código: uso adecuado de las características del FW y de la API.
* Completitud de los requerimientos.

### 2.2 - Planificación
* Progreso en las capacidades para planificar adecuadamente y tomar acciones correctivas.
* Adecuación de las entregas con tiempos y acciones.

### 2.3 - Repositorio
* El desarrollo deberá realizarse en una plataforma de git gratuita. Se recomienda GitHub o GitLab.
* Se evaluará el uso de git: Frecuencia y responsables de los commits, uso de branches y merge.

## 3 - Entrega final
La entrega final deberá hacerse enviando por email a los profesores la URL del repositorio de git.

En el archivo readme.md deberá indicarse, el trabajo, año de cursado e integrantes (legajo, nombre y apellido)

Fecha de entrega final: 17/11/2017

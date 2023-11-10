# Documentación del Proyecto *Onebasketball*

1. [Sección 1](#sección-1)
2. [Sección 2](#sección-2)
3. [Sección 3](#sección-3)

## Descripción General

Este proyecto utiliza Python y WSGI para crear una aplicación web que gestiona información relacionada con deportes, incluyendo publicaciones, eventos, jugadores, usuarios, ligas, estadios, equipos, likes, registros, comentarios y puntos.


## Base de datos
La [Visit OpenAI](https://www.openai.com "Base de datos")
 


## DOCUMENTACION DE WEB
### VIEWS.PY
Variabels globales
user_info -> A traves de de las cookies se guardaran en este diccionario </br>
Get template -> page = env.get_template('page_example.html')
#### Funncion ejemplo para renderizar
'''
def page_example(environ, start_response):
    # Get data from models
    publicaciones = get_posts()
    # This response the html with the data and render own css
    response = index.render(publicaciones=publicacionescss_name='inicio.css').encode('utf-8')
    status = '200 OK'
    response_headers = [('Content-type', 'text/html')]
    start_response(status, response_headers)
    return [response]
'''
### MODELS.PY
  ## 
### CONTROLLER.PY
### UTILITIES.PY
 ## Funcitons that we need
  ### Set_new_password
# FLASH_MANAGER.PY
 This flash_manager have functions to show messages on html

# Versiones futuras
## VALIDAR CON REGEX
### CRUD PARA UN USUARIO MISMO
### PROTECCION PATH


## Métodos de Inserción
Se han proporcionado métodos para insertar datos en cada una de las tablas mencionadas anteriormente. Estos métodos facilitan la incorporación de nueva información al sistema.

CRUD de la Aplicación
Se ha implementado un conjunto de operaciones CRUD (Crear, Leer, Actualizar, Eliminar) para cada entidad del sistema. Estas operaciones permiten gestionar eficientemente la información almacenada en la base de datos.

## Operaciones CRUD
1. Crear (Create)
 - insert_publicacation_data(data): Crea una nueva publicación con los datos proporcionados.
 - insert_event_data(data): Crea un nuevo evento con los datos proporcionados.
 - insert_player_data(data): Crea un nuevo jugador con los datos proporcionados.
 - insert_user_data(data): Crea un nuevo usuario con los datos proporcionados.
 - insert_league_data(data): Crea una nueva liga con los datos proporcionados.
 - insert_stadium_data(data): Crea un nuevo estadio con los datos proporcionados.
 - insert_team_data(data): Crea un nuevo equipo con los datos proporcionados.
 - insert_likes_data(data): Crea un nuevo like con los datos proporcionados.
 - insert_register_data(data): Crea un nuevo registro con los datos proporcionados.
 - insert_commentas_data(data): Crea un nuevo comentario con los datos proporcionados.
1. Leer (Read)
 - get_all_publicaciones(): Obtiene todas las publicaciones almacenadas.
 - get_all_eventos(): Obtiene todos los eventos almacenados.
 - get_all_jugadores(): Obtiene todos los jugadores almacenados.
 - get_all_usuarios(): Obtiene todos los usuarios almacenados.
 - get_all_ligas(): Obtiene todas las ligas almacenadas.
 - get_all_estadios(): Obtiene todos los estadios almacenados.
 - get_all_equipos(): Obtiene todos los equipos almacenados.
 - get_all_likes(): Obtiene todos los likes almacenados.
 - get_all_registros(): Obtiene todos los registros almacenados.
 - get_all_comentarios(): Obtiene todos los comentarios almacenados.
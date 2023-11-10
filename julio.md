# DOCUMENTACION DE WEB
# VIEWS.PY
  ## Variabels globales
    ### user_info -> A traves de de las cookies se guardaran en este dict
    ### Get template -> page = env.get_template('page_example.html')
  ## Function to render the page
    '''
    def page_example(environ, start_response):
        # Get data from models
        publicaciones = get_posts()
        # This response the html with the data and render own css
        response = index.render(publicaciones=publicacionescss_name='inicio.css').encode(
            'utf-8')
        status = '200 OK'
        response_headers = [('Content-type', 'text/html')]
        start_response(status, response_headers)
        return [response]
    '''
# MODELS.PY
  ## 
# CONTROLLER.PY
# UTILITIS.PY
 ## Funcitons that we need
  ### Set_new_password
# FLASH_MANAGER.PY
 This flash_manager have functions to show messages on html

# Versiones futuras
## VALIDAR CON REGEX
### CRUD PARA UN USUARIO MISMO
### PROTECCION PATH


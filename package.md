# Crear un paquete

## Crear un entorno virtual

Crea un entorno virtual mediante ``venv``

Ejecutamos en la terminal: ``python3 -m venv env`` o bien ``python -m venv env``

Activamos el entorno virtual: ``source env/bin/activate``
    
Vemos que en la terminal se ve lo siguiente ``(env)``. Eso significa que se ha activado el entorno virtual y se ha aislado del resto de la máquina.


## Instalar una biblioteca

Instalamos una biblioteca con el comando ``pip install``:

Si ejecutamos ```pip freeze``` se muestra la lista de bibliotecas que tienes instaladas en el entorno virtual:
    

## Desactivar un entorno virtual

Para desactivar el entorno virtual se debe ejecutar el comando ``deactivate``:

Al hacerlo cambia el mensaje de la terminal ``(env)`` a cómo se veía antes.
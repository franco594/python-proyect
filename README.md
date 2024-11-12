
# Entorno virtual en Python

<br>Comenzamos con el entorno 
virtual de Python, para ingresar
al repo después  de un tiempo tuve 
que hacer lo siguiente, abrí la
terminal de Ubuntu desde windows
como administrador: <br>

```sh
    mkdir py-proyect
    cd py-proyect
    git clone https://...
    ll
    cd python-pip
    code .
    git branch # Solo está la rama main
    git branch second # Comenzamos a crear nuevas ramas
    git branch profe
    git branch ariel22
    git status # Desde la rama main ya hay cambio para commitear
    git add .
    git commit -m"Agrego el archivo txt
    donde detallo cada parte de las clases"
    git push origin main # Surge un problema, debo crear un token para poder cargar cambios
    # Se debe entrar en GitHub settings - Developer settings - Personal accesstokens - token classic
    # Se genera escribiendo las notas de que trabajo se va a tratar y se debe tildar cuanto tiempo de duración tendrá el token y tilder los permisos, generar y por último copiar el token
    git pull origin main
    Usuario: franco594
    Password: accessToken # el que hemos creado y debemos guardar bien
    which python3 # Nuestra la ruta donde se está ejecutando python3
```
# Archivo requirements.txt
    <br>Vamos a ver este archivo, este gestiona todas las dependencias y en que versiones se necesitan, vamos a dejar aquí los comandos para alguien logre contribuir con este proyecto, los comandos son los siguientes
    <br>

    ```sh
        git clone https://...
        cd app
        python3 -m venv env # Se debe crear el entorno virtual, este no se comparte desde github
        source env/bin/activate # ctivamos el entorno en linux
        venv/Script/activate # Activa el entorno en windows
        pip3 install -r requirements.txt # Instala las dependencias el -r significa reutilizar
        python3 main.py
    ```

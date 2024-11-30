# Proyecto Final PASSKEEPER

Este proyecto es una aplicación de **gestión de contraseñas** que permite a los usuarios almacenar, editar, eliminar y visualizar las contraseñas de diferentes servicios de manera segura. La aplicación incluye una interfaz gráfica donde los usuarios pueden registrar nuevas contraseñas, acceder a la lista de servicios y realizar modificaciones.

## Descripción

La aplicación permite a los usuarios gestionar sus contraseñas de manera eficiente y segura. Con un sistema de inicio de sesión, los usuarios pueden almacenar, editar, consultar y eliminar contraseñas asociadas a diferentes servicios. La aplicación cifra y desencripta las contraseñas para garantizar su seguridad.

### Funcionalidades:
- **Registro de contraseñas**: Los usuarios pueden registrar sus credenciales (usuario, contraseña, servicio).
- **Edición de contraseñas**: Permite editar las contraseñas de los servicios ya registrados.
- **Eliminación de contraseñas**: Los usuarios pueden eliminar los registros de contraseñas asociadas a un servicio.
- **Consulta de contraseñas**: Los usuarios pueden ver la lista de contraseñas registradas.
- **Cifrado de contraseñas**: Se utiliza el algoritmo **SHA-256** para cifrar las contraseñas antes de almacenarlas.
- **Interfaz gráfica**: Desarrollada con **PyQt5**, permite una interacción amigable con el sistema.

## Integrantes del Equipo

- **CHAUPIS ESPINOZA FERNANDO RODRIGO**
- **JHEYSON PAUL PAYTAN HUAMAN**
- **JULIO CESAR QUISPE ZARATE**
- **GABRIEL ERNESTO SOLIS EGOAVIL**

## Docente

- **GAMARRA MORENO JOB DANIEL**

## Tecnologías Utilizadas

- **Python**: Lenguaje de programación principal.
- **PyQt5**: Para la interfaz gráfica de usuario (GUI).
- **SQLite**: Base de datos para almacenamiento local.
- **Hashlib**: Para encriptar y proteger las contraseñas.

## Instalación

Sigue estos pasos para instalar y ejecutar el proyecto en tu máquina local:

1. Clona el repositorio en tu computadora:

    ```bash
    git clone https://github.com/usuario/proyecto-gestion-contrasenas.git
    ```

2. Navega al directorio del proyecto:

    ```bash
    cd proyecto-gestion-contrasenas
    ```

3. Instala las dependencias necesarias (asegúrate de tener Python 3.x instalado):

    ```bash
    pip install -r requirements.txt
    ```

4. Ejecuta el programa:

    ```bash
    python main.py
    ```

## Uso

### Registro de Contraseña

1. Ingresa tu **usuario**, **contraseña** y el **servicio** al que corresponde.
2. La contraseña se cifrará antes de ser almacenada en la base de datos.
3. Haz clic en el botón **REGISTRAR** para registrar la nueva contraseña.

### Edición de Contraseña

1. En la pantalla de consulta de contraseñas, selecciona el servicio que deseas editar.
2. Modifica el **usuario**, **contraseña** o **servicio** según sea necesario.
3. Haz clic en el botón **Guardar** para aplicar los cambios.

### Eliminación de Contraseña

1. En la pantalla de consulta de contraseñas, selecciona el servicio que deseas eliminar.
2. Haz clic en el botón **Eliminar** para borrar el registro de contraseñas de la base de datos.

### Consulta de Contraseñas

1. Puedes ver todas las contraseñas almacenadas y asociadas a tus servicios en la pantalla principal.
2. Las contraseñas se muestran de manera cifrada para mayor seguridad.
3. Si deseas ver detalles, puedes hacer clic sobre el servicio y editar o eliminar el registro.

### Ingreso al Sistema

1. Para acceder a tus contraseñas registradas, debes **iniciar sesión** con tu usuario y contraseña.
2. Si aún no tienes cuenta, puedes registrarte ingresando un nuevo usuario y contraseña.

## Contribución

Las contribuciones son bienvenidas. Si deseas contribuir al proyecto, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature-nueva`).
3. Realiza los cambios y haz commit de tus cambios (`git commit -m 'Descripción de la nueva funcionalidad'`).
4. Envía un pull request.


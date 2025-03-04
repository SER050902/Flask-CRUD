# Flask CRUD - Videojuegos y Desarrolladores

Este es un proyecto CRUD (Crear, Leer, Actualizar y Eliminar) desarrollado con Flask y SQLite. Permite gestionar videojuegos y desarrolladores, proporcionando una interfaz sencilla para realizar operaciones básicas sobre la base de datos.

##  Características
- Listar videojuegos y desarrolladores.
- Agregar nuevos videojuegos y desarrolladores.
- Eliminar videojuegos y desarrolladores.
- Uso de Flask y SQLAlchemy para la gestión de la base de datos.

##  Tecnologías utilizadas
- Python 3
- Flask
- Flask-SQLAlchemy
- SQLite

##  Instalación y ejecución
1. Clonar este repositorio:
   ```sh
   git clone https://github.com/SER050902/Flask-CRUD.git
   cd Flask-CRUD
   ```
2. Crear un entorno virtual (opcional pero recomendado):
   ```sh
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   ```
3. Instalar las dependencias:
   ```sh
   pip install -r requirements.txt
   ```
4. Ejecutar la aplicación:
   ```sh
   python app.py
   ```
5. Acceder a la aplicación en el navegador: `http://127.0.0.1:5000`
6. Los usuarios y contraseñas estan en fichero contraseña.txt para accedir login

##  Estructura del proyecto
```
Flask-CRUD/
├── app.py                    # Archivo principal de la aplicación
├── dp.py                     # Archivo de base de datos
├── README.md                 # Documentación del proyecto
├── static/
│   └── css/
│       └── vi-de.css         # Estilos de la aplicación
├── templates/
│   ├── base.html             # Plantilla base
│   ├── delete.html           # Página para eliminar registros
│   ├── desarrollador.html    # Gestión de desarrolladores
│   ├── index.html            # Página principal
│   ├── inser_desarrollador.html   # Formulario para agregar desarrollador
│   ├── inser_videojuego.html      # Formulario para agregar videojuego
│   ├── login.html            # Página de inicio de sesión
│   ├── modificar_desarrollador.html  # Modificar desarrollador
│   ├── modificar_videojuego.html  # Modificar videojuego
│   ├── no_admin_desarrollador.html  # Vista sin privilegios (desarrollador)
│   ├── no_admin_index.html   # Vista sin privilegios (inicio)
│   ├── no_admin_videojuego.html  # Vista sin privilegios (videojuego)
│   └── videojuego.html       # Gestión de videojuegos
├── usuarios.txt              # Archivo de almacenamiento de usuarios
└── VI-DE.sqlite              # Base de datos SQLite
```

##  Licencia
Este proyecto está bajo la licencia MIT. Puedes usarlo, modificarlo y distribuirlo libremente.

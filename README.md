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
flask_crud_videojuegos/
│── templates/
│   ├── index.html
│── app.py
│── requirements.txt
│── videojuegos.db
```

##  Licencia
Este proyecto está bajo la licencia MIT. Puedes usarlo, modificarlo y distribuirlo libremente.

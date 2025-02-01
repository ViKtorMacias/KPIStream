# KPIStream

flask_project/
│── app/                     # Carpeta principal de la aplicación
│   ├── __init__.py          # Inicializa la aplicación y Flask
│   ├── routes.py            # Define las rutas principales
│   ├── models.py            # Modelos de base de datos (SQLAlchemy)
│   ├── forms.py             # Formularios (Flask-WTF)
│   ├── services.py          # Lógica de negocio
│   ├── templates/           # Carpeta para las plantillas HTML (Jinja2)
│   │   ├── base.html        # Plantilla base
│   │   ├── index.html       # Página principal
│   │   ├── login.html       # Página de login
│   ├── static/              # Archivos estáticos (CSS, JS, imágenes)
│   │   ├── css/
│   │   ├── js/
│   │   ├── img/
│   ├── blueprints/          # Módulos de la aplicación (Blueprints)
│   │   ├── __init__.py
│   │   ├── auth/            # Módulo de autenticación
│   │   │   ├── __init__.py
│   │   │   ├── routes.py
│   │   │   ├── models.py
│   │   │   ├── templates/
│   │   │   ├── static/
│── config.py                # Configuración de la aplicación
│── requirements.txt         # Dependencias del proyecto
│── run.py                   # Punto de entrada de la aplicación
│── migrations/              # Migraciones de base de datos (Flask-Migrate)
│── venv/                    # Entorno virtual de Python (opcional)
│── .env                     # Variables de entorno
│── .gitignore               # Archivos a ignorar en Git

# todo-list

Este es un proyecto basico usando Flask para crear una lista de tareas para la materia Practica profesionalizante I del instituto ITEC

Para generar la base de datos, se utiliza la libreria de Click, simplemente usar estos comandos antes de abrir la app:
    Export:
	export FLASK_DATABASE_HOST=localhost (nombre del host)
	export FLASK_DATABASE_USER=     (nombre del usuario para la base de datos)
	export FLASK_DATABASE_PASSWORD=     (password del usuario en la base de datos)
	export FLASK_DATABASE=      (nombre de la base de datos)
	export FLASK_APP=todo/      (Set la app para iniciar el proyecto de flask)

inicializar la base de datos:
	flask init-db       (Comando para iniciar la base de datos)
    flask run       (Comando para ejectutar Flask)

Luego de haber cargado estos datos en forma linear, el proyecto ya deberia de funcionar completamente.

Al ejectuar la App automaticamente se es redireccionado hacia la plantilla de 'Register' para registrarse como un usuario, Luego de esto
se genera la pantalla de 'Login' donde un usuario previamente registrado puede logearse para empezar a usar la App.
Una vez logeado se carga la pagina principal donde se encuentra la Lista de Todos cargados desde la base de datos. Para crear un todo simplemente
presionar en el boton para agregar un todo y una vez generado la applicacion te devuelve hacia el index donde ya mencionado previamente,
estan todos los todos, para editar o eliminar un todo usar el boton de editar el todo.
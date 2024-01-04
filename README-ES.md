# Sistema básico de preguntas y respuesestas en Smalltalk

- Sistema web básico para realizar preguntas y respuestas (QA por las siglas en inglés de Question y Answer) hecho con Pharo Smalltalk, el framework Seaside y Bootstrap.

### Características

- En este sistema se puede:
  - **Registrar** un usuario.
  - **Iniciar sesión** como usuario.
  - **Preguntar** a la comunidad sobre algún tópico.
  - **Responder** una pregunta.
  - **Buscar** usuarios.
  - **Seguir** otros usuarios.

### Arquitectura

- Este sistema fue construido siguiendo el modelo **MVC** y **TDD**, por ello se compone de tres estructuras fundamentales:
  - **El modelo de dominio:** que contiene la lógica y comportamiento del sistema.
  - **La interfaz de usuario:** que contiene el front-end del sistema hecho en tecnología web.
  - **Los tests:** que contienen los tests del modelo de dominio.

- Dado que la aplicación fue desarrollada en el lenguaje de programación Smalltalk, está hecha siguiente los **criterios, heurísticas y patrones** de la **Programación Orientada a Objetos (POO)**.

### Screenshots:

- **Login**

![Login page in a pc screen](https://github.com/J-4352681/Basic-QA-smalltalk-web-system/blob/development/img/login.png?raw=true "PC: 1280x720 display")


- **Home**

![Home page in a pc screen](https://github.com/J-4352681/Basic-QA-smalltalk-web-system/blob/development/img/home.png?raw=true "PC: 1280x720 display")

- **User profile**

![User profile page in a pc screen](https://github.com/J-4352681/Basic-QA-smalltalk-web-system/blob/development/img/user.png?raw=true "PC: 1280x720 display")

- **Búsqueda**

![Search page in a pc screen](https://github.com/J-4352681/Basic-QA-smalltalk-web-system/blob/development/img/search.png?raw=true "PC: 1280x720 display")

- **Preguntas**

![Question making form page in a pc screen](https://github.com/J-4352681/Basic-QA-smalltalk-web-system/blob/development/img/question.png?raw=true "PC: 1280x720 display")

### Instrucciones para ejecutar la app en Pharo Smalltalk:

1. Descargar [Pharo Smalltalk](https://pharo.org/).

2. Hacer una nueva imagen e iniciarla.

3. Instalar [Seaside framework](https://github.com/SeasideSt/Seaside) using a playground.

4. Importar los paquetes `.st`.

5. Ejecutar los siguientes comandos usando un Playground:

  ```Bash
  QAApp clearSoleInstance.
  waapp := QAUI urlBase: '/qaapp'.
  ```

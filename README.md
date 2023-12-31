# Basic QA Smalltalk web system

- A basic question-answer (QA) web system made with Pharo Smalltalk and the Seaside Framework.

### Features

- With this system you can:

  - **Register** as a new user.
  - **Login** to your account.
  - **Ask** a question.
  - **Answer** questions from other users.
  - **Search** users.
  - **Follow** other users.

### Architecture

- The system is built in three main structures:

  - **The domain model:** contains the logic and behaviour of the system.
  - **The user interface:** contains the web user interface of the app.
  - **The tests of the domain model:** contains the system tests of the model.

- Since the entire app is developed in the Smalltalk programming language, it's built entirely using **Object Oriented Programming (OOP)**.

### Screenshots:

- **Login**

![Login page in a pc screen](https://github.com/J-4352681/Basic-QA-smalltalk-web-system/blob/development/img/login.png?raw=true "PC: 1280x720 display")


- **Home**

![Home page in a pc screen](https://github.com/J-4352681/Basic-QA-smalltalk-web-system/blob/development/img/home.png?raw=true "PC: 1280x720 display")

- **User profile**

![User profile page in a pc screen](https://github.com/J-4352681/Basic-QA-smalltalk-web-system/blob/development/img/user.png?raw=true "PC: 1280x720 display")

- **Search**

![Search page in a pc screen](https://github.com/J-4352681/Basic-QA-smalltalk-web-system/blob/development/img/search.png?raw=true "PC: 1280x720 display")

- **Question**

![Question making form page in a pc screen](https://github.com/J-4352681/Basic-QA-smalltalk-web-system/blob/development/img/question.png?raw=true "PC: 1280x720 display")


### Steps to run app in Pharo Smalltalk:

1. Download [Pharo Smalltalk](https://pharo.org/).

2. Make a new image and start it.

3. Install [Seaside framework](https://github.com/SeasideSt/Seaside) using a playground.

4. Import the `.st` packages.

5. Run the following commands usign a playground:

  ```Bash
  QAApp clearSoleInstance.
  waapp := QAUI urlBase: '/qaapp'.
  ```

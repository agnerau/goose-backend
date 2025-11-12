# Homework system backend

For my Bachelor Degree project, I developed a **website** and **3D game** to make **homework more engaging** for students. Teachers could assign tests via the website, which students would complete through the 3D game interface.

**Here you can find a backend server part.**

In the backend, I used **Django REST Framework** to develop APIs serving both the frontend website and the game interface. Website requests include **CRUD operations, grade report generation, and leaderboard calculations**, while the game interacts with the API to **fetch test questions and submit answers**. Django REST Framework provides built-in tools for **authentication, permissions, and secure access**, improving the overall security and reliability of the server and database. Its mixins and viewsets help keep the **code clean and maintainable**. Additionally, I used **Celery** to automatically update class information annually.

- **Frontend repository** can be found here: https://github.com/agnerau/goose-frontend
- **WebGL build** for the game can be found here: https://github.com/agnerau/goose-game

## Technologies Used

- **Framework:** Django REST Framework
- **Database** MySQL
- **Asynchronous task manager** Celery
- **Testing** rest_framework.test library

## Usage

To run the development server locally follow install.md intructions

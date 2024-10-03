# LevelUp Docker Homework [DONE]

### How to Start the Project

0. **Everything in one command (3 in 1)**
   ```bash
   git clone git@github.com:krshkov/levelup_docker_exercise.git && cd levelup_docker_exercise/ && ./start.sh

---

#### Or do it step by step:

---

1. **Clone the Git project:**
   ```bash
   git clone git@github.com:krshkov/levelup_docker_exercise.git

3. **Enter the directory:**
   ```bash
   cd levelup_docker_exercise/

---

3. **Execute the script below:**
   ```bash
   ./start.sh

#### Or start it manually

3. **Copy the Environment Variables:**
   ```bash
   cp .env.example .env

4. **Start the application**
    ```bash
   docker compose up

### 5. That's it 😃

You can now access the project on:
[localhost:3000](http://localhost:3000/)

---


This repository contains the homework related to the Docker classes we did this week.

Your task is simple: ensure that the application can be started by simply running `docker compose up`.

The application is a simple `node` server checking if it can connect to the database on a specific port
and writing that status as the response.

To achieve this there are four main things you will need to do:

1. write a `Dockerfile` for the main application ✔
2. find an appropriate image on DockerHub to run MariaDB ✔
3. connect the app with the database on the right port ✔
4. ensure that you can access the application from the host machine. ✔

If you did everything correctly, after navigating to `http://localhost:3000` in your browser you should see the message:

* `Well done you have dockerized your first application!`

Other than the main 4 items mentioned above, you are free to implement the best practices
we've mentioned in the class to make working on this app a truly wonderful developer experience :)

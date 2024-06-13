### To run the app

Clone the repository:

```sh
git clone https://github.com/abhisheky97/Blog_Js
```

### Running the App Without Docker

- **Navigate to the project directory:**

  ```sh
  cd Blog_Js
  ```

- **Install the dependencies:**

  ```sh
  npm install
  ```

- **Install the json-server (if not present):**

  ```sh
  npm install -g json-server
  ```

- **Start the JSON server:**

  In one terminal, run:

  ```sh
  json-server --watch data/db.json --port 3500
  ```

- **Start the development server:**

  In a different terminal, run:

  ```sh
  npm start
  ```

  The app should now be running at `http://localhost:3000`.

- **Stop the development server:**

  Press `Ctrl + C` in the terminal.

### Running the App With Docker

- **Navigate to the project directory:**

  ```sh
  cd Blog_Js
  ```

- **Start the app using Docker Compose:**

  ```sh
  docker-compose up
  ```

  The app and the JSON server should now be running. By default, the app will be accessible at `http://localhost:3000`.

- **Stop the development server:**

  ```sh
  docker-compose down
  ```
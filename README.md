# Angular Homes App

This project is an Angular-based web application designed to showcase various homes and properties. It provides users with the ability to browse, search, and view details about different homes.

## Configuration

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/angular-homes-app.git
    cd angular-homes-app
    ```

2. **Install dependencies:**
    Make sure you have Node.js and npm installed. Then run:
    ```bash
    npm install
    ```

## Running the Application


1. **Set up json-server:**
    Install json-server globally using npm:
    ```bash
    npm install -g json-server
    ```

    Currently, a `db.json` file is used in the root directory with some sample data.

    Start the json-server with the following command:
    ```bash
    json-server --watch db.json
    ```

    The json-server will run at `http://localhost:3000`.


2. **Development server:**
    Run the following command to start the development server:
    ```bash
    ng serve
    ```
    Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Additional Information

For more detailed information, refer to the [Angular CLI documentation](https://angular.io/cli).

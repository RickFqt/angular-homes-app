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

3. **Environment setup:**
    Create a `.env` file in the root directory and add necessary environment variables. For example:
    ```env
    API_URL=https://api.example.com
    ```

## Running the Application

1. **Development server:**
    Run the following command to start the development server:
    ```bash
    ng serve
    ```
    Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

2. **Build:**
    To build the project, run:
    ```bash
    ng build
    ```
    The build artifacts will be stored in the `dist/` directory.

3. **Running unit tests:**
    Execute the following command to run unit tests via [Karma](https://karma-runner.github.io):
    ```bash
    ng test
    ```

4. **Running end-to-end tests:**
    Execute the following command to run end-to-end tests via [Protractor](http://www.protractortest.org/):
    ```bash
    ng e2e
    ```

## Additional Information

For more detailed information, refer to the [Angular CLI documentation](https://angular.io/cli).

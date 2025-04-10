# Film Social Network

This project is a social networking application designed specifically for the film industry. It allows users to connect, share, and discover content related to films, actors, directors, and more.

## Project Structure

The project is divided into two main parts: the backend and the frontend.

### Backend

The backend is built with Node.js and Express. It handles user authentication, data management, and serves as the API for the frontend.

- **src/app.js**: Entry point of the backend application. Initializes the Express app and sets up middleware and routes.
- **src/controllers/userController.js**: Contains the UserController class with methods for user-related operations such as creating, retrieving, and updating users.
- **src/models/userModel.js**: Defines the User model schema using a database ORM (like Mongoose).
- **src/routes/userRoutes.js**: Sets up user-related routes and links them to the UserController methods.
- **src/utils/db.js**: Manages database connections and configurations.
- **package.json**: Lists dependencies and scripts for the backend application.
- **.env**: Contains environment variables for the backend application.

### Frontend

The frontend is built with React Native. It provides a user-friendly interface for users to interact with the application.

- **src/components/Login.js**: Handles user login functionality.
- **src/components/Signup.js**: Manages user registration functionality.
- **src/components/Profile.js**: Displays user profile information.
- **src/navigation/AppNavigator.js**: Defines the navigation structure of the React Native app.
- **src/screens/HomeScreen.js**: Main screen of the app.
- **src/screens/LoginScreen.js**: UI for user login.
- **src/screens/SignupScreen.js**: UI for user registration.
- **src/utils/api.js**: Contains functions for making API calls to the backend.
- **package.json**: Lists dependencies and scripts for the frontend application.
- **App.js**: Entry point of the React Native application.

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- MongoDB (or any other database you choose)

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd film-social-network
   ```

2. Set up the backend:
   - Navigate to the backend directory:
     ```
     cd backend
     ```
   - Install dependencies:
     ```
     npm install
     ```
   - Create a `.env` file and configure your environment variables.
   - Start the backend server:
     ```
     node src/app.js
     ```

3. Set up the frontend:
   - Navigate to the frontend directory:
     ```
     cd ../frontend
     ```
   - Install dependencies:
     ```
     npm install
     ```
   - Start the React Native application:
     ```
     npm start
     ```

## Usage

Once both the backend and frontend are running, you can access the application on your mobile device or emulator. Users can sign up, log in, and interact with the film community.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License.
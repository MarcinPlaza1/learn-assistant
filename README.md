
# Learn Assistant

**Learn Assistant** is a modern web application aimed at improving the educational experience for both teachers and students. 
It provides a streamlined interface for managing learning resources, user authentication, and component development. 
This project is built using **React** and comes equipped with mock data for testing, a Storybook environment for UI development, and end-to-end testing using Cypress.

## Features

- **User Authentication**: Built-in login system with mocked data for various user roles (teachers, students, etc.).
- **Resource Management**: Tools to create and manage educational content.
- **Interactive UI Development**: Powered by **Storybook**, ensuring smooth development of UI components.
- **Testing Suite**: Includes end-to-end tests with **Cypress** and unit testing to ensure code stability.

## Project Setup

### Prerequisites
Ensure you have the following installed:

- Node.js
- npm or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/MarcinPlaza1/learn-assistant.git
   cd learn-assistant
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open the application in your browser at `http://localhost:3000`.

## Mock Data

Mock data is located in the `src/mocks/db` folder. This data simulates various user roles and allows for testing without a live backend.

### Test Credentials

- **Teacher Account**: 
  - Email: `teacher@learnassistant.com`
  - Password: `Test123`

- **Student Account**:
  - Email: `student@learnassistant.com`
  - Password: `Test123`

## Storybook

To develop or review UI components in isolation, run Storybook:

```bash
npm run storybook
```

Visit `http://localhost:6006` to access the Storybook interface.

## Testing

Run unit tests:

```bash
npm test
```

Run end-to-end tests:

```bash
npm run test:e2e
```

Cypress will launch the testing suite for interaction-based tests.

## Building for Production

To generate a production-ready build of the project:

```bash
npm run build
```

The build artifacts will be output to the `build/` directory.

## Folder Structure

- **`/src`**: Main source code folder.
- **`/src/components`**: Reusable React components.
- **`/src/mocks`**: Mock data for local development.
- **`/cypress`**: Cypress test configurations and scripts.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/my-new-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/my-new-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

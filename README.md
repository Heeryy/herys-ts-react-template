# create-herys-ts-react-app

This is a TypeScript React app project alongside with a predefined folder structure. The folder structure is tailored to help organize and streamline development, though not everyone follows the same setup. I use this structure for every project to maintain consistency and improve productivity.

This project is based on the `create-react-app` (`--template typescript`) package. I have modified the default folder structure to better suit my development style and to streamline the development process. I do not hold any rights nor am I associated with the official `create-react-app` package.

## Folder Structure

Here’s a breakdown of each folder in the project and its purpose:

### `src/components/`
Contains reusable components across your app.

- **Purpose**: Houses all the UI components that can be reused throughout the application.
- **Example**: Buttons, modals, input fields, headers, footers, etc.

### `src/features/`
This folder holds specific features of the application that might contain multiple components, states, and logic tied to a single feature.

- **Purpose**: Keeps code organized by separating features into their own modules.
- **Example**: A "User Profile" feature might have components, hooks, and logic related to managing the user profile.

### `src/hooks/`
Custom React hooks go here.

- **Purpose**: Any reusable logic that can be abstracted into hooks, such as state management, API calls, etc.
- **Example**: `useFetch.ts` for handling API requests.

### `src/locales/`
Contains localization files for managing translations.

- **Purpose**: Keeps language files organized so the app can support multiple languages.
- **Example**: JSON files or JavaScript objects containing translated text.

### `src/providers/`
Context providers for managing state globally.

- **Purpose**: Holds all React Context providers that share state globally across the app, like authentication or theme.
- **Example**: `ThemeProvider.tsx` for managing the theme state globally.

### `src/services/`
API and utility services.

- **Purpose**: Manages API calls, utilities, and other services that interact with external systems or logic in the backend.
- **Example**: A service for making fetch requests or interacting with a database.

### `src/styles/`
Global and component-level styles.

- **Purpose**: Contains your global styles (like CSS or styled-components) as well as individual component styles.
- **Example**: `App.css`

### `src/tests/`
Unit tests for the application.

- **Purpose**: All the test files for components, hooks, and services should be here.
- **Example**: Files testing the logic of your React components or custom hooks.

## Note

While this folder structure works well for me and the way I approach React development, **not everyone follows this type of organization**. Feel free to adapt it to suit your own needs. This package is meant to save you time by starting with an organized structure, but you are free to change it as your project grows.

---

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).


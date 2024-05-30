# ContactBook

ContactBook is a simple contact manager application built with React, designed to store contacts using local storage in the browser.

## Dependencies

- **React** - A JavaScript library for building user interfaces.
- **react-dom** - Provides DOM-specific methods that can be used at the top level of a web app.
- **uuid** - A library to generate unique identifiers.
- **uuidv4** - A library for generating UUID version 4.

## Development Dependencies

- **@types/react** - TypeScript types for React.
- **@types/react-dom** - TypeScript types for React DOM.
- **@vitejs/plugin-react** - Vite plugin for React.
- **autoprefixer** - A plugin to parse CSS and add vendor prefixes to CSS rules.
- **eslint** - A tool for identifying and reporting on patterns found in ECMAScript/JavaScript code.
- **eslint-plugin-react** - React specific linting rules for ESLint.
- **eslint-plugin-react-hooks** - ESLint plugin for React hooks.
- **eslint-plugin-react-refresh** - ESLint plugin for React Refresh.
- **postcss** - A tool for transforming CSS with JavaScript plugins.
- **tailwindcss** - A utility-first CSS framework for rapidly building custom designs.
- **vite** - A fast, opinionated web dev build tool that serves your code via native ES Module imports during development.

## Scripts

- **dev**: Start the development server using Vite.
- **build**: Build the project for production using Vite.
- **lint**: Run ESLint to lint JavaScript and JSX files.
- **preview**: Start the Vite server to preview the production build.

## Usage

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Run the development server using `npm run dev`.
4. Access the application in your browser at [http://localhost:3000](http://localhost:3000).

## Docker

You can also run the application using Docker. Follow these steps:

1. Build the Docker image:
   ```sh
   docker build -t contactbook .
   ```

# Pre-Configured React Project with TypeScript, Tailwind CSS, SCSS, ESLint, and Prettier

This project is a custom setup for a **React** application using **TypeScript**, **Tailwind CSS**, **SCSS**, **ESLint**, and **Prettier**. It includes a custom directory structure and is configured to follow best practices.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Available Scripts](#available-scripts)
- [Directory Structure](#directory-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project is a React app set up using **TypeScript** for type safety and **Tailwind CSS** for utility-first styling. It includes **SCSS** for additional styling flexibility. The project is linted using **ESLint** and automatically formatted using **Prettier**.

## Features

- **React with TypeScript**: Improved type checking and autocomplete support.
- **Tailwind CSS**: Rapid UI development with utility-first CSS classes.
- **SCSS Support**: Additional flexibility in styling.
- **ESLint**: Static code analysis for catching errors early.
- **Prettier**: Automatic code formatting for consistent style.
- **Custom Directory Structure**: A structured way to organize components, assets, and utilities.

## Installation

To get started with the project:

1. Create a New Project Using the Template:

   ```bash
   npx create-react-app my-app --tempalte configured
   ```

2. Change Directory to the New Project:

   ```bash
   cd my-app
   ``` 

3. Install Additional Dependencies (If Any)

   ```bash
   npm install
   ```

4. Verify the Configurations

   - **TypeScript**: Check if `tsconfig.json` is present.
   - **Tailwind CSS**: Verify `tailwind.config.js` is correctly set up and that your `index.css` or `index.scss` imports the Tailwind directives (`@tailwind base;`, `@tailwind components;`, `@tailwind utilities;`).
   - **SCSS**: Ensure your styling files are using `.scss` extension.
   - **ESLint**: Ensure `.eslintrc.json` is present and configured.
   - **Prettier**: Verify the `.prettierrc.json` file for formatting rules. 

5. Run Your React App

   ```bash
   npm start
   ```
  
This will launch the project in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Available Scripts

In the project directory, you can run:

- **`npm start`**: Runs the app in development mode.
- **`npm run build`**: Builds the app for production.
- **`npm run lint`**: Lints the project using ESLint.
- **`npm run format`**: Formats the code using Prettier.

## Directory Structure

Here’s an overview of the project’s directory structure:

```bash
my-app/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── assets/              # Static assets like images, fonts, etc.
│   │   ├── images/          # images.
│   │   └── styles/          # global styles.
│   │       └── global.scss
│   ├── components/          # Reusable components
│   ├── Configs/             # App configuration files (e.g. constants)
│   │   ├── apiConfig.ts     # API base URLs, keys, etc.
│   │   └── appConfig.ts     # General app settings (e.g. theme)
│   ├── context/             # Context Providers (e.g. ThemeProvider)
│   ├── features/            # Redux Slices or Context features
│   ├── helpers/             # Any helper classes
│   ├── hooks/               # Custom hooks (e.g. useFetch.ts)
│   ├── pages/               # Page-level components
│   ├── services/            # API calls and service functions
│   ├── store/               # Redux store or Context provider setup
│   ├── tests/               # Tests
│   ├── types/               # TypeScript types and interfaces
│   ├── utils/               # Utility functions (e.g. dateUtils)
│   ├── App.module.scss      # Main App-level styles 
│   ├── App.tsx              # Main App component
│   ├── index.scss           # Global styles import
│   ├── index.tsx            # Entry point for React
│   └── react-app-env.d.ts   # TypeScript declaration file for React
├── .eslintrc.json           # ESLint configuration
├── .prettierrc.json         # Prettier configuration
├── tailwind.config.js       # Tailwind CSS configuration
├── postcss.config.js        # PostCSS configuration
├── tsconfig.json            # TypeScript configuration
└── package.json             # Dependencies and scripts
```

## Technologies Used

- **React**: v18+
- **TypeScript**
- **Tailwind CSS**: v3+
- **SCSS**
- **ESLint**
- **Prettier**

## Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```

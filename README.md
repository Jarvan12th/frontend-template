# chatee-frontend
## Project Structure
```frontend/
|-- .husky/                   # Configuration and scripts for Husky git hooks.
|-- node_modules/             # Installed project dependencies.
|-- public/                   # Static files which will be served as-is by Vite.
|   |-- index.html            # Main HTML file for your app.
|   |-- favicon.ico           # App favicon.
|-- src/                      # Source code of your application.
|   |-- assets/               # Static assets required by your components.
|   |   |-- images/           # Images for your app.
|   |-- components/           # React components.
|   |-- hooks/                # Custom React hooks.
|   |-- redux/                # Redux toolkit slices and store.
|   |-- routes/               # Route definitions and async route components.
|   |-- App.tsx               # Root React component.
|   |-- main.tsx              # Entry point of the app.
|-- .eslintrc.js              # ESLint configuration.
|-- .prettierrc               # Prettier configuration.
|-- postcss.config.js         # PostCSS (with TailwindCSS and Autoprefixer) configuration.
|-- tsconfig.json             # TypeScript configuration.
|-- tsconfig.node.json        # TypeScript configuration for Node.js specific parts if needed.
|-- package.json              # Project manifest.
|-- package-lock.json or yarn.lock # Dependency versions lock file (depends on package manager).
|-- vite.config.js            # Vite configuration.
```
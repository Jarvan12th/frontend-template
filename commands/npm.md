1. Initialize a npm project \
    `npm init -y`
2. Install Vite \
    `npm install --save-dev vite`
    `npm install vite-plugin-svgr --save-dev`
3. Setup React with Vite \
    `npm install --save react react-dom`
    `npm install --save-dev @vitejs/plugin-react`
4. Setup TypeScript \
    `npm install --save-dev typescript @types/react @types/react-dom`
5. Install Other Dependencies \
    `npm install --save-dev eslint eslint-plugin-react eslint-plugin-react-hooks`
6. Setup Configuration Files \
    Create a vite.config.js, tsconfig.json, postcss.config.js, and .eslintrc.js file \
    Use TypeScript (.tsx for React components and .ts for other TypeScript files) \
7. Development & Build
    - `npm run dev` to start a dev server
    - `npm run build` to build for production
    - `npm run serve` to preview the production build
8. Linting & Formatting \
    - `npm install eslint --save-dev` to install ESLint
    - `npm install prettier --save-dev` to install Prettier
    - create a .prettierrc file and add the following:
    ```json
    {
        "semi": true,
        "trailingComma": "all",
        "singleQuote": true,
        "printWidth": 80,
        "tabWidth": 4
    }
    ```
    - `npm install eslint-plugin-prettier --save-dev` to install eslint-plugin-prettier
    - `npm install eslint-config-prettier --save-dev` to install eslint-config-prettier
    - update .eslintrc.cjs file to include the extends 'plugin:prettier/recommended'
9. Husky and lint-staged
    - `npm install --save-dev husky lint-staged` to install Husky and lint-staged
    - `npx husky install` to install Husky hooks
    - `npx husky add .husky/pre-commit "npx lint-staged"` to add a pre-commit hook \
    if it says "No valid configuration found." then follow the instructions to fix it
    - `rm -rf .git/hooks` to remove the .git/hooks folder
    - `npx husky install --save-dev` to reinstall Husky hooks

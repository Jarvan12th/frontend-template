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
    - `npm install --save-dev eslint @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-prettier eslint-config-standard-with-typescript eslint-plugin-import eslint-plugin-n eslint-plugin-prettier eslint-plugin-promise eslint-plugin-react eslint-plugin-unused-imports prettier prettier-plugin-tailwindcss` to install ESLint and Prettier
    - `npm init @eslint/config` to create a .eslintrc.js file
9. Husky and lint-staged \
    - `npm install --save-dev husky lint-staged` to install Husky and lint-staged
    - `npx husky install` to install Husky hooks
    - `npx husky add .husky/pre-commit "npx lint-staged"` to add a pre-commit hook

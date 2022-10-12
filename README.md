# Getting Started with Create React App

- npx create-react-app@latest [name-app/.] --template typescript
- npm start

### `Install Storybook`

-- npx storybook init
-- npm run storybook

### `Install Tailwindcss`

-- npm install -D tailwindcss postcss autoprefixer
-- npx tailwindcss init -p
-- add this argument to content "./src/\*\*/\*.{js,jsx,ts,tsx}"
-- add directives code to index.css
@tailwind base;
@tailwind components;
@tailwind utilities;
-- custom tailwind.config.js as needed

### `package.json`

-- "peerDependencies": {
"react": ">=16",
"react-dom": ">=16"
},

### `tsconfig.json`

-- "target": "ESNext",
-- "baseUrl": "src",
-- "module": "CommonJS",
-- "noEmit": false,
-- "outDir": "dist",
-- "declaration": true,

\\ outside compiler options
-- "exclude": ["src/stories"]

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

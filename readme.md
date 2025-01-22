### Code

```markdown
# create-react-project

## Project Setup

This project uses several npm scripts to manage development, building, and testing processes. Below is a description of each script and how to use them.

### Scripts

- **start**: This script starts the development server using Webpack. It serves the application based on the configuration specified in `webpack.config.js`.
  ```sh
  npm run start
  ```

- **build**: This script builds the project using Webpack according to the configuration in `webpack.config.js`. It compiles the source code into a production-ready bundle.
  ```sh
  npm run build
  ```

- **pack-ts**: This script compiles the TypeScript files in the project using the TypeScript compiler (`tsc`).
  ```sh
  npm run pack-ts
  ```

- **watch**: This script watches for changes in TypeScript files and recompiles them automatically.
  ```sh
  npm run watch
  ```

- **dev**: This script runs both the `start` and `watch` scripts concurrently. It starts the development server and watches for changes in TypeScript files simultaneously.
  ```sh
  npm run dev
  ```

- **test**: This script is a placeholder for running tests. Currently, it outputs an error message indicating that no tests are specified.
  ```sh
  npm run test
  ```

### Dependencies

The project relies on the following dependencies:
- `react` ^19.0.0
- `react-dom` ^19.0.0
- `react-router-dom` ^7.1.3

### Author and License

- **Author**: [P K Akash]
- **License**: ISC
```

This `README.md` file provides a clear description of each npm script and how to use them, making it easier for new developers to get started with the project.
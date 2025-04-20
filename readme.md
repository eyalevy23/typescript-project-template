# TypeScript Project Template

```markdown
Welcome to the TypeScript Project Template!

This repository serves as a starting point for future TypeScript projects. It is configured with best practices and includes tools to help you quickly set up and run your project with minimal configuration.

## Features

- **TypeScript Setup:** Configured with a `tsconfig.json` to compile the project from the `src` folder to the `dist` folder.
- **Development Mode:** Uses `concurrently` to run TypeScript compiler in watch mode along with `nodemon` to automatically restart the node application on changes.
- **Clean Project Structure:** Separate folders for TypeScript source code (`src`), compiled JavaScript (`dist`), and additional project utilities.

## Getting Started

Follow the steps below to use this template for your new TypeScript project:
```

### 1. Clone the Repository

```bash
git clone https://github.com/eyalevy23/typescript-project-template.git
cd my-new-project
```

### 2. Install Dependencies

This template uses [pnpm](https://pnpm.io/) by default. If you use another package manager like npm or yarn, adjust the commands accordingly.

```bash
pnpm install
```

### 3. Run the Project in Development Mode

The development script concurrently runs the TypeScript compiler in watch mode and `nodemon` to restart the application whenever changes are detected.

```bash
pnpm run dev
```

### 4. Build the Project

To compile the TypeScript code into JavaScript, run:

```bash
pnpm run build
```

### 5. Run the Compiled Application

After building the project, you can run the compiled application with:

```bash
pnpm start
```

## Customization

- **TypeScript Configuration:** Modify the `tsconfig.json` file to adjust compiler options, include/exclude files, or change the output directory as needed.
- **Scripts:** Update or add scripts in the `package.json` file to fit your project's specific requirements.
- **Additional Tools:** Integrate other libraries or tools that suit your workflow.

## License

This template is provided under the ISC License. Please refer to the [LICENSE](./LICENSE) file for more details.

## Contributing

Feel free to fork this repository and submit pull requests if you have improvements or additional features that could benefit future projects.

## Future Projects

When starting a new TypeScript project, use this repository as a baseline. Simply clone it and update the project details (such as the `name`, `description`, and `author`) in the `package.json` and `README.md` files to reflect your new project.

Happy coding!

```

---

This **README.md** provides a clear guide for cloning the template, installing dependencies, and running or building the project, along with tips on how to customize the template for future projects. Enjoy using this template as a foundation for your next TypeScript project!

```

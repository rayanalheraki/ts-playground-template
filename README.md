# TypeScript Project Template

A minimal but complete TypeScript project template with hot-reload development setup. Perfect for learning TypeScript or starting new projects.

## Features

- 🚀 TypeScript 5.x configuration
- ♨️ Hot reload development with Nodemon
- 🔧 Preconfigured development environment
- 🌐 Express.js server setup
- 📦 NPM scripts for common tasks

## Prerequisites

Before you begin, ensure you have installed:
- [Node.js](https://nodejs.org/) (version 14.x or higher)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)

## Getting Started

### Using this template

1. Click the "Use this template" button on GitHub
2. Clone your new repository
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

### Manual Setup

1. Clone the repository
```bash
git clone https://github.com/original-repo/typescript-template.git
cd typescript-template
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

## Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build the TypeScript code
- `npm start` - Run the built code
- `npm run watch` - Watch for changes and compile TypeScript

## Project Structure

```
typescript-template/
├── src/                    # Source directory
│   ├── index.ts           # Entry point
├── dist/                  # Compiled output (generated)
├── package.json           # Project configuration
├── tsconfig.json         # TypeScript configuration
├── nodemon.json          # Nodemon configuration
└── .gitignore           # Git ignore rules
```

## Making Changes

1. The development server will automatically restart when you make changes
2. Edit files in the `src` directory
3. Add new TypeScript files as needed
4. Import new files in `index.ts` if they need to be included in the build

## Building for Production

1. Run the build command:
```bash
npm run build
```

2. The compiled JavaScript will be in the `dist` directory

## Configuration Files

### tsconfig.json
- Configures TypeScript compiler options
- Set to ES2020 target
- Includes strict type checking
- Outputs to `dist` directory

### nodemon.json
- Configures the development server
- Watches `.ts` and `.js` files
- Uses ts-node for TypeScript execution


## License

This project is licensed under the MIT License - see the LICENSE file for details

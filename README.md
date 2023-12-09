# Webpack Demo Project

This is a simple webpack demo project that serves as a starting point for building modern web applications. It is configured with webpack to handle development and production builds, including the compilation of JavaScript (TypeScript), CSS (Sass), and asset files.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Scripts](#scripts)
- [Dependencies](#dependencies)
- [Author](#author)
- [License](#license)

## Installation

Before you begin, make sure you have Node.js and npm installed on your machine. Then, clone this repository and install the dependencies:

```bash
git clone https://github.com/your-username/webpack-demo.git
cd webpack-demo
npm install
```

## Usage

This project is configured with webpack to streamline your development and build processes. Here are the main scripts you can use:

### Development Mode

To run the project in development mode, execute:

```bash
npm run dev
```

This will start the webpack dev server, watch for changes in your source files, and automatically reload the browser.

### Production Build

To create a production-ready build, use:

```bash
npm run build
```

This will generate optimized and minified files in the `dist` directory.

## Scripts

- **dev**: Run the project in development mode using webpack dev server.
- **build**: Generate a production-ready build.

## Dependencies

The project depends on the following development packages:

- **@babel/core**: Babel core functionality.
- **@babel/preset-env**: Babel preset for compiling JavaScript to a compatible version.
- **babel-loader**: Babel loader for webpack.
- **css-loader**: CSS loader module for webpack.
- **file-loader**: File loader module for webpack.
- **html-webpack-plugin**: Plugin to simplify HTML file creation to include the generated bundles.
- **mini-css-extract-plugin**: Extracts CSS into separate files.
- **node-sass**: Node.js bindings to libsass.
- **sass-loader**: Sass loader for webpack.
- **style-loader**: Style loader module for webpack.
- **ts-loader**: TypeScript loader for webpack.
- **typescript**: TypeScript language.
- **webpack**: Module bundler.
- **webpack-cli**: Command-line interface for webpack.
- **webpack-dev-server**: Development server for webpack.

## Author

Ismatullo Asatullaev

- Email: [ismatullome@gmail.com](mailto:ismatullome@gmail.com)
- Website: [https://ismatullo.uz/](https://ismatullo.uz/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

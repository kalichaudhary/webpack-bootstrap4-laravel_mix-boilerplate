# Webpack Bootstrap 4 Laravel Mix Boilerplate
**Bootstrap 4.0** and **FontAwesome 4.7** Boilerplate, bundled with **Webpack** and managed by **Laravel Mix**.


## Introduction
**Webpack Bootstrap 4 Laravel Mix Boilerplate** comes with [Bootstrap 4 higher](https://getbootstrap.com/) framework, [FontAwesome](http://fontawesome.io/) icons pack and makes use of [Laravel Mix](https://laravel-mix.com) for defining basic [Webpack](http://github.com/webpack/webpack) build steps for your application.

Webpack Bootstrap 4 Laravel Mix Boilerplate is **preconfigured to perform these Mix tasks**:
- Sass compilation with URL rewriting and Autoprefixer PostCSS plugin
- JavaScript bundling with ES5 code compilation
- Vendor libraries extraction, for improved long-term caching
- In-file source maps generation
- Browser synchronization on changes
- Minification on production


## Requirements

This project requires [Node.js](https://nodejs.org/) to be installed on your machine. Run <code>node -v</code> on your shell to check if you are ready. Your Node.js version must be 4.0 or higher.


## Quick Start
These instructions will get you a copy of **Webpack Bootstrap 4 Laravel Mix Boilerplate** up and running on your local machine.

### 1. Install
Clone the repository and install with npm:
```shell
git clone https://github.com/kalichaudhary/webpack-bootstrap4-laravel_mix-boilerplate.git
```
```shell
cd webpack-bootstrap4-laravel_mix-boilerplate
```
```shell
npm install | yarn install
```

### 2. Configure
Open <code>webpack.mix.js</code> file and edit these constants as you prefer:
```javascript
// Path to dist folder
const DIST = 'dist';

// Proxy an existing virtual host (eg: 'your-project.dev', 'localhost/your-project').
// If null, use the built-in static server.
const PROXY = null;
```

### 3. Get Started
Mix is a configuration layer on top of Webpack, so to run your Mix tasks you only need to execute one of the NPM scripts that is included with the default package.json file.

#### Run all Mix tasks
```bash
npm run dev | yarn start
```

#### Watch assets for changes and Sync browser
```bash
npm run watch | yarn watch
```

#### Run all Mix tasks and minify output
```bash
npm run prod
```


## Documentation
- [Laravel Mix API](https://github.com/JeffreyWay/laravel-mix/tree/master/docs#readme)
- [Bootstrap](https://getbootstrap.com/docs/4.0/getting-started/introduction/)


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

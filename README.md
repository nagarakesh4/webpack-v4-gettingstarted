## Webpack v4 Getting Started

to run this repo webpack v4 in your local,

On Command line

1. Clone this repo:

```
    git clone https://github.com/nagarakesh4/webpack-v4-gettingstarted.git
```

2. Install webpack v4 modules from package.json:

```
    npm install
```

you may use yarn as well

3. To run development mode:

```
    npm run dev
```

under ./dist/main.js you can verify the babel converted js file as unminfied

3. To run production mode:

```
    npm run build
```

under ./dist/main.js you can verify the babel converted js file as minified

### Key points:

1. No need to maintain a separate config.js file to store entry point (input file and output file), instead webpack just looks for ./src/index.js

2. Development and production mode can be easily set with --mode flag (look in package.json file), and for production mode, TreeShaking, ScopeHoisting and Minification are out of box (and no need of UglifyJS plugin etc...,)

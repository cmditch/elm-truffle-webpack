# elm-truffle-webpack-starter


### About:
A Webpack setup for writing [Elm](http://elm-lang.org/) + [Web3](https://github.com/ethereum/web3.js/) apps:

* Dev server with live reloading, HMR
* Support for CSS/SCSS (with Autoprefixer), image assets
* Bootstrap 3.3+ (Sass version)
* Bundling and minification for deployment
* Basic app scaffold, using `Html.beginnerProgram`
* A snippet of example code to get you started!


### Install:
Clone this repo into a new project folder, e.g. `my-elm-web3-project`:
```
git clone https://github.com/cmditch/elm-truffle-webpack my-elm-web3-project
cd my-elm-web3-project
```

Re-initialize the project folder as your own repo:
```
rm -rf .git
git init
git add .
git commit -m 'first commit'
```

Install all dependencies using the handy `reinstall` script:
```
npm run reinstall
```
*This does a clean (re)install of all npm and elm packages, plus a global elm install.*


### Serve locally:
```
npm start
```
* Access app at `http://localhost:8080/`
* Get coding! The entry point file is `src/elm/Main.elm`
* Browser will refresh automatically on any file changes..


### Build & bundle for prod:
```
npm run build
```

* Files are saved into the `/dist` folder
* To check it, open `dist/index.html`


### Run Tests
```
truffle test
npm run test (Will be added)
```

### Lint
```
npm run lint
```


### Changelog

**Ver 0.1.0**

* Basic Build Operational

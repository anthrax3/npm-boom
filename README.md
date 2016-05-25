# npm-es6-boilerplate

Use this boilerplate to get up and running quickly. (eslint, es6, mocha)

# quick start

**clone repo**
```sh
git clone git@github.com:reergymerej/npm-es6-boilerplate.git ./your-project
```

**reset git**
```sh
cd ./your-project
rm -rf ./.git
git init
```

**reset npm**
```sh
npm init
npm i
```

# guide

Write your es6 in `./src`.

Write your tests in `./test`.

Build with `npm run build`.

Test with `npm test`.


## npm scripts

* **lint** - runs eslint on `./src` and `./test`
* **test** - runs tests in `./test` with Mocha
* **build** - transpiles `./src` to `./lib`
* **prepublish** - automatically runs when publishing to build `./lib`

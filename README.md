# angular2quickstart
based on https://angular.io/docs/js/latest/quickstart.html

## quick start

1. `npm install -g jspm http-server typescript tsd`

2. `tsd reinstall -r -o`

3. `tsc -p ./src` to compile with typescript

4. `jspm install` to install all external libraries

5. open a new tab and run `http-server`

6. browse to <http://localhost:8080/index.html>

### Starting from Scratch with JSPM

1. delete the following JSPM folders and files

```
jspm_packages
config.js
```

2. remove the `jspm` section in `package.json`

3. run `jspm install angular2 reflect-metadata es6-shim`

4. open a new tab and run `http-server`

5. browse to <http://localhost:8080/index.html>

### More about JSPM

**Install Angular2**

`jspm install angular2`

**Install Angular2 support libraries**
`jspm install reflect-metadata es6-shim`

**Install the Latest TypeScript**
`jspm install typescript`

**Install optional Angular2 support libraries**
`jspm install immutable text zone.js`

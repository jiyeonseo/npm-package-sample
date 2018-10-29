# NPM Package example

## Add npm user
```bash
$ npm adduser
Username: jiyeonseo
Password:
Email: (this IS public) seojeee@gmail.com
Logged in as jiyeonseo on https://registry.npmjs.org/.
$ npm whoami
jiyeonseo
```

## Initiate npm package 
```
$ npm init
npm init

{
  "name": "npm-package-sample",
  "version": "1.0.0",
  "description": "this is hello world npm package",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC"
}
```

## `index.js`
```js
export.module.sample = () => "this is the way to export your module";
```

## Update the version 
```
$ npm version  // check version
{ 'npm-package-sample': '1.0.0',
  npm: '6.4.1',
  ares: '1.10.1-DEV',
  cldr: '31.0.1',
  http_parser: '2.7.0',
  icu: '59.1',
  modules: '57',
  nghttp2: '1.25.0',
  node: '8.9.4',
  openssl: '1.0.2n',
  tz: '2017b',
  unicode: '9.0',
  uv: '1.15.0',
  v8: '6.1.534.50',
  zlib: '1.2.11' }
$ npm version 1.0.1 // update version 
v1.0.1
```

## Publish npm package
- to publish your npm, name have to be **unique**
```
$ npm publish   
```

[![publish](/npm-package-sample.png)](/npm-package-sample.png)


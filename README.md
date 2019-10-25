# nodejs-pkj-template

>This is the template for starting a Node.js package

<!-- ## Usage -->

## Quick Start

Create the app:
```sh
mkdir /tmp/foo && cd $_;
npm init -y;
```

Since the package is ESM, install ESM:
```sh
npm i -S esm;
```

Install nodejs-pkj-template:
```sh
npm i -S nodejs-pkj-template;
```

Create main module: 
```sh
vi /tmp/foo/app.js;
```

```js
/* /tmp/foo/app.js */
import {add, sub, div, mul} from 'nodejs-pkj-template';
console.log(`add(1,2)=${add(1,2)}`);
console.log(`sub(1,2)=${sub(1,2)}`);
console.log(`div(1,2)=${div(1,2)}`);
console.log(`mul(1,2)=${mul(1,2)}`);
```

Run the main module: 
```sh
cd /tmp/foo/;
node -r esm app;
```

<!-- ## Demo -->

## Unit test the package
Test nodejs-pkj-template:
```sh
cd ./node_modules/nodejs-pkj-template/;
npx jest --coverage;
#npm run test;
```

## License
[MIT](LICENSE.txt)

## Author
- Github: [sasadango](https://github.com/sasadango)
mail to: caution.sk@gmail.com

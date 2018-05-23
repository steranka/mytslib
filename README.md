# My Simple TypeScript example library
Code based off of 
https://www.tsmean.com/articles/how-to-write-a-typescript-library/ and
and associated GIT code at https://github.com/bersling/typescript-library-starter.
 
Also see  
https://www.tsmean.com/articles/how-to-write-a-typescript-library/
and code at https://github.com/bersling/typescript-library-starter

# Developer Notes
You can download this 

```git clone git@github.com:steranka/mytslib.git```

Compile the library, and transpile code to "lib" directory.

```
npm run build
ls lib
```

Run the test cases

```npm run test```

Publish the package to npm

```
npm login
npm publish --access public
```

# Using the library
This library can be used importing it as follows

```
const { sum } = require('@pats2265/mytslib)
console.log('sum(1,2) is ' + sum(1,2));
output ==> sum(1,2) is 3
```
See full example at [examples/usemytslib-node](./examples/usemytslib-node/README.md)

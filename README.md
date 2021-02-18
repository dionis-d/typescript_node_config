# typescript_node_config
How Compile TypeScript

init

    npm init
    
install

      npm i typescript ts-node nodemon eslint @types/node @typescript-eslint/eslint-plugin @typescript-eslint/parser
package.json/scripts

   
    "dev":"nodemon src/index.ts"
init tsc

    tsc --init

in typescript.json/compilerOptions

    "target": "es5", /* Specify ECMAScript target version: 'ES3' (default), 'ES5', 'ES2015', 'ES2016', 'ES2017', 'ES2018', 'ES2019' or 'ESNEXT'. */
    "module": "commonjs", /* Specify module code generation: 'none', 'commonjs', 'amd', 'system', 'umd', 'es2015', or 'ESNext'. */
    "sourceMap": true, /* Generates corresponding '.map' file. */
    "outDir": "./build", /* Redirect output structure to the directory. */
    "rootDir": "./src", /* Specify the root directory of input files. Use to control the output directory structure with --outDir. */
    "strict": true, /* Enable all strict type-checking options. */
    "moduleResolution": "node", /* Specify module resolution strategy: 'node' (Node.js) or 'classic' (TypeScript pre-1.6). */
    "esModuleInterop": true, /* Enables emit interoperability between CommonJS and ES Modules via creation of namespace objects for all imports. Implies 'allowSyntheticDefaultImports'. */
    "forceConsistentCasingInFileNames": true  /* Disallow inconsistently-cased references to the same file. */
    
optionals after compiler options config:
"include": ["src/**/*"],
"exclude": ["node_modules"]

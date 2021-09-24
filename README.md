- First-ts-package: folder contains all initial files to create npm package.
- First-consumer: Import newly created package in main.ts file for use.

# Typescript Config for typescript code compilation
     - tsconfig.json: typescript config file to compile typescipt code in to js code for the all the files under source folder.
     
     "compilerOptions": {
          "module": "commonjs",
          "target": "es5",
          "declaration": true,
          "outDir": "./dist"
     },
     "include": ["src/**/*"]

# Package Defination for first npm library
     {
       "name": "my-first-library",
       "version": "0.0.1",
       "scripts": {
         "build": "tsc"
       },
       "description": "",
       "main": "dist/index.js",
       "types": "dist/index.d.ts"
     }

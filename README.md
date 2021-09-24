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

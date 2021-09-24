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
## Angular Library Features:
     1. Platform Independent
     2. Bundled and Distributed in public/private platform for uses
     3. Ahead-of-time compilation ready
     4. Code should be in Typescript
     
## Angular Package Format:
     1. Inline all the templates as Angular not prefer to use any external template and styles in library
     2. Library should bundle as single file and take all external templates in to one place
     3. Compile it with ngc
     4. Build with ESM2015, ESM5 and UMD Formats
     
     

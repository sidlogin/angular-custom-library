#Create a first package using typescript
     - tsconfig.json: typescript config file to compile typescipt code in to js code for the all the files under source folder.
     
     "compilerOptions": {
          "module": "commonjs",
          "target": "es5",
          "declaration": true,
          "outDir": "./dist"
     },
     "include": ["src/**/*"]

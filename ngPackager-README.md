## Ng-packager
  1. Angular Package Format
  2. Bundles in (F)ESM2015, (F)ESM5, UMD
  3. Consumed by different module loaders
  4. Creates type definitions (.d.ts)
  5. Ahead-of-time metadata
  6. Inlining styles and templates

### npm install ng-packager -g
- Installing ng-packager globally
- Makes the "ng-packager" command globally available

### Metadata for ng-packager in package.json
"ng-packager": {
  "lib": {
    "entryFile": "public_api.ts"
  },
  "dest": "dist"
}

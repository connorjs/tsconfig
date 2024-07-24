# @connorjs/tsconfig

@connorjs’s tsconfig files.

## Available configurations

- `app`: Application-specific configuration (disables emit).
- `base`: Base configuration file that sets strict settings.

## Usage

1. Install the package.

   ```shell
   npm i -D @connorjs/tsconfig
   ```

2. Extend it in your `tsconfig.json`.
   Change the extends based on the configuration.

   ```json
   {
     "extends": "@connorjs/tsconfig/app/tsconfig.json",
     "compilerOptions": {
   	   // Your compiler options here
   	   "baseUrl": ".",
   	   "outDir": "./artifacts/tsc"
     },
     "include": ["src"]
   }
   ```

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
   An example follows.

   ```json
   {
     "extends": "@connorjs/tsconfig/app/tsconfig.json",
     "compilerOptions": {
       "baseUrl": ".",
       "outDir": "./artifacts/tsc"
     },
     "include": ["src"]
   }
   ```

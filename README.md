# NestJS Scaffolding

Here is what it should be done (IMHO) to start a NestJS project

```bash
# Scaffold with nestjs/cli
npx @nestjs/cli new project-name

# Open the project directory
cd project-name

# Add .gitignore (?)
# Add .editorconfig

# Install the tslint airbnb configuration
yarn add --dev tslint-config-airbnb
# Replace the tslint.json file

# Install the configuration manager
yarn add node-config-ts
# Add the "postinstall" script: "node-config-ts"
# Add the "config" directory with a default.json file inside

# Remove the app/app.* files
```

## Modules / libraries / repos

- [NestJS](https://github.com/nestjs/nest)
- [AirBnb tslint](https://github.com/progre/tslint-config-airbnb)
- [node-config-ts](https://github.com/tusharmath/node-config-ts)
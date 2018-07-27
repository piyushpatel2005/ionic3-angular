# Ionic 3 Framework for Hybrid Mobile App Development

This is a repo contains Ionic Mobile App

## Prerequisites:
- NodeJS v6.9.1
- npm 3.10.8
- nvm (Optionally)
- Ionic 3.20.0

## How to launch the project?

Install Ionic Cordova

`npm install ionic cordova -g`

## Ionic Framework Mini Tutorial

### Creating Template for the project

```shell
npm install ionic cordova -g
ionic start conFusion sidemenu
ionic serve --lab
```

Ionic Page is pretty much similar to Angular controllers.

```shell
ionic info # view the info of Ionic installations
ionic help
ionic docs
ionic signup
ionic login
ionic logout

# Create new page using 
ionic g page about
# Update app.component.ts to include those new pages
# Update app.module.ts to include declarations for new components/pages
```

Visit `http://localhost:8100/ionic-lab` to view the application

- Define interfaces for different objects.
- Define Ionic providers using commands:
Ionic providers are the similar to Angular services

```shell
ionic g provider Dish
```

Ionic CLI import Providers automatically. It doesn't do so for Pages in `app.module.ts`.

Create generic HttpmsgProvider to handle every Http observable response.
Use this provider in different other providers.

Configure JSON-server to run locally

```shell
npm install json-server -g
# Run following command from server folder.
json-server --watch db.json -d 2000
```

The Navigation is handled through NavController and NavParams. Ionic navigation is a parent-child relationship with parent pushing the data to child on the stack.

## More Info:

Please, contact the repo developer for more information on the project.
# MyPorfolio - Hacer un deploy

Este proyecto se generó con Firebase, HTML5, CSS3, JavaScript.

## Procedimiento para subir la WebSite a la nube

1- Loguearse en Firebase (firebase login)
2- Autenticar cuenta de google
3- Iniciar firebase (firebase init)
4- Are you ready to proceed? (Y)
5- Seleccionar Hosting: Configure files for Firebase Hosting and (optionally) set up GitHub Action deploys (*)
6- What do you want to use as your public directory? (public)
7- Configure as a single-page app (rewrite all urls to /index.html)? (Yes)
8- Set up automatic builds and deploys with GitHub? (Yes)
9- For which GitHub repository would you like to set up a GitHub workflow? (format: user/repository) (maurifl/MyPorfolio)
10- Set up the workflow to run a build script before every deploy? (Yes)
11- What script should be run before every deploy? (npm ci)
12- GitHub workflow file for PR previews exists. Overwrite? firebase-hosting-pull-request.yml (Yes)
13- Set up automatic deployment to your site's live channel when a PR is merged? (Yes)
14- What is the name of the GitHub branch associated with your site's live channel? (main)
15- The GitHub workflow file for deploying to the live channel already exists. Overwrite? firebase-hosting-merge.yml (Yes)
16- firebase deploy
17- Copiamos los archivos trabajados de nuestra page y reescribimos los de la carpeta public
18- firebase deploy
19- Veremos las URL generadas con nuestro site
    Project Console: https://console.firebase.google.com/project/myporfolio-65b10/overview
    Hosting URL: https://myporfolio-65b10.web.app

## Material de Consulta

URL: https://www.youtube.com/watch?v=drvXMz75k5s

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

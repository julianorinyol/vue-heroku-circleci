example vue app that automatically deploys to heroku using circle ci
* follow these instructions to create a heroku app.
    - https://medium.com/netscape/deploying-a-vue-js-2-x-app-to-heroku-in-5-steps-tutorial-a69845ace489

* add the circle CI add-on to your github account
* create the circle CI project linking it to your github repo 
* Set Environment variables in Circle CI Project
    - click on the Gear icon on the far right on the project page
    - click on Environment Variables
    - add HEROKU_API_KEY
        + get this from the "api key" section of your heroku settings here
             https://dashboard.heroku.com/account 
    - add HEROKU_APP_NAME 

GET 

# vue-heroku-circleci

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

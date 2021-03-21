# cli-tools

git, npm/yarn, composer, pypi

### npm • nodejs package manager
```sh
# make sure nodejs is installed
# npm -v
# prints npm version

# npm install 
npm install 
```


##  create-react-app, angular-cli and vue-cli
### create-react-app 
visit https://create-react-app.dev to know  more
```sh
# the preffered way
npx create-react-app app-name # creates a react app
cd app-name
npm build # builds the project in /build dir.
```

### angular-cli, a rich cmd tool for creating and maintain angular app
```sh
# install angular-cli using npm
# basic commands
ng new app-name # creates an angular app
cd app-name
ng serve # builds the priject
ng serve # runs the project in development server
```





### yarn • similar to npm
https://yarnpkg.com/

```bash
# installation
npm install -g yarn
```

### composer • php package manager
https://getcomposer.org
```sh
# create composer.json in root directory with proper json format.

```sh
# then run the command 
composer update
```
this will install the dependencies to /vendor dorectory. a file called composer.lock will aslo created to lock the dependencies of your project to a known state. 
for example, to deploy a php project on Heroku, suppose putting this in composer.json
```json
{
  "require" : {
    "silex/silex": "^2.0.4",
    "monolog/monolog": "^1.22",
    "twig/twig": "^2.0",
    "symfony/twig-bridge": "^3"
  },
  "require-dev": {
    "heroku/heroku-buildpack-php": "*"
  }
}
```
```sh
composer update
```
this will genarate required /vendor and composer.lock
Heroku will detect composer.json and treat the project as php project



### phpmyadmin • php to handle the administration of MySQL
```

```



### PyPI • The Python Package Index 
https://pypi.org
```
```






# deployment tools
## Heroku
## netlify
## firebase


### flutter and android studio
#### installing android studio










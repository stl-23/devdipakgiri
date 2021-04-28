# cli-tools

curl, git, npm/yarn, composer, pypi/anaconda

## curl 
### a very basic example
command to create a file google.html and save response from google.com
```sh
curl -X GET https://www.google.com > google.html
# it means 
# -X GET reffers request method is GET
# then url
# then '>' refers the output file to save the response
```


## Anaconda
### installation
this video tutorial makes it easy: https://www.youtube.com/watch?v=DY0DB_NwEu0

## git 
### deleting a branch
with examples

## add existing preject to repo
```
# create a repository from github website
git init
git add .
git commit -m "commit massage"
git branch -M main
git remote add origin https://github.com/path-to-repo.git
git push -u origin main
```

to delete master branch
```git push origin :master```

### npm • nodejs package manager
```sh
# make sure nodejs is installed
# npm -v
# prints npm version

# npm install 
npm install 
```
``` 
# this command will update all the packages listed to the latest version.
npm update [-g] [pkg] 
# npm update inside a project will update all packages to the latest version
```

### yarn - preffer to use yarn over npm
```sh
# create react app using yarn
yarn create react-app myapp
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

### vue-cli

#### install vue-cli globally

```sh
npm install -g @vue/cli
# OR
yarn global add @vue/cli
```

#### create vue project

```sh
vue create my-project
# OR
vue ui
```

#### run 
```sh
npm run serve
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
```
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
- login
- new site
- check build config
- deploy

### to change site name
settings -> general -> change site name






## firebase


### flutter and android studio
#### installing android studio
#### install vscode
#### install flutter
run following command to install flutter  using ```sudo snap install flutter --classic```
then, run ```flutter doctor``` to complete the setup to install flutter, it will download required SDK
#### install android studio SDK by installing android studio
dont't mess with android studio if you're not intrested in native android app development.

#### be patient with flutter
press ```ctrl + shift + p``` to open command pallet in vscode
type Flutter: New Application
locate SDK path when asked
get sdk path of flutter by ```flutter sdk-path```

lets rock, i don't do flutter or android!






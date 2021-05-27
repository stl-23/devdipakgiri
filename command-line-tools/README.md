# cli-tools
this repo is all about using command line tools like curl/wget, git, npm/yarn, composer, pypi/anaconda

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

# python tools
## Anaconda
### installation
this video tutorial makes it easy: https://www.youtube.com/watch?v=DY0DB_NwEu0
make sure to add conda properly

### PyPI • The Python Package Index 
https://pypi.org
```
# nothing for now
```


# github 
### deleting a branch
#### to delete master branch
```git push origin :master```
#### add existing preject to repo
```
# create a repository from github website
git init
git add .
git commit -m "commit massage"
git branch -M main
git remote add origin https://github.com/path-to-repo.git
git push -u origin main
```

# PHP tools
## composer: php package manager
goto https://getcomposer.org for more details
```sh
# create composer.json in root directory with proper json format.
```
```sh
# then run the command 
composer update
```
#### Heroku specific example
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



### phpmyadmin: php to handle the administration of MySQL
```sh
# nothing for now
```


# deployment tools
## Heroku

## netlify
- login
- new site
- check build config
- deploy

### to change site name from website
settings -> general -> change site name


## firebase

# flutter and android studio

## installing android studio
## install vscode
## install flutter
run following command to install flutter  using ```sudo snap install flutter --classic```
then, run ```flutter doctor``` to complete the setup to install flutter, it will download required SDK

## install android studio SDK by installing android studio
dont't mess with android studio if you're not intrested in native android app development.

## be patient with flutter
press ```ctrl + shift + p``` to open command pallet in vscode
type Flutter: New Application
locate SDK path when asked
get sdk path of flutter by ```flutter sdk-path```

lets rock, i don't do flutter or android!






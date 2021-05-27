# NPM, stands for node package manager
## npm
### install command

## npx

### creating a Next.js app
```npx create-next-app money-by-typing```

if yarn is installed it will use yarn
### to prevent yarn
```npx create-next-app money-by-typing --use-npm```































# RAW text




# NodeJS tools
### npm: the nodejs package manager
make sure nodejs is installed
```sh
# npm -v
# prints npm version

# npm install 
npm install 
```
## npm commands
### install
```
npm install  [-g] [pkg] [options] 
# used for either to install packages locally in dependencies or development 
# or to install globally
```
### upgrade
``` 
# this command will update all the packages listed to the latest version.
npm update [-g] [pkg] 
# npm update inside a project will update all packages to the latest version
```
## npx commands
TODO: write about it later


## yarn
i preffer to use yarn over npm
```sh
# create react app using yarn
yarn create react-app myapp
```


###  create-react-app, angular-cli and vue-cli
### create-react-app 
visit https://create-react-app.dev to know  more
```sh
# the preffered way
npx create-react-app app-name # creates a react app
cd app-name
npm build # builds the project in /build dir.
```

### angular-cli
a rich cmd tool for creating and maintain angular app
```sh
# install angular-cli using npm
# basic commands
ng new app-name # creates an angular app
cd app-name
ng serve # builds the priject
ng serve # runs the project in development server
```

### vue-cli
install vue-cli globally
```sh
npm install -g @vue/cli
# OR
yarn global add @vue/cli
```
create vue project
```sh
vue create my-project
# OR
vue ui
```
run 
```sh
npm run serve
```

## yarn: similar to npm
goto https://yarnpkg.com/ for more details
```bash
# installation
npm install -g yarn
```

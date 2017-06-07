# Yarn Package Manager
A package manager release by Facebook

Yarn has a local cache. Has an offline mode if the dependencies are in your local cache. 

[Yarn package manager](https://yarnpkg.com/en/)

## Install Yarn

```bash
npm install yarn -g
```


## Run this example project
Download or clone

```bash
yarn install
```

### Run dev
```bash
yarn run dev
```

### Run prod
```bash
yarn run start
```

## Create a new project
### Initialize
```bash
yarn init -y 
```

## Work with an existing project
### Add a package

```bash
yarn add express
yarn add express@3.0.0
```

### Add dev dependency
```bash
yarn add mocha --dev
```

### Remove package
```bash
yarn remove mocha
```

### Upgrade to most recent version of a package
```bash
yarn upgrade express
```

### Downgrade a version of a package
```bash
yarn upgrade express@3.0.0
```

### Yarn outdated
Shows you the versions you have versus what is the latest release.
```bash
yarn outdated
```

### Reinstall

```bash
yarn install
```
### Clear local cache
```bash
yarn cache clean
```

### Run scripts

```bash
 yarn run start
```

### Install global modules
```bash
yarn global add nodemon
```

### Upgrade global modules
```bash
yarn global upgrade nodemon
```

### Remove global modules
```bash
yarn global remove nodemon
```

### Clock your NPM install time
This will only work on OSX and Linux.
```bash
time npm install
```


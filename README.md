# KOKI-BLOCKCHAIN

# Prerequisite
- NPM version 5.8.0
- TRUFFLE verson 4.1.5
- Ganache or your private network
- Metamask: not mandatory but better if you want to register more users

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

# Quick Installation
1) Download the project and decompress it into the folder **~/KOKI-BLOCKCHAIN** (or wherever you want).
2) Start ganache (or your private blockchain).
3) npm install
4) Open the terminal (if you are using Windows you **must use the Power Shell**) in the folder **~/app-token** and run the command:
```sh
$ truffle console --network ganache
```
5) If ganache is running you should be inside the truffle console; now run the following command in the truffle console:
```sh
> migrate --reset --compile-all
```
6) If the migration was successful, copy all file from **~/KOKI-BLOCKCHAIN/build/contracts/** to the folder **~/KOKI-BLOCKCHAIN/app-token/src/assets/**

8) Once all the dependencies are installed run the command:
```sh
$ npm run dev
```
If everything went fine, the terminal will display a message similar to:
```sh
DONE  Compiled successfully in 5166ms           15:54:53

Your application is running here: http://localhost:8080
```
9) Open the browser, go to the URL shown by your terminal and play with the Koki!

**NOTE:** if you want to try to add more user profiles you have to install metamask in your browser, then import the accounts into metamask and finally change account on metamask in order to register a new user.
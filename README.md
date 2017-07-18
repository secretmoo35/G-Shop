This is a starter template for [Ionic3](http://ionicframework.com/docs/) projects.

## How to use this template

```bash
$ npm install
$ ionic serve
```

## How to add platform

```bash
$ ionic cordova platform add [android/ios] || $ ionic cordova build
$ ionic cordova run [android/ios] --device
```

### With the Ionic CLI:

Take the name after `ionic2-starter-`, and that is the name of the template to be used when using the `ionic start` command below:

```bash
$ sudo npm install -g ionic cordova
$ ionic start mySideMenu sidemenu
```

Then, to run it, cd into `mySideMenu` and run:

```bash
$ ionic cordova platform add ios
$ ionic cordova run ios
```

Substitute ios for android if not on a Mac.


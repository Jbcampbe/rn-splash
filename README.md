# rn-splash

Automatic splash screen generator for React Native. Based on [cordova-splash](https://github.com/AlexDisler/cordova-splash). Create a splash screen once in the root folder of your React Native project and use rn-splash to automatically crop and copy it for all the platforms your project supports.

The splash screen image should be 2208x2208 px with a center square of about 1200x1200 px. The image may be cropped around the center square. You can also use larger images with similar proportions.

### Installation

    $ sudo npm install rn-splash -g

### Requirements

- ImageMagick installed (*Mac*: `brew install imagemagick`, *Debian/Ubuntu*: `sudo apt-get install imagemagick`, *Windows*: [See here, install "Legacy tools"](http://www.imagemagick.org/script/binary-releases.php#windows))
- React Natives app.json file must exist in the root folder

### Usage

Create a `splash.png` file in the root folder of your RN project and run:

    $ rn-splash

You also can specify manually a location for your `config.xml` or `splash.png`:

    $ rn-splash --config=config.xml --splash=splash.png

### Icons

Check out [app-icon](https://github.com/dwmkerr/app-icon)

### License

MIT

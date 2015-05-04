# Run

    alias ionic="docker run -ti -p 8100:8100 -p 35729:35729 --privileged -v /dev/bus/usb:/dev/bus/usb -v \$PWD:/myApp:rw agileek/ionic-framework"
    ionic bash
    cordova create ./foo
    cd foo/
    cordova platforms add android
    cordova build

connect your android device with usb

    cordova run android

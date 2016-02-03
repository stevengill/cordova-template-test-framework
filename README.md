# Cordova Template Test Framework

This is a cordova template that automatically fetches [cordova-plugin-test-framework](https://github.com/apache/cordova-plugin-test-framework) and sets the start page to `<content src="cdvtests/index.html" />` in `config.xml`.

To use this plugin

    1) add a platform. `cordova platform add android`
    2) add a plugin `cordova plugin add cordova-plugin-device`
    3) add a plugins tests `cordova plugin add https://github.com/apache/cordova-plugin-device#:/tests`

Read more about writing a plugin test [here](https://github.com/apache/cordova-plugin-test-framework#writing-plugin-tests).

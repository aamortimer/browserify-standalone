Browerify standalone bundle
===
Browerify now lets you create standalone builds thanks to intergration with UMD (universal module definition) library. UMD allows allows you to generate code that will work with all module systems and work just in a browser.


Install node modules
```
npm install
```

Now install bower components
```
bower install
```

To compile the standalone browerify run the following
```
browserify js/beep.js --standalone beep > js/bundle.js
```

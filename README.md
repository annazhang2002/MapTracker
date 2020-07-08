MapTracker
========================

A simple Google Maps Android API v2 Demo app. This app helps us test if we have the play services properly setup on our emulator. For detailed installation instructions, check [this Maps guide](https://github.com/thecodepath/android_guides/wiki/Google-Maps-Fragment-Guide)

![Walkthrough][(walkthrough.gif)

MapTracker User Stories/Features: 
* [X] App open Google Maps within the Android phone with the help of the Maps SDK
* [X] User can scroll over the whole map 
* [X] User can long press anywhere on the map to open a new dialog
    * [X] From this dialog, a title and snippet can be entered
* [X] After the user enters text into the dialog and pressed OK, a map pin marker is dropped
* [X] The pin dropping is animated with a bouncing effect
* [X] Pin shows the information in a custom view window

The Google Maps Api helps us to lay down the map into our Android App. It can have different types of map like satellite, terrain and many more. Adding these features on the map helps us to add cool features to our app and make our app able to guide to places to which the user wants.

Make sure that you've setup your Android API key (com.google.android.maps.v2.API_KEY) in manifests/AndroidManifest.xml!  Otherwise, you may not find the maps rendering.

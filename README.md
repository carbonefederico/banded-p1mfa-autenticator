# Authenticator sample app

This sample application demonstrates a branded PingOne MFA branded application.

## To brand the application

Import the project File -> New -> Import Project and open the cloned repo. From the Android view:

- to chaange the app name: in app -> manifests -> AndroidManifest.xml change the android:label value
- to change the logos and the background image: in app -> res -> drawable replace the main_background.jpg logo_horizontal.png and logo_splash.png files with the desired background and logos. Make sure to chose the v24 option to overwrite the existing file
- to change the launcher icon: right click app -> new -> image asset update the foreground by choosing the logo and the background by choosing a color (sometimes this step does not complete correctly and needs repeating)
- to change the text color: in app -> res -> values -> sytles.xml change android:textColor
- to change the button background: in app -> res -> drawable -> roundable_button_white_enabled.xml change the <solid android:color element

A simple blank Ionic project with phonegap-plugin-push added.

## To run
Ensure Ionic and Cordova are installed globally (along with Android SDKs etc.)
`npm install`
`ionic cordova platform add android`

And then try a build with
`ionic cordova build android --debug --device`

If you need to troubleshoot, it may be worth it to try:
`cordova plugin remove phonegap-plugin-push --no-save && cordova plugin add phonegap-plugin-push`
and then rebuild.

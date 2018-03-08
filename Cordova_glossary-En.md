**Memo Cordova**

|Cordova command|what is does|
|--|--|
|cordova create < path >|creates a directory at the specified path|
|cordova platform add < platform name >|platform name (e.g. android, ios, windows etc.) to be added to the project|
|cordova run < platform name >|prepares, builds, and deploys app on specified platform devices/emulators|
|cordova plugin add < plugin name > < path >|adds plugin from specified path|
|cordova run browser|compiles code / starts a localhost in browser |
|cordova run android|complies/creates app|
***
**How is a Cordova project  structured**
|Folder name|Contents|
|--|--|
|config.xml|configuration file that controls many aspects of a cordova application's behavior and stores metadata (ie description/author name, etc.)|
|package.json|Node's config file (contains plugin list, project name, version number, etc.)|
| platforms | contains all that is needed for the app to work on a given platform |
|plugins|contains all the plugins available to your app|
|www|code, media|
|www/index.html|end-user HTML of all your app code (all the components)|
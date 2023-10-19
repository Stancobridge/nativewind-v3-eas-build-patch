1. Install patch-package and post-install `yarn add patch-package postinstall-postinstall`
2. In package.json add this under scripts `"postinstall": "patch-package"`
3. create patches folder in root of your app and paste attached file in the folder.
 
Now eas build works
 

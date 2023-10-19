
Hey,

Are you having issues with building an expo app with nativewind, which causes the builds on EAS to timeout and never complete when using v3, follow the instruction below to fix



1. Install patch-package and post-install `yarn add patch-package postinstall-postinstall`
2. In package.json add this under scripts `"postinstall": "patch-package"`
3. create patches folder in root of your app and paste attached file in the folder.
 
Now eas build works
 
_Originally posted by @anurag-alla in https://github.com/marklawlor/nativewind/issues/363#issuecomment-1418988918_

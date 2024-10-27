# meo backports
This repo contains backports for meo to older browsers.

### [Open](https://ios14.meo-5d3.pages.dev)

## About this branch
This branch contains fixes to make meo work on iOS 14.2 and later. Anything earlier is untested but should work down to around iOS 13.

## Known Issues
This branch is tested on an iPhone 8 running iOS 14.2 and an iPhone 11 Pro Max running iOS 15.2. The following features are known to not work but may work on newer versions of iOS:

- Uploading photos and videos from the camera roll or taking a photo/video on the website does not work. Uploading from the Files app works fine
- Some uploaded files do not display correctly. This is a bug with the browser and not the backport.
- Profile pictures are only shown in the main chat view. They are not shown on the home page, in settings etc.
- Chat Icons do not appear. A line with the chat colour is shown instead.
- Some buttons are not styled correctly. There is nothing wrong with the functionality, just the appearance.
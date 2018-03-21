# cordova-plugin-screenshot
cordova截屏监听事件for ios and android

cordova detect ios or android screen shot event and return the screenshot file fullpath
## Supported platforms

- Android 4.0.0 or above.
- iOS 7.0 or above. Xcode 7 is required.

### Installation

This requires cordova 7.0+

```sh
cordova plugin add cordova-plugin-screenshotv2
```

### Quick start guide
add a  callback function in global

```javascript
function receiveScreenShotCallback(data){
    alert(data); //data return the file full path
    
   };

```

###update

edit gradle config refrence
update git url

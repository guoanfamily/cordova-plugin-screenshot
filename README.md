# cordova-plugin-screenshot
cordova截屏监听事件for ios and android

## Supported platforms

- Android 4.0.0 or above.
- iOS 7.0 or above. Xcode 7 is required.

### Installation

This requires cordova 5.0+ (current stable 1.5.3)

```sh
cordova plugin add cordova-plugin-screenshot
```

### Quick start guide
add a  callback function in global

```javascript
function receiveScreenShotCallback(data){
    alert(data); //data return the file full path
    
   };

```

# react-native-x5-webkit-webview

## Getting started

`$ npm install react-native-x5-webkit-webview --save`

### Mostly automatic installation

`$ react-native link react-native-x5-webkit-webview`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-x5-webkit-webview` and add `X5WebkitWebview.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libX5WebkitWebview.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.X5WebkitWebviewPackage;` to the imports at the top of the file
  - Add `new X5WebkitWebviewPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-x5-webkit-webview'
  	project(':react-native-x5-webkit-webview').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-x5-webkit-webview/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-x5-webkit-webview')
  	```


## Usage
```javascript
import X5WebkitWebview from 'react-native-x5-webkit-webview';

// TODO: What to do with the module?
X5WebkitWebview;
```

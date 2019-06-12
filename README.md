
# react-native-amazon-iap

## Getting started

`$ npm install react-native-amazon-iap --save`

### Mostly automatic installation

`$ react-native link react-native-amazon-iap`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-amazon-iap` and add `RNAmazonIap.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNAmazonIap.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNAmazonIapPackage;` to the imports at the top of the file
  - Add `new RNAmazonIapPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-amazon-iap'
  	project(':react-native-amazon-iap').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-amazon-iap/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-amazon-iap')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNAmazonIap.sln` in `node_modules/react-native-amazon-iap/windows/RNAmazonIap.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Amazon.Iap.RNAmazonIap;` to the usings at the top of the file
  - Add `new RNAmazonIapPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNAmazonIap from 'react-native-amazon-iap';

// TODO: What to do with the module?
RNAmazonIap;
```
  
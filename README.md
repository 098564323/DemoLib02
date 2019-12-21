
# react-native-demo-lib02

## Getting started

`$ npm install react-native-demo-lib02 --save`

### Mostly automatic installation

`$ react-native link react-native-demo-lib02`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-demo-lib02` and add `RNDemoLib02.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNDemoLib02.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNDemoLib02Package;` to the imports at the top of the file
  - Add `new RNDemoLib02Package()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-demo-lib02'
  	project(':react-native-demo-lib02').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-demo-lib02/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-demo-lib02')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNDemoLib02.sln` in `node_modules/react-native-demo-lib02/windows/RNDemoLib02.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Demo.Lib02.RNDemoLib02;` to the usings at the top of the file
  - Add `new RNDemoLib02Package()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNDemoLib02 from 'react-native-demo-lib02';

// TODO: What to do with the module?
RNDemoLib02;
```
  
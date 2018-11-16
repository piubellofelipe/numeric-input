
# react-native-numeric-input

## Getting started

`$ npm install react-native-numeric-input --save`

### Mostly automatic installation

`$ react-native link react-native-numeric-input`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-numeric-input` and add `RNNumericInput.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNNumericInput.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNNumericInputPackage;` to the imports at the top of the file
  - Add `new RNNumericInputPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-numeric-input'
  	project(':react-native-numeric-input').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-numeric-input/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-numeric-input')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNNumericInput.sln` in `node_modules/react-native-numeric-input/windows/RNNumericInput.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Numeric.Input.RNNumericInput;` to the usings at the top of the file
  - Add `new RNNumericInputPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNNumericInput from 'react-native-numeric-input';

// TODO: What to do with the module?
RNNumericInput;
```
  
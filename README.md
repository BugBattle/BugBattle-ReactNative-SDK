# React Native BugBattle

The BugBattle SDK for React Native is the easiest way to integrate BugBattle into your apps!
 
## Docs & Examples

Checkout our [documentation](https://docs.bugbattle.io/docs/reactnative-sdk) for full reference.

## Installation

Open a terminal window and navigate to the root.

**Install via npm**

```
$ npm install react-native-bugbattle-sdk --save
```

**iOS installation**

Navigate to your iOS project folder within the terminal and update the cocoapods by typing

```
pod install
```

**Initialize BugBattle SDK**

Import the BugBattle SDK by adding the following import inside your ```index.js```.

```js
import BugBattle from 'react-native-bugbattle-sdk';
```

Initialize the BugBattle SDK by adding the following line within one of your components. The SDK should be initialized only once!

```js
BugBattle.initWithToken('YOUR_API_KEY', BugBattle.SHAKE);
```

Your API key can be found in the project settings within BugBattle. Possible values for the activation method are ```BugBattle.NONE``` and ```BugBattle.SHAKE```.


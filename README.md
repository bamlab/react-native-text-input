# React Native Text Input

**On React Native Android, you cannot change the color of an input of type password.**  
It is a known issue and [a PR has already been merged](https://github.com/facebook/react-native/pull/6563)
and should land in React Native 0.23 or 0.24.

In the meantime, you can use this module which is basically a copy-paste of the
TextInput component in React Native 0.20 including the fix made in the PR above.

## Install it

```shell
npm install --save react-native-text-input
```

Link the module with [RNPM](https://github.com/rnpm/rnpm):
```shell
npm install -g rnpm
rnpm link react-native-text-input
```

Now you can replace:
```javascript
import { TextInput } from 'react-native';
```
by:
```javascript
import TextInput from 'react-native-text-input';
```

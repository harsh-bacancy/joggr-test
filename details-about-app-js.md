<!--@@joggrdoc@@-->
<!-- @joggr:version(v1):end -->
<!-- @joggr:warning:start -->
<!-- 
  _   _   _    __        __     _      ____    _   _   ___   _   _    ____     _   _   _ 
 | | | | | |   \ \      / /    / \    |  _ \  | \ | | |_ _| | \ | |  / ___|   | | | | | |
 | | | | | |    \ \ /\ / /    / _ \   | |_) | |  \| |  | |  |  \| | | |  _    | | | | | |
 |_| |_| |_|     \ V  V /    / ___ \  |  _ <  | |\  |  | |  | |\  | | |_| |   |_| |_| |_|
 (_) (_) (_)      \_/\_/    /_/   \_\ |_| \_\ |_| \_| |___| |_| \_|  \____|   (_) (_) (_)
                                                              
This document is managed by Joggr. Editing this document could break Joggr's core features, i.e. our 
ability to auto-maintain this document. Please use the Joggr editor to edit this document 
(link at bottom of the page).
-->
<!-- @joggr:warning:end -->
## Requirements

*   expo-status-bar\@latest
*   react-native\@latest

## Steps

### 1. Create a new file

Create a new file named `App.js`.

### 2. Import required modules

Import the required modules `StatusBar` and `View` from the `expo-status-bar` and `react-native` libraries respectively.

```javascript
import { StatusBar } from 'expo-status-bar';
import { View } from 'react-native';
```

### 3. Define the main component

Define the main component `App` as a function that returns the JSX code for the app UI.

```javascript
export default function App() {
  return (
    <View style={styles.container}>
      {/* App UI code goes here */}
      <StatusBar style="auto" />
    </View>
  );
}
```

### 4. Define the app UI

Within the `View` component, add the desired UI elements, such as a `Text` component with the text 'Open up App.js to start working on your app!'.

```javascript
<Text>Open up App.js to start working on your app!</Text>
```

### 5. Apply styles

Define the `styles` object using `StyleSheet.create()` to apply styles to the `container` property.

```javascript
const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#fff',
    alignItems: 'center',
    justifyContent: 'center',
  },
});
```

<!-- @joggr:editLink(17697e65-ffd9-4240-819c-376be6bd5b6b):start -->
---
<a href="https://app.joggr.io/app/documents/17697e65-ffd9-4240-819c-376be6bd5b6b/edit" alt="Edit doc on Joggr">
  <img src="https://storage.googleapis.com/joggr-public-assets/github/badges/edit-document-badge.svg" />
</a>
<!-- @joggr:editLink(17697e65-ffd9-4240-819c-376be6bd5b6b):end -->
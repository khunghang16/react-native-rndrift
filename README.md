# react-native-rndrift

![React Native Drift Demo](demo.gif)



## Getting started

`$ npm install react-native-rndrift --save`

### Mostly automatic installation

`$ react-native link react-native-rndrift`

## Usage
```javascript
import Rndrift from 'react-native-rndrift';

// Init Drift - https://app.drift.com/settings/livechat
Rndrift.setup("YOUR API TOKEN");

// Create a user
Rndrift.registerUser("unique id of the user", "email");

// Logout user
Rndrift.logout();

// Display conversations view
Rndrift.showConversations();

// Display create conversation view
Rndrift.showCreateConversation();
```

# Employee Directory: React Native Sample App

See [this](http://coenraets.org/blog/2017/01/react-native-sample-app-tutorial/) blog post for more info.

## Installation Instructions

1. Follow the React Native getting started instructions to install React Native

1. Create a new React Native app named EmployeeDirectory:
    ```
    react-native init EmployeeDirectory
    cd EmployeeDirectory
    react-native run-ios
    ```
1. Clone the sample app repository:
    ```
    git clone https://github.com/ccoenraets/employee-directory-react-native
    ```

1. Copy the `app` folder from `employee-directory-react-native` into your `EmployeeDirectory` project folder

1. Open `index.ios.js`. Delete the existing content and replace it with:
    ```
    import {AppRegistry} from 'react-native';
     
    import EmployeeDirectoryApp from './app/EmployeeDirectoryApp';
     
    AppRegistry.registerComponent('EmployeeDirectory', () => EmployeeDirectoryApp);
    ```

1. Save index.ios.js

1. Hit Cmd + R to refresh the app in the emulator